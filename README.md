# Alumnus Scores Managerment
+ This project will help you built a scores manager system.
# IDE used:
+  netbeans 8.2
# JAR Dependencies:
  + Download Microsoft JDBC Driver 12.4 for SQL Server (zip)
  + Download-sql-server-2019
# Setting up the database:
  + Create a database named QLSinhVien  
  + Run the "use QLSinhVien" line  
  + Run all table in the sql  
  + Run Insert Into  
# Setting project in netbeans:
   Step 1: Right click on Database -> New Connection -> Add -> add mssql-jdbc-12.4.1-jre11.jar        
  ![image](https://github.com/Khoavo26042004/AlumnusScoresManagerment/assets/154489298/33f8949d-9a11-44a8-818a-df35917d8b40) ![image](https://github.com/Khoavo26042004/AlumnusScoresManagerment/assets/154489298/21397bed-b151-42a4-9223-1437dd8fbca4)
  
   Step 2:Click on Next button  
  + At Database line is your the project name in sql.Example: Above I have a name database is QLSinhVien  
  + At User Name and Password line, it is your usename and password int sqlserver  
  + At The JDBC URL, you must add more this code ";encrypt=true;trustServerCertificate=true;" at the end the line and press the Test Connection button(remember coppy code in the JDBC URL line) -> press Next button two times and finish   
    ![image](https://github.com/Khoavo26042004/AlumnusScoresManagerment/assets/154489298/84eae431-2bde-421f-a5ed-9c45b1c60593)
    ![image](https://github.com/Khoavo26042004/AlumnusScoresManagerment/assets/154489298/58f1cd06-2a2d-48ac-b6b6-d88f26075861)
    ![image](https://github.com/Khoavo26042004/AlumnusScoresManagerment/assets/154489298/c268baf3-8654-4894-8662-97855353edfd)

  Step 3: 
  + In sources packages, open the file named MySQLConnection in qlsinhvien -> changes the url(Here, paste the one I asked you to copy above),user(your username in sql),pass(your password in sql)  
  +And run my project.
![image](https://github.com/Khoavo26042004/AlumnusScoresManagerment/assets/154489298/ad1244b1-8ca6-485c-9a66-159e5634f8f9)
![image](https://github.com/Khoavo26042004/AlumnusScoresManagerment/assets/154489298/35a82c4f-a344-4432-ad3d-c04d359efe48)

# Useraccount of alumnus and lecturer 
  + MSSV(of alumnus),MaGV(of lecturer)-(username)
  + MatKhau(both alumnus and lecturer)-(password)
  + Login of alumnus:  
  ![image](https://github.com/Khoavo26042004/AlumnusScoresManagerment/assets/154489298/f9ed7d79-2e4d-4693-8b17-cde46ff2affd)
  ![image](https://github.com/Khoavo26042004/AlumnusScoresManagerment/assets/154489298/db1e7c7e-1dd3-413b-893b-d20c4186acfa)
  +Login of lecturer:
  ![image](https://github.com/Khoavo26042004/AlumnusScoresManagerment/assets/154489298/82451fee-4632-4bb1-89af-6c1e494e5f77)
  ![image](https://github.com/Khoavo26042004/AlumnusScoresManagerment/assets/154489298/ca533f5f-da4d-4f84-9686-8bf6682e2246)

# Author
- [@Khoavo](https://www.github.com/octokatherine)

   
  


