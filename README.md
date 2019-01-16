# Video-Super-Resolution
Frame by Frame super resolution of a low quality video to higher quality



## Training
If you wish to train the network on your own data set, follow these steps (Performance may vary) :
<br><b>[1]</b> Save all of your input images of any size in the <b>"input_images"</b> folder
<br><b>[2]</b> Run img_utils.py function, `transform_images(input_path, scale_factor)`. By default, input_path is "input_images" path.
<br><b>[3]</b> Open <b>ftests.py</b> and un-comment the lines at model.fit(...), where model can be sr, esr or dsr, ddsr. 
<br><b>Note: It may be useful to save the original weights in some other location.</b>
<br><b>[4]</b> Execute ftests.py to begin training. GPU is recommended, although if small number of images are provided then GPU may not be required.
