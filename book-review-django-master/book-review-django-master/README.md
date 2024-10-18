# Book Review Website using Django
Making a book review website using Django for a class assignment
This repository serves as an explanation for the website

### Instructions and Requirements
In this project, I built a book review website. Users will be able to register on the website and then log in using their username and password. Once they log in, they will be able to search for books, leave reviews for individual books, and see the reviews made by other people.

***

## Getting Started

In making this website, no special tools/IDE such as Pycharm or Anaconda were used. Instead, I try to install dependencies through the command line (CMD) for both python and django

The specific tools that were used were: <br>
Text-Editor : Notepad++ <br>
Browser     : Google Chrome


## The Website

The book review website is named **Andi's Book**.
<br>
Here we will demonstrate the whole process of starting the website and how it operates.

We start by running the django server.
```
python manage.py runserver
```
And then accesssing the *localhost:8000/reviews*.

We should arrive at **Andi's Book** website homepage which displays recent reviews made by other users.
![Home](https://github.com/andkwv/book_review_django/blob/master/andisbook/images/home.png)


On the nav-bar we can see a few options :
- **Book List**: This bar will take you to the catalog of books that is already registered registered
- **Login**: This bar allows existing users to login
- **Register**: This bar allows new users to register

On the **Book List** webpage we can see a list of books. Each book has an author and an average number of rating that it has.
By clicking one of the Books, we will arrive at the book detail webpage which shows the details of the book as well as the reviews made by other users.

![Book_List](https://github.com/andkwv/book_review_django/blob/master/andisbook/images/book_list.png)

![Book_Detail](https://github.com/andkwv/book_review_django/blob/master/andisbook/images/book_detail.png)



At around the bottom of the page we can see there is a form that allows us to add a new review to the book. However, this action is disable for any user that is not logged in. It will instead redirect you to a login page.

![Try_Review](https://github.com/andkwv/book_review_django/blob/master/andisbook/images/try_review.png)



Therefore first, we can try to register through the register tab at the top right corner.

![Register](https://github.com/andkwv/book_review_django/blob/master/andisbook/images/register.png)



After being registered we can then try to login as a new user

![Login](https://github.com/andkwv/book_review_django/blob/master/andisbook/images/login_jez.png)

![user](https://github.com/andkwv/book_review_django/blob/master/andisbook/images/reviews_jez.png)



Then we can navigate to the booklist to then add a review to the Book that we have read.

![add_review](https://github.com/andkwv/book_review_django/blob/master/andisbook/images/add_review.png)



We can see now that our review has been listed on the website along with the other reviews that others have made.

![result](https://github.com/andkwv/book_review_django/blob/master/andisbook/images/success_review.png)



## Acknowledgments

Thankyou to:
* Jose A Dianes https://www.codementor.io/jadianes/get-started-with-django-building-recommendation-review-app-du107yb1a
* Django Documentation team
 
