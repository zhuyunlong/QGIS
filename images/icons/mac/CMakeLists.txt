
IF (WITH_DESKTOP)
  FILE (GLOB ICONS *.icns)
  INSTALL (FILES ${ICONS}
           DESTINATION ${CMAKE_INSTALL_PREFIX}/../Resources)
ENDIF (WITH_DESKTOP)
