Network Protocols

1. IP (address + port)
  1.1 address IPv4 216.58.215.110, IPv6 2a00:1450:401b:807::200e (216.58.215.110->NAT<-192.168.1.1)
  1.2 ports 1-65000
  2.3 TCP
  2.4 UDP
  2.5 ICMP

2. Client and Server
  2.1 Browser (Client) -> Google (Server)
    Send Data Request -> google.com (how to earn money)
    Request -> https://www.google.com/search?q=news
    www.google.com - address of server - 216.58.215.110
    https:// - HyperText Transfer Protocol Secure - default 443 (http default port - 80)
    search - path to end-point (resource)
    ?q=news - parameters to end-point (resource) (q - parameter name, news - parameter value)

3. OSI - 7 levels
  1 level - Physical
  2 level - Data link
  3 level - Packet
  4 level - Transport (IP)
  5 level - Session (Data)
  6 level - Presentation (Data)
  7 level - Application (Data)

4. DNS - domain name server
  Server gives IP by domain name

5. HTTP protocol
  Request:
    Methods: GET, POST, PUT, DELETE, HEAD, OPTIONS, TRACE, PATCH, CONNECT
    Headers: sessionId, cookies, etc.
    Body: data inside request
  Response:
    Headers: sessionId, cookies, etc.
    Body: data inside response
    CODE: 200 - success

6. HTTPS = HTTP + secure (certificate)

7. FTP = File Transfer Protocol
