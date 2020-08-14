CREATE TABLE customers (id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
    -> full_name VARCHAR(20),
    -> username VARCHAR(20),
    -> email VARCHAR(30),
    -> no_hp VARCHAR(20),
    -> address VARCHAR(100));

ALTER TABLE customers
    -> DROP COLUMN no_hp;

ALTER TABLE customers
    -> ADD no_hp VARCHAR(20);

INSERT INTO `customers` (`id`, `full_name`, `username`, `email`, `address`, `no_hp`) VALUES (NULL, "Christiana Yeo", "Chris", "chrisyeo.tr@gmail.com", "Jakarta Utara", "081261802823");
INSERT INTO `customers` (`id`, `full_name`, `username`, `email`, `address`, `no_hp`) VALUES (NULL, "David Winalda", "David", "davidwinalda94@gmail.com", "Jakarta Utara", "0813452587");
INSERT INTO `customers` (`id`, `full_name`, `username`, `email`, `address`, `no_hp`) VALUES (NULL, "Rumondang Tampubolon", "Mon", "rumondang@gmail.com", "Jakarta Utara", "0856613301");
INSERT INTO `customers` (`id`, `full_name`, `username`, `email`, `address`, `no_hp`) VALUES (NULL, "Ridho Abdul Majid", "Ridho", "ridho@gmail.com", "Bandung", "08564215235");
 INSERT INTO `customers` (`id`, `full_name`, `username`, `email`, `address`, `no_hp`) VALUES (NULL, "Budhi Arta", "Budhi", "budhi@gmail.com", "Bali", "087786452321");