# Interfacing-flightgear-with-UDP-socket.

#copy both input & output protocol files to:

flightgear's installation folder -> data -> protocol.

# configure flightgears' network properties as for example
fgfs--generic=socket,in,1,localhost,8000,udp,output_protocol

Note port numbers should be the same in the code.
