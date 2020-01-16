# Fastest way to launch development server for SearchX

1. First type in following commands in terminal:
``` 
git clone https://github.com/ArthurCamara/searchx-front-scaffolding.git
cd searchx-front-scaffolding
git checkout visual-progress-bar
npm install (https://github.com/fsevents/fsevents/issues/302)
cp .env.example .env
vim .env
```
2. This will open the .env file. Here you have to change the value of ```REACT_APP_SERVER_URL``` to ```http://irbackend.ewi.tudelft.nl:443```
3. Then save and exit the .env file.

4. ```npm run start```will start the development server at localhost:8080. If it says 'Disqualified User' go to step 5 else if it launches the home page of SearchX go to step 6.
5. In Local Storage change value of invalid-user key to 0. Then refresh page. This should launch the home page of SearchX.
6. Navigate to localhost:8080/sync to launch the Study description page. The backend is already up in the irbackend server. To make sure the backend is up type http://irbackend.ewi.tudelft.nl:443/ in your address bar. If it is okay it will display the message ```{"error":false,"message":"The API is up and running."}```.
7. Fill in personal details form
8. Pre Test for topic 1 - Put 1 for all ten questions
9. Pre Test for Sports - Put 2 for all ten questions
10. Pre Test for topic 3 - Put 1 for all ten questions
11. This will lead you to the search page of searchX. Scaffolding container should be on the right.
12. To play around with the styling, you have to check the files in the path ``` ./src/js/app/search/features/scaffolding/components/```.
The files specifically -> Scaffolding.js ScaffoldingItem.js and Scaffolding.pcss
