# custom-turtlesim
This repo shows what changes you need to make to the turtlesim repository to add your own turtle image.

## Instructions
1. Add your image to the [image folder](https://github.com/aaryanmurgunde/custom-turtlesim/tree/master/images) in this repository. Make sure the image is a `transparent png` or an `svg`.
2. Go to line 93 in the [src/turtle_frame.cpp](https://github.com/aaryanmurgunde/custom-turtlesim/blob/5b8755844b5d90d2798e3a46dec828ce0e1da7fa/src/turtle_frame.cpp#L93) and replace `"custom.svg"` with the name of your file name.

![image](https://user-images.githubusercontent.com/44398228/159955270-d2f8790d-5232-4541-a93d-53f0376b2361.png)

3. If you wish to add more then one image, add `custom_image.append("<image_name>");` on line 99 with <image_name> as your image name with the extension `.png` or `.svg`
