# Answers.sql
-- Create the SalesDB database
CREATE DATABASE SalesDB;

-- Use the SalesDB database
USE SalesDB;

-- Create the KingEnterprisesSales table
CREATE TABLE KingEnterprisesSales 
(
    SaleID INT PRIMARY KEY AUTO_INCREMENT, -- Unique ID for each sale
    GoodsName VARCHAR(255), -- Name of the goods sold
    QuantitySold INT, -- Number of goods sold
    AmountPerGood DECIMAL(10, 2), -- Price of each good (e.g., 10.50)
    TotalCost DECIMAL(10, 2) -- Total cost of the sale
);

-- Example: Insert some data (optional)
INSERT INTO KingEnterprisesSales (GoodsName, QuantitySold, AmountPerGood, TotalCost) VALUES
('Pencils', 100, 0.50, 50.00),
('Notebooks', 50, 2.00, 100.00),
('Erasers', 200, 0.25, 50.00),
('Rulers', 30, 1.50, 45.00);

-- To see the table you just created and the data you added, you can use:
-- SELECT * FROM KingEnterprisesSales;

