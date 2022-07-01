--find the top 10 most followed accounts on twitter
SELECT rank, name, username, followers_millions FROM top_twitter LIMIT 10

-- select the twitter accounts with more than 100 million followers
SELECT name, followers_millions, country FROM top_twitter WHERE followers_millions > 100

--select the 3rd, 4th and 5th country with the most number of top representation
SELECT country, COUNT(country) FROM top_twitter GROUP BY country ORDER BY country DESC LIMIT 3 OFFSET 2

--select top 5 occupation with the most number of representation
SELECT DISTINCT occupation, count(occupation) FROM top_twitter GROUP BY occupation ORDER BY occupation DESC LIMIT 5

 -- countries with the most combined followers_millions
SELECT country, sum(followers_millions) AS sum FROM top_twitter GROUP BY country ORDER BY sum DESC










