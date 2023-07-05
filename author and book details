# my_sql_project3

create database book_details;
create table book_details.book(
Book_id int primary key auto_increment,
Book_Title varchar(50),
Book_Author varchar(50),
Book_genre varchar(100),
publication_year int ,
Book_price int 
);
insert into book_details.book values
(1,"In the name honour","Mukthar mai","honour",1995,1000),
(2,"Honour","frank henderson","thriiling",1998,1049),
(3,"Moral capital","Herman Melville","Comedy",2000,849),
(4,"Evil DEAD","Tolstoy","fantasy",1981,750),
(5,"HARRY POTTER","J.k.ROWLING","navels",1997,500);
select * from book_details.Author;


create table book_details.Author (
Si_NO int primary key auto_increment,
Author_name varchar(50),
Book_Title varchar(50),
foreign key(SI_NO) References Book(Book_id)
);
select * from book_details.Author;
insert into book_details.Author values
(1,"Gandhi","The indian"),
(2,"Manirathanam","PS-II"),
(3,"THE BOYS","ALAN WALKER"),
(4,"KABARAMAYANAM","Kabar"),
(5,"sulthan","jai sulthan");

select * from book_details.Author;
select * from book_details.book;

select distinct Book_Title from book_details.book;
select distinct Book_Title from book_details.Author;

update book_details.book set Book_Title="the rome" where Book_id=5;
update book_details.book set Book_Author="chris hermath" where Book_id=5;

delete from book_details.Author where SI_NO=5;

select avg(Book_price) from book_details.book;





