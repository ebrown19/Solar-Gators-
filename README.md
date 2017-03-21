# Solar-Gators-
2017 Solar Car Code

Message Eric Brown on Slack to be added as a contributor to the repository 

NEEDED PROGRAMS<br />
  -Battery Pack: <br />
      Reads: Voltage, Temperature <br />
      Receives: Voltage, Temperature (From Previous Arduino in Comm. loop) <br />
      Sends: Voltage, Temperature, Alarm if T or V isn't within proper range <br />
  -Battery Management System: <br />
      Receives: Data from battery pack  <br />
      Reads: Current through battery pack <br />
      Sends: Strobe signal if tripped, LED control to cockpit, Data to other devices, Battery charging status  <br />
  -MPPT Board (Max Power Point Tracking):  <br />
      Read: Temperature, Current, Voltage  <br />
      Send/Receive Data  <br />
      Controls duty cycle  <br />
  -DC-DC Converter  <br />
      Read Voltage  <br />
      Output Voltage  <br />
  -Motor Controller  <br />
      Read: Throttle, Brake, Regenerative Braking, "Go Faster" Command, Quadratic Position (encoder?)  <br />
      
      
      
      
      
     
  
      
