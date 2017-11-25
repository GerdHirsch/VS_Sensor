# VS_Sensor
Sensor Implementation with Policy to manage Observers

this is a header only library with a demo application in main.cpp

template<listenerManagePolicy> Sensor is a template which manages its observers aka listeners
 with the given listenerManagePolicy.

provided Policies:
- ListenerSingleRawPointerPolicy manages only one Listener
- ListenerMultiple manages multiple Listener either as 
   - Raw or as 
   - std::weak_ptr
  

