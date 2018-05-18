# GALA
Testing enviroment: Linux 2.6.18-238.el5
Required Sofwares and libraries: MySQL 5.7, libmysqlclient, CUDA 4.0.

1. Construct the database GHO. All data tables required are in Data folder. Please import all *_DATA.sql and *_INFO.sql. In our example, we use foo and foo as username and password. You may select your own username and passowrd.

2. Install GALA with make, and try two preference files in "Example" folder. For example,
   ./gala la_female_pref.txt [Database IP] [username] [password]

3. In R, install LA package by follwoing R codes:
   R> setwd("[your local path]/gala.codes.data/R/")
   R> install("la")
   R> library("la")
   
4. Run replication.Rmd.
