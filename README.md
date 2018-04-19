# The "std_msgs_stamped" ROS messages

Stamped versions of "std_msgs" ROS messages. These may be useful in several situations. ROS maintainers will not include stamped versions of std_msgs messages in official ROS distributives due to (quite making sense) [following reasons](https://answers.ros.org/question/9715/stamped-std_msgs/):

> We don't plan to offer our own "Stamped" versions of the std_msgs as Header itself is a bit too tied to a 
> particular implementation of coordinate frames (it's only in std_msgs for historical reasons).

Be careful with ROS design ideology when using these.

## Messages included in this package:

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

## Installation:
Clone the package into your catkin workspace folder, and then build using "catkin_make".

```
cd <your_catkin_workspace>/src
git clone https://github.com/SoulGateW/std_msgs_stamped.git
cd ..
catkin_make --pkg std_msgs_stamped
catkin_make install
```
