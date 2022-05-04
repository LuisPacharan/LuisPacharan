



```sql
USE [DB_LUIS_PACHARAN]
GO
-- =============================================
-- Author: <Luis Enrique,Pacheco A>
-- Description:	<Database developer & Data Specialist, CDMX, México>
-- =============================================
ALTER PROCEDURE [dbo].[SP_MY_SKILLS] AS

	BEGIN
	
		declare @Databases table (databases char(20))
		 insert into @Databases values ('SQLServer'), ('MySQL'), ('PostgreSQL')
		  select * from @Databases

		declare @Frontend table (softwareF char(20))
		 insert into @Frontend values ('HTML'), ('CSS'), ('Boostrap')
		  select * from @Frontend

		declare @Backend table (softwareB char(20))
		 insert into @Backend values ('PHP'), ('Python')
		  select * from @Backend

		declare @Frameworks table (Frameworks char(20))
		 insert into @Frameworks values ('MSSQLServer'),('Teradata'), ('DBVisualizer'), ('Jupyter'),('VSCode')
		  select * from @Frameworks
	END
  ```


- 👋 Hi, I’m @LuisPacharan
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
LuisPacharan/LuisPacharan is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
