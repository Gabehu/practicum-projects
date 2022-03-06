# Data: 
The data is extracted from SQL queries, conducted outside of this notebook file.

The `books` table (data on books):

- *book_id*
- *author_id*
- *title*
- *num_pages* — number of pages
- *publication_date*
- *publisher_id*


The `authors` table (data on authors):

- *author_id*
- *author*


The `publishers` table (data on publishers):

- *publisher_id*
- *publisher*


The `ratings` table (data on ratings):

- *rating_id*
- *book_id*
- *username* — the name of the user who rated the book
- *rating*


The `reviews` table (data on reviews):

- *review_id*
- *book_id*
- *username* — the name of the user who reviewed the book
- *text* — the text of the review


# Goal:
Using the database provided, analyze the data and create conclusions based on the questions provided

# Content:
- Create a database connection
- Find the number of books released after January 1, 2000.
- Find the number of user reviews and the average rating for each book.
- Identify the publisher that has released the greatest number of books with more than 50 pages (this will help you exclude brochures and similar publications from your analysis).
- Identify the author with the highest average book rating: look only at books with at least 50 ratings.
- Find the average number of text reviews among users who rated more than 50 books.

# Libraries used
pandas
sqlalchemy

# Language used
SQL
