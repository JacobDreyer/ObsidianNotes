To write good tests we need to know what the code is supposed to do. What are the requirements?

Example:    To meet the criteria a password must have:
- A length of at least 8
- At least one special character
- At least one uppercase character

Example:    check length is correct (Test Case)
| Input              | Expected Output | Actual Output | Result |
| ------------------ | --------------- | ------------- | ------ |
| ""(Empty Password) | false           | false         | Pass       |

### Three Types of Tests
- Good
	- Tests along the most common code path with expected results
- Bad 
	- Tests along possible errors and expects graceful error
- Boundary
	- Tests at the data boundary for the test with expected results
	- For password example with at least 8 required characters this would include passwords with 7,8,9 characters

