CREATE TABLE Products (
    codigo_produto INT PRIMARY KEY,
    nome_produto VARCHAR(100) NOT NULL,
    preco_Unitario_Kg DECIMAL (10, 2) NOT NULL,
    comentarios TEXT
);
SELECT * FROM Products;
