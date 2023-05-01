# SQL
SQL Portfolio
CREATE TABLE kks_store (id INTEGER PRIMARY KEY, item TEXT, aisle INTEGER, price INTEGER, quality TEXT);
INSERT INTO kks_store VALUES
 (1, "avocados",3,7,"good");
INSERT INTO kks_store VALUES(2, "Hummus",1,12, "Excellent");
INSERT INTO kks_store VALUES(3, "Peaches",3,2,"Good");
INSERT INTO kks_store VALUES(4, "Pears",3,7,"Fair");
INSERT INTO kks_store VALUES(5, "Granny Smith Apples",3,7,"Good");
INSERT INTO kks_store VALUES(6, "Bran muffins",3,7,"Good");
INSERT INTO kks_store VALUES(7, "Nature’s Own Wheat Bread",10,1,"Good");
INSERT INTO kks_store VALUES(8, "Gava",2,15,"Great");
INSERT INTO kks_store VALUES(9, "Miracle Whip",8,1,"Not great");
INSERT INTO kks_store VALUES(10, "Milk",3,1,"Good");
INSERT INTO kks_store VALUES(11, "Walnuts",6,11,"Great");
INSERT INTO kks_store VALUES(12, "Gouda Cheese",3,4,"Excellent");
INSERT INTO kks_store VALUES(13, "LIFE Cereal",6,6,"Fair”);
INSERT INTO kks_store VALUES(14, "Bagels",5,2,"Great");
INSERT INTO kks_store VALUES(15, "Cream Cheese", 1,5, "Delectable");

SELECT*FROM kks_store;
SELECT aisle, SUM(aisle) FROM kks_store GROUP BY aisle;
SELECT SUM(aisle) FROM kks_store;

SELECT*FROM kks_store WHERE price >=2 ORDER BY price asc;
