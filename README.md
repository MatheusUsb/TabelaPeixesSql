#TabelaPeixesSql

CREATE TABLE peixes (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(100) NOT NULL,
    peso DECIMAL(10, 2) NOT NULL,
    comprimento DECIMAL(10, 2) NOT NULL
);
