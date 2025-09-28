# Extract using API Key
```
python code
```

# Create the database in SQL
```
--create database databasename;--
create database fxrate_db;

```
# Tranfor,m to SQL
```
.dlt\
  -> secrets.toml
```

# Open Terminal to load the data into sql
```
cd foldername
pip install requests pandas dlt psycopg2-binary sqlalchemy
python ETL_EXTRACT.py


```


# output 
```
Pipeline fxrate_pipeline load step completed in 0.57 seconds
1 load package(s) were loaded to destination postgres and into dataset incremental
The postgres destination used postgresql://postgres:***@localhost:5432/fxrate_db location to store data
Load package 1759022659.4351814 is LOADED and contains no failed jobs
(venv) PS D:\ETL> pip install requests pandas dlt psycopg2-binary sqlalchemy
```


# go to the sql
```
select the schema
use select quer yor script -> select
```

<img width="1187" height="861" alt="image" src="https://github.com/user-attachments/assets/d736e7a3-dbbc-4a11-99f9-0432463373ad" />
