qt5_add_resources(ukui-theme-customizer_SRCS resources.qrc)
add_executable(ukui-theme-customizer main.cpp ${ukui-theme-customizer_SRCS})
target_link_libraries(ukui-theme-customizer Qt5::Qml Qt5::Gui)

