# Samsung Floating Features Collection For Custom Rom .!!

# Read it : All features came from samsung J6 - S9 - S20 -S21 5G and more .
# Samsung gave them for us those features and we just found them from samsung firmware . Nothing is made by us .

Use them one by one . Dont copy and paste all code on same time . It will give you bootoop . Because some code depend on software and hardware .

You need to add those code into your floating_feature.xml

Use notepad++ for editing floating feature. ( Recommend )

Floating feature locating >

If you have just system partition then 

    system/etc/floating_feature.xml

If you have separate vendor partition then 

    vendor/etc/floating_feature.xml   


# 01 : Screen recorder feature enabler code .

    <SEC_FLOATING_FEATURE_FRAMEWORK_CONFIG_SCREEN_RECORDER_ITEM>-pip</SEC_FLOATING_FEATURE_FRAMEWORK_CONFIG_SCREEN_RECORDER_ITEM>
    <SEC_FLOATING_FEATURE_FRAMEWORK_SUPPORT_SCREEN_RECORDER>TRUE</SEC_FLOATING_FEATURE_FRAMEWORK_SUPPORT_SCREEN_RECORDER>
   
# 02 : Dolby Atmos all feature enabler code .
 
   <SEC_FLOATING_FEATURE_MMFW_SUPPORT_DOLBY_AUDIO>TRUE</SEC_FLOATING_FEATURE_MMFW_SUPPORT_DOLBY_AUDIO>
   <SEC_FLOATING_FEATURE_AUDIO_CONFIG_SOUNDALIVE_NUMBER_OF_SPEAKER>1</SEC_FLOATING_FEATURE_AUDIO_CONFIG_SOUNDALIVE_NUMBER_OF_SPEAKER>
   <SEC_FLOATING_FEATURE_AUDIO_SUPPORT_DUAL_SPEAKER>TRUE</SEC_FLOATING_FEATURE_AUDIO_SUPPORT_DUAL_SPEAKER>
   <SEC_FLOATING_FEATURE_AUDIO_SUPPORT_DOLBY_GAME_PROFILE>TRUE</SEC_FLOATING_FEATURE_AUDIO_SUPPORT_DOLBY_GAME_PROFILE>
   <SEC_FLOATING_FEATURE_AUDIO_SUPPORT_DEFAULT_ON_DOLBY_IN_GAME>TRUE</SEC_FLOATING_FEATURE_AUDIO_SUPPORT_DEFAULT_ON_DOLBY_IN_GAME>
   <SEC_FLOATING_FEATURE_AUDIO_CONFIG_SOUNDALIVE_VERSION>eq_custom,uhq_onoff,karaoke,adapt,spk_stereo,dvfs_700000</SEC_FLOATING_FEATURE_AUDIO_CONFIG_SOUNDALIVE_VERSION>

# 03 : Function menu key enabler code .

    <SEC_FLOATING_FEATURE_SETTINGS_SUPPORT_FUNCTION_KEY_MENU>TRUE</SEC_FLOATING_FEATURE_SETTINGS_SUPPORT_FUNCTION_KEY_MENU>
   
# 04 : High performance enabler code .

    <SEC_FLOATING_FEATURE_COMMON_CONFIG_DYN_RESOLUTION_CONTROL>WQHD,FHD,HD</SEC_FLOATING_FEATURE_COMMON_CONFIG_DYN_RESOLUTION_CONTROL>
    <SEC_FLOATING_FEATURE_COMMON_SUPPORT_HIGH_PERFORMANCE_MODE>TRUE</SEC_FLOATING_FEATURE_COMMON_SUPPORT_HIGH_PERFORMANCE_MODE>

# 05 : High contrast keyboard enabler code .

    <SEC_FLOATING_FEATURE_SIP_SUPPORT_HIGHCONTRAST_KEYBOARD>TRUE</SEC_FLOATING_FEATURE_SIP_SUPPORT_HIGHCONTRAST_KEYBOARD>
   
# 06 : Charging info showing enabler code 

    <SEC_FLOATING_FEATURE_LCD_SUPPORT_AMOLED_DISPLAY>TRUE</SEC_FLOATING_FEATURE_LCD_SUPPORT_AMOLED_DISPLAY>
    
# 07 : All motion features enabler code .

    <SEC_FLOATING_FEATURE_SETTINGS_SUPPORT_DEFAULT_DOUBLE_TAP_TO_WAKE>TRUE</SEC_FLOATING_FEATURE_SETTINGS_SUPPORT_DEFAULT_DOUBLE_TAP_TO_WAKE>
    <SEC_FLOATING_FEATURE_SETTINGS_SUPPORT_MOTION>TRUE</SEC_FLOATING_FEATURE_SETTINGS_SUPPORT_MOTION>
    <SEC_FLOATING_FEATURE_SETTINGS_SUPPORT_MOTION_DOUBLE_TAP>TRUE</SEC_FLOATING_FEATURE_SETTINGS_SUPPORT_MOTION_DOUBLE_TAP>
    <SEC_FLOATING_FEATURE_SETTINGS_SUPPORT_MOTION_PALM_SWIPE>TRUE</SEC_FLOATING_FEATURE_SETTINGS_SUPPORT_MOTION_PALM_SWIPE>
    <SEC_FLOATING_FEATURE_SETTINGS_SUPPORT_MOTION_PALM_TOUCH>TRUE</SEC_FLOATING_FEATURE_SETTINGS_SUPPORT_MOTION_PALM_TOUCH>
    <SEC_FLOATING_FEATURE_SETTINGS_SUPPORT_MOTION_PAN>TRUE</SEC_FLOATING_FEATURE_SETTINGS_SUPPORT_MOTION_PAN>
    <SEC_FLOATING_FEATURE_SETTINGS_SUPPORT_MOTION_PAN_TO_BROWSE_IMAGE>TRUE</SEC_FLOATING_FEATURE_SETTINGS_SUPPORT_MOTION_PAN_TO_BROWSE_IMAGE>
    <SEC_FLOATING_FEATURE_SETTINGS_SUPPORT_MOTION_PICK_UP>TRUE</SEC_FLOATING_FEATURE_SETTINGS_SUPPORT_MOTION_PICK_UP>
    <SEC_FLOATING_FEATURE_SETTINGS_SUPPORT_MOTION_PICK_UP_TO_CALL_OUT>TRUE</SEC_FLOATING_FEATURE_SETTINGS_SUPPORT_MOTION_PICK_UP_TO_CALL_OUT>
    <SEC_FLOATING_FEATURE_SETTINGS_SUPPORT_MOTION_SHAKE>TRUE</SEC_FLOATING_FEATURE_SETTINGS_SUPPORT_MOTION_SHAKE>
    <SEC_FLOATING_FEATURE_SETTINGS_SUPPORT_MOTION_TILT>TRUE</SEC_FLOATING_FEATURE_SETTINGS_SUPPORT_MOTION_TILT>
    <SEC_FLOATING_FEATURE_SETTINGS_SUPPORT_MOTION_TRUN_OVER>TRUE</SEC_FLOATING_FEATURE_SETTINGS_SUPPORT_MOTION_TRUN_OVER>
    
# 08 : Launcher background transparency increaser code .

    <SEC_FLOATING_FEATURE_GRAPHICS_SUPPORT_3D_SURFACE_TRANSITION_FLAG>TRUE</SEC_FLOATING_FEATURE_GRAPHICS_SUPPORT_3D_SURFACE_TRANSITION_FLAG>

# 09 : All dex features enabler code .

    <SEC_FLOATING_FEATURE_COMMON_SUPPORT_DEX_WIRELESS>TRUE</SEC_FLOATING_FEATURE_COMMON_SUPPORT_DEX_WIRELESS>
    <SEC_FLOATING_FEATURE_COMMON_CONFIG_DEX_MODE>dual,wireless,dexforpc</SEC_FLOATING_FEATURE_COMMON_CONFIG_DEX_MODE>

# 10 : All Edge features enabler code .

    <SEC_FLOATING_FEATURE_SYSTEMUI_CONFIG_EDGELIGHTING_FRAME_EFFECT>frame_effect</SEC_FLOATING_FEATURE_SYSTEMUI_CONFIG_EDGELIGHTING_FRAME_EFFECT>
    <SEC_FLOATING_FEATURE_COMMON_CONFIG_EDGE>people,task,circle,panel,-edgefeeds,edgelighting_v2,debug,search,phonecolor,cleanhome</SEC_FLOATING_FEATURE_COMMON_CONFIG_EDGE>
    <SEC_FLOATING_FEATURE_FRAMEWORK_CONFIG_EDGE_QUICKTOOLS_SCREEN_HEIGHT>1317,0</SEC_FLOATING_FEATURE_FRAMEWORK_CONFIG_EDGE_QUICKTOOLS_SCREEN_HEIGHT>

# 11 : Some gallery features enabler code .
    
    <SEC_FLOATING_FEATURE_GALLERY_SUPPORT_MORE_ALBUM>TRUE</SEC_FLOATING_FEATURE_GALLERY_SUPPORT_MORE_ALBUM>
    <SEC_FLOATING_FEATURE_GALLERY_SUPPORT_MOVE_COPY_ALBUM_THUMBNAIL>TRUE</SEC_FLOATING_FEATURE_GALLERY_SUPPORT_MOVE_COPY_ALBUM_THUMBNAIL>
    <SEC_FLOATING_FEATURE_GALLERY_SUPPORT_SLOW_FAST_MOTION_EXPORT>TRUE</SEC_FLOATING_FEATURE_GALLERY_SUPPORT_SLOW_FAST_MOTION_EXPORT>

# 12 : Smart fitting enabler code .

    <SEC_FLOATING_FEATURE_MMFW_SUPPORT_SMARTFITTING>TRUE</SEC_FLOATING_FEATURE_MMFW_SUPPORT_SMARTFITTING>

# 13 : Brief notification enabler code .

     <SEC_FLOATING_FEATURE_SYSTEMUI_SUPPORT_BRIEF_NOTIFICATION>TRUE</SEC_FLOATING_FEATURE_SYSTEMUI_SUPPORT_BRIEF_NOTIFICATION>

# 14 : Navigation bar enabler code .

      <SEC_FLOATING_FEATURE_FRAMEWORK_CONFIG_NAVIGATION_BAR_THEME>SupportLightNavigationBar|SupportCustomBgColor|SupportNaviBarRemoteView</SEC_FLOATING_FEATURE_FRAMEWORK_CONFIG_NAVIGATION_BAR_THEME>

# 15 : Smart switch enabler code .

      <SEC_FLOATING_FEATURE_COMMON_SUPPORT_SMART_SWITCH>TRUE</SEC_FLOATING_FEATURE_COMMON_SUPPORT_SMART_SWITCH>

# 16 : Flash notification enabler code .

      <SEC_FLOATING_FEATURE_COMMON_SUPPORT_FLASH_NOTIFICATION>TRUE</SEC_FLOATING_FEATURE_COMMON_SUPPORT_FLASH_NOTIFICATION>

# 17 : Camera avatar support enabler code .

      <SEC_FLOATING_FEATURE_CAMERA_SUPPORT_AVATAR>TRUE</SEC_FLOATING_FEATURE_CAMERA_SUPPORT_AVATAR>

# 18 : Audio multi device sound enabler code .

      <SEC_FLOATING_FEATURE_AUDIO_SUPPORT_MULTI_DEVICE_SOUND>TRUE</SEC_FLOATING_FEATURE_AUDIO_SUPPORT_MULTI_DEVICE_SOUND>

# 19 : Smooth scroll enabler code .

      <SEC_FLOATING_FEATURE_FRAMEWORK_SUPPORT_SMOOTH_SCROLL>TRUE</SEC_FLOATING_FEATURE_FRAMEWORK_SUPPORT_SMOOTH_SCROLL>

# 20 : Bluetooth audio recorder enabler code .

      <SEC_FLOATING_FEATURE_AUDIO_SUPPORT_BT_RECORDING>TRUE</SEC_FLOATING_FEATURE_AUDIO_SUPPORT_BT_RECORDING>

# 21 : Camera torch brightness level enabler code .

      <SEC_FLOATING_FEATURE_CAMERA_SUPPORT_TORCH_BRIGHTNESS_LEVEL>TRUE</SEC_FLOATING_FEATURE_CAMERA_SUPPORT_TORCH_BRIGHTNESS_LEVEL>

# 22 : Camera support front display flash in night .

       <SEC_FLOATING_FEATURE_CAMERA_SUPPORT_NIGHT_FRONT_DISPLAY_FLASH>true</SEC_FLOATING_FEATURE_CAMERA_SUPPORT_NIGHT_FRONT_DISPLAY_FLASH>

# 23 : Bixby support enabler code .

       <SEC_FLOATING_FEATURE_COMMON_SUPPORT_BIXBY>TRUE</SEC_FLOATING_FEATURE_COMMON_SUPPORT_BIXBY>

# 24 : Ultra power saving enabler code .

       <SEC_FLOATING_FEATURE_COMMON_SUPPORT_ULTRA_POWER_SAVING>TRUE</SEC_FLOATING_FEATURE_COMMON_SUPPORT_ULTRA_POWER_SAVING>

# 25 : 4 Screen mode enabler code .

       <SEC_FLOATING_FEATURE_LCD_CONFIG_DEFAULT_SCREEN_MODE>4</SEC_FLOATING_FEATURE_LCD_CONFIG_DEFAULT_SCREEN_MODE>

# 26 : AC4 Audio codec support enabler code .
      
      <SEC_FLOATING_FEATURE_MMFW_SUPPORT_AC4_CODEC>TRUE</SEC_FLOATING_FEATURE_MMFW_SUPPORT_AC4_CODEC>

# 27 : Weather support detail city viewer code .

      <SEC_FLOATING_FEATURE_WEATHER_SUPPORT_DETAIL_CITY_VIEW>TRUE</SEC_FLOATING_FEATURE_WEATHER_SUPPORT_DETAIL_CITY_VIEW>

# 28 : Corner round disabler code .

      <SEC_FLOATING_FEATURE_SYSTEMUI_CONFIG_CORNER_ROUND>0</SEC_FLOATING_FEATURE_SYSTEMUI_CONFIG_CORNER_ROUND>
