### An Application-Layer Protocol Defines:
- Types of messages exchanged:
	- e.g. request, response
- Message syntax:
	- what fields in messages & how fields are delineated
- Message semantics:
	- meaning of information in fields
- Rules for when and how processes send & respond to messages

## Types of Protocols
- Open Protocols:
	- defined in [[RFC]]s, everyone has access to protocol definition
	- allows for interoperability
	- e.g. HTTP, SMTP
- Proprietary Protocols:
	- Skype Zoom

## What Transport Service does an App Need?
[[Data Integrity]]
- Some apps (e.g. file transfer, web transactions) require 100% reliable data transfer
- other apps (e.g. audio) can tolerate some loss

Timing
- some apps (e.g. Internet telephony, interactive games) require low delay to be "effective"

[[Throughput]]
- some apps (e.g. multimedia) require minimum amount of throughput to be "effective"
- other apps (e.g. [[elastic apps]]) make use of whatever throughput they get

Security
- encryption, data integrity

| Application           | Data Loss     | Throughput                             | Time Sensitive? |
| --------------------- | ------------- | -------------------------------------- | --------------- |
| File transfer         | no loss       | elastic                                | no              |
| E-mail                | no loss       | elastic                                | no              |
| Web documents         | no loss       | elastic                                | no              |
| Real time Audio/Video | loss-tolerant | audio: 5Kbps-1Mbps video: 10Kbps-5Mbps | yes, 10's msec  |
| Streaming Audio/Video | loss-tolerant | audio: 5Kbps-1Mbps video: 10Kbps-5Mbps | yes, few secs   |
| Interactive Games     | loss-tolerant | Kbps+                                  | yes, 10's msec  |
| Text Messaging        | no loss       | elastic                                | yes and no      |


