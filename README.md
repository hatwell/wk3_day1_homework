## My solutions for the homework

1.  SELECT * FROM movies
2.  SELECT name FROM people;
3.  UPDATE people SET name = 'John Harper' WHERE name = 'jhn Harper';
4.  SELECT name FROM people WHERE name = 'Caroline Hatwell'
5.  DELETE FROM movies WHERE title = 'Batman Begins';
6.  INSERT INTO people(name) VALUES ('Tony Goncalves');
7.  DELETE FROM people WHERE name = 'Zsolt Podoba-Szalai'
8.  UPDATE people SET name = 'Darren Breen' WHERE name = 'instructor' AND id = 10;
8.  UPDATE people SET name = 'Sandy McMillan' WHERE name = 'instructor';
9.  INSERT INTO movies(title, year, show_time) VALUES ('Guardians of the Galaxy 2', 2017, '00:00');
10. UPDATE movies SET show_time = '21:30' WHERE title = 'Guardians of the Galaxy';


#### To delete multiple items with one query, you can run a query like the one below


DELETE FROM [table] WHERE [column title] IN ([values to match for deletion])


 in this example i've matched titles, but you could use anything. probably best to
use ID? or some other unique identifier, so you definitely know what you're deleting.]


e.g. DELETE FROM movies WHERE title IN ('Thor', 'Iron Man 3');
