# books-mysql-async-type1

## install

1. npm i express morgan cors mysql2 dotenv

## steps

1. set up express

2. create html

3. set static dir

4. install ejs

5. set view engine

6. rename html to ejs

7. render views

## uzd pasipraktikuoti

1. pasikurti is naujo visa projekta nuo boiler plate ir pasisetupinti ejs view engine nepamirsi css ir js

2. Add few images, and display them (add image file)

3. create posts page. Connect to mysql db and display post with an include of post.ejs component

4. in server.js file create global constant CuurentUser with email and username pass this user object to posts page in header show user email if it exists

5. Create users page. Generate users from mysql db users table, show only emails in the list

6. contact page. make cards link

## uzduotys ejs toliau

1. sukurti forma irasyti naujai knygai su ivesties laukais
2. forma siusti su front end fetch
3. forma siusti be front end fetch (action=books/new method=post)
4. padaryti front end validacija ivesties laukui title, be refresh (min 3 raides)
5. padaryti validacija validaija ivesties laukui title back end su refresh (min 3 raides)
6. padaryti sort mygtuka isrikuioti duomenis su refresh naudojant query params (?sort=asc) pagal title/author/timestamp