1-SELECT * FROM country WHERE country LIKE 'A%a'; 
2-SELECT * FROM country WHERE country LIKE '_____%n'; 
3-SELECT title FROM film WHERE title ILIKE '____%' and title ILIKE 't%' or title ILIKE '%t%' or title ILIKE '%t'; 
4-SELECT * FROM film WHERE title LIKE 'C%' and length >90 and rental_rate=2.99  ; 
