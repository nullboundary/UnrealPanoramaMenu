# Unreal Panorama Menu

##Tested 4.14

### Stereo Panorama Settings UI

![Image](images/PanoSetting.PNG?raw=true)

- Advanced Settings Options

![Image](images/PanoSetting2.PNG?raw=true)

### How to Setup

- Download and import both Uasset files from this repository.
- Open your player blueprint (often ThirdpersonBP or FirstpersonBP).
- In the upper left corner of your blueprint editor. Add component and select the PanMenuControl component.

![Image](images/PanoSetting3.PNG?raw=true)

- With PanMenuControl component selected, make sure PanMenuClass is set to PanMenu (user widget type) in the details panel.

![Image](images/PanMenuClass.PNG?raw=true)


- Under the Settings menu (gear icon) -> plugins. Activate the Movie Capture Plugin.

![Image](images/PanoSetting4.PNG?raw=true)

- Under Play menu -> Advanced Settings -> Play in Standalone Game section -> Advanced (toggle arrow).  
- Add fixed time step. ```-usefixedtimestep -fps=60 -notexturestreaming```

![Image](images/PanoSetting5.png?raw=true)

- Play in Standalone Game.
- Press Escape to toggle Stereo Panorama Settings Menu. 
