project(winetricks-zh)
cmake_minimum_required(VERSION 2.6)

set(WINETRICKS_PREFIX /usr)
set(WINETRICKS_PKGDATADIR ${IBUS_PREFIX}/share/winetricks-zh)
set(WINETRICKS_VERSION 20171018.1)

install(PROGRAMS  winetricks-zh                 DESTINATION ${IBUS_PREFIX}/bin)
install(FILES     icons/winetricks-zh.svg       DESTINATION ${IBUS_PREFIX}/share/icons/hicolor/scalable/apps)
install(FILES     winetricks-zh.desktop         DESTINATION ${IBUS_PREFIX}/share/applications)
install(DIRECTORY verb/                         DESTINATION ${IBUS_PREFIX}/share/winetricks-zh)
