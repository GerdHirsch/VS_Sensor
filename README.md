# VS_Sensor
Sensor Implementation with Policy to manage Observers

Dieses Projekt ist eine header only library mit
einer Demo Anwendung in main.cpp

Das Sensor Template kann mit verschiedenen Policies zur Verwaltung
der Observer (aka Listener) instanziiert werden.
 Policies:
ListenerSingleRawPointerPolicy verwaltet nur einen Observer
ListenerMultiple verwaltet mehrere Observer entweder
als Raw oder als WeakPointer
  

