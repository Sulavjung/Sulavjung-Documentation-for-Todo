
## 1. Application Layer: TV, Laptop, and phone support the application layer.
   1. Presentation Layer
      1. SMTP, IMAP, HTTP
   2. Session Layer.
      1. Implementing APIs, Serverless APIs,
      2. Handling encryption
      3. Handling SSL
   3. The order in which the presentation and session layers are implemented depends sending and receiving.

## 2. Transport Layer
   1. Facilitates logical communication between processes.
   2. The transport layer doesn't have access to IP addresses.
   3. This layer implements the TCP and UDP protocols.
   4. TCP is a reliable protocol, whereas UDP isn't reliable.
   5. In TCP, the client requests a connection, and the server acknowledges it. Then the client can send data to the server. However, with UDP, the server cuts off the connection after the data is sent. In TCP, the server acknowledges receipt of data before the client can send more, ensuring reliable transmission.
   6. TCP employs timeouts; if the server fails to respond within a set time, the client resends the data, minimizing the risk of data loss.
   7. UDP is faster, but there's a higher chance of data loss.

## 3. Network Layer
   1. Data Plane:
      - Input buffers exist in the router. Segments created from the transport layer arrive at the input buffer and are then routed to different interfaces.
      - Segments become packets once they reach the input buffer.
      - Routing decisions are made using priority scheduling or round-robin algorithms.
      - The router determines the interface for packet transmission based on the device's IP address. The forwarding protocol is used for this purpose.
   2. Control Plane:
      - Implements routing protocols.
      - Determines the shortest path for packets to reach their destinations.
      - Examples include Link State Protocol and Distance Vector Protocol (Bellman-Ford Algorithm).
      - Routing tables are created based on these protocols.
      - Only the network layer, link layer, and physical layer are accessible from the router. The network layer provides the IP address, guiding the router in data transmission.

## 4. Link Layer
   1. Ensures proper data transfer across links, between machines or routers.
   2. Data traveling through the link layer is referred to as a frame.
   3. When collisions occur between frames sent by two routers, acknowledgments are sent to the sender.
   4. The link layer aims to prevent collisions but cannot guarantee 100% prevention due to potential energy interference, which detects data transmission by other routers.
   5. Source and destination MAC addresses are used by the link layer.

## 5. Physical Layer:
   1. Converts data from binary to volts.
   2. For example, 6-bit data 00100100 is converted to volts, with 0 mapped to 1V and 1 to -1V.



## Drawing: 
<img width="1155" alt="image" src="https://github.com/Sulavjung/Sulavjung-Documentation-for-Todo/assets/79497159/2728b7c2-eb73-443d-bd8d-26bbe06e866b">
