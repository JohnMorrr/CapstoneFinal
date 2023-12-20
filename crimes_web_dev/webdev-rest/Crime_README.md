This was my final project for my web development class. It was two parts - first making the API that connects to our St. Paul Crimes database with UPDATE, PUT, DELETE, and GET requests, as well as some sql syntax for querying. In the second part we used Vue.js and Foundation CSS frameworks to create the actual page. I worked with two other group members on this, and our information can be seen in the 'About' page in the project. When logging in you'll see a pop-up to enter a localhost url - this is where our database API is running. Aftering entering the URL you can see the map outlining St. Paul's neighborhoods, the crimes within the neighborhoods, the option to create a new incident form (crime), and if you scroll to the bottom you can view the actual database rows with them highlighted based on the crime commited. Because it is run with a backend API, any modifications to the database will result in the page changing everytime it is refreshed since it is rendering via the server-side.

HOW TO USE:
1. Install node.js for the page
2. after installing, run 'npm install' in the terminal and wait for all packages to be installed
3. Next run 'npm run build' and let the app build, then run 'npm run dev' to run the Vue.js app.
4. Next to make sure the database API is live, go to the rest_server.mjs page and in the terminal (you may have to open a second) type 'node ./rest_server.mjs' and wait to get the server successfully connected.
5. Once connected, enter that same http://localhost:8000 URL in the pop-up and Voila! You are in the St. Paul Crimes API project!
