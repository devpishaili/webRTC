# Introduction to WebRTC

- [ ] What is webRTC?
- [ ] Web Sockets
- [ ] Socket.io
- [ ] Agora io
- [ ] [Glossary](https://github.com/devpishaili/webRTC/edit/main/README.md#glossary)
- [ ] [Further Reading and References](https://github.com/devpishaili/webRTC/edit/main/README.md#further-reading--reference)
---

### What is WEBRTC?
WebRTC (Web Real-Time Communication) is a technology that enables Web applications and sites to capture and optionally stream audio and/or video media, as well as to exchange arbitrary data between browsers without requiring an intermediary. The set of standards that comprise WebRTC makes it possible to share data and perform teleconferencing peer-to-peer, without requiring that the user install plug-ins or any other third-party software.
[_While WebRTC is largely a peer-to-peer technology, it does still require servers to help signal the initial connection, navigate NATs, and to support advanced calling scenarios._](https://www.youtube.com/watch?v=Y1mx7cx6ckI).

### What are Web Sockets?
WebSocket is bidirectional, a full-duplex protocol that is used in the same scenario of client-server communication. It is a stateful protocol, which means the connection between client and server will keep alive until it is terminated by either party (client or server). After closing the connection by either of the client and server, the connection is terminated from both ends. 

### Socket.io
Socket.IO is a library that enables bidirectional and event based communication between a client and server.It is built on the top of websocket protocol but first of all what does it means the answer to this question is that socket.io enables the client and server to have connection persistent so they can exchange data in realtime.  Socket.io is library that uses websockets under the hood.

### What is a STUN server?
A STUN (Session Traversal of User Datagram Protocol [UDP] Through Network Address Translators [NATs]) server allows NAT clients (i.e. IP Phones behind a firewall) to set up phone calls to a VoIP provider hosted outside of the local network.

The STUN server allows clients to find out their public address, the type of NAT they are behind and the Internet side port associated by the NAT with a particular local port. This information is used to set up UDP communication between the client and the VoIP provider to establish a call. https://www.ietf.org/rfc/rfc3489.txt


### Glossary

- [x] **ICE**: Internal Communication Establishment
- [x] **RTC**: Real-Time Communication
- [x] **SDP**: Session Description Protocol

### Further Reading & Reference

https://medium.com/agora-io/how-does-webrtc-work-996748603141 <br />
https://www.ietf.org/rfc/rfc3489.txt  <br />
https://www.geeksforgeeks.org/what-is-web-socket-and-how-it-is-different-from-the-http/  <br />
https://www.agora.io/en/
