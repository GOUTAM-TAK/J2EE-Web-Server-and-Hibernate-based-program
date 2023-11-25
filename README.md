# J2EE-Web-Server-and-Hibernate-based-program
IPL Management System
2 Tables 1)Team 2)Player
Team  - -> Player => Many to one relationship
Aggregation Association Team has list of Players
Player has a Team.
Team pojo properties 1)name 2)abbreviation 3)Maximum Age limit 4)Batting_Avg 5)MIN'm Wicket limit 6)owner name
Player pojo has properties 1)name 2)Dob 3)Batting_Avg 4)Wickets taken

Function -> 1)Add Team 2)add player 3)validate player{ age ristriction, Batting_Avg ristriction , Wickets ristriction } if player pass all restriction then it successfully register and entity
write into Data base by hibernate


data Transfer - -> Client - -> JSP[UI, Controller of Beans]- -> JAVA Beans[Service provider] - -> Dao[Dao has dependency on HibernateUtils where database connection establish ,Pojo[table 
representation] ] - -> Data Base 
