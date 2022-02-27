# Salesforce-Class
- [whatsapp group link for boys](https://chat.whatsapp.com/EcKAZJsvJaq8XSo7QFoWHT)
- [Zoom Link](https://zoom.us/j/93976264086?pwd=MU9IcC9PbXJmcTU1eS8yczFVUjNoUT09)
- Zoom Credential:-  
                   - Zoom Id : 939 7626 4086 
                   - passcode:salesforce

----------------------------------------------------------------------------------------------------------------------------------------
**DAY-1--31-01-2021
- [DAY-1_VIDEO LINK](https://youtu.be/rW-hrimHdyY)
- **DISCUSSED TOPICS:-**
  1. **INTRODUCTION**
     - SALES FORCE--IT IS A CRM TOOL WHICH INCLUDES ALL MODULES IN SINGLE PLATFORM AND IT IS A CLOUD COMPUTIONG PLATFORM
     - CLOUD COMPUTING--STORE THE DATA,PROCESS THE DATA,ACCESS THE DATA THROUGH SERVER WITH HELP OF INTERNET
     - CRM--CUSTOMER RELATIONSHIP MANAGEMENT

---------------------------------------------------------------------------------------------------------------------------------------
**DAY-2--01-02-2021
- [DAY-2_VIDEO LINK](https://www.youtube.com/watch?v=2Ve6cF2eijk)
- **DISCUSSED TOPICS:-**
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
- **DISCUSSED TOPICS:-**
- [Task no:-1](https://trailhead.salesforce.com/content/learn/modules/data_modeling?trailmix_creator_id=digitalbhardwaj&trailmix_slug=for-absolute-beginners)

- **Data Modeling:-tasks:-**
 1. **Understand Custom & Standard Objects:-**
     -  Challenge:-
        - Build a Custom Offer Object
          1. create custom object(Offer)--give the required values
          2. goto Offer object--select field & relationship--give the required values

 2. **Create Object Relationship:-**
    - Challenge:-
      - Create The Relationships For The Offer Object
        1. create custom object(property) and alredy Offer object is created
        2. goto Offer object--goto field & relationship--and give data types:Master Detail,field label:property,field name:property
        3. goto Offer object--goto field & relationship--and give data types:lookup,field label:contact,field name:contact
           
 3. **Work With Schema Builder:-**
  - Challenge:-
    - Use Schema Builder To Create A Custom Field For The Property Object
      1. Goto Object Manager--Select Schema Builder-Select Object Find The Property Object Select Checkbox-Click Element--Select The Text Area--Give The Field Label:Street Address,Field Name:Street_Address,And Select The Checkbox.

- **Master-Detail Relationship:-**
  - Branch is parent
  - students is child
    - Branch is Deleted Automatically Students also Delete
    - Parent is Deleted Automatically Child also Delete

---------------------------------------------------------------------------------------------------------------------------------------------
**DAY-4-03-02-2022
- VIDEO LINK:
- **DISCUSSED TOPICS:-**
- **Lookup Relationship:-**
  - Creates a relationship that links this object to another object. The relationship field allows users to click on a lookup icon to select a value from a popup list. The other object is the source of the values in the list.
  - **example:-**
    - Account to Contact 
    - we create the contacts to account lookup relation we delete account record data and we related data of contact also deleted.
- one to many relationship using master details and lookup
- many to many ralationship using master details in junction object
- many to many relationship creation:-
  1. first we create student group is junction object
  2. secound we create student object,branch object
  3. we go for junction object(student group)--select new--using master details--select one by one student object and branch object
  4. now we check the junction object select new--now we see to many to many relationship
- **example:-**
  - student group Name
    - unity 
  - student
    - mani
  - group
    - mechanical

- self relationship creation look up using same object
- self relationship creation:-
  1. we go for one created object we using lookup relationship we create self relationship
- **example:-**
  - student Name
    - mani
  - branch
    - MECH
  - Refer_by
    - rohit

- **Task:-no:-2**
  1. **Build a Data Model for a Recruiting App:-**
- [TASK-NO-2](https://trailhead.salesforce.com/en/content/learn/projects/build-a-data-model-for-a-recruiting-app)

---------------------------------------------------------------------------------------------------------------------------------------------------
Day-5-(04-02-2021)
- VIDEO LINK:
- **DISCUSSED TOPICS:-**
- **APP CREATION:-**
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

- **TASK LINKS:-no-3**
  1. **Picklist Administration:-**
     - [Picklist Administration](https://trailhead.salesforce.com/content/learn/modules/picklist_admin)
  2. **Accounts & Contacts for Lightning Experience:-**
     - [Accounts & Contacts for Lightning Experience](https://trailhead.salesforce.com/content/learn/modules/accounts_contacts_lightning_experience?trailmix_creator_id=digitalbhardwaj&trailmix_slug=for-absolute-beginners)
  3. **Leads & Opportunities for Lightning Experience:-**
     - [Leads & Opportunities for Lightning Experience](https://trailhead.salesforce.com/content/learn/modules/leads_opportunities_lightning_experience?trailmix_creator_id=digitalbhardwaj&trailmix_slug=for-absolute-beginners)

-------------------------------------------------------------------------------------------------
**Day-6-(07-02-2022)**
- VIDEO LINK:
- **DISCUSSED TOPICS:-**
- **Validation Rule Creation:-**
- **Example:-No:1 (Course Duration Creation In Student Object)**
- when open new record give the starting data is Always Greater then (>) the ending date other wise give the error
  1. Goto Student Object--Create 2 Reports using Date Data Type--one is starting Date and Second is Ending Date--next-save
  2. Goto Student Object--Select Validation Rules--new--give the Rule Name (Duration) and Error Condition Formula (Starting_date__c > Ending_Date__c) and also give the Error Message--save
- **Example:-No:2 (using opportunity object)**
- when open new record select the closed won and it is mandatary to fill the close reason other wise give the Error Message
  1. Goto opportunity object--select text data type--give the Field Name (close reason) --next--save
  2. Goto Validation Rule--new--Give the Rule Name And Error Condition Formula (ISPICKVAL(StageName, "Closed Won") && ISBLANK( close_reason__c )) and also give the Error Message--Save
- **Example:-No:3 (using Lead object)**
- when open new record select closed-converted and is mandatary to fill the AnnualRevenue other wise give the Error Message
  1. Goto Lead Object--Select validation Rule--new--Give the Rule Name And Error Condition Formula (ISPICKVAL(Status, "Closed - Converted") && ISBLANK(AnnualRevenue)) and also give the Error Message--save

- **Task Links:-no-4**
  1. **Create Validation Rules:-**
- [Create Validation Rules](https://trailhead.salesforce.com/en/content/learn/modules/point_click_business_logic/validation_rules)
-------------------------------------------------------------------------------------------
**Day-7--(08-02-2022)**
- video link:
- **DISCUSSED TOPICS:-**
- **Validation Rule Creation:-**
- **Example:-No:4 (Account Name validation In Account Object)**
- When Open New Record give the Account name do not allow the special characters if enter it is showing error message
  1. Goto Account Object--Select Validation Rule--New--Give The Rule Name(Account_Name_validation) And Description(no one can add any special character in Account Name)--And Give The Error Condition Formula (NOT(REGEX(Name,"[a-zA-Z]+"))--And give Error Message--Save
- **Formula Creation:-**
  - It is Only Readable Data Do not Modify
- **Example:-**
  1. Goto Student Object--create 2 text data type fields--save
  2. Goto Student Object --Select Formula Data type--Give The Field Name--Next--Select Advance Formula (Name  +  student_Last_Name__c)next--next--save
- **Task Links:-no-5**
  1. Formulas and Validations:-
- [Formulas and Validations](https://trailhead.salesforce.com/en/content/learn/modules/point_click_business_logic)
- **Roll-Up Creation:-**
- A read-only field that displays the sum, minimum, or maximum value of a field in a related list or the record count of all records listed in a related list.
-------------------------------------------
**DAY-8--09-02-2022**
- **DISCUSSED TOPICS:-**
- **Record Type Creation:-**
- **record type:**
  1. Goto Student Object Select Record Type
     - choose the Master
     - give the Record Type Label (salesforce Student)
     - Description (We are storing the data of salesforce students)
  2. Goto srudent object select Record Type
     - choose the Master 
     - give the Record Type Label (Blockchain Students)
     - Description ()
- **Blockchain:-**
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
**DAY-9--11-02-2022**
- **DISCUSSED TOPICS:-**
- its showing  which field is showing in select field record
  1. Salesforce Fee Showing Only Salesforce PageLayout
     - Goto student object--select new--select text--Give Field Label (Salesforce Fee)--next--disable the Blockchain PageLayout
  2. BlockChain Course Fee Showing Only BlockChain PageLayout
     - Goto student object--select new--select text--Give Field Label (BlockChain Course Fee)--next--disable the Salesforce PageLayout

- How to identify the values in background in salesforce ?
  - Every Records have Generate the Unique id
- **SOQL ?**
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
- **Task Links:-no-6**
  1. **Write SOQL Queries**
- [Write SOQL Queries](https://trailhead.salesforce.com/en/content/learn/modules/apex_database/apex_database_soql)

------------------------------------------------------------
**DAY-10--12-02-2022**
- **DISCUSSED TOPICS:-**
  -  Write SOQL Queries
  - Goto Developer Console--select Query Editor
1. **using Limit**
   - Select id From Account Limit 10--Execute
2. **check the number of counts** 
   - Select Count() From Account--Execute
3. **check the id from account**
   - Select id From Account--Execute
- Goto Account object select Field &Relation--copy the select field names
4. **InnerQuery**
   - SELECT Id,Name,AccountNumber,(SELECT iD,EMAIL,Phone,Title From Contacts) From Account)--Execute

- **Task**
  - **Relationship Queries in SOQL parent to child in Master relationship in custom relationship field**
- **example:1**
  - student is parent
  - student groups is child
  - select id,name,(select id,CreatedById,Name from student_groups__r)from student__c
- **example:2**
  - branch is parent
  - student is child 
- select id,name,(select id,student_Full_Name__c from students__r)from branch__c


- **Task Links:-no-7**
  1. **Customize a Salesforce Object**
     - [Customize a Salesforce Object](https://trailhead.salesforce.com/content/learn/projects/customize-a-salesforce-object?trailmix_creator_id=digitalbhardwaj&trailmix_slug=for-absolute-beginners)
  2. **Salesforce CRM**
     - [Salesforce CRM](https://trailhead.salesforce.com/content/learn/modules/lex_implementation_basics?trailmix_creator_id=digitalbhardwaj&trailmix_slug=for-absolute-beginners)
  3. **Formulas and Validations**
     - [Formulas and Validations](https://trailhead.salesforce.com/content/learn/modules/point_click_business_logic?trailmix_creator_id=digitalbhardwaj&trailmix_slug=for-absolute-beginners)
  4. **Customize the User Interface for a Recruiting App**
     - [Customize the User Interface for a Recruiting App](https://trailhead.salesforce.com/content/learn/projects/customize-the-ui-for-a-recruiting-app?trailmix_creator_id=digitalbhardwaj&trailmix_slug=for-absolute-beginners)

---------------------------------------------------------------------------------------------------------------------------------------------------------
**DAY-11--15-02-2022**
- **DISCUSSED TOPICS:-**
  - **Salesforce Licensing:**
  - **Data Security:**
    - salesforce security model
      1. Organization Level Security 
      2. Object Level
      3. Field Level
      4. Record Level
        - Organization-Wide-Defaults
        - Role Hierarchy
        - Sharing Rule
        - Manual Sharing

- **TASK LICKS:-NO-8**
  - **Salesforce Licensing**
    - [Salesforce Licensing](https://trailhead.salesforce.com/en/content/learn/modules/salesforce-licensing)
  - **Data Security**
    - [Data Security](https://trailhead.salesforce.com/en/content/learn/modules/data_security)

-------------------------------------------------------------------------------------------------
**day-12--17-02-2021**
- **DISCUSSED TOPICS:-**
  - **Data Security:**
  - salesforce security model
    1. **Organization Level Security:**
         1. **Network Access:**
            - it is access the specified ip address only
              - Goto Quick Find--type Network Access
              - New
              - Give the start ip to end ip
         2. **Password:**
            - it is protected the password
              - Goto Quick Find--type passord policies
              - and give the policies
         3. **Login Restriction:**
             - it is allow only the some specified time
                - Goto Quick Find--type profile
                - Select stand platform user
                - Goto last page select the edit of login hours
                - Give the login hours
     2. **Object Level**
         - we are created two users and give the extra excess to the another user
           - Permissions sets
           - Extra Security
           - For user
       - goto users select permission sets--create new--give label name (Account permission)--and also give the license (salesforce)--save
       - select permission sets--goto apps--object settings--select account--give the perrmission--object permissions (select the check box read,create,edit)--and select field permission (click the checkbox of account number)--save
       - goto users select users--select the vanitha user--goto permission set assignments (edit assignments)--select the account permission add--save
     3. **Field Level**
        - we created field is visiable or not visiable to the selected user
          - Profile Level Field
            - goto student object--create a text type field (data science fee)--and remove the mani admin checkbox--save
    4. **Record Level**
         1. **Organization-Wide-Defaults:**
         - **example no:1**
            - Goto Quick Find type sharing settings--select lead object to private--save
            - goto app launcher select the lead and give the record values--save
            - search to todays leads
            - goto users select to profiles--select the another user--select--unselect the last two leads checkboxs--save
         - **example no:2**
            - Goto Quick Find type sharing settings--select oppertunity object to private--save
            - goto app launcher select the oppertunity and give the record values--save
            - all opportunities
            - goto users select to profiles--select the another user--select--unselect the last two opportunity checkboxs--save
         2. **Role Hierarchy:**
            - create the rules
         3. **Sharing Rule:**
            - select sharing settings
            - goto lead sharing rules--new--give the
              1. label name and 
              2. select based on critira
              3. select field (city),operator (equals),value (new delhi) 
              4. give the role,vp marketing 
              5. Readonly --save
         4. **Manual Sharing:**
            - it is direct to share the record
            - goto record value and select content--search to user--save

----------------------------------------------------------------
**day-13--18-02-2022**
- **DISCUSSED TOPICS:-**
- **Assignment Rules:**
- service cloud
- Queues
  - set of users
    1. select new
    2. Give the Label Name (case Queue)--and add to select object (case)--and add to select users (MANIKANTA BALLA,another user)--save
- **case assignment rules**
  1. New
  2. Case Assignment Rule--click to active checkbox--save
  3. set order--1
  4. give the field (case case origin)--operator (equals)--value (phone)
  5. assign (case Queue)
  - checking
  - goto give record data--select the checkbox of assign using active assignment rule--save
  - chage to users

- **salesforce there are 3 automations**
  - workflow
  - process builder
  - flow builder
- freelancing work

**1. workflow rules:**
  - **goto workflow rules**
  - select stdent object--and create the email data type--save
  - goto workflow rules--new--continue with work flow--select object (Student)--next--Rule Name (Work)--select create checkbox--Rule Criteria  (criteria are met)--field (student),operator (equals),value (new delhi)--save
- **Email Templates:**
  - search classic Email template
  - create new template--Text,next--give the floder (unfiled public classic email templates),email template name (sucessfully registered), template unique name (sucessfully_Registered),description (we are sending email to students),subject (welcome)--email body (hi (student_cname_c) we are enrolled to join the course )--save
- **Email Alerts:**
  - student field,name,student_c_name_c
  -  description (student registration)--select email field--add--save
- **checking:-**
  - give the stdent object to give the required data and mail is sending automatically
- **field updates**
  - new-- give the name (field update)--select student,salesforce fee--next--
  - use a formula to set the new value-- text (25000)--check the sintex--save
- **checking:-**
  - give the student field data--it is attomatically give the sales force fee

**2. process builder**
   - search procee builder-- give the process name ()->A record changes->save
   - select object oppertunity--save
   - Add Criteria->give the criteria name (checking the stage)->select the field (opportunity stage) choose,equals,picklist,closed won--save
   - add action->action type (create a record)->action name (create a contract)->record type (contract)->
   - field (account id),type (field reference),value (account id),(account id)->choose
   - field (status),type (picklist),value (draft)
   - field (contract start dates),type (formula),click the build a formula->insert the function->date & time ->TODAY()->Choose->use te formula
   - field (contract team),type (number),value (12)
   - save
- **checking:-**
  - goto oppertunity object record give the required data
  - te contracts object record is atomatically stored the record using process builder

**3. flow builder:**
- **example:1**
  - go to flow->Record Triggered Flow->create->select the account object->select fast field updates->done
  - select freeform
  - create the assignment->give the label (update the field)->
  - variables ($Record > account number),operator (equals),value (anu)--save
  - save the flow--active
- **checking:**
  - goto account object give the required field->save
  - the account number field is automatically updated
- **example:2**
- case object:
   - goto case object--create 2 picklists--one is (category)--values (Renewal,inquiry,service,warrantry)--secound one is (case priority),values (1,2,3,4)--another date data type due date--save
   - goto flow builder--record trigger flow--record is created and updated--select case object--select fast field updates
     - select condition requirement (and)
     - field(catagory),operator(equal),value (inquery)--done
  - select freeform
  - managers->new resource->Resource Type (Formula),api name (no_of_days),data type (number),decimal places (2),formula ({!$Record.due_date__c}-{!$Flow.CurrentDateTime})->done
  - decision element->label name (checking the no of days)
  - outcome details:1
    - label (if no of days less then 30),condition (and),resource (no_of_days),operator (less then),value (30)
  - outcome details:2
    - label (if no of days greater then 30 and less then 60),condition (and),([resource (no_of_days),operator (less then or equal),value (60)] And [resource (no_of_days),operator (greater then or equal),value (30)])
  - outcome details:3
    - label (if no of days greater then 60 and less then 90),condition (and),([resource (no_of_days),operator (less then or equal),value (90)] And [resource (no_of_days),operator (greater then or equal),value (60)])
  - outcome details:4
    - label (if no of days greater then 90),condition (and),([resource (no_of_days),operator (greater then or equal),value (90)])
  - done
  - new assignment:1
    - label (update 1),variable ($record > case priority),operator (equals),value (1)->done
  - new assignment:2
    - label (update 2),variable ($record > case priority),operator (equals),value (2)->done
  - new assignment:3
    - label (update 1),variable ($record > case priority),operator (equals),value (3)->done
  - new assignment:4
    - label (update 4),variable ($record > case priority),operator (equals),value (4)->done
  - connect the flows->save->give the flow label (case updated)->save
- **checking:-**
  - goto case object give the required field and the case priority is dependend on the due date on the field

- **TASK LICKS:-NO-9**
  - **Flow Builder (3/5)**
    - [Flow Builder](https://trailhead.salesforce.com/en/content/learn/modules/flow-builder)
  - **Build Flows with Flow Builder (done)**
    - [Build Flows with Flow Builder](https://trailhead.salesforce.com/en/content/learn/trails/build-flows-with-flow-builder)
  - **Flow Basics (done)**
    - [Flow Basics](https://trailhead.salesforce.com/content/learn/modules/flow-basics)
  - **Salesforce Flow (1/4)**
    - [Salesforce Flow](https://trailhead.salesforce.com/content/learn/modules/business_process_automation)
  - **Set Up Case Escalation and Entitlements (0/7)**
    - [Set Up Case Escalation and Entitlements](https://trailhead.salesforce.com/content/learn/projects/set-up-case-escalation-entitlements)
- udemy course (The Complete Salesforce Development Course)
  - [udemy course](https://www.udemy.com/course/salesforce-development/)
- [REFERENCE](dataloader.io/static/#tasks)

---------------------------------------------------------------------------------------------------------------------------------------------------
