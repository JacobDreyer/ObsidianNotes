## Services
###### [[TCP]] Service:
- Reliable transport between sending and receiving process
- Flow control: sender won't overwhelm receiver
- Congestion control: throttle sender when network overloaded
- Connection-oriented: setup required between client and server processes
- Does not provide: timing, minimum throughput guarantee, security
###### [[UDP]] Service:
- unreliable data transfer between sending and receiving processes
- does not provide: reliability, flow control, congestion control, timing, throughput guarantee, security, or connection setup

| Application           | [[Application Layer Protocol]]                           | Transport Protocol |
| --------------------- | -------------------------------------------------------- | ------------------ |
| file transfer         | [[FTP]] \[RFC 959]                                       | [[TCP]]            |
| E-mail                | [[SMTP]] \[RFC 5321]                                     | [[TCP]]            |
| Web Documents         | [[HTTP]] \[RFC 7239, 9110]                               | [[TCP]]            |
| Internet Telephony    | [[SIP]] \[RFC 3261], [[RTP]] \[RFC 3550], or proprietary | [[TCP]] or [[UDP]] |
| Streaming Audio/Video | [[HTTP]] \[RFC 7230], [[DASH]]                           | [[TCP]]            |
| Interactive Games     | [[WOW]], [[FPS]] (proprietary)                           | [[UDP]] or [[TCP]] |

