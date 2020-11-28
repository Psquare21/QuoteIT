# QuoteIT

Technical Stacks: React.js, Node.js, Express.js, MongoDB, JavaScript, Python, CSS, HTML, RESTful API (MERN), Flask, Tensorflow

Developed a SAAS platform to solve the problem of searching a caption for any images uploaded by the user on social media with the help of machine learning.

Designed Front-end of website using JavaScript, CSS, HTML

Connected Front-end with MongoDB database of website with the help of Node.js, Express.js

Additionally, Connected the website with our SAAS backend with the help of Flask and Python. 

Trained ML Model using Tensorflow 

#How to use this code

First of all, Download or Clone this code.

Once it is downloaded, just change path to backend,  frontend-finished and server folder in different terminal

In backend and frontend-finished terminal, download all the dependency using npm install and inside server folder download and activate tensorflow using conda install tensorflow and activate tensorflow.

Once it is done, in the backend folder, go to app.js file and give path of your own MongoDB database and in the location.js file provide API of your GCP for geocoding functionality.

In the frontend-finished foler, gor to public folder and in the index.html file change the path of google map and provide API key of your GCP.

Once all the above strps are done, You can run this program with ease with the following commands: "node app.js" in backend, "npm start" in frontend, "python monolith.py" on ML side

