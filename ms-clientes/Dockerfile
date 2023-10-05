
docker pull mysql

docker run --name mysql-producto -p 4306:3306 -e MYSQL_ROOT_PASSWORD=123456 -d mysql

create database BD_VENTAS;
use BD_VENTAS;

INSERT INTO producto (nombre, precio, stock_maximo, stock_minimo)
VALUES
       ('Laptop Lenovo', 799.99, 11, 61),
    ('Smartphone Samsung', 349.50, 12, 62),
    ('Impresora HP', 149.99, 13, 63),
    ('Tablet Android', 199.99, 14, 64),
    ('Teclado inalámbrico', 39.99, 15, 65),
    ('Mouse óptico', 19.99, 16, 66),
    ('Monitor LED', 249.99, 17, 67),
    ('Auriculares Bluetooth', 59.99, 18, 68),
    ('Altavoz portátil', 79.99, 19, 69),
    ('Cámara digital', 299.99, 20, 70);