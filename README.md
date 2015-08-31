# Middleware Source Code
Source code to compile and run database middleware
Need to have MySQL local server running on computer
Extra library to download is MySQL Connector/J (http://dev.mysql.com/downloads/connector/j/)

How to compile:
cd into the sourceCode folder
javac data/DBView.java data/Parser.java data/UserView.java net/ChangeSchema.java net/Connect.java net/LoadData.java net/Query.java ui/GUI.java ui/TableForm.java

How to run:
java ui/GUI
