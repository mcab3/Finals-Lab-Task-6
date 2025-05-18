# Finals Lab Task 6.  MOngoDBCRUD
In this task, I learned that MongoDB is a NoSQL database that stores data in flexible, JSON-like documents instead of traditional relational tables. It’s designed to handle unstructured or semi-structured data, with collections that don’t require a fixed schema. MongoDB also offers features like horizontal scaling, indexing, and an aggregation framework, making it suitable for high-performance, dynamic applications. However, I learned that it may not be the best choice for applications needing strict consistency or complex relational queries.
Here are the tasks that were provided and the code for the MongoDB:

## Part 1. MongoDB Exercise in Mongo shell
- **Create database**
Connect to a running mongo instance, use a database named `mongo_practice`
<img src="Images/view1_tbl.png" width="500">
  
- **Insert the following documents into a `movies` collection:**

  
title : Fight Club
writer : Chuck Palahniuk
year : 1999
actors : [
  Brad Pitt
  Edward Norton
]
  
  
title : Pulp Fiction
writer : Quentin Tarantino
year : 1994
actors : [
  John Travolta
  Uma Thurman
] 
  

title : Inglorious Basterds
writer : Quentin Tarantino
year : 2009
actors : [
  Brad Pitt
  Diane Kruger
  Eli Roth
]


title : The Hobbit: An Unexpected Journey
writer : J.R.R. Tolkein
year : 2012
franchise : The Hobbit

title : The Hobbit: The Desolation of Smaug
writer : J.R.R. Tolkein
year : 2013
franchise : The Hobbit

title : The Hobbit: The Battle of the Five Armies
writer : J.R.R. Tolkein
year : 2012
franchise : The Hobbit
synopsis : Bilbo and Company are forced to engage in a war against an array of combatants and keep the Lonely Mountain from falling into the hands of a rising darkness.

title : Pee Wee Herman's Big Adventure

title : Avatar  

**Query / Find Documents**
1. get all documents

   
2. get all documents with `writer` set to "Quentin Tarantino"

3. get all documents where `actors` include "Brad Pitt"

4. get all documents with `franchise` set to "The Hobbit"

5. get all movies released in the 90s

6. get all movies released in the 90s

**Update Documents**
  
1. add a synopsis to "The Hobbit: An Unexpected Journey" : "A reluctant hobbit, Bilbo Baggins, sets out to the Lonely Mountain with a spirited group of dwarves to reclaim their mountain home - and the gold within it - from the dragon Smaug."
  
2. add a synopsis to "The Hobbit: The Desolation of Smaug" : "The dwarves, along with Bilbo Baggins and Gandalf the Grey, continue their quest to reclaim Erebor, their homeland, from Smaug. Bilbo Baggins is in possession of a mysterious and magical ring."

3. add an actor named "Samuel L. Jackson" to the movie "Pulp Fiction"

**Text Search**
1. find all movies that have a synopsis that contains the word "Bilbo"

2. find all movies that have a synopsis that contains the word "Gandalf"

3. find all movies that have a synopsis that contains the word "Bilbo" and not the word "Gandalf"

4. find all movies that have a synopsis that contains the word "dwarves" or "hobbit"

5. find all movies that have a synopsis that contains the word "gold" and "dragon"
  
**Delete Documents**
1. delete the movie "Pee Wee Herman's Big Adventure"
2. delete the movie "Avatar"
  
**Relationships**
username : GoodGuyGreg
first_name : "Good Guy"
last_name : "Greg"
  
username : ScumbagSteve
full_name :
  first : "Scumbag"
  last : "Steve"

