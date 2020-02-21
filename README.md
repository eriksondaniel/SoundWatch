
Introduction
------------
a handheld and an Wear device communicate
using the [DataApi][2]

Pre-requisites
--------------

- Android SDK 28
- Android Build Tools v28.0.3
- Android Support Repository

Screenshots
-------------

Getting Started
---------------

- Point buildPython in build.grade to your local python installation (both of application and wearable modules)
- Change ARCHITECTURE in MainActivity to switch between Architectures
- WARNING: If use WATCH_ONLY_ARCHITECTURE, please copy the tflite model into assets folder in Wearable src folder, and specify the filename inside MODEL_FILENAME in SoundRecorder
- Change AUDIO_TRANMISSION_STYLE in MainActivity to change the Audio Transmission Style (Raw Audio vs. Audio Features)

Support
-------

