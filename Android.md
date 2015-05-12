## 模块类型

- Action Bar
- Navigation Drawer
- Fixed Tab
- Spinner
- Notification
- Launcher
- Dialog


## id

id 的命名方式为：类型_名字，类型采用缩写的形式。

| Asset                             | Type	Prefix    | Example                   |
|-----------------------------------|-----------------|---------------------------|
| Button                            | btn_            | btn_done                  |
| EditText                          | et_             | et_username               |
| TextView                          | tv_             | tv_title                  |
| Checkbox                          | chk_            | chk_on                    |
| ImageButton                       | ib_             | ib_avatar                 |
| RadioButton                       | rb_             |	rb_boy                    |
| ToggleButton                      | tb_             | tb_yes                    |
| ImageView                         | iv_             | iv_avatar                 |
| LinearLayout                      | ll_             | ll_name_field             |
| RelativeLayout                    | rl_             | rl_login_form             |
| FrameLayout                       | fl_             | fl_login                  |

[Naming convention for component/widget in xml files](https://github.com/NexMM/android-naming-conventions)

## layout

layout 命名方式为：类型_名字，例如：
- activity_login
- dialog_validate_failure
- listitem_school

## colors

color 的命名方式应该使用颜色的名字。例如white、green、gray_light、gray_dark。

## dimens

dimens 的命名方式为：类型_尺码。类型一般分为字体(font)、空间(space)、控件(例如button、edittext)。尺码使用5种类型xlarge、large、medium、small、xsmall。命名示例如下：
font_xlarge、font_large 、font_normal、font_small、font_xsmall、
spacing_larger、spacing_large、spacing_medium、spacing_small、spacing_tiny
button_larger_height、button_larger_width、button_medium_height、button_short_height 

## icon 

icon 的命名方式为：前缀_类型_

| Asset                             | Type	Prefix    | Example                   |
|-----------------------------------|-----------------|---------------------------|
| Icons                             | ic_             | ic_star.png               |
| Launcher icons                    | ic_launcher     | ic_launcher_calendar.png  |
| Menu icons and Action Bar icons   | ic_menu         | ic_menu_archive.png       |
| Status bar icons                  | ic_notification | ic_notification_msg.png   |
| Tab icons                         | ic_tab          |	ic_tab_recent.png         |
| Dialog icons                      | ic_dialog       | ic_dialog_info.png        |

## drawables

drawable 的命名方式为：类型_名称

| Asset Type    | Prefix        | Example                   |
|---------------|---------------|---------------------------|
| Action bar    | ab_           | ab_stacked.png            |
| Button        | btn_          | btn_send_pressed.9.png    |
| Dialog        | dialog_       | dialog_top.png            |
| Divider       | divider_      | divider_horizontal  .png  |
| Menu          | menu_         | menu_submenu.png          |
| Notification  | notification_ | notification.9.png        |
| Tabs          | tab_          | tab_pressed.png           |

[Naming conventions for drawables](http://petrnohejl.github.io/Android-Cheatsheet-For-Graphic-Designers/#naming-conventions-for-drawables)

## icon

图标文件的命名方式为：前缀_模块_名字

| Asset Type        | Prefix          | Example                   |
|-------------------|-----------------|---------------------------|
| Icons             | ic_             | ic_star.png               |
| Launcher icons    | ic_launcher     | ic_launcher_calendar.png  |
| Action bar icons  | ic_menu         | ic_menu_archive.png       |
| Status bar icons  | ic_stat_notify  | ic_stat_notify_msg.png    |
| Tab icons         | ic_tab          | ic_tab_recent.png         |
| Dialog icons      | ic_dialog       | ic_dialog_info.png        |

[Naming conventions for icon assets](http://petrnohejl.github.io/Android-Cheatsheet-For-Graphic-Designers/#naming-conventions-for-icon-assets)

## background

背景图片文件的命名方式为：前缀_模块_名字。示例如下：

| Asset Type            | Prefix          | Example                   |
|-----------------------|-----------------|---------------------------|
| Background            | bg_             | bg_invitation.png         |
| Launcher background   | bg_launcher     | bg_launcher_calendar.png  |
| Menu background       | bg_menu         | bg_menu_save.png          |
| Button background     | bg_button       | bg_button_submit.png      |
| Tab background        | bg_tab          | bg_tab_selected.png       |
| Dialog background     | bg_dialog       | bg_dialog_validate.png    |

## state

资源文件中如果要标识状态，则在文件问后面添加状态的后缀。示例如下：

| State     | Suffix    | Example                   |
|-----------|-----------|---------------------------|
| Normal    | _normal   | btn_order_normal.9.png    |
| Pressed   | _pressed  | btn_order_pressed.9.png   |
| Focused   | _focused  | btn_order_focused.9.png   |
| Disabled  | _disabled | btn_order_disabled.9.png  |
| Selected  | _selected | btn_order_selected.9.png  |

[Naming conventions for selector states](http://petrnohejl.github.io/Android-Cheatsheet-For-Graphic-Designers/#naming-conventions-for-selector-states)

## .9 文件

.9文件的命名方式为在文件名后面增加.9的后缀。例如btn_order_normal.9.png 
