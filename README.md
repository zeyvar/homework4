# homework4
ödev 4 / disticnt ve count

--SORU 1 
SELECT DISTINCT replacement_cost FROM film;

--SORU 2
SELECT COUNT(DISTINCT replacement_cost) FROM film;

cevap '21'

-- SORU 3

SELECT title,rating FROM film
WHERE title LIKE 'T%' AND rating='G'

-- SORU 4
SELECT COUNT(country) FROM country
WHERE country ILIKE '_____'

cevap '13'

--SORU 5
SELECT COUNT(city) FROM city
WHERE city ILIKE'%r'

cevap '33'
