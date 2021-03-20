# Web Camera Library
jQuery and JavaScript based library for capture image from attached camera devices

#### Features
* Camera invocation support for mobile: front and back
* Switch camera support for mobile and iPad 
* Support to select from the available camera for laptop and desktops
* Support for timer
* Retake image feature
* Custom class support for better designing
* Callback function

#### Installation
1. Add jQuery in footer
    * `<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>`
2. Add Library in footer
    * `<script src="webCamLib.min.js"></script>`
3. Add html tag in body where you want to initialize the camera
    * `<div class="image-capture"></div>`
4. Add Initializing script in footer
    * `<script>$('.image-capture').customWebCam()</script>`
    
#### Options
| Option | Default | Description |
| :---: | :---: | :---: |
| videoClass | [] | This class applies to the video tag. |
| canvasClass | [] | This class applies to the canvas tag which holds the preview of image |
| captureButtonClass | [] | This class applies to the image capture button |
| retakeButtonClass | [] | This class applies to the retake image button |
| okButtonClass | [] | This class applies to the OK button |
| actionButtonWrapperClass | [] | This class applies to the wrapper div of all action buttons |
| countdownClass | [] | This class applies to the countdown timer div |
| selectClass | [] | This class applies to the select dropdown of the devices |
| showHideCameraDropdownButtonClass | [] | This class applies to the gear icon |
| SwitchCameraIconClass | [] | This class applies to the switch camera icon on top right in mobile devices |
| canvasWidth | "100%" | This is the width of the captured image preview canvas |
| facingMode | "user" | This is to invoke default camera. Supported values: user, environment |
| callbackFunction | null | function that get executed after the image capture |
| captureTimeoutInSeconds | "5" | This is the capture timeout. To disable it set it to 0 |