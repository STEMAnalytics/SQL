# SQL
Create you own grocery store database_SQL Portfolio

CREATE TABLE Integral_Eats (id INTEGER PRIMARY KEY, item TEXT, aisle INTEGER, price INTEGER, quality TEXT);
INSERT INTO Integral_Eats VALUES
 (1, "avocados",3,7,"good");
INSERT INTO Integral_Eats VALUES(2, "Hummus",1,12, "Excellent");
INSERT INTO Integral_Eats VALUES(3, "Peaches",3,2,"Good");
INSERT INTO Integral_Eats VALUES(4, "Pears",3,7,"Fair");
INSERT INTO Integral_Eats VALUES(5, "Granny Smith Apples",3,7,"Good");
INSERT INTO Integral_Eats VALUES(6, "Bran muffins",3,7,"Good");
INSERT INTO Integral_Eats VALUES(7, "Nature’s Own Wheat Bread",10,1,"Good");
INSERT INTO Integral_Eats VALUES(8, "Gava",2,15,"Great");
INSERT INTO Integral_Eats VALUES(9, "Miracle Whip",8,1,"Not great");
INSERT INTO Integral_Eats VALUES(10, "Milk",3,1,"Good");
INSERT INTO Integral_Eats VALUES(11, "Walnuts",6,11,"Great");
INSERT INTO Integral_Eats VALUES(12, "Gouda Cheese",3,4,"Excellent");
INSERT INTO Integral_Eats VALUES(13, "LIFE Cereal",6,6,"Fair”);
INSERT INTO Integral_Eats VALUES(14, "Bagels",5,2,"Great");
INSERT INTO Integral_Eats VALUES(15, "Cream Cheese", 1,5, "Delectable");

SELECT*FROM Integral_Eats;
SELECT aisle, SUM(aisle) FROM Integral_Eats GROUP BY aisle;
SELECT SUM(aisle) FROM Integral_Eats;

SELECT*FROM Integral_Eats WHERE price >=2 ORDER BY price asc;
