# Room Database

"Room" is a persistence library introduced by Google that provides an abstraction layer over SQLite to help with robust database access while harnessing the full power of SQLite. Room supports the creation of databases and defines queries in compile-time-checked SQL strings. These databases belong to the data classes that you create representing your app's data. Room comprises three main components: **Database**, a container that holds your app's data tables; **Entity**, representing a table within the database; and **DAO (Data Access Object)**, containing SQL query methods to interact with the database.