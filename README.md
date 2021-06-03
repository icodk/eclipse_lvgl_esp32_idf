### ESP-IDF Eclipse Plugin project using LVGL with TFT 2.8" 320X240 with Touch display

#### Clone this project with:
`git clone  --recurse-submodules    https://github.com/icodk/eclipse_lvgl_esp32_idf.git`

#### Flasher speed
Flsher speed is set to 460800 by the plugin.
To use  different baudrate edit the Launch Target to looks like:

##### 1. Click on the Launch Target configuration:

![image](https://user-images.githubusercontent.com/15612908/120640366-b233ff00-c472-11eb-9784-c155048cf8db.png)
##### 2. Fill the Main tab as below:
![image](https://user-images.githubusercontent.com/15612908/120640853-3edebd00-c473-11eb-9d38-b24ba4ad3e72.png)

The demo application is the `lv_demo_widgets` project from the [lv_examples](https://github.com/lvgl/lv_examples) repository.
#### Versions
- Version of eclipse idf plugin: ### ESP-IDF Eclipse Plugin v2.1.0 (Build: 2.1.0.202104161244)
- Version of ESP-IDF required 4.2.
- Version of LVGL used: 7.9.
- Version of lv_examples used: 7.9.


## Display and touch controllers

The display and touch (indev) controllers are now into it's own repository, you can find it [here](https://github.com/lvgl/lvgl_esp32_drivers).
To report any issue or add new display or touch (indev) drivers you can do so in the `lvgl_esp32_drivers` repo.

