#Alumnus Scores Managerment 
  This project will help you built a scores manager system.<space><space>
#IDE used:
  netbeans 8.2
#JAR Dependencies:
  Download Microsoft JDBC Driver 12.4 for SQL Server (zip)
  Download-sql-server-2019
#Setting up the database:
  Create a database named QLSinhVien
  Run the "use QLSinhVien" line
  Run all table in the sql
  Run Insert Into
#Setting project in netbeans:
  Right click on Database -> New Connection -> Add -> add mssql-jdbc-12.4.1-jre11.jar  
  ![image](https://github.com/Khoavo26042004/AlumnusScoresManagerment/assets/154489298/33f8949d-9a11-44a8-818a-df35917d8b40)
  Click on Next button 
  ![image](https://github.com/Khoavo26042004/AlumnusScoresManagerment/assets/154489298/84eae431-2bde-421f-a5ed-9c45b1c60593)
  At Database line is your the project name in sql.Example: Above I have a name database is QLSinhVien
  At User Name and Password line, it is your usename and password int sqlserver
  At The JDBC URL, you must add more this code ";encrypt=true;trustServerCertificate=true;" at the end the line and press the Test Connection button(remember coppy code in the JDBC URL line) -> press Next button two times and finish
  In sources packages, open the file named MySQLConnection in qlsinhvien -> changes the url(Here, paste the one I asked you to copy above),user(your username in sql),pass(your password in sql)
  And run my project.
)
#Useraccount of alumnus and lecturer 
  MSSV(of alumnus),MaGV(of lecturer)-(username) 
  MatKhau(both alumnus and lecturer)-(password)


