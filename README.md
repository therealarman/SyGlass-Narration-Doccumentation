
# The Syglass Recording Guide

This documentation will help you learn the ins and outs of making a presentation/narration with SyGlass!

# General Virtual Reality Usage

If this is your first time using virtual reality, take your time learning everything. Make sure you're situated with the headset and controller before jumping into all the more complicated components of SyGlass.

## The Headset

### Head Strap:
In the back of your headset, there's a knob that controls the tightness of the headset around your head. Use this knob to adjust the headset to a point where it's comfortable, and allows you to clearly see through the lenses.

### Lens Distance Dial:
Underneath the front of the controller, right above your nose, is a dial that adjusts he distance between the two lenses inside your headset. Adjust this dial until you're able to clearly see through both lenses without them being blurry or unclear.

## The Controllers

This section will review the basic buttons on your controllers and their functionality, including their functionality with SyGlass.

### Trigger:
- The trigger allows you to utilize the selected tool for each controller and move around your project or other objects in your VR environment. The trigger allows you to select options in the menu and controller menu, as well as adjusting the visualization settings. The trigger is your key to interacting with SyGlass's various user interfaces.

### Touchpad:
- Pressing down on the touchpad enables the radial menu. With the radial menu, you can select different abilities or settings for the current tool on each controller. To select an option from the radial menu, move your controller to the option, and press the trigger.

### Menu Button:
- The menu button opens a menu that allows for various settings changes. You can change your project's visualization settings, your selected tool for each controller, and render settings.

### Power Button:
- The power button is under an MPFI Logo sticker on your controller. To turn your controller on, press down on the sticker until you hear a beep, and the lights on your controllers turn on. Hold down on this button again to turn the controller off.

### Grip Button:
- The grip button is a button on the base of your controller, where your middle finger may lay. Each controller can have 2 different SyGlass "tools" bound to them at a time. Pressing the grip button allows you to cycle between these two tools. For example, by default your controller will have the Transform and CutPlane tools selected. Pressing the grip button will cycle between these two tools.

# SyGlass Specifics

## Importing projects
In order to import a project into SyGlass, navigate to the **file** button at the top menu bar. From there, if creating a new project, select the "create new project" button. Otherwise, select "Import Existing Project."

Pressing "Create New Project" will open the [New Project Wizard](https://www.youtube.com/watch?v=0X5R60u8V6U). From there, you can add the volumetric data files you would like included in your project. Once you have them selected, hit the Next button, which allows you to specify more settings, such as choosing a channel and importing visualization settings from another project.

## Loading Projects
Navigate to the Project Library tab on the left side of your SyGlass application. To import a project, right-click on the project you would like to import and press "Launch Project." From there, you should see the selected project loaded into your SyGlass environment.

### Loading Multiple Projects
In order to load multiple projects into the same environment, hold down the **control** button on your keyboard and left-click on the projects you would like to import to highlight them. Once you select your desired projects, right-click while still holding control and press "Launch Project."

## Enabling Virtual Reality
In the bottom right corner of your SyGlass environment, you should see a white VR helmet with "off" written underneath it. This button enables you to enter and exit virtual reality mode. By turning it on and selecting "SteamVR," the view mode will change from desktop to VR, and you will be able to interact with the scene using your headset and controllers.

## Adjusting visualization settings
After loading your project, you can change the project's visualization settings using an interactive menu. Each volume that you import will be different, so you may need to adjust the visualization settings for a new project to make have it show correctly to your viewer.

By pressing "control" on the keyboard, or the menu button on your Virtual Reality controller, the visualization menu will open.

At the top of the menu, you will see various visualization options with settings sliders underneath them.

### Settings Sliders
### [**Stride**](https://www.youtube.com/watch?v=Xa8EJ20cAU8&t=31s)
- Stride adjusts the "noisiness" of your project. Increasing the stride will generally decrease the quality of your volume (making it appear more jittery), while decreasing the slide increases the quality and makes it clearer. It is not recommended to have stride at 0 until recording, as it will cause your project to lag.

### [**Intensity**](https://www.youtube.com/watch?v=Xa8EJ20cAU8&t=43s)
- Intensity alters the brightness of your project. Increasing the intensity makes the volume appear brighter, while decreasing the intensity makes it darker.

### [**Contrast**](https://www.youtube.com/watch?v=Xa8EJ20cAU8&t=51s)
- Contrast adjusts the gamma-correction of your volume. By increasing and decreasing the contrast, you can make some lighter values less visible, revealing details that might be hidden deeper in the volume.

### [**Window**](https://www.youtube.com/watch?v=Xa8EJ20cAU8&t=67s)
- Window is one of two sliders that has two adjustable values.
- Values *less* than the first slider will become black (less intense)
- Values *higher* than the second slider will become white (more intense)

### [**Threshold**](https://www.youtube.com/watch?v=Xa8EJ20cAU8&t=87s)
- Threshold also includes two adjustable values.
- Values not in range of the two sliders will disappear completely

## Adding Meshes from files
With a project open, navigate to the Project tab in the top menu bar. Select the "Surfaces" button, which will open the Surface Wizard. Here, you should see a list of your project's active meshes. To add a new one, select the "add surfaces" button in the Surface Wizard, and select the mesh you would like to add in the file explorer.

## Important Tools

### Selecting Tools
After opening the menu by pressing the menu button, you will see two rows of tools at the bottom of the menu. Pointing at one of these buttons with your controller and pressing your trigger will select it. You're able to select two tools at a time. The first tool you select will be your "main" tool, and the second would be your "secondary" tool. Pressing the Grip button on your controller allows you to switch between these two tools.

### Transform Tool
The transform tool is used to move meshes and volumes around in your environment. By default, with the transform tool selected, grabbing in the air allows you to move around all meshes and volumes in the scene, while grabbing inside of a volume allows you to move and rotate it individually. 

While both controllers are set to the transform tool, grabbing at two different areas in space and moving your hands closer or farther apart will shrink or enlarge your objects. The same rules apply when trying to scale an individual object up or down.

On the radial menu, a setting called "Transform Surfaces Only" with a picture of a rabbit will be shown. Selecting this tool allows you to move meshes that you have imported into your scene individually. Selecting this option again turns it off.

On the radial menu, a setting called "Reset All Surfaces" will also be available. Selecting this will reset the position, rotation, and scale of all meshes in your scene.

### Cut Tool
The cut tool allows you to add a cut plane to volumes in your scene. By holding down the trigger, you will spawn in a cut plane to your controller location. While holding the trigger, you can move your controller in and around a volume to cut through it. By releasing the trigger, the cut plane will stay at its last moved position. 

In order to remove a cut plane, hold the trigger down and move the plane away from the volume.

### Surface Selection Tool
Usually, when trying to move meshes, they will move with the rest of the scene and not individually, even when grabbing them directly. Using the Surface Selection tool, you can point at a mesh and select it, separating it from the rest of the scene and allowing you to move it. 

Once you have selected a mesh, it should have a yellow outline around it. You are only able to select one at a time. In order to move the mesh, use the transform tool and the "transform surfaces only" function.

### Studio Tool
The studio tool is your interface with everything to do with recording. By pressing down on your trigger, your camera will go into "selfie stick mode" by attaching itself with a pole to your controller. By using the lengthen and shorten options on your radial menu, you can increase and decrease this distance to place your camera where you'd like.

In the menu, there are more options that can be used to help with recording. For example, the "Font Size" selector allows you to increase or decrease the font size of your scripts as they appear on your teleprompter. The teleprompter is covered more in the "Podium" section of this guide, including turning it on and off and selecting which script you'd like displayed.

## Adjusting recording settings

By hitting "control" on your keyboard and navigating to the gear icon in the top right corner of the menu, you will be taken to the settings menu. These settings control various features surrounding the recording and exporting of your presentation. One thing to remember is that these settings **must** be how you want them before you start recording, as they cannot be changed afterward. **PLEASE double check your settings before recording**

### Changing the background of the room
Under the "Rendering" tab, scroll to "Skybox." Here you can scroll through different backgrounds to appear around you in your recording, replacing the default room that you are in. I recommend "Nebulae," which puts you into a space background.

### Changing video dimensions
Under the "Video" tab, scroll to "Capture Resolution." This selection allows you to change the aspect ratio of your video before exporting. The higher the ratio, the higher quality your video will be. However, as you reach higher values, it may cause your videos to take more time to render.

### Controller & Headset Smoothing
Under the "Controller" tab, scroll to "Headset Smoothing" and "Controller Smoothing." These settings allow you to add "smoothness" to your movements in virtual reality, making your recording have smoother movement of your hands and head. Adding some smoothing to your controllers and headset is essential, as, without it, your actions may seem jerky, distracting, or disorienting.

## Importing Scripts
Importing scripts allows you to have text inside of SyGlass that only you can see, for you to read off of while recording. Click on the File tab in the top menu bar, and navigate to the "Manage Teleprompter Scripts" button. From here, the scripts wizard should open. Press the "add scripts" button, which will open up a new menu. From here, paste in your script text and title your script. This text will appear on the teleprompter, which is discussed more in this guide's "Podium Tool" section. The podium section also goes more in depth on selecting which of your scripts is shown at a time.

## Podium tool

By turning your wrist to face you on your left controller (as if you were checking a watch), a new radial menu will appear. The **podium** tool is handy when recording, sporting many functions to make your narration experience a breeze. The podium tool is only available with the VR mode of SyGlass enabled.

### Moving the Podium
There should be a ball in the center of the podium with no label. Grabbing this ball with your controller and moving it will move the podium along with it. Use this to position the podium to your ideal spot for recording.

### Record button
Pressing the record button will start a countdown to your recording beginning. Once it starts, all of your movements and audio will be recorded. To end the narration, hit the record button again and choose whether or not to save the narration.

### Camera
A joystick on the podium allows you to control the camera placement. This camera placement dictates where others will be when they play your recording in virtual reality, as well as the point that will video, will be seen from when exported as MP4s.

### Teleprompter
The teleprompter allows you to see and scroll through your scripts while recording. There is a joystick that allows you to move the teleprompter and options to change scripts or scroll through the current script on the teleprompter.

## Exporting Recordings
### Recording MP4s
Once you have finished a narration, you can export it as an Mp4 video. In order to do this, right-click on your recording in the narration menu and press "Record Mp4." These videos may take some time to render, so don't be alarmed if the wait time is long or SyGlass seems like it's crashing. Once your video is done rendering, it can be found in a folder named "syglass" in your computer's video directory.

### Creating Presentations
Presentations allow you to stitch multiple narrations together before exporting. Click on the "Create Presentations" button under the presentations tab in the top menu bar. Select and arrange the narrations you would like to combine on the timeline. 
