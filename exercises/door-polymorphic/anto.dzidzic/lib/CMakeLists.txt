ADD_LIBRARY(
  door-polymorphic-anto.dzidzic

  door.h
  door.cpp

  motor.h
  motor-mock.h
  motor-mock.cpp

  light-barrier.h
  light-barrier.cpp

  push-button.h
  push-button.cpp
)

TARGET_INCLUDE_DIRECTORIES(
  door-polymorphic-anto.dzidzic

  PUBLIC
  .
)
