# SQL_Odev9
lcw bootcamp sql 9.ödev reposudur.

-- 1. City ve Country Tablosunu INNER JOIN Kullanarak Birleştirmek
SELECT city.city, country.country
FROM city
INNER JOIN country ON city.country_id = country.country_id;

-- 2. Customer ve Payment Tablosunu INNER JOIN Kullanarak Birleştirmek
SELECT payment.payment_id, customer.first_name, customer.last_name
FROM customer
INNER JOIN payment ON customer.customer_id = payment.customer_id;

-- 3. Customer ve Rental Tablosunu INNER JOIN Kullanarak Birleştirmek
SELECT rental.rental_id, customer.first_name, customer.last_name
FROM customer
INNER JOIN rental ON customer.customer_id = rental.customer_id;

