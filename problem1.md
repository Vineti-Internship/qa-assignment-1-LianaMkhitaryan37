### Problem 1
**Test cases for calculator of shipping**

| Country       | SHIPPING METHOD   | TYPE OF ORDER  | Real Weight / kg  | SHIPPING COST  | EXPECTED COST  | Test Status |
| ------------- |:-----------------:| :-------------:| :----------------:| :-------------:| :-------------:|:-----------:|
| USA     | BY AIR    | ONLINE SHOPPING         | 1.1          | 4400  AMD  | 4400  AMD       | PASS    |
| USA     | BY AIR    | ONLINE SHOPPING         | -1          | Value must be greater then or equal to 0 / 400 AMD   | Min Price      | PASS    |
| USA     | BY AIR    | ONLINE SHOPPING         | 9+5         | Please Enter a number/ 400 AMD   | Min Price - default value     | PASS    |
| USA     |  BY SEA    | PERSONAL PARCEL         | 11.5         | 29  USD    | 29  USD       | PASS  |
| USA     |  BY SEA    | ONLINE SHOPPING         | 3 , 9, 10          | 12.000  AMD  | 12.000  AMD       | PASS  |
| USA     |  BY SEA    | ONLINE SHOPPING         | 11.5         | 13800  AMD  | 13800  AMD       | PASS  |
|  RUS     |  BY AIR    | ONLINE SHOPPING         | 2.7         | 5400  AMD  | 5400  AMD       | PASS  |
|  UK     |  BY AIR    | ONLINE SHOPPING         | 5         | 20000  AMD  | 20000  AMD       | PASS  |
|  CHINA     |  BY AIR    | ONLINE SHOPPING         | 7         | 28000  AMD  | 28000  AMD       | PASS  |
|  USA new address  | BY AIR          |  ONLINE SHOPPING          | 1         | 6000  AMD| 3.000 amd | FAIL       |