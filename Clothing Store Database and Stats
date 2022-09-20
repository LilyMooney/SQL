# Lily Mooney's SQL Portfolio

## Welcome to my SQL Portfolio! This code respository contains examples of SQL I've written. Feel free to take a look and reach out via email if you have any questions: lilymooney8871@gmail.com

--Create a cothing store database

CREATE TABLE clothing_store (id INTEGER PRIMARY KEY, item TEXT, quantity_sold INTEGER, price INTEGER, cost INTEGER);

INSERT INTO clothing_store VALUES (1, "Shirts", 25, 22.95, 12.24);
INSERT INTO clothing_store VALUES (2, "Pants", 27, 38.75, 18.00);
INSERT INTO clothing_store VALUES (3, "Skirts", 32, 26.00, 11.50);
INSERT INTO clothing_store VALUES (4, "Hats", 10, 20.00, 9.66);
INSERT INTO clothing_store VALUES (5, "Sunglasses", 30, 15.00, 6.27);
INSERT INTO clothing_store VALUES (6, "Sneakers", 5, 44.00, 18.49);
INSERT INTO clothing_store VALUES (7, "Sandals", 6, 37.00, 15.93);
INSERT INTO clothing_store VALUES (8, "Jackets", 12, 50.00, 30.18);
INSERT INTO clothing_store VALUES (9, "Watches", 8, 75.00, 43.84);
INSERT INTO clothing_store VALUES (10, "Long Sleves",15, 28.00, 13.38);
INSERT INTO clothing_store VALUES (11, "Tank Tops", 17,20.00, 11.29);
INSERT INTO clothing_store VALUES (12, "Shorts", 22, 25.00,13.44);
INSERT INTO clothing_store VALUES (13, "Boots", 9, 66.00, 42.12);
INSERT INTO clothing_store VALUES (14, "Necklaces", 20, 18.00, 8.39);
INSERT INTO clothing_store VALUES (15, "Rings", 32, 15.00, 6.92);

--display the database ordered by price.
SELECT * FROM clothing_store 
ORDER BY price;

--what items cost the store less than $10 to purchase?
SELECT item, cost FROM clothing_store 
WHERE cost <10;

--what are the 5 most sold items?
SELECT item, quantity_sold FROM clothing_store
ORDER BY quantity_sold desc
limit 5;
