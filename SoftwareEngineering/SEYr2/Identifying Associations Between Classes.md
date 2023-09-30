[[Association]]s have several properties:
- A Name to describe the association between the two classes. Association names are optional and need not be unique globally
- A role at each end, identifying the role of each class with respect to the associations (e.g. FieldOfficer has a collection (an array) called reports of type EmergencyReport)
- A multiplicity at each end, identifying the possible number of instances

### Heuristics for Identifying Associations
- Initially the associations between [[Entity Objects]] are the most important, as they reveal more information about the application domain
- Associations can be identified by examining [[Verb]]s and [[Verb Phrases]] (e.g. has, is part of, reports to, etc)
- In addition the following heuristics can be used
	- Examine Verb Phrases
	- Name associations and roles precisely
	- Use qualifiers as often as possible to identify namespaces and key attributes
	- Eliminate any association that can be derived from other associations
	- Do not worry about multiplicty until the set of associations are stable
	- Too many associations make a model unreadable

### Filtering Verb Phrases for Association
- if we consider all [[Association]]s identified after examining [[Verb Phrases]], our model will initially include too many associations
- Adding unecessary associations complicates the model, leading to incomprehensible models and redundant information