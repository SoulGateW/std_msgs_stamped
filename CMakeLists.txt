cmake_minimum_required(VERSION 2.8.3)
project(std_msgs_stamped)

#------------------------------------------------------------------------------#
#----                              Configure                               ----#
#------------------------------------------------------------------------------#

find_package(catkin REQUIRED COMPONENTS
      std_msgs
      message_generation)

add_message_files(
      FILES
      BoolStamped.msg
      ByteStamped.msg
      ByteMultiArrayStamped.msg
      CharStamped.msg
      ColorRGBAStamped.msg
      DurationStamped.msg
      Float32MultiArrayStamped.msg
      Float32Stamped.msg
      Float64MultiArrayStamped.msg
      Float64Stamped.msg
      Int8MultiArrayStamped.msg
      Int8Stamped.msg
      Int16MultiArrayStamped.msg
      Int16Stamped.msg
      Int32MultiArrayStamped.msg
      Int32Stamped.msg
      Int64MultiArrayStamped.msg
      Int64Stamped.msg
      StringStamped.msg
      TimeStamped.msg
      UInt8MultiArrayStamped.msg
      UInt8Stamped.msg
      UInt16MultiArrayStamped.msg
      UInt16Stamped.msg
      UInt32MultiArrayStamped.msg
      UInt32Stamped.msg
      UInt64MultiArrayStamped.msg
      UInt64Stamped.msg
)

generate_messages(
      DEPENDENCIES
      std_msgs
)

catkin_package(
      CATKIN_DEPENDS
      std_msgs
)

#------------------------------------------------------------------------------#
#----                                Build                                 ----#
#------------------------------------------------------------------------------#

include_directories(
      ${catkin_INCLUDE_DIRS}
)

#------------------------------------------------------------------------------#
#----                                Install                               ----#
#------------------------------------------------------------------------------#


#------------------------------------------------------------------------------#
#----                                Testing                               ----#
#------------------------------------------------------------------------------#


#------------------------------------ END -------------------------------------#
