# dataToSql
convert data string on LeetCode to DDL and insert SQL   
input guide   
1st line is table name   
data string on leetcode   
example:    
Employee   
+----+-------+--------+--------------+   
| Id | Name  | Salary | DepartmentId |   
+----+-------+--------+--------------+   
| 1  | Joe   | 70000  | 1            |   
| 2  | Henry | 80000  | 2            |   
| 3  | Sam   | 60000  | 2            |   
| 4  | Max   | 90000  | 1            |   
| 5  | Janet | 69000  | 1            |   
| 6  | Randy | 85000  | 1            |   
+----+-------+--------+--------------+   
create table Employee(Id	int	 NULL,   
Name	varchar(64)	 NULL,   
Salary	int	 NULL,   
DepartmentId	int	 NULL);   
insert into Employee values(1,'Joe',70000,1),(2,'Henry',80000,2),(3,'Sam',60000,2),(4,'Max',90000,1),(5,'Janet',69000,1),(6,'Randy',85000,1);   
