AsteroidNavigator
-------------------------------------

A cute little game made with Unity and C#.
[Demo](https://jgarza9788.github.io/AsteroidNavigator_Demo/)

[Asset Store Link](http://u3d.as/Jto)  
© 2017 Justin Garza

PLEASE LEAVE A REVIEW OR RATE THE PACKAGE IF YOU FIND IT USEFUL!
Enjoy! :)


Contact  
-------------------------------------
Questions, suggestions, help needed?  
Contact me at:  
Email: jgarza9788@gmail.com  
Cell: 1-818-251-0647  
Contact Info: [justingarza.info/contact](http://justingarza.info/contact/)  
Alternate Website: [jgarza9788 - UnityPortfolio](https://github.com/jgarza9788/UnityPortfolio)  

  
Description/Features
-------------------------------------
A Space themed physics game!

* GaussianBlur Pause Effect
* ShockWave Effect
* DropShadow Effect
* Carousel Picker
* Multiple Characters
* Unity Ads
* Saves Last Score and High Score!
* Scene Transitions
* Fully Commented C# code
* And More
* ...Reach out to me to request new features!  


Terms of Use
-------------------------------------
You are free to add this asset to any game you’d like
However:  
please put my name in the credits, or in the special thanks section. :)  
please do not re-distribute.  

Table of Contents 
-------------------------------------
1. Systems/Effect
	* SceneSwitchAnimator
	* ShockWave
	* DropShadow
	* GaussianBlur
	* 3D Carousel Picker
	* Pool Manager
	* Repairs/Ads
2. Scenes	
3. Scripts
4. Special Thanks


  
Systems/Effect
-------------------------------------
There are a few different Systems/Effects that are within this asset below will give a small discription of some of them.

**SceneSwitchAnimator:**  
This controls the changing of one scene to another.

**ShockWave:**  
This creates a small shockwave effect when the ship crashes

**DropShadow:**  
This creates a shadow behind the player and the asteroids

**GaussianBlur:**  
This creates a blur effect, this can be seen during pause. (see image below)

![Imgur](https://i.imgur.com/39cTMAOm.png)

**3D Carousel Picker:**  
This 3D Carousel Picker is used for picking your character, and repairing them.

![Imgur](http://i.imgur.com/xB2cPLfm.png)

![Imgur](https://i.imgur.com/AE6Ns02m.png)

**Pool Manager:**  
This system (PoolManager.cs**, ObjectPool.cs**, and RecycleAfter.cs** ) is used for Spawning and Recycling objects, instead of creating and destorying since creating and destorying objects takes up too much resources.

**Repairs/Ads:**  
When you lose with a character their ship breaks, and the only way to repair the ship is to watch an ad. please see **CharacterSelectManager.cs** for more details.


Scenes 
-------------------------------------
Here is a List of Scenes, and a breif description of what they do.

**TitleScene**  
This is exactly what it sounds like...
it's a setup/title screen.

![Imgur](https://i.imgur.com/Qs9DvsKm.png)


**CharacterSelect**
This is where the user can select a character, or repair a character with a broken ship.

![Imgur](https://i.imgur.com/AE6Ns02m.png)

**Game**  
This scene stores the core game.
Tap the L and R buttons to control the trust of your rockets, and Navigate the Asteroid field.

![Imgur](https://i.imgur.com/ZT7VPoYm.png)
![Imgur](https://i.imgur.com/sDkVe5Fm.png)
![Imgur](https://i.imgur.com/Luxwqj2m.png)

Scripts 
-------------------------------------
Here is a list of some of the scripts that are in this asset, along with a breif description.

**BlurControl.cs**  
Used to allow the animator to control the Blur Materail during pausing/unpausing.

**CameraBounds.cs**  
sets bounds to determine what is in the camera's view

**CameraFollow.cs**  
Used to Move the camera during the Game

**CharacterSelectManager.cs**  
Used to Select Character, repair Characters/ShowAds, and more.

**ControlButtons.cs**  
This script matches a down press on a button to the player's action

**createAsteroids.cs**  
This Script creates the Asteroids in the game

**createAsteroidsTitleScene.cs**  
creates Asteroids on the TitleScene

**createSoftCircles.cs**  
create soft circles at random position in the game...just to make things look nice

**DestroyAfter.cs**  
Destorys a the GameObject it is attached to after time

**displayPlayerPref.cs**  
this script will display PlayerPref Data.

**DontDestroy.cs**  
This script will allow an object to live on after scene transition.

**DontRotate.cs**  
used to force an Object to not rotate (dispite the rotation of the parent object)

**Floaty.cs**  
Used to move the object as if it was floating...used in the CharacterSelect scene

**GameManager.cs**  
Used to manage the states of the game (StartGame, Play, Win, Death, Pause)

**GoToScene.cs**  
This Script can be assigned to buttons to Switch Scenes.

**Hearts.cs**  
Manages the Hearts in the HUD.

**loopMe.cs**  
Loops objects to the other side of the screen, requires the camera to have CameraBounds.cs** attached

**MusicManager.cs**  
This script is used to manage the music.

**ObjectPool.cs**  
A pool of objects that can be reused.

**PauseButton.cs**  
Used with the toggle PauseButton.

**Player.cs**  
This script manages the player

**PlayerPrefsBool.cs**  
Contains methods for storing bools in the PlayerPrefs.
Note: stores 0 and 1 as int, but converts it to a bool on return

**PlaySound.cs**  
This script is used to play a sound

**PoolManager.cs**  
This script manages pools of objects
Spawning and Recycling.

**RecycleAfter.cs**  
This script Recycles an Object after t seconds

**SceneMusic.cs**  
Changes the music track on Start

**SetUp.cs**  
Creates GameObjects on Awake...but don't create them if they exists.

**SoundManager.cs**  
This script is used to manage the Sounds.

**VolumeSwitch.cs**  
This Script can be assigned to a toggle to control Music or Sound

Special Thanks 
-------------------------------------
Kenney Vleugels www.kenney.nl  
(he provided most of the images assets for free!)
