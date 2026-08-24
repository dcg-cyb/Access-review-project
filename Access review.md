# Before
<img width="2162" height="866" alt="image" src="https://github.com/user-attachments/assets/0ee840f6-ba7f-44df-88f6-706609150f8b" />


# Key findings
**1.** IT Service Desk (Shared Login) - Multiple concurrent sessions / multiple locations

**Concerns:**
Shared login with Sys-Admins group access leaves gap in accounting & logging of user activity. Activity cannot be tied to a singular user given shared access

**Action**: 
a. Sys-Admins Grouping should be removed unless absolutely necessary for Service Desk responsibilities.
b. Individual users within the Service desk group granted user logins for complete repudiation.
     
**2.** Reese Lindqvist - Last login 134 days ago

**Concerns:** 
Likely a user no longer in the organisation. 'Leaver' workflow should have been initiated

**Action:** 
a. Confirm employment status with 2 authoritative figures within HR and department manager.
b. Identify why 'Leaver' workflow was not triggered
     
**3.** Finn Njoku - Assigned 'Privileged Role Administrator' role

**Concerns:** 
User holds enhanced admin rights opposed to eligibility.
     
**Action:** 
Downgrade membership group to PIM-Eligible 
     
**4.** Talia Kellerman - Last login 52 days ago

**Concerns:** 
Potentially a user no longer in the organisation with PII access. 'Leaver' workflow should have been initiated
     
**Action:** 
a. Confirm employment status with 2 authoritative figures within HR and department manager.
b. Identify why 'Leaver' workflow was not triggered
     
**5.** Ivo Salim - Delegated 'SysAdmin' access with no PIM inclusion

**Concerns:** 
User is a DevOps Engineer with 'Sys-Admins' grouping, posing high privilege access within production environments.

**Action:** 
Implement PIM eligibility and JITA
     
**6.** Sarah Petrova - User assigned 'Sys-Admins' membership group whilst being in 'Finance' department.

**Concerns:** 
Privilege creep, likely due to moving roles

**Action:** 
a. Remove 'Sys-Admins' group memebership.
b. Identify why 'Mover' workflow was not triggered
