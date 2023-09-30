[[SE 3309 - Group Project - Ideas]]

Comparison 

- List Users in Hackathon table with group attribute 
    

- Hackathon lists users. User has an attribute indicating which team they are part of (Group1) 
    
- Much fewer tables (Just the one for the hackathon) 
    
- How to assign group owner? 
    

- Extra attribute in table? Is group owner (yes/no) 
    

- Needed in other approach anyways 
    

- Each user has a status. Make owner status? (pending, approved, denied, owner) 
    

- Easier to iterate through because 1 table 
    
- How to view available teams? 
    

- Would need to search entire list of participants to see what group they are part of 
    
- Separate table to list teams? 
    

- At that point is it worth it to just go with other approach? Would still require a lot more tables in second approach. This approach would only add 1 
    
- List teams in hackathon table and users in team table 
    

- Results in a lot of tables each needing their own unique id/name (across ALL hackathons) 
    

- Can just have generated id for team 
    

- Where to put participant who hasn’t joined group yet? 
    

- General team? User is added to general team (not actual team and with no member limit) temporarily and then can join desired team/create team 
    

- Easier to summarize team. Find id from hackathon table and just pull all info from corresponding team table 
    
- Harder to summarize User. Requires going to hackathon then search each group for user
