
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
- 👋 Hola,Soy Luis Enrique

### Mis Competencias son

- Extracción,Transformación y Carga de Datos (ETL / ELT).
- Elaboración de DTS mediante (SSIS) SQL Server Integrations Services con Visual Studio.
- Microsoft SQL Server, DDL, DML, atomatización de procesos (scheduled jobs,stored procedures, triggers). 
- MySQL, Oracle PL/SQL, Teradata, DBVisualizer,SQL Developer, BigQuery GCP.
- Análisis Exploratio de Datos (EDA) con Python.
- PHP,HTML,CSS,C#.
- Tester QA / Automatización de Procesos mediante - RPA Robocorp, Selenium, Pandas.
- En constante aprendizaje de nuevas herramientas en Tecnologías de Información (TI). 

--- 
### Me puedes contactar por alguna de estas vías  📫

- [Web Personal](https://luispacharan.github.io/luispachecoarana.github.io/)
- [LinkedIn](https://www.linkedin.com/in/luis-enrique-pacheco-arana/)
- [GitHub](https://github.com/LuisPacharan/)
- [Medium](https://medium.com/@pacheco.arana.luis)


<!---
LuisPacharan/LuisPacharan is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.

https://github.com/kautukkundan/Awesome-Profile-README-templates/blob/master/code-styled/AnhellO.md
--->
