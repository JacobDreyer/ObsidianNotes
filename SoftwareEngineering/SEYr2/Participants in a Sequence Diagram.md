- A [[Sequence Diagram]] is made up of a collection of Participants
	- The parts of your system that interact with each other during a time sequence
- A participant is placed vertically on a sequence diagram
- Participants are always arranged horizontally with no two participants overlapping
- Each Participant has a corresponding lifeline running down the page
![[Pasted image 20230303211005.png]]

### Participant Names:
- Participants on a sequence diagram can be named in a number of different ways, picking elements from the standard format:
	- name [selector] : class_name ref decomposition
	- ex: reports [2] : EmergencyReports
		- a participant accessed at element 2 of an array and is of class EmergencyReports

### Participant Creation and Destruction [[Message]]s
- Participants do not necessarily live for the entire duration of a [[Sequence Diagram]]'s interaction
- Participants can be created and destroyed according to the messages that are being passed
![[Pasted image 20230313160419.png]]

