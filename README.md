# Mysql
MySQL Commands

  1). Create Database
      
      create database dbname;

  2). Drop Database
      
      drop database dbname;
      
  3). Create Database if not exist
      
      create database if not exist dbname;
      
  4). Drop Database if exist
      
      create database if exist dbname;
      
  5). Show Database
      
      show database;
      
  6). Use Database
      
      use dbname;
      
  7). Display the current database
      
      select database();
      
  8). Getting Information About Tables
      
     describe tablename;
     
  9).SHOW CREATE TABLE Statement 
  
     show create table tablename;
     
  10). Inset Data in db
    
      INSERT INTO tableName VALUES ('Example',4500);
      ex-
      INSERT INTO customer values ('C033','Mr','Saa','1990-05-14',98000,'No 34 Galle Rd Hikkaduwa','Galle','Southern','80100');
      
  11).Delete table data (AThogakade DB)
  
      delete from customer where CustID = "C033"; 
      
