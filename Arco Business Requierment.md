# ```Create Customer```

- If customer wants to take employee(labour) from ARCO for house keeping work (or) car driving, customer should be registered first in ARCO by the sales person.

#### (A). Actions :
- Print:

Print button helps sales user to print the customer details.

#### Message Send List:

All customer send messages are listed here

#### Verify Mobile:


- First process is to create contract for this customer and to verify his mobile number

- Verification code(OTP) sent to customer for mobile verification
- Enter the OTP in the opened popup and verify the mobile number
- Successful message displayed to user if OTP is correct

#### Verify Customer:

- Third process is to "Verify Customer" using following Check list

- Verify Details
- Verify Attachments


#### Once customer verified "verify customer" button hidden to sales user and this confirms customer is verified
- Action
- Refresh
- Back

### In Arco Customer information are separated into customer details page and finance page

# ```Customer Details``` 

- Customer details are further classified into following sections and the sales user have the access
to create following respective section details.

#Identification Section

- Second process is to create contract for this customer and to verify his email

- Verification code(OTP) sent to customer e-mail
- Enter the OTP in the opened popup and verify the e-mail
- Successful message displayed to user if OTP is correct

| work steps | Action |
| ---------- | ------ |
| Work Info Section | ok |
| Profile Picture Section | ok|
| Family Info Section | ok |
| Muqeem Info Section | ok |
| General Section | ok |
| Location Section | ok |
| Contact Section | ok |
| Affiliate Need to check | ok |


Sales users have the option to create following fields and update the following fields

Mobile Number
Email

- Sales users have the option to create "Bank" details and update the "Bank" details

***Active Bank*** 
***My Bank***


# ```Finance``` 

### Once customer details saved, following finace section available to sales users

- Customer Balance
- Customer Invoice
- Payment Details
- Advance Payment
- Customer Refund
- Wallet Transaction


# ```Note : Verification```

### First process to create contract for this customer is to verify his/her "mobile number"

- Verification code(OTP) sent to customer for mobile verification
- Enter the OTP in the opened popup and verify the mobile number
- Successful message displayed to user

### Second process is to create contract for this customer is to verify his Email

- Verification code(OTP) sent to customer e-mail
- Enter the OTP in the opened popup and verify the e-mail
- Successful message displayed to user if OTP is correct

### Third process is to "Verify Customer" using following check list

- Verify Details
- Verify Attachments
- Once customer verified "verify customer" button hidden to sales user and this confirms customer is verified.


# ```Create Per Day Contract``` 

- Once customer mobile number, 
- customer email and verify customer are verfied, 
- Action button enabled to sales user,
- sales user can create perday contract

# ```Job Specification```

- Private Driver
- House Work - Male
- House Work - Female

# ```Nationality```

- All nationality displayed in drop down

# ```Package Days```

- package days maximum is 180 days
- Based on nationality minimum package days may differ

### Promo Code :
### Document Branch :

- Branch location where customers can submit their respective documents.

# ```Service Location``` 

- Save the location using map in "Customer Details Page"

### Create Contract Button : Click on create contract button to create the contract.

### Contract Details Page :

- Contract created for the customer with the following details
(1). Contract Number : IRM000XXXX
(2). Now Contract Status is "New"

***(A). Actions :****
- Payment -

# ```` Send To POS (Point of sales)```` 
- Customer will pay the amount through card swipe machine in branch location, 
- card swipe machine integrated with our ERP system

### POS Manual Payment :

- Pos manual payment helps sales user to get the contract payment from the customer.
- Choose file attachement helps sales user to attach the receipt
- After clicking save button, payment made
- Now Contract Status changed to "Waiting For Selection"

### Pay From Balance-0 :
- pay from balance option helps sales user to get the contract payment from the customer
- Send To Sadad Bill -- Need to check

- Print New -
- Request -
- Attach -
- Refresh -
- Back -

# ```(B). Contract details for customer``` 

### Contract 

- Contract details for customers further classified into following sections

```Contract section```
**Branch : Sales users have the option to change branch
**Change Location : Sales users have the option to change customer branch location, this branch will be contact branch, any document related to the employee will be delivered from here.

### Send Location : Sales users have the option to send employee lodge, branch and both location to customer

- Customer section
- Package section
- Employee section
- Location section
- Contract Delegate section
- Contract Extension Agreement section
- Contract Task section
- Comments section

# ```Finance```

- Advance Payment
- Payment Details
- Request Pending for Payment
- Customer Invoice
- Contract Transaction
- Discount
- Financial Status
- Credit Note
- Credit / Debit Pending Approval
- Customer Refund
- Wallet Transaction

# ```(C). History & Request Sections```

- Contract Package History
- Contract Status History
- Employee History
- Delivery Request
- Customer Request
- Pending Request
- Escape Request
- Sadad Pending Request


# ```Per Day Contract -- After payment made by customer, employee assign to customer```

### (A). Action : Employee Assign :

1. Click on employee assign button to assign the employee
2. Click on select employee and assign the same.
3. Give employee assign date and save the same.
4. Sales user will get "Created Successfull message"
5. Now contract status changed to "Document Verification"

### Document Verification Stage :  

1. Click on "Attachment Button" to upload the contract copy   
2. Click on "Verify Button" and click on "verify" button inside the popup to verify  

if you get message like "Current User Branch Not Found"

- Click on Role Master in security and assign sales user   
- Click on Organization and select "Branches" and Assign sales user  

       ### Note :
        ------
        (1). If the user is not sales user, admin should assign this user to "Sales User Role"
        (1). One Sales user can not handle multiple ARCO branches, only one sales user can handle one ARCO branch
        (2). There are 8 to 9 branches in ARCO
        (3). If sales man will transfer from one branch to another branch admin will
                un-assign that particular sales user from one branch and assign to another branch
                using Menu [Organization----->Branches, click + icon], then only sales user can able to "Verify"
        
3. User will get popup message "Contract Verified"

4.Now contract status changed to "Waiting For Delivery"


# ```(B). ACTION - DELIVERY```

Click on "Delivery" button, popup will open and show following TABS

### TAB 1 : PICKUP FROM LODGE

Customer will pick employee directly from lodge
No charge for customer

### TAB 2 : PICKUP FROM BRANCH
- ARCO deliver the employee ARCO to Branch
- Customer will pick employee from ARCO Branch
- Customer will be charged for the delivery from Arco Lodge to Arco Branch.

### TAB 3 : DELIVER TO HOME
Employee will be delivered directly to home by ARCO.
Customer will be charged for the employee delivery


***After choosing any tabs from the above and save the respective tabs, Delivery work flow process get started...


# ```PER DAY CONTRACT -- Individual Sector---->Labour Movement--->Delivery Request```

(1). Contract Number : IRM000XXXX
(2). Now Contract Status is "Waiting For Delivery"
(A). Request Checkout (Workflow Stage)

### Search contract number

- Click on complete action to move to "Waiting For Checkout"

### (B). Waiting for Checkout (Workflow Stage)

### Search contract number

- Go to Lodging Module and check out the employee LDG-->Labour Movement-->Labour CheckOut

### (C). Labour CheckOut (Workflow)

- LDG-->Labour Movement-->Labour CheckOut
- Click on "Requested" workflow stage
- Lodging user will monitor "Labour Check Out" page
- Lodging user will search employee in "Request" stage and click on "Action"---->Complete
- Employee moved to next stage "Waiting For CheckOut"
- Finger print verification should be made with the device
- If finger print device not available, user will get the message "error - Delivery Request Not Found"
- Waiting For Checkout---->Action--->Complete
- Employee record moved to Complete
- Record moved from LDG module to Individual Sector

### (D).By default Record moved to CSE Confirmation (Individual Sector---->Labour Movement--->Delivery Request)

1. Click on Action--->Complete
(E).Next stage "Delivery To Home" will not go due to customer chosen "Pick up from lodge", so the employee record
directly moved to "Customer Confirmation"
(F). sales user will call customer and check whether employee is delivered or not, upon confirmation from customer through phone, sales user will completed the following stage.
(G). Customer Confirmation (Individual Sector---->Labour Movement--->Delivery Request)
1. Click on Action--->Complete
(H). Now contract status is "CHANGED TO VALID"
(I). PER DAY CONTRACT will be created for customers.

[Low Cost Package Contract](https://gitlab.com/fts-projects/arco-documentation/-/blob/master/Individual%20Sector/Individual%20Sector%20Customer%20Lowcost%20Contract.md)

[Contract Extend](https://gitlab.com/fts-projects/arco-documentation/-/blob/master/Individual%20Sector/Individual%20Sector%20Customer%20Contract%20Extend.md)

[Employee Exchange](https://gitlab.com/fts-projects/arco-documentation/-/blob/master/Individual%20Sector/Individual%20Sector%20Customer%20Contract%20Employee%20Exchange.md)

[Change Nationality](https://gitlab.com/fts-projects/arco-documentation/-/blob/master/Individual%20Sector/Individual%20Sector%20Customer%20Contract%20Change%20Nationality.md)

[Sponsor Change](https://gitlab.com/fts-projects/arco-documentation/-/blob/master/Individual%20Sector/Individual%20Sector%20Customer%20Contract%20Sponsor%20Change.md)
