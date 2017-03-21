# Solar-Gators-
2017 Solar Car Code

Message Eric Brown on Slack to be added as a contributor to the repository 

#### NEEDED PROGRAMS<br />
  ### -Battery Pack: <br />
      Reads: Voltage, Temperature 
      Receives: Voltage, Temperature (From Previous Arduino in Comm. loop) 
      Sends: Voltage, Temperature, Alarm if T or V isn't within proper range 
  ### -Battery Management System: <br />
      Receives: Data from battery pack  
      Reads: Current through battery pack 
      Sends: Strobe signal if tripped, LED control to cockpit, Data to other devices, Battery charging status  
 ###  -MPPT Board (Max Power Point Tracking):  <br />
      Read: Temperature, Current, Voltage  
      Send/Receive Data 
      Controls duty cycle 
 ### -DC-DC Converter  <br />
      Read Voltage  
      Output Voltage  
 ### -Motor Controller  <br />
      Read: Throttle, Brake, Regenerative Braking, "Go Faster" Command, Quadratic Position (encoder?) 
      
      
      
      
      
     
  
      
