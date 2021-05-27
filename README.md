### What is this?

Its an environment for machine learning. <br>
NOTE: this will just be one component for a machine learning project. It's designed to be included as a submodule on other projects. <br>
This uses Unity ML-Agent repo, see that repo for lots of documentation.

### Setup

1. Download or clone this repository (Note: it is currently quite large)<br>
    `git clone --recursive https://github.com/jeff-hykin/unity_basic_car_track.git`
    
2. Download Unity Hub (from an App Store, Package manger, or Unity's website)
    - agree to the license thing (green arrow)
    - press back (yellow arrow)
    <img src="/documentation/images/activate.png" alt="where-to-click">
    
    - go to projects (should be empty)
    <img src="/documentation/images/unity_hub.png" alt="where-to-click">

    - click the "Add", find the folder you just downloaded/cloned (e.g. "unity_basic_car_track"), and open it 
    - Then click the name of the project ("car-track-environment"), and there should be a black pop-up (at the bottom) like this
    <img src="/documentation/images/install_prompt.png" alt="where-to-click">
    
    - Click install, then try opening the project again

3. Opening up the scene
    - You won't see the car immediately, but your menus should look something like this
    <img src="/documentation/images/car_track_scene.png" alt="where-to-click">

    - Under the project tab (White arrow)
    - Select `Assets` (Lime green arrow)
    - Select `Scenes` (Green arrow)
    - Select `CarTrainPython.unity` (Blue arrow)
4. Now you should be able to see the car/track! 
5. Start the python listener (there should be instructions in a seperate repo ([example](https://github.com/jeff-hykin/model_racer)) for this) 
6. Now, go back to the Unity App and click the start button
<img src="/documentation/images/car_track_scene_ready_to_start.png" alt="description">

7. (you should see output inside the terminal now!)
8. If you want to modify the camera resolution, follow click the carcam (lime green), then go to the inspector, and scroll down until you see the camera settings.
<img src="/documentation/images/camera_sensor.png" alt="description">