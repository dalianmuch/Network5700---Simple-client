High-Level Approach
1st. Use socket to connect to the server
2nd. Send HELLO to server
3rd. Receive STATUS from server
4th. Send SOLUTION to server
5th. Receive another STATUS will go to step 4
     Receive BYE will end the socket connection

Challenges You Faced
didn't find challenges for this project

Overview of How You Tested Your Code
1st. Tried different arguments on command lines
2nd. Assert False when STATUS/BYE messages are in wrong type
