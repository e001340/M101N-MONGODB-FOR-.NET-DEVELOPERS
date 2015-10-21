# M101N-MONGODB-FOR-.NET-DEVELOPERS
M101N: MONGODB FOR .NET DEVELOPERS

## HOMEWORK:HOMEWORK 1.1

Install MongoDB on your computer and run it on the standard port.

Download the HW1-1 from the Download Handout link and uncompress it.

Use mongorestore to restore the dump into your running mongod. Do this by opening a terminal window (mac) or cmd window (windows) and navigating to the directory so that you are in the parent directory of the dump directory (if you used the default extraction method, it should be hw1/). Now type:

mongorestore dump
Note you will need to have your path setup correctly to find mongorestore.

Next, go into the Mongo shell, perform a findOne on the collection called hw1 in the database m101. That will return one document. Please provide the value corresponding to the "answer" key from the document returned.

hint: if you get back a document that looks like { "_id": 1234, "answer": 2468 }, please only put in 2468 (with no spaces) for your answer.

### Ans. 42

## HOMEWORK: HOMEWORK 1.2

Which of the following are valid JSON documents? Please choose all that apply.


{ "a" : 1, "b" : { "b" : 1, "c" : "foo", "d" : "bar", "e" : [1, 2, 4] } }
{}
{ "name" : "Fred Flinstone" ; "occupation": "Miner" ; "wife" : "Wilma" }
{ "title" : "Star Wars", "quotes" : [ "Use the Force", "These are not the droids you are looking for" ], "director" : "George Lucas" }
{ "city" = "New York", "population" = 7999034, "boroughs" = ["queens", "manhattan", "staten island", "the bronx", "brooklyn"] }

### Ans. 

{ "a" : 1, "b" : { "b" : 1, "c" : "foo", "d" : "bar", "e" : [1, 2, 4] } }
{}
{ "title" : "Star Wars", "quotes" : [ "Use the Force", "These are not the droids you are looking for" ], "director" : "George Lucas" }

## HOMEWORK: HOMEWORK 1.3

This homework assignment is designed to ensure that you have Visual Studio set up and ready to go for next week, when you'll need it.

Download and extract the handout.

Run it in Visual Studio, and to make sure that you've got everything set up, it will post a number at localhost:61245. You can view it in your browser.

Please input that number into the box below to demonstrate that you have Visual Studio set up.

There should be no characters except numbers, and perhaps a minus sign. Do not include spaces. Do not include a decimal place.

### Ans. -1030
