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
>> "TOP" "CENTER" "AXIS_CLIP" "AXIS_PULL_AFTER" "AXIS_PULL_BEFORE" "AXIS_SPECIFIED" "AXIS_X_SHIFT" "AXIS_Y_SHIFT" "BOTTOM" "CENTER_HORIZONTAL" "CENTER_VERTICAL" "CLIP_HORIZONTAL" "CLIP_VERTICAL" "DISPLAY_CLIP_HORIZONTAL" "DISPLAY_CLIP_VERTICAL" "FILL" "FILL_HORIZONTAL" "FILL_VERTICAL" "HORIZONTAL_GRAVITY_MASK" "LEFT" "NO_GRAVITY" "RIGHT" "VERTICAL_GRAVITY_MASK"
>>
>> defult value is "BOTTOM"
>
> current version has many bugs,welcome to correct.

## Contact
email: yangyun4814@gmail.com
blog: [http://blog.helloarron.com](http://blog.helloarron.com)
