# Unreal Panorama Menu

### Stereo Panorama Settings UI

![Image](images/PanoSetting.PNG?raw=true)

- Advanced Settings Options

![Image](images/PanoSetting2.PNG?raw=true)

### How to Setup

- Download and import both Uasset files from this repository.
- Open your player blueprint (often ThirdpersonBP or FirstpersonBP).
- In the upper left corner of your blueprint editor. Add component and select the PanMenuControl component

![Image](images/PanoSetting3.PNG?raw=true)

- Under the project settings menu -> plugins. Activate the Movie Capture Plugin.

![Image](images/PanoSetting4.PNG?raw=true)

- Under Editor Settings -> Play in Standalone Game -> Advanced.  
- Add fixed time step. ```-usefixedtimestep -fps=60 -notexturestreaming```

![Image](images/PanoSetting5.png?raw=true)

- Play in Standalone Game.
- Press Escape to toggle Stereo Panorama Settings Menu. 
