# Web Forms Testing Rules

*Start with positive testing first (* Start with Happy Path testing first. No other tests until we make sure that an instance of a completed form passes)

### 1. Required fields
+ Each required field has an asterisk
+ Error message provided if required field is empty (has no input)
### 2. Data retained in database - test for each field
### 3. Emails retaining data (if applicable)
+ send to correct email address
+ correct data sent out for each field
### 4. Values in lists
+ one value represents the entire list - one test case per list is enough
+ values to be consistent with the rest of the list
+ values offered in the list to be complete (compare with similar services)
+ make sure “Other”/”None”/”Less than”/”Over” is present when applicable
+ negative test case - assign nothing - get the error message
### 5. Default Button Assignment (Default button  is highlighted  if the field is inactive. It is chosen when push [Enter] button. If it is needed, test that it works properly.) 
+ make sure there is one if it makes sense at all
+ make sure the choice of default button is not conflicting with anything
+ the choice should be consistent from form to form in the application if it has multiple forms
### 6. Controls
+ identical controls in different forms are consistent (look, name, behavior)
+ checkboxes/radiobuttons - have reasonable initial values
### 7. Edit text boxes
+ capacity testing (5 test cases)
+ valid/invalid inputs (3+ test cases)
+ Zip code (digits only, 5 digits only)
+ Phone number: no letters, no special characters (possible exceptions: dash, round brackets, dot, space) 10 digits, 3 text fields for the phone number, two fields for three digits and one for four digits.
+ Email (accept letters, digits, some sp. characters - @ . - _)
+ are wild card accepted? (https://en.wikipedia.org/wiki/Wildcard_character)
+ Date field needs validation for month (01-12), day (01-31), year (1900-current)
+ Time needs validation for minutes (00-59), hours (0-23), seconds (0-59)
### 8. Data input rules
+ use lists whenever possible versus text boxes ( you should use dropdown lists and choose from it neather then input data in text field to minimize mistakes)
+ calculate rather then ask for input ( for example: calculate country by ZIP instead of country name to minimize mistakes)
+ functionality/validation ( ex.: type name in lower case, go to another line, and the name must be displayed with first letter in upper case - this is the functionality of the field. And for [email] field this functionality mustn't work.)
### 9. Exception handling 
+ messaging
+ data loss (если вписываешь данные, переходишь ниже или на другую вкладку и вписанные данные теряются)
### 10. Error/warning messages
Messages:
- Error message   (points to the problem, user cannot proceed
- Warning Message (there is a problem, user is able to proceed)
- Notification messages (no problem, just informing user of some aspects of application work)

Problems in messages:
- Confusing
- Misleading
