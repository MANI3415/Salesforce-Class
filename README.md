# Salesforce-Class
- whatsapp group link for boys:https://chat.whatsapp.com/EcKAZJsvJaq8XSo7QFoWHT
- Zoom Link: https://zoom.us/j/93976264086?pwd=MU9IcC9PbXJmcTU1eS8yczFVUjNoUT09 
- Zoom Credential:-  
                   - Zoom Id : 939 7626 4086 
                   - passcode:salesforce

-------------------------------------------------------------------
**DAY-1--31-01-2021
- VIDEO LINK:https://youtu.be/rW-hrimHdyY
- DISCUSSED TOPICS:-
  1. INTRODUCTION
     - SALES FORCE--IT IS A CRM TOOL WHICH INCLUDES ALL MODULES IN SINGLE PLATFORM AND IT IS A CLOUD COMPUTIONG PLATFORM
     - CLOUD COMPUTING--STORE THE DATA,PROCESS THE DATA,ACCESS THE DATA THROUGH SERVER WITH HELP OF INTERNET
     - CRM--CUSTOMER RELATIONSHIP MANAGEMENT

-----------------------------------------------------------------------
**DAY-2--01-02-2021
- VIDEO LINK:https://www.youtube.com/watch?v=2Ve6cF2eijk
- DISCUSSED TOPICS:-
  - SalesForce Account Creation
  - CREATE OBJECT:-
    1. GOTO OBJECT MANAGER--CREATE CUSTOM OBJECT--AND GIVE THE LABEL NAME AND PLURAL LABEL --ALLOW EVERYTHING--SAVE
    2. IT IS OPEN TAG AND SELECT TAB STYLE--SAVE
    
  - LETS CHECKING OBJECT:-
    1. GOTO SETTING--SETUP--SELECT OBJECT MANAGER--SEARCH THE OBJECT NAME--ITS SHOWING API NAME(API NAME IS CREATING BY SALESFORCE FOR BACKEND)

  - WHEN WAS CREATED CUSTOM OBJECT BY DEFAULT FIELD & RELATIONSHIPS IS CREATED
    - FIELD & RELATIONSHIPS:-FIELD LABEL:-
                                        1. CREATED BY 
                                        2. LAST MODIFIED BY
                                        3. OWNER
                                        4. NAME
   - CREATE REPORTS:-
     1. GOTO APP LAUNCHER--SEARCH OBJECT SELECT--SELECT NEW--ONLY ONE FIELD IS THERE--SO CREATING ANOTHER FIELD
     2. GOTO SETTING SELECT EDIT OBJECT--SELECT OBJECT MANAGER--SEARCH THE OBJECT NAME--SELECT NEW--SELECT THE FIELD TYPE(EMAIL)--GIVE THE NAME AND PERMISSIONS--NEXT.
       
   - CHECK THE REPORTS
     1. GOTO APP LAUNCHER--SEARCH OBJECT SELECT--SELECT NEW--THERE ARE TWO FIELD IS THERE--NAME,EMAIL

-------------------------------------------------------------------------------------------------------------
**DAY-3--02-02-2022
- VIDEO LINK:
- DISCUSSED TOPICS:-
- Task no:-1
- https://trailhead.salesforce.com/content/learn/modules/data_modeling?trailmix_creator_id=digitalbhardwaj&trailmix_slug=for-absolute-beginners

- Data Modeling:-tasks:-
 1. Understand Custom & Standard Objects:-
     -  Challenge:-
        - Build a Custom Offer Object
          1. create custom object(Offer)--give the required values
          2. goto Offer object--select field & relationship--give the required values

 2. Create Object Relationship:-
    - Challenge:-
      - Create The Relationships For The Offer Object
        1. create custom object(property) and alredy Offer object is created
        2. goto Offer object--goto field & relationship--and give data types:Master Detail,field label:property,field name:property
        3. goto Offer object--goto field & relationship--and give data types:lookup,field label:contact,field name:contact
           
 3. Work With Schema Builder:-
  - Challenge:-
    - Use Schema Builder To Create A Custom Field For The Property Object
      1. Goto Object Manager--Select Schema Builder-Select Object Find The Property Object Select Checkbox-Click Element--Select The Text Area--Give The Field Label:Street Address,Field Name:Street_Address,And Select The Checkbox.

- Master-Detail Relationship:-
  - Branch is parent
  - students is child
    - Branch is Deleted Automatically Students also Delete
    - Parent is Deleted Automatically Child also Delete

---------------------------------------------------------------------------------------------------------------
**DAY-4-03-02-2022
- VIDEO LINK:
- DISCUSSED TOPICS:-
- Lookup Relationship:- 
  - Creates a relationship that links this object to another object. The relationship field allows users to click on a lookup icon to select a value from a popup list. The other object is the source of the values in the list.
  - example:-
    - Account to Contact 
    - we create the contacts to account lookup relation we delete account record data and we related data of contact also deleted.
- one to many relationship using master details and lookup
- many to many ralationship using master details in junction object
- many to many relationship creation:-
  1. first we create student group is junction object
  2. secound we create student object,branch object
  3. we go for junction object(student group)--select new--using master details--select one by one student object and branch object
  4. now we check the junction object select new--now we see to many to many relationship
- example:-
  - student group Name
    - unity 
  - student
    - mani
  - group
    - mechanical

- self relationship creation look up using same object
- self relationship creation:-
  1. we go for one created object we using lookup relationship we create self relationship
- example:-
  - student Name
    - mani
  - branch
    - MECH
  - Refer_by
    - rohit

- Task:-no:-2
  1. Build a Data Model for a Recruiting App:-
- https://trailhead.salesforce.com/en/content/learn/projects/build-a-data-model-for-a-recruiting-app

---------------------------------------------------
Day-5-(04-02-2021)
----------------------
- VIDEO LINK:
- DISCUSSED TOPICS:-
- APP CREATION:-
  - Search Quick Find--App Manager--Select New Lightning App--give the app name--next--next--select the navigation items--next--select the system administrator--save&next
- students to create 2 picklist----1.city 2.country
  1. label--city
    - enter vale
      - mumbai 
      - pune
      - delhi
      - hyderabad
      - bengaluru
      - sydney
      - auckland
      - loundon
      - kakinada
  2. label--country
     - enter value
      - india
      - austalia
      - England
      - newzeland 
- check the picklist:-
  - now click the app launcher seach the student object--select new--to see the picklists

- created a picklists into global:-
  - goto home--search pick list value sets--give label name--use the global picklist value set
  - goto student object--select field&relationship--select field dependendies--new--select Controlling Field--select Dependent Field--select the included values in the controlling fields--save

- TASK LINKS:-no-3
  1. Picklist Administration:-
     - https://trailhead.salesforce.com/content/learn/modules/picklist_admin
  2. Accounts & Contacts for Lightning Experience:-
     - https://trailhead.salesforce.com/content/learn/modules/accounts_contacts_lightning_experience?trailmix_creator_id=digitalbhardwaj&trailmix_slug=for-absolute-beginners
  3. Leads & Opportunities for Lightning Experience:-
     - https://trailhead.salesforce.com/content/learn/modules/leads_opportunities_lightning_experience?trailmix_creator_id=digitalbhardwaj&trailmix_slug=for-absolute-beginners

-------------------------------------------------------------------------------------------------
- Day-6-(07-02-2022)
--------------------
- VIDEO LINK:
- DISCUSSED TOPICS:-
- Validation Rule Creation:-
- Example:-No:1 (Course Duration Creation In Student Object)
- when open new record give the starting data is Always Greater then (>) the ending date other wise give the error
  1. Goto Student Object--Create 2 Reports using Date Data Type--one is starting Date and Second is Ending Date--next-save
  2. Goto Student Object--Select Validation Rules--new--give the Rule Name (Duration) and Error Condition Formula (Starting_date__c > Ending_Date__c) and also give the Error Message--save
- Example:-No:2 (using opportunity object)
- when open new record select the closed won and it is mandatary to fill the close reason other wise give the Error Message
  1. Goto opportunity object--select text data type--give the Field Name (close reason) --next--save
  2. Goto Validation Rule--new--Give the Rule Name And Error Condition Formula (ISPICKVAL(StageName, "Closed Won") && ISBLANK( close_reason__c )) and also give the Error Message--Save
- Example:-No:3 (using Lead object)
- when open new record select closed-converted and is mandatary to fill the AnnualRevenue other wise give the Error Message
  1. Goto Lead Object--Select validation Rule--new--Give the Rule Name And Error Condition Formula (ISPICKVAL(Status, "Closed - Converted") && ISBLANK(AnnualRevenue)) and also give the Error Message--save

- Task Links:-no-4
  1. Create Validation Rules:-
- https://trailhead.salesforce.com/en/content/learn/modules/point_click_business_logic/validation_rules
-------------------------------------------------------------------------------------------
- Day-7--(08-02-2022)
- video link:
- DISCUSSED TOPICS:-
- Validation Rule Creation:-
- Example:-No:4 (Account Name validation In Account Object)
- When Open New Record give the Account name do not allow the special characters if enter it is showing error message
  1. Goto Account Object--Select Validation Rule--New--Give The Rule Name(Account_Name_validation) And Description(no one can add any special character in Account Name)--And Give The Error Condition Formula (NOT(REGEX(Name,"[a-zA-Z]+"))--And give Error Message--Save
- Formula Creation:-
  - It is Only Readable Data Do not Modify
- Example:-
  1. Goto Student Object--create 2 text data type fields--save
  2. Goto Student Object --Select Formula Data type--Give The Field Name--Next--Select Advance Formula (Name  +  student_Last_Name__c)next--next--save
- Task Links:-no-5
  1. Formulas and Validations:-
- https://trailhead.salesforce.com/en/content/learn/modules/point_click_business_logic
- Roll-Up Creation:-
- A read-only field that displays the sum, minimum, or maximum value of a field in a related list or the record count of all records listed in a related list.
-------------------------------------------
- DAY-8--09-02-2022
----------------- 
- Record Type Creation:-
- record type:
  1. Goto Student Object Select Record Type
     - choose the Master
     - give the Record Type Label (salesforce Student)
     - Description (We are storing the data of salesforce students)
  2. Goto srudent object select Record Type
     - choose the Master 
     - give the Record Type Label (Blockchain Students)
     - Description ()
- Blockchain:-
  - stored the data from blocks
  - fully encypted
  - without 3rd party involved
  - Example:-cryptocurrency (Bitcoin)
   3. now we go for page layouts
      - select new
      - select student layout
      - and give page layout name (BlockChain PageLayout)
      - Save
   4. create another page Layout
      - select new
      - select student Layout
      - and give page layout name(SalesForce Page Layout)
      - save
   5. Goto Record Types
      - edit page layout assignment--student
      - page layout to use--blockchain pagelayout to blockchain student
      - page layout to use--salesforce pagelayout to salesforce student
      -save
-------------------------------
- DAY-9--11-02-2022
--------------
- its showing  which field is showing in select field record
  1. Salesforce Fee Showing Only Salesforce PageLayout
     - Goto student object--select new--select text--Give Field Label (Salesforce Fee)--next--disable the Blockchain PageLayout
  2. BlockChain Course Fee Showing Only BlockChain PageLayout
     - Goto student object--select new--select text--Give Field Label (BlockChain Course Fee)--next--disable the Salesforce PageLayout

- How to identify the values in background in salesforce ?
  - Every Records have Generate the Unique id
- SOQL ?
  - It is a Database of Salesforce
  - (Salesforce Object Query Language) together give the developers powerful tools for managing Salesforce data and processes of their application.
- Goto Developer Console
  - select the Query Editor
     1. Check the id's From Account
        - select Id From Account--Execute
     2. check the count from Account
        - SELECT COUNT() FROM Account--Execute
     3. check the ID,Name,AccountNumber,Active_c,OwnerId From Account
        - SELECT ID,Name,AccountNumber,Active_c,OwnerId From Account--Execute

- Goto Home--Select Users--and selcet username of Trainer Salesforce--copy the id
- goto account object select field&relationship--copy the field name of (Active)
     4. where location to find the value
        - SELECT ID,Name,AccountNumber,Active_c,OwnerId From Account WHERE id=" "--Execute
- Task Links:-no-6
  1. Write SOQL Queries
- https://trailhead.salesforce.com/en/content/learn/modules/apex_database/apex_database_soql

------------------------------------------------------------
- DAY-10--12-02-2022
-------------------
- Goto Developer Console--select Query Editor
1. using Limit
   - Select id From Account Limit 10--Execute
2. check the number of counts 
   - Select Count() From Account--Execute
3. check the id from account
   - Select id From Account--Execute
- Goto Account object select Field &Relation--copy the select field names
4. InnerQuery
   - SELECT Id,Name,AccountNumber,(SELECT iD,EMAIL,Phone,Title From Contacts) From Account)--Execute

- Task
- Relationship Queries in SOQL parent to child in Master relationship in custom relationship field
- example:1
  - student is parent
  - student groups is child
  - select id,name,(select id,CreatedById,Name from student_groups__r)from student__c
- example:2
  - branch is parent
  - student is child 
- select id,name,(select id,student_Full_Name__c from students__r)from branch__c


- Task Links:-no-7
  1. Customize a Salesforce Object
- https://trailhead.salesforce.com/content/learn/projects/customize-a-salesforce-object?trailmix_creator_id=digitalbhardwaj&trailmix_slug=for-absolute-beginners
  2. Salesforce CRM
- https://trailhead.salesforce.com/content/learn/modules/lex_implementation_basics?trailmix_creator_id=digitalbhardwaj&trailmix_slug=for-absolute-beginners
  3. Formulas and Validations
- https://trailhead.salesforce.com/content/learn/modules/point_click_business_logic?trailmix_creator_id=digitalbhardwaj&trailmix_slug=for-absolute-beginners
  4. Customize the User Interface for a Recruiting App
- https://trailhead.salesforce.com/content/learn/projects/customize-the-ui-for-a-recruiting-app?trailmix_creator_id=digitalbhardwaj&trailmix_slug=for-absolute-beginners

---------------------------------------------------------------------
- DAY-11--15-02-2022
-----------------------
- Salesforce Licensing:
  
- Data Security:
  - salesforce security model
    1. Organization Level Security 
    2. Object Level
    3. Field Level
    4. Record Level
       - Organization-Wide-Defaults
       - Role Hierarchy
       - Sharing Rule
       - Manual Sharing

- TASK LICKS:-NO-8
- Salesforce Licensing
  - https://trailhead.salesforce.com/en/content/learn/modules/salesforce-licensing
- Data Security
  - https://trailhead.salesforce.com/en/content/learn/modules/data_security

-------------------------------------------------------------------------------------------------
- day-12--(17-02-2022)
- 
