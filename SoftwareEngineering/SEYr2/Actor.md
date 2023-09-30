An actor is drawn in [[UML]] notation useing either a "stick man" or a stereotpyed box, and is labelled with an appropriate name.

![[Pasted image 20230301091507.png]]

### Identifying Actors:
- Anything that you can affect during system design and have some control over, is likely to be part of the system
- Be carefull when it comes to people, some people get benefit from the system and they are not actors
- Note: ==Timer== is often an actor

Asking the following questions will help you to identify actors:
- Who or What uses the system?
- What roles do they play in the interaction?
- Who installs the System?
- Who or what starts and shuts down the system?
- Who maintains the system?
- What other systems interact with this system?
- Who or What gets and provides information to the system?
- Does anything happen at a fixed time?

##### Some Heuristics:
- in Terms of identifying actors remember:
	- Actors are always external to the system - they are therefore outside your control
	- Actors interact directly with the system
	- Actors represent ==roles== that people and things play in relation to the system, not specific people or things
	- Each actor has a unique name and description

We can also have actors inherit other actors (they are similar just specialized more and slightly different)