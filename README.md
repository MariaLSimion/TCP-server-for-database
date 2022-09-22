# TCP-server-for-database

Management of accessing objects from a database:
  ○ The server manages a list of objects retrieved from a database, each one
object being identified by a unique key;
   ○ The client can query the server to select or list objects with
certain key values;
  ○ The server keeps for each the list of key values for the selected objects;
  ○ Customers can update or delete objects by key;
  ○ When an object is modified, the server will notify all clients who pre-select the respective object;
  ○ Changes to the objects are saved in the server memory and in the database.
