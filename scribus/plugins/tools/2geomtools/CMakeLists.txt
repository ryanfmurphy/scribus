INCLUDE_DIRECTORIES(
  ${CMAKE_SOURCE_DIR}
  ${CMAKE_SOURCE_DIR}/scribus
)

INCLUDE_DIRECTORIES( ${Boost_INCLUDE_DIR} )
ADD_SUBDIRECTORY (meshdistortion)
ADD_SUBDIRECTORY (pathalongpath)
