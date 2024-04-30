# dl

Problem Statement - Design a distributed application using RPC for remote computation where
client submits an integer value to the server and server calculates factorial and returns the result to
the client program.
Theory:
Remote Procedure Call (RPC) is a communication protocol that allows a program to execute procedures or
functions located on another computer, typically a remote server, as if they were local. It abstracts away the
complexities of network communication, providing transparency to the client. RPC systems use interface
definition languages to define remote procedures and data types, and they handle marshalling and
unmarshalling of parameters and return values. Despite its convenience, RPC introduces challenges such
as ensuring reliability and compatibility between client and server versions. Overall, RPC is a powerful
paradigm for building distributed applications, enabling seamless communication between components
running on different machines.
1. Open Command Prompt:
On Windows: Press Win + R, type cmd, and press Enter.
On Linux/macOS: Open a terminal.
2. Navigate to the Script's Directory:
Use the cd command to change to the directory where your Python script is located.
For example:
3. Run the Python Script:
Use the python command followed by the name of your Python script to run it.
For example:
First execute factserver.py on command prompt
2
 Department of Artificial Intelligence and Data Science
Then open another Command Prompt window and execute factclient.py
Conclusion
Thus, we have successfully implemented distributed application using RPC for remote computation.
