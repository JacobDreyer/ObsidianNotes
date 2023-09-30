Elicitation is a process of discovery used to bring forward or produce information relevant to the project or program by drawing out information from stakeholders and other sources

This process aims to identify the causes of the business problem or the reasons for addressing an opportunity, as well as the information to be used to derive a sufficient level of requirements to enable a solution to be developed and implemented

The result of this activity is a description of the system in terms of actors and use cases
- Actors represent the external entities that interact with the system
	- Actors include roles such as end users, other computers the system needs to deal with
- Use cases are general sequences of events that describe all the possible actions between an actor and the system for a given piece of functionality

### Types of Requirements
##### [[Business Requirement]]
- high-level needs, goals, and objectives of the organization
- They should express what needs to happen, NOT how
- They should be measurable and timebound
- Example: Increase [[Revenue]] be accepting credit-card payments before the new year
##### [[Stakeholder Requirement]]
- Express the needs of a specific stakeholder or group of stakeholders, which may include customers, users, or suppliers
- Communicate the material interest of the stakeholders in the outcome of the product, service, or result
- Provide a basis for identifying the solution requirements
##### [[Solution Requirement]]
- Describe the characteristics of a solution in enough detail to design a solution. Has 2 categories:
	- [[Functional Requirement]]s describe the required behaviors of the solution. These are often expressed from the perspective of the system
		- Examples:
			- Search by product code, name, or category
			- Compliance with specified business rules
			- Expected system behavior when a precondition or system fails
			- Data validation rules
	- [[Non-Functional Requirement]]s are so called because they do not directly specify functionality. Rather, they describe how well the system must perform in its intended environment and how it should respond to constraints on it's behavior. Translate into quality attributes or design goals that directly affect the architecture design. NFRs are also called[[ service-level requirements]], [[supplementary requirements]], and [[quality requirements]]
		- Examples:
			- [[Scalability]] is the ability of the solution to grow and accommodate increased demand or scope.
			- [[Reliability]] describes the level of resiliency of the system
			- [[Availability]] is the ability of the solution to perform its agreed function when required. It includes the specification of when and how the business can access the solution
			- [[Recoverability]] describes how quickly the solution should be made available following an outage
			- [[Capacity]] is the amount of data or services that the solution can manage.
			- [[Maintainability]] is the ability of the system to be changed or repaired easily and it's ability to react to an expanded user base or new business units
			- [[Security]] is the ability to ensure the confidentiality, integrity, and availiblity of assets, information, and services 
			- [[Data Integrity]] is the ability to manage data consistency across the business
			- [[Interoperability]] is the ease with which the solution may be used with other software systems.
			- [[Usability]] is the extent to which its intended users can use the solution with effectiveness, efficiency, and satisfaction.
##### [[Transition Requirement]]
- Describe how the solution will be deployed and released into production - such as [[migration]] and training requirements

### Techniques
##### Interviews
- With all [[Stakeholder]]s (both customers and users)
- Take note and keep track of who said what for traceability and conflict resolution
- May be structured, where questions are prepared in advance of a meeting, or unstructured, where questions are asked in a free-flowing manner based on responses to to previous questions. (or hybrid)
##### Facilitated Workshops
- Convene stakeholders or multidisciplinary teams in a focused and structured session to identify requirements, reconcile differences, and reach consensus among the participants. These interactive workshops enable discovery of requirements while resolving conflicts early in the project life cycle
##### Focus Groups
- Focus groups assemble prequalified participants, such as subject matter experts, in a group setting to share their attitudes and expectations about a particular product, service, or result. The group members voice their opinions and provide clarity on specific topics. This technique provides qualitative feedback that can be further examined as requirements are analyzed
##### Brainstorming (Group Creativity)
- Is a group technique used to generate multiple ideas related to a particular subject. It uses the collective input from the group to understand different perspectives of a problem or solution and to build upon each other's ideas
##### Questionnaires and Surveys
- Used to quickly solicit and obtain information from a large number of users
- Involve prepared questions to elicit subjective and demographic data from respondents
- Can be closed-ended or open-ended
##### Document Analysis
- Document analysis inspects a wide range of materials, such as a glossary of terms, strategic and business plans, process flows, problem/issue logs, regulations, policies, and procedures to discover and/or verify requirements
- This technique provides a good starting point for eliciting relevant product details
- Using up-to-date and accurate documentation is important to safeguard against erroneous information
##### Interface Analysis
- Used to define requirements by examining system interactions between users, processes, and other system components
- It helps to establish relationships and boundaries by determining the input and output needs of each interfacing system
- This method is useful for identifying additional stakeholders who may be impacted by changes to the system interfaces, as well as interoperability issues
##### Prototypes
- A method of obtaining early feedback on requirements by providing a working model of the expected product before actual development
- This model is used to progressively refine requirements by giving stakeholders an opportunity to test, experiment, and provide feedback
##### Mock-ups/Wireframes (Design Thinking)
- Creating mock-ups or wireframes wither on paper or using tools like [[Visio]] to facilitate the communication
- Can be seen as an overlap between [[Requirements Elicitation]], [[Requirements Analysis]], and interface design
##### Observation
- Also known as "job shadowing" provides a way of viewing people in their environment to see how they perform their jobs or tasks can carry out processes within their environment
- The technique is particularly helpful for eliciting tacit requirements that are difficult to verbalize
##### Analyzing Existing Systems
- For system replacement project it might be good to understand how things are currently (previously) done to keep the pros and remove the cons
##### Analyze Similar Systems
- To learn how things are done in the field and find inspiration for the new system and allows the stakeholder to know/confirm what they want
### Success Factors
##### Preparation
- Think about how to conduct elicitation sessions, which stakeholders to involve, and in which order
- Preparation should be completed before requirements can be properly elicited
##### Active Stakeholder Engagement
- Stakeholders are a principal source of requirements, which places them at the center of many project and program issues related to unrealistic expectations, lack of user involvement, and ambiguous, unclear requirements
- Input should be collected from a broad, diverse set of stakeholders to confirm that varying perspectives are captured and to reduce the risk of missing requirements
- Make sure their input is recorded and considered in subsequent steps so that they don't feel like you are wasting their time
##### Defined Business/Organizational Need
- A comprehensive understanding of the business need, problem, or opportunity helps to determine that the right information is elicited and the appropriate stakeholders and elicitation techniques to obtain that information are selected
##### Domain Knowledge
- The person responsible for elicitation should be competent in the domain or have access to subject matter experts for support so as to ask the right questions during elicitation activities. 
- Understanding the relevant terms, processes, and procedures within a specified domain greatly increases the ability to accurately define and examine requirements
##### Plan for the Elicitation
- Select the technique based on the specific project needs and the requirements type you want to collect
- Schedule the meetings and book the rooms ... etc
- Decide on the deliverable expected from the activity
- Plan on how are you going to record the elicited requirements and how to communicate it with the stakeholders
##### Finally
- Conduct the elicitation activity
- Document and communicate the results
