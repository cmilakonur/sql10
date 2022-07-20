# sql10
patika.dev linkim: https://app.patika.dev/cmilakonur <br />

1- city tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz LEFT JOIN sorgusunu yazınız. <br />

select city, country from city <br />
left join country <br />
ON country.country_id = city.country_id; <br />


2- customer tablosu ile payment tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name <br />
isimlerini birlikte görebileceğimiz RIGHT JOIN sorgusunu yazınız. <br />

select payment.payment_id,customer.first_name,customer.last_name from customer <br />
RIGHT JOIN payment <br />
ON payment.customer_id = customer.customer_id; <br />


3- customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name  <br />

isimlerini birlikte görebileceğimiz FULL JOIN sorgusunu yazınız. <br />
select rental.rental_id, customer.first_name, customer.last_name from customer <br />
FULL JOIN rental <br />
ON rental.customer_id = customer.customer_id; <br />
