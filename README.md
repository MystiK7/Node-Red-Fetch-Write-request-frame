My goal is to send a fetch/write frame into a PLC with Node-Red, in order to collect data thanks to captors.

I created a flow to do that, but I don't very understand how the nodes are working in Node-Red. 
There are several steps to do :
  1. Establish the connection to the port, which is 2000 here (reading).
  2. Creating and sending the fetch/write request frame, who will ask the PLC the data I want to retrieve.
  3. Response of the PLC, and printing the values in Node Red (debug or dashboard). The received frame will be different from the request frame.

 The frame is a 16 bits buffer that I want to send : [83,53,16,1,3,5,3,8,1,62,0,0,0,2,255,2] for example.

 How can I do that ? I know my flow is not running but this was my idea. I am a beginner in Node-Red, so it is a little complicated for now. 

 Thank you for your help :)
