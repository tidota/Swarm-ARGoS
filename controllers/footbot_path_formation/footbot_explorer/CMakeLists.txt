add_library(footbot_explorer MODULE footbot_explorer.h footbot_explorer.cpp
  motor_schema.cpp motor_schema.h behaviour.cpp behaviour.h vec2d.h)
target_link_libraries(footbot_explorer
  argos3core_simulator
  argos3plugin_simulator_footbot
  argos3plugin_simulator_genericrobot)

