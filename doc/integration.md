# Points of integration to a device

### Media Player

- Existing Media Players are
  - GStreamer based (https://github.com/sw-devendra/avs-device-sdk/tree/master/MediaPlayer/GStreamerMediaPlayer)
  - Android (https://github.com/sw-devendra/avs-device-sdk/tree/master/MediaPlayer/AndroidSLESMediaPlayer)
- Build configuration https://github.com/sw-devendra/avs-device-sdk/blob/master/MediaPlayer/CMakeLists.txt 
- Implementation of Speaker Interface, Media Player Interface, Equalizer Interface

### Mic

- Existing Microphone implementations are
  - Android Microphone ( https://github.com/sw-devendra/avs-device-sdk/tree/master/ApplicationUtilities/AndroidUtilities )
  - PortAudio ( https://github.com/sw-devendra/avs-device-sdk/blob/master/SampleApp/src/PortAudioMicrophoneWrapper.cpp )
- Implementation of MicrophoneInterface ( https://github.com/sw-devendra/avs-device-sdk/blob/master/ApplicationUtilities/Resources/Audio/include/Audio/MicrophoneInterface.h ) 

### GUI

- GuiRenderer in SampleApp ( https://github.com/sw-devendra/avs-device-sdk/blob/master/SampleApp/src/GuiRenderer.cpp )
- Implments TemplateRuntimeObserverInterface ( https://github.com/sw-devendra/avs-device-sdk/tree/master/AVSCommon/SDKInterfaces/include/AVSCommon/SDKInterfaces ) 
