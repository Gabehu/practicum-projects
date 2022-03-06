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
- Following through with each individual tasks

# Libraries used
pandas
sqlalchemy

# Language used
SQL
