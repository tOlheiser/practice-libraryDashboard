# Database

## Borrows
*This acts as the central table which students & books connect to.*
* **borrowId**
* **studentId**
* **bookId**
* takenDate
* returnDate

## Students
* **studentId**
* name
* surname
* birthdate
* gender
* class

## Books
* **bookId**
* title
* pagecount
* authorId

### Sub-table: Authors
* **authorId**
* name
* surname

### Sub-table: Publishers
* **publisherId**
* publisherName