# Ex.No: 10  Test cases for Library Application

### DATE: 16/10/2024                                                                        
### REGISTER NUMBER : 212222040077
### AIM: 

For Library Application system study its system specifications and generate test cases.

### GUI Test:
Pass criteria: librarians could use this GUI to interface with the backend library database
without any difficulties

### Database Test:
Pass criteria: Results of all basic and advanced operations are normal (refer to section 4)

### Functional Test:

1. ### Add a Student
   □ Each customer/student should have following attributes: Student ID/SSN
(unique), Name, Address and Phone number.

   □ The retrieved customer information by viewing customer detail should contain
the four attributes.

3. ### Update/ Delete student
   □ The record would be selected using the student ID
   
   □ Updates can be made on full. Items only: Name, Address, Phone number
   
   □ The record can be deleted if there are no books issued by user.
   
   □ The updated values would be reflected if the same customer's ID/SSN is called
for.

   □ If customer were deleted, it would not appear in further search queries.

5. ### Add a book

   □ Each book shall have following attributes: Call Number, ISBN, Title, Author
name.

   □ The retrieved book information should contain the four attributes.

7. ### Update/Delete Book
   □ The book item can be retrieved using the call number
   
   □ The data items which can be updated are: ISBN, Title, Author name.
   
   □ The book can be deleted only if no user has issued it.
   
   □ The updated values would be reflected if the same call number is called for.
   
   □ If book were deleted, it would not appear in further search queries.

9. ### Search for book
   □ The product shall let Librarian query books„ detail information by their
ISBN number or Author or Title.

   □ The search results would produce a list of books, which match the
search parameters with following Details: Call number, ISBN
number, Title, Author

   □ The display would also provide the number of copies which is available for issue
   
   □ The display shall provide a means to select one or more rows to a user-list.
   
   □ A detailed view of each book should provide information about checkin/
check out status, with the borrower’s information.

   □ The search display will be restricted to 20 results per page and there
would be means to navigate from sets of search results.

   □ The user can perform multiple searches before finally selecting a set
of books for check in or checkout. These should be stored across
searches.

   □ A book may have more than one copy. But every copy with the same
ISBN number should have same detail information.

   □ The borrower’s list should agree with the data in student’s account.

11. ### Check-in-book
   □ Librarians can check in a book using its call number.
   
   □ The check-in can be initiated from a previous search operation where
user has selected a set of books.

   □ The return date would automatically reflect the current
system date.

   □ Any late fees would be computed as difference between due date and
return date at rate of 10 cents a day.

   □ A book, which has been checked in once, should not be checked in again.

11. ### Check-out-book
   □ Librarians can check out a book using its call number.
   
   □ The checkout can be initiated from a previous search operation where user has selected a set of
books.

   □ The student ID who is issuing the book would be entered.
   
   □ The issue date would automatically reflect the current system date. 
   
   □ The due date would automatically be stamped as 5 days from current date. 
   
   □ A book, which has been checked out once, should not be checked out again.
   
   □ A student who has books due should not be allowed to check out any books.
   
   □ The max. No of books that can be issued to a customer would be 10. The system should not
allow checkout of books beyond this limit.

   □ This view would display details about a selected book from search operation.
   
   □ The details to be displayed are: Call number, IBN, Title, Author, Issue status (In library or
checked out), If book is checked out it would display, User ID & Name, Checkout date, Due
date.

   □ Books checked in should not display user summary.
   
   □ Books checked out should display correct user details.

### View Student details:
□ Librarians can select a user record for detailed view 

□ The detail view should show:
a. User name, ID, Address & Phone number.

b. The books issued by user with issue date, due date, call number, title.

c. Late fees & Fines summary and total.

□ The display should match existing user profile.

□ The books checked out should have their statuses marked.

□ The book search query should show the user id correctly.

### Network test:
Pass criteria: Results of operations (ping, ftp and ODBC connectivity check) are normal

Result: did not test this item, because no enough machines and no available environment.

### Result:
Thus, the Test cases for Banking Application is implemented and output is verified successfully. 
