
```sql
USE [DB_LUIS_PACHARAN]
GO
-- =============================================
-- Author: <Luis Enrique,Pacheco A>
-- Description:	<Database developer & Data Specialist, CDMX, M茅xico>
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
- 馃憢 Hola,Soy Luis Enrique

### Mis Competencias son

- Extracci贸n,Transformaci贸n y Carga de Datos (ETL).
- Elaboraci贸n de DTS mediante (SSIS) SQL Server Integrations Services con Visual Studio.
- Microsoft SQL Server, DDL, DML, atomatizaci贸n de procesos (scheduled jobs,stored procedures). 
- MySQL, Teradata, DBVisualizer.
- An谩lisis Exploratio de Datos (EDA) con Python.
- PHP + HTML.
- En constante aprendizaje con las nuevas tecnolog铆as de Informaci贸n.

--- 
### Me puedes contactar por alguna de estas v铆as  馃摣

- [Web Personal](https://luispacharan.github.io/luispachecoarana.github.io/)
- [LinkedIn](https://www.linkedin.com/in/luis-enrique-pacheco-arana/)
- [GitHub](https://github.com/LuisPacharan/)
- [Medium](https://medium.com/@pacheco.arana.luis)


<!---
LuisPacharan/LuisPacharan is a 鉁? special 鉁? repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.

https://github.com/kautukkundan/Awesome-Profile-README-templates/blob/master/code-styled/AnhellO.md
--->
