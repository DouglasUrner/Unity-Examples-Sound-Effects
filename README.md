# Unity-Examples-Sound-Effects

How to add sounds to your games.

## Tutorials

* [Introduction to Unity Sound](https://www.raywenderlich.com/6449-introduction-to-unity-sound)
* [Sound Effects & Scripting](https://unity3d.com/learn/tutorials/topics/audio/sound-effects-scripting) - this one is old, it is marked as "Checked with version: 4.5" and includes a section on "Sound Effects in Unity 5" so it may take some translation. The starter and final code for this tutorial is in the **Barn Blaster** directory.

## Key Points

**Components:**

* AudioSource - plays the sound (think iPod)
  - AudioClip - the sound to play (the sound file the iPod plays)
* AudioListener - the game object that "hears" the sound, often the player or the main camera. In 3D games the distance between the AudioSource and the AudioListener affects the volume when the AudioClip is played.
