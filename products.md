CREATE TABLE products (id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
    -> product_name VARCHAR(50),
    -> price INT(20),
    -> stock INT(30));
SHOW tables;

INSERT INTO `products` (`id`, `product_name`, `price`, `stock`) VALUES (NULL, "Samsung", 1800000, 30);
INSERT INTO `products` (`id`, `product_name`, `price`, `stock`) VALUES (NULL, "Iphone",
5000000, 50);
INSERT INTO `products` (`id`, `product_name`, `price`, `stock`) VALUES (NULL, "Xiaomi", 3000000, 10);
INSERT INTO `products` (`id`, `product_name`, `price`, `stock`) VALUES (NULL, "Asus", 1000000, 60);
INSERT INTO `products` (`id`, `product_name`, `price`, `stock`) VALUES (NULL, "Nokia", 1200000, 100);
SELECT * FROM products;