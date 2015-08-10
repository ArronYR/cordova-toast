# cordova-toast
A Cordova Toast plugin for Android


## Install plugin
cordova plugin add com.helloarron.cordova.toast

## How to use
- AToast.toast();
>  defult toast message is "默认Toast样"

- AToast.toast("hello cordova pulgin");


- AToast.toast("hello cordova pulgin", 'SHORT');
> the second argument can be "SHORT" or "LONG"

- AToast.toast("hello cordova pulgin", 'LONG', ['CENTER', 0, 0]);
> the third argument is a Array likes the demo, it has three element
>
> ['CENTER', 0, 0]
>> first element is a string, others are number
>>
>> the first element can be these values:
>>
>> "TOP" <br/> "CENTER" <br/> "AXIS_CLIP" <br/> "AXIS_PULL_AFTER" <br/> "AXIS_PULL_BEFORE" <br/> "AXIS_SPECIFIED" <br/> "AXIS_X_SHIFT" <br/> "AXIS_Y_SHIFT" <br/> "BOTTOM" <br/> "CENTER_HORIZONTAL" <br/> "CENTER_VERTICAL" <br/> "CLIP_HORIZONTAL" <br/> "CLIP_VERTICAL" <br/> "DISPLAY_CLIP_HORIZONTAL" <br/> "DISPLAY_CLIP_VERTICAL" <br/> "FILL" <br/> "FILL_HORIZONTAL" <br/> "FILL_VERTICAL" <br/> "HORIZONTAL_GRAVITY_MASK" <br/> "LEFT" <br/> "NO_GRAVITY" <br/> "RIGHT" <br/> "VERTICAL_GRAVITY_MASK" <br/>
>>
>> defult value is "BOTTOM"
>
> current version has many bugs,welcome to correct.

## Contact
email: yangyun4814@gmail.com
blog: [http://blog.helloarron.com](http://blog.helloarron.com)
