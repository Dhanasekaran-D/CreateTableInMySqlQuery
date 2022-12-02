# CreateTableInMySqlQuery





USE mysql_demo_tnj;


CREATE TABLE tb_dhanasekaran_dhanapal( 



id INT NOT NULL, 
user_name  VARCHAR (250) NOT NULL ,
father_name VARCHAR(250) NOT NULL,
email VARCHAR (250) NOT NULL ,
phone_no LONG NOT NULL ,
emp_or_not BIT NOT NULL DEFAULT 0,
city VARCHAR(100) NOT NULL,
state VARCHAR (100) NOT NULL ,
PRIMARY KEY (id));



USE mysql_demo_tnj;
use  tb_dhanasekaran_dhanapal;
insert  INTO tb_dhanasekaran_dhanapal(id,user_name,father_name,email,phone_no,emp_or_not,city,state)
 VALUES (1,'danasekaran','dhanapal','dhanasekaran2122001@gmail.com',9095113137,1,'thanjavur','tamilnau');                          
                
insert  INTO tb_dhanasekaran_dhanapal(user_name,father_name,email,phone_no,emp_or_not,city,state)
VALUES ('desapriyan','sivaji','desa@gmail.com',9887665666,0,'thanjavur','tamilnadu');

insert  into tb_dhanasekaran_dhanapal(user_name,father_name,email,phone_no,emp_or_not,city,state)
values ('kanmani','ravi','kanmani@gmail.com',7865432198,1,'pattukottai','tamilnadu');

insert  into tb_dhanasekaran_dhanapal(user_name,father_name,email,phone_no,emp_or_not,city,state)
VALUES ('srimathi','veraperumal','sri@gmail.com',098765432,0,'peravurani','thanjavur');

insert  into tb_dhanasekaran_dhanapal(user_name,father_name,email,phone_no,emp_or_not,city,state)
VALUES ('manimaran','poovaragavan','mani@gmail.com',12165430987,1,'thanjavur','tamilnadu');

insert  into tb_dhanasekaran_dhanapal(user_name,father_name,email,phone_no,emp_or_not,city,state)
VALUES ('suresh','ramamoorthy','suresh@gmail.com',0988776654,0,'oorathanadu','tamilnadu');

insert  into tb_dhanasekaran_dhanapal(user_name,father_name,email,phone_no,emp_or_not,city,state)
VALUES ('tharaneesh','dhanapal','dharanee@gmail.com',0987654321,0,'peravurani','tamilnadu');

insert  into tb_dhanasekaran_dhanapal(user_name,father_name,email,phone_no,emp_or_not,city,state)
VALUES ('vicky','veeran','vicky@gmail.com',0965721341,0,'aranthangi','tamilnadu');

insert  into tb_dhanasekaran_dhanapal(user_name,father_name,email,phone_no,emp_or_not,city,state)
VALUES ('arun','prakash','arun@gmail.com',43219056878,1,'pudukottai','tamilnadu');

insert  into tb_dhanasekaran_dhanapal(user_name,father_name,email,phone_no,emp_or_not,city,state)
VALUES ('abinesh','karuna','abi@gmail.com',8765901341,0,'nagudi','thamilnadu');

insert  into tb_dhanasekaran_dhanapal(user_name,father_name,email,phone_no,emp_or_not,city,state)
VALUES ('santhosh','balu','santhosh@outlook.com',0934568721,0,'thirchy','tamilnadu');
 
 insert  into tb_dhanasekaran_dhanapal(user_name,father_name,email,phone_no,emp_or_not,city,state)
VALUES ('santhosh','','santhosh@outlook.com',0934568721,0,'thirchy','tamilnadu');
 
 
 UPDATE tb_dhanasekaran_dhanapal  SET city ='thanjavur' WHERE user_name='kanmani';
 
 
 DELETE FROM tb_dhanasekaran_dhanapal WHERE id =11;
 
 SELECT * FROM tb_dhanasekaran_dhanapal;
 
 
 SELECT * FROM tb_dhanasekaran_dhanapal WHERE city IN ('peravurani');
 
 SELECT * FROM tb_dhanasekaran_dhanapal WHERE city NOT IN ('tanjavur');
 
 SELECT * FROM tb_dhanasekaran_dhanapal WHERE user_name='abinesh' AND city='nagudi';
 
 
SELECT * FROM tb_dhanasekaran_dhanapal WHERE user_name ='dhanasekaran' OR city ='aranthangi';

UPDATE tb_dhanasekaran_dhanapal SET father_name='balu' WHERE id=12;
 
 ALTER TABLE tb_dhanasekaran_dhanapal
DROP COLUMN  emp_or_not;









![table 1](https://user-images.githubusercontent.com/116792869/205262879-39abb8d7-d086-4cb0-9fd0-8a5ec27b5d95.png)


![table 2](https://user-images.githubusercontent.com/116792869/205262919-df4de3a3-91bd-4922-a842-7c6bf8f77127.png)





![table delete 1](https://user-images.githubusercontent.com/116792869/205262979-9bb39115-1faa-45eb-96ce-8f117bc8cf75.png)


![select table](https://user-images.githubusercontent.com/116792869/205263001-5a58cb4f-4827-4422-a874-9286bd71e165.png)


![unic select table1](https://user-images.githubusercontent.com/116792869/205263027-026bf4a3-ad99-4fae-9a4d-a6f0a6b9560d.png)

![not in table](https://user-images.githubusercontent.com/116792869/205263044-fc283589-a650-4b64-94cf-b77260d9375f.png)

![or](https://user-images.githubusercontent.com/116792869/205263063-8da485bd-211c-4383-bea4-acf2a2a835e1.png)

![drop](https://user-images.githubusercontent.com/116792869/205263091-0d31b678-49fd-4c36-a39d-e25005c15fb8.png)





