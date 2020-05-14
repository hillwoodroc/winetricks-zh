project(winetricks-zh)
cmake_minimum_required(VERSION 2.6)

set(PREFIX /usr)
set(PKGDATADIR ${PREFIX}/share/winetricks-zh)
set(WINETRICKS_VERSION 20200421.2)

install(PROGRAMS  winetricks-zh                 DESTINATION ${PREFIX}/bin)
install(FILES     icon/winetricks-zh.svg       DESTINATION ${PREFIX}/share/icons/hicolor/scalable/apps)
install(FILES     winetricks-zh.desktop         DESTINATION ${PREFIX}/share/applications)
install(DIRECTORY verb/                         DESTINATION ${PKGDATADIR})
