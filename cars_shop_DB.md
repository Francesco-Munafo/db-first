# Carshop Database

## Table name

- cars

## Table columns

- id | PK  //PK will set automatically some data types (AUTO_INCREMENT, UNIQUE ETC.)
- brand | NOT_NULL, VARCHAR(50)
- model | NOT_NULL, VARCHAR(255) //255 is the maximum value for varchar
- km_count | NULL, MEDIUMINT //MEDIUMINT accept a maximum value of 2^24 
- power_kw | NULL, SMALLINT(2000)
- year | YEAR, NULL
- gear_shift | NULL, VARCHAR(14) //maximum characters is 14 for SEMI-AUTOMATIC
- fuel_type | NULL, VARCHAR(10)
- seats | NULL, TINYINT
- doors | NULL, TINYINT
- weight |  NULL, MEDIUMINT //MEDIUMINT accept a maximum value of 2^24 
- class | NULL, VARCHAR(7) //For EURO-6, I added one more for future classes
- price | NOT_NULL, INT //Actually the most expensive car is 50million dollars so for the future I decided to use an INT value for a better range
- location | NULL, VARCHAR(100) 
- plot | NULL, VARCHAR(255)
- car_image | NULL, VARCHAR(255)


