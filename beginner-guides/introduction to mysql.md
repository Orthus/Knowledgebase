Many game servers and game server plugins/mods rely on an external database to store data. Rather than spending the valuable resources on your game server itself, you can use a database engine such as MySQL to store and retrieve the data with little to no reduction in lookup time.

### What is MySQL?

MySQL is a relational database which is optimized for quick CRUD operations (Create, Read, Update, Delete). MySQL servers use SQL (Structured Query Language) to request data and write changes to the database. SQL is the most popular language for adding, accessing and managing content in a database and is most noted for its quick processing, proven reliability, and ease and flexibility of use.
### Does NodeCraft offer MySQL Databases?
Absolutely! With each location, we offer at least one server dedicated to providing our customers with a stable MySQL database for each of their game servers at no additional charge. 
### How does one setup MySQL?
Before you can start setting up the MySQL for your service, you first need to create a database. From our control panel you can find a tab on the left called MySQL. This interface will create a database for you and provide you with the information needed to connect to your database. Be sure not to share this information as this can lead to data loss on your service. 

Much like FTP, a MySQL server has 4 parts to any connection. Below is the listed description of each:
| | |
|---|---|
|  Hostname      | The address of the MySQL Server. |
| Port           | Defaults to **3306**  |
| Username | Authentication username provided by MySQL server. |
| Password | Authentication password provided by MySQL server. |

Make sure each section of information is correct before adding it to the configuration of your program or plugin.
