# rudra

CREATE DATABASE hotel_db;

USE hotel_db;

CREATE TABLE reservations (
    reservation_id INT PRIMARY KEY AUTO_INCREMENT,
    guest_id INT NOT NULL,
    guest_name VARCHAR(100),
    contact_number VARCHAR(20),
    room_number INT,
    check_in DATETIME DEFAULT CURRENT_TIMESTAMP,
    check_out DATETIME
);
