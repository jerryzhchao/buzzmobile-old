#ROS

- Package
  - Packages are folders specifically defined as packages by including a `manifest.xml` or `package.xml`
  - Packages need to be defined in the ROS global packagepath settings
  - So subdirectory organizations don't really matter
  - Workspace needs to be in package path for Rosbuild
  - Packages contain nodes
- Build systems
  - Catkin -> sucks
    - new one
  - rosbuild -> doesn't suck
- Subdirectory
  - They are subfolders, come on now
- topics
  - can publish or subscribe to a single topic
  - Are essentially 
- nodes
  - Nodes are a ROS program
  - Can be a publisher, subsriber, or service (function call and response)
  - subscribe to one or more topics
- messages
  - stuff sent between nodes
- publisher
  - constantly
- subscriber
  - gets alerts from things it is subscribed to and can then do stuff based on them
- service
  - a function call like thing, essentially a 1-time call in ROS
- latched topic
  - provides the last known value instead of timing out 

hydro
