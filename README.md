# Pitch Perfect
This app records a conversation between you and a friend, and then alters your voices to sound like a Chipmunk or Darth Vader.

<p align="center">
  <img width="250" height="500" src="https://user-images.githubusercontent.com/27751735/55437890-c5a06280-55a8-11e9-8267-b78385bcefcc.png">
  
  <img width="250" height="500" src="https://user-images.githubusercontent.com/27751735/55437891-c5a06280-55a8-11e9-8efa-9dc22173a9f2.png">
</p>


## Implementation

**The app has two view controller scenes:**

* **RecordSoundsViewController**  consists a record button with a microphone image. Tapping this microphone button starts an audio recording session and present a stop button. When the stop button is clicked, the app completes recording and then show the PlaySound controller.

* **PlaySoundsViewController** contains six buttons to play the recorded sound file with different effects and a button to stop the playback.

