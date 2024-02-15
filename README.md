# PIVision-UpdateLimits

![Update PI Tag Attributes](https://github.com/BURNT64/PIVision-UpdateLimits/assets/88587722/acdb5d80-f63d-4f5c-950c-4f1e448d3971)

This is a modified custom symbol for PI Vision displays, it lets users update all tag attributes directly from PI Vision rather than using PI System explorer, PI Vision communicates with System Explorer Via a tool called PI Web API. this was created for engineers at Tata Steel to be able to change asset limits without using the database

Follow these instructions to install this custom symbol; (Make sure PI Vision is installed on your system)

In Windows Explorer, navigate to the "PIPC\PIVision" installation folder on your PI Vision server; typically, it's located in "C:\Program Files\PIPC\PIVision"

From within the folder named "PIVision", navigate to the "\Scripts\app\editor\symbols" sub-folder.

Within the folder named "symbols", if there is not already a folder called "ext", create a folder called "ext".

Now that the "ext" folder exists, or already exits, open it, and paste into the "ext" folder the one .js and two .html files contained in the custom symbol .ZIP folder that you were sent.

Within the folder named "ext", if there is not already a folder called "Icons", create a folder called "Icons".

Now that the "Icons" folder exists, or already exits, open it, and paste into the "Icons" folder the one .png image file contained in the custom symbol .ZIP folder that you were sent.

The next time you open a web browser and navigate to PI Vision and create a new PI Vision display, you will see this new symbol appear in the top-left-hand corner of the PI Vision display editor.
