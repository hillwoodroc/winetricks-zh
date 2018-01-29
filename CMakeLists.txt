project(winetricks-zh)
cmake_minimum_required(VERSION 2.6)

set(WINETRICKS_PREFIX /usr)
set(WINETRICKS_PKGDATADIR ${WINETRICKS_PREFIX}/share/winetricks-zh)
set(WINETRICKS_VERSION 20171018.1)

install(PROGRAMS  winetricks-zh                 DESTINATION ${WINETRICKS_PREFIX}/bin)
install(FILES     icons/winetricks-zh.svg       DESTINATION ${WINETRICKS_PREFIX}/share/icons/hicolor/scalable/apps)
install(FILES     winetricks-zh.desktop         DESTINATION ${WINETRICKS_PREFIX}/share/applications)
install(DIRECTORY verb/                         DESTINATION ${WINETRICKS_PKGDATADIR})
