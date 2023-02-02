# Food_Hygiene_Rating_Analysis
</br>
https://github.com/ericyang91/Food_Hygiene_Rating_Analysis/blob/main/NoSQL_setup_starter.ipynb
## Purpose:

  The purpose of this project is to lay the groundwork for evaluation of various establishments across the UK. It uses <a href= "https://www.mongodb.com"> <b>MongoDB</b></a> to create a database and to import the data and <a href= "https://pymongo.readthedocs.io/en/stable/"> <b>PyMongo</b></a> to make different queries that are needed for analytical work.

## How to Use:

1. Connect to MongoDB: `"C:\Program Files\MongoDB\Server\6.0\bin\mongod.exe" --dbpath="c:\data\db"`
2. Locate the directory in which <a href= "https://github.com/ericyang91/Food_Hygiene_Rating_Analysis/tree/main/Resources"> <b>establishments.json</b></a> is located, and then import: `mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json`
3. Launch <a href= "https://pymongo.readthedocs.io/en/stable/"> <b>MongoDB Shell</b></a>: `mongosh.exe`
4. Check whether the database has been created: `show dbs`
5. Open the <a href= "https://github.com/ericyang91/Food_Hygiene_Rating_Analysis/blob/main/NoSQL_setup_starter.ipynb"> <b>setup</b></a> and <a href= "https://github.com/ericyang91/Food_Hygiene_Rating_Analysis/blob/main/NoSQL_analysis_starter.ipynb"> <b>analysis</b></a> files and explore.
</br>

## Languages and Libraries:
</br>

`python v.3.9.12`
`jupyter notebook v.6.4.8`
`pandas v.1.4.2`
`MongoDB v.6.0.4`
