# information_about_satellites

### ISRO launched EOS-01 (Earth Observation Satellite) using PSLV-C49 in November 2020. This article provides the complete list of satellites launched by India till 2020. This is an important topic for UPSC and other government exams.

### what is a satellite ?
>The satellite is an artificial object which has been deliberately put into space for different purposes like remote sensing, weather forecasting, image mapping, education, and research.


## Mongo DB is not a SQL 
> It follows    *JSON*  format for storing the data.

as example, here I  am taking inf.about satellites  & its importance.


first we will create a DB with a defined *collection name*.

next there is two ways to insert data 
#### 1. Either we can _import a file_ or _insert a doc._

2. we can insert data with _MONGOSH_    >test.


for insert a single data db. collection name
```json


db.launches.inertONE({
    "satellite_name" : "Chandrayaan-1",
    "year" : 2008,
    "imp" : "first lunar probe"	
})



to insert multiple data 
> db.launches.insertMany([{"name" : "cartosat-3",
"year" : 2019,
"importances" "optical stellite with highest resolutions in the world"},


{"name" : "GSAT-30",

"year" : 2020,

"importances" :"41st communication satellite launched by ISRO to replace INSAT-4A. it provides advance telecomunnications services to the entire indian sub-continent.

}])



