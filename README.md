# Data-Entry-Portfolio
Portfolio for coding

CREATE TABLE store(id INTEGER PRIMARY KEY, shirts TEXT, size TEXT, price TEXT, aisle TEXT);

INSERT INTO store VALUES (1, "Blue", "Small", 5, 2 );
INSERT INTO store VALUES (2, "Red", "Small", 5, 2);
INSERT INTO store VALUES (3, "Orange", "Small", 5, 2);
INSERT INTO store VALUES (4, "Pink", "Small", 5, 2);
INSERT INTO store VALUES (5, "Purple", "Small", 5, 2);
INSERT INTO store VALUES (6, "Blue", "Medium", 10, 3);
INSERT INTO store VALUES (7, "Red", "Medium", 10, 3);
INSERT INTO store VALUES (8, "Orange", "Medium", 10, 3);
INSERT INTO store VALUES (9, "Pink", "Medium", 10, 3);
INSERT INTO store VALUES (10, "Purple", "Medium", 10, 3);
INSERT INTO store VALUES (11, "Blue", "Large", 15, 4);
INSERT INTO store VALUES (12, "Red", "Large", 15, 4);
INSERT INTO store VALUES (13, "Orange", "Large", 15, 4);
INSERT INTO store VALUES (14, "Pink", "Large", 15, 4);
INSERT INTO store VALUES (15, "Purple", "Large", 15, 4);

SELECT * from store;
SELECT * from store ORDER BY aisle;
