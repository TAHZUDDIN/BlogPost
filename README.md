# BlogPost
it is a small php app where user could upload blogs on a particular topic


To run it. In MySql need to create a database 'blog' with two tables 'categories' and 'posts'. the fields of 'categories' are 
id(int, primary key, autoincrement) and name(varchar(255))  and fields of 'posts' table are id(int(11)) , category(int(11)) FK to 'categories'
table id, 	title(varchar(255)), body(text), author(varchar(255)), tags(varchar(255)), date(timestamp,CURRENT_TIMESTAMP).


I have used XAMPP username 'root' and no password that is '' .Go to Database.php for setting your username ,password etc .first run    
..localhost/phploversblog/ main page where blogs will shpw up. As initially no data is there nothing will show . You could add posts 
either going to database or going to admin.php that is  ..//localhost/phploversblog/admin/  . The id of 'categories' and 'posts' table
category field should be same . There in the heading bar  Dashboard, AddPost, AddCategory, VisitBlog , options are there. In the Admin
page you could edit posts , edit categories could add  new categories new posts etc. 

