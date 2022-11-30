# Book-Rental-Recommendation
DESCRIPTION
Book Rent is the largest online and offline book rental chain in India. They provide books of various genres, such as thrillers, mysteries, romances, and science fiction. The company charges a fixed rental fee for a book per month. Lately, the company has been losing its user base. The main reason for this is that users are not able to choose the right books for themselves. The company wants to solve this problem and increase its revenue and profit. 
Dataset description:
BX-Users: It contains the information of users.
•	user_id - These have been anonymized and mapped to integers
•	Location - Demographic data is provided
•	Age - Demographic data is provided
If available, otherwise, these fields contain NULL-values.
 
BX-Books: 
•	isbn - Books are identified by their respective ISBNs. Invalid ISBNs have already been removed from the dataset.
•	book_title
•	book_author
•	year_of_publication
•	publisher

 
BX-Book-Ratings: Contains the book rating information. 
•	user_id
•	isbn
•	rating - Ratings (`Book-Rating`) are either explicit, expressed on a scale from 1–10 (higher values denoting higher appreciation), or implicit, expressed by 0.
 
Note: Download the “BX-Book-Ratings.csv”, “BX-Books.csv”, “BX-Users.csv”, and “Recommend.csv” using the link given in the Book Rental Recommendation project problem statement.
