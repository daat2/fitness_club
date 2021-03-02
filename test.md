## Daat Fitness-Club Testing.

### Manual Testing ###

**Test Objective**

*To satisfy shoppers requirements based on the user stories*

*To test the application can be opened in Heroku*

*Confirm all navigation links works and no broken links*

*users can complete end to end transactions to checout*


**Pre-Requisite(s)**:

*A shopper Access to internet*

*Heroku link sent to shopper and prodcut manager*


**Shopper Test**



1.  Instruction:  log into Heroku using the link sent to you.

  *  Click  on the All products tab, select all products from the list of drop down.
  *  Expected Result: It should display the list of all products.
  *  Actual Result : List of ll products displayed.
  *  Pass/Fail:  Pass

2.  Instruction : Select a product from the list e.g select pinky leggins.

    * Add a quantity using the plus sign or the drop drow button.
    * Expected Result: Quantity Added using the plus sign.
    * Actual result :  Quantity Added  using the plus sign.
    *  Pass or Fail:    Pass


3.   Instruction : Add to bag, checkout securely , then checkout securely again to see total in your bag. 
  
      Note : A shopper have the option to continue shopping which will take you back to the products page 

       and items will still remain in your bag.
     
 * Expected Result:  Shopper was able to check out securely
 * Actual result :  Same as Expected.
 *  Pass/Fail:      Pass.

3.  Instructiobn : On the Checkout order page, complete your personal details and cahrge card details.

    Note : You will be able to see your order summary page, order total, delivery charge if applicable and grand total.

    * Expected Result: Shopper was able to checkout order,view order summary and add card payment.
    * Actual Result: Same as Expected.
    * Pass/Fail #:Pass .


4.  Instruction : Click complete order. 

   * Expected Result: Shopper was able to checkout order,view order summary and add card payment.   
   * Actual Result: Same as Expected 
   * Pass/Fail #:Pass .


5. Instruction: Check an Email confirmation page acknowledging  your  order and payment. 
    * Expected Result : Shopper received an email confirmation of ordre placed .
    * Actual Result: Same as Expected
    * Pass/Fail : Pass


**Test Auditing**

-  Navigate all the links, carry out same process on a random selection of products following the  steps above. 
-  All testing steps described above should pass successfully.

## Prodcut Manager.

- Product manager should be given administrative account to perform Update, Delete and Remove Products.
- For an admin account you will be able to see the product management link on your login details.

- I have tested this part by myself as a store manager and i can confirm the test passed.

## Defect Reports.
 
 In building the project, i have lot of debugging issues mostly with deployments.

 Top most debug issue i faced was my environmental variables,i could not deploy to Heroku due to secret key issues integrity.

 this was a challenging issues for hours.
 
 Other errors are due to page not loading, indentation and syntax erro on python 

 Heroku configuration issues.

 Database Error.
 
  ### Leasson Learnt:
 
I have used this error to understand how to debug issues, have insights on how to troubleshot and learn new skills along

the way.


#### Conclusion:

Having found as many defects as possible, it does not necessarily satisfy the app will be satisfactory to end users.

Certain parts are more prone to errors than others this based on the principle of testing which  states

 *you cannot test every possible combination of scenarios*.

In conclusion, I have carried out regression testing on part of the code not changed to verify 

changes do not affect functionality of unchanged code.

The test have been completed to meet the functional requirements of the project.




