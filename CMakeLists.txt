if(CONFIG_ZMK_STATUS_ADVERTISEMENT OR CONFIG_ZMK_CUSTOM_SETTINGS)
  target_include_directories(app PRIVATE include)
endif()
