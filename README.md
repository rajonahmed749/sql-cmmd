# SQL

#### Create table 
    create table Job (
        Emp_Id varchar(20) PRIMARY KEY,
        Emp_name varchar(50), 
        Dept varchar(100), 
        Salary int,
        Designation varchar(100)
    )

#### Insert Data
    insert into Job values('Emp_07', 'nuru','labour','2500','Labour')

#### Selcet Data
    SELECT * from Job where 
    Salary > 5000


#### Update Data
    update Job set Salary=15000
    where Salary=8000

#### Delete Data
    delete from Job 
    where Emp_name='nuru'


#### Delete Column

    ALTER TABLE Students 
    DROP COLUMN Salary

#### Add Column

    ALTER TABLE Students 
    ADD COLUMN BirthDate date