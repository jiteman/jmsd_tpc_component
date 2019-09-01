cmake_minimum_required( VERSION 3.7.1 )

project( jmsd_tp_component )


JMSD_SHOW_PROJECT_GROUP_HEADER()


set( JMSD_COMPONENT_SOURCE_ROOT_PATH ${PROJECT_SOURCE_DIR}/_tp_sources )
set( JMSD_COMPONENT_CMAKE_SETTINGS_PATH ${PROJECT_SOURCE_DIR}/_tp_cmake_settings )


add_subdirectory( tp_base_lib )
# add_subdirectory( tp_derived_lib )
# add_subdirectory( tp_executabe )


JMSD_SHOW_PROJECT_GROUP_FOOTER()
