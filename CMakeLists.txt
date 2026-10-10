if(CONFIG_ZMK_KEY_STATS OR CONFIG_ZMK_CUSTOM_SETTINGS)
  target_include_directories(app PRIVATE include)
endif()
