# youho
Textual analysis of youho

About "main_CgRisk.Rmd"
Run this code, which provides the representative values such as TTR and TFIDF, in a folder "R_code."
"R_code" is located in the shared folder. It has some data files loaded in this code.

About "main_CG.Rmd" and "main_Risk.Rmd"
They send the values to a database of SQLite. In the codes, the name of the database is set to be "youho.sqlite3."
The database has three tables whose names are "riskTTR", "cgTTR", and "cgTfidf", such that the query of "nature inner join" allow to integrate these tables by the columns the tables commonly have (code and year).
