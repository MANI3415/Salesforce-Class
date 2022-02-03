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
  - INTRODUCTION
  - SALES FORCE--IT IS A CRM TOOL WHICH INCLUDES ALL MODULES IN SINGLE PLATFORM AND IT IS A CLOUD COMPUTIONG PLATFORM
  - CLOUD COMPUTING--STORE THE DATA,PROCESS THE DATA,ACCESS THE DATA THROUGH SERVER WITH HELP OF INTERNET
  - CRM--CUSTOMER RELATIONSHIP MANAGEMENT

-----------------------------------------------------------------------
**DAY-2--01-02-2021
- VIDEO LINK:https://www.youtube.com/watch?v=2Ve6cF2eijk
- DISCUSSED TOPICS:-
  - SalesForce Account Creation
  - CREATE OBJECT

    - GOTO OBJECT MANAGER--CREATE CUSTOM OBJECT--AND GIVE THE LABEL NAME AND PLURAL LABEL --ALLOW EVERYTHING--SAVE
    - IT IS OPEN TAG AND SELECT TAB STYLE--SAVE

  - LETS CHECKING OBJECT

    - GOTO SETTING--SETUP--SELECT OBJECT MANAGER--SEARCH THE OBJECT NAME--ITS SHOWING API NAME(API NAME IS CREATING BY SALESFORCE FOR BACKEND)

  - WHEN WAS CREATED CUSTOM OBJECT BY DEFAULT FIELD & RELATIONSHIPS IS CREATED
    - FIELD & RELATIONSHIPS:-FIELD LABEL:-
                                        - CREATED BY 
                                        - LAST MODIFIED BY
                                        - OWNER
                                        - NAME
   - CREATE REPORTS:-

     - GOTO APP LAUNCHER--SEARCH OBJECT SELECT--SELECT NEW--ONLY ONE FIELD IS THERE--SO CREATING ANOTHER FIELD
     - GOTO SETTING SELECT EDIT OBJECT--SELECT OBJECT MANAGER--SEARCH THE OBJECT NAME--SELECT NEW--SELECT THE FIELD TYPE(EMAIL)--GIVE THE NAME AND PERMISSIONS--NEXT.
       
- CHECK THE REPORTS
- GOTO APP LAUNCHER--SEARCH OBJECT SELECT--SELECT NEW--THERE ARE TWO FIELD IS THERE--NAME,EMAIL

-------------------------------------------------------------------------------------------------------------
**DAY-3--02-02-2022
- VIDEO LINK:
- DISCUSSED TOPICS:-
- https://trailhead.salesforce.com/content/learn/modules/data_modeling?trailmix_creator_id=digitalbhardwaj&trailmix_slug=for-absolute-beginners

- Understand Custom & Standard Objects:-
 - Build a Custom Offer Object
   1. create custom object(Offer)--give the required values
   2. goto Offer object--select field & relationship--give the required values

- Create Object Relationship:-
 - Create The Relationships For The Offer Object
   1. create custom object(property) and alredy Offer object is created
   2. goto Offer object--goto field & relationship--and give data types:Master Detail,field label:property,field name:property
   3. goto Offer object--goto field & relationship--and give data types:lookup,field label:contact,field name:contact
           
- Work With Schema Builder:-
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
  - S10

