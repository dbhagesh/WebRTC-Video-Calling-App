# WebRTC (Web Real-Time Communications)
https://webrtc.org/

# NAT (NETWORK ADDRESS TRANSLATION)
https://www.geeksforgeeks.org/network-address-translation-nat/
https://whatismyipaddress.com/nat

# TURN 
https://webrtc.org/getting-started/turn-server

# Creating your own TURN SERVER
https://medium.com/av-transcode/what-is-webrtc-and-how-to-setup-stun-turn-server-for-webrtc-communication-63314728b9d0

# STUN (Session Traversal of User Datagram Protocol [UDP] Through Network Address Translators [NATs]


# ICE (Interactive Connectivity Establishment) protocol



ICE Candidate -> to pass information about current nodes to nearby nodes
https://stackoverflow.com/questions/21069983/what-are-ice-candidates-and-how-do-the-peer-connection-choose-between-them


https://www.wowza.com/blog/webrtc-signaling-servers

Part of what needs to be done involves attempting to go through firewalls and NAT devices. This is done using a protocol called ICE, which collects, exchanges, and then attempts to connect a session using ICE candidates. ICE candidates are pairs of potential addresses that can get the devices to connect to each other either 1) directly by using a private or a public IP address obtained via a STUN server or 2) indirectly through TURN servers.


https://stackoverflow.com/questions/29032884/why-is-a-signaling-server-needed-for-webrtc

Signaling server : pigeon, it exchanges the offer and answer between clients
ICE candidates : its used to get to the client via TURN(RELAY) and STUN(To gets its ip address and port) server
These candidates can be more than one which allows me to reach the destination

