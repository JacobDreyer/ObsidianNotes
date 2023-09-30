### Naming
![[Pasted image 20230308124101.png]]

### Identifying Boundary Objects
- Boundary Objects represent the system interface with the actors
- The boundary object collects the information from the actor and translates it into a form that can be used by both entity and control objects

##### Heuristics for Identifying Boundary Classes
- Select a [[Noun]] that can be used to
	- Identify user interface controls that the user needs to initiate the [[Use Case]] (e.g., ReportEmergencyButton)
	- Identify forms the users needs to enter data into the system (e.g. EmergencyReportForm)
	- Identify Notices and Messages the system uses to respond to the user (e.g. AcknowledgementNotice)
	- Always use the end user's terms for describing interfaces; do not use terms from the solution or implementation domains
	- 