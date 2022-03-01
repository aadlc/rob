# Partner’s directory

## Functionalities: 

1. Search for a partner by name 
1. Displays list partners 
1. View partner’s details 

## API calls 

1. Get all partners 
1. Get partner by id (for editing) 

# Partner’s form 

## Functionalities: 

1. Create new partner 
1. Edit existing partner 

 
## API calls 

1. Create new partner 
1. Edit existing partner 

 
## Form JSON schema 

To be included 
 
## Form fields 

1. Partner organization name * (Data type string) 
2. Primary contact person * (Data type string) 
3. Contact email * (Data type string)
4. Secondary email (Data type string)   
5. Contact phone * (Data type string) 
6. Website (Data type string) 
7. Do we have a signed agreement with this Partner? * (Data type string)
* Resource Contact Sheet – RCS 
* Memorandum of Understanding – MOU 
* Program and Service Agreement 
* Other 
* None  
8. Do we require a police clearance for presenters from this organization? * (Data type Boolean)
* Yes 
* No 
9. Please provide an explanation * (Data type string)
> :information_source:  
> Conditionally rendered when Q.8 equals “No”
10. Does the organization has WCB coverage? * (Data type Boolean) 
* Yes 
* No 
11. WCB number * (Data type string) 
> :information_source:  
> Conditionally rendered when Q.10 equals “Yes”
12. Does the organization charges GST? * (Data type Boolean) 
* Yes 
* No 
13. Enter GST number * (Data type string)
> :information_source:  
> Conditionally rendered when Q.12 coverage equals “Yes”
14. Additional Info (Data type string)