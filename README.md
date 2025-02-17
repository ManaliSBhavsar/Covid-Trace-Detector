# Covid-Trace-Detector

The application uses the face recognition algorithm for recognizing the face of the person who visits the shop. The trace of the person is marked against the Aadhaar card number of that person along with the current time and date in the database. The Aadhaar card database is used for face recognition. If the person who visited the shop tests COVID positive after some days then the last 15 days traces of the person can be obtained by entering the Aadhaar card number of the person in the web browser. The system for detecting the traces of COVID positive patients will be useful to take preventive measures at the places where the infected person has visited in the last 15 days. This will help to control the pace of spreading of the disease and will decrease the count of the infected people.

# Research paper
# The project was published in the Bioscience Biotechnology Research Communications(BBRC),New Delhi, India Approved Journal

Tech Stack:
Face API JS
MongoDB
Express
React
Node
Internet of Things (IoT)

Methodology:
The purposed method for developing the system consists of mainly five main steps.
1.	Detecting the person using camera
2.	Recognizing the person using Face API
3.	Obtaining Aadhaar number and sending it to the central server
4.	Obtaining traces
5.	Visualizing the traces

The application uses the face recognition algorithm implemented using Face API JS which is internally based on Tensorflow, for recognizing the face of the person captured by the camera. The trace of the person is marked against the Aadhaar card number of that person along with the current time and date in the database. The Aadhaar card database is used for face recognition. The Aadhar number is obtained from database and is sent to central server (express server) using REST API. Based on the Aadhaar number, the query is executed on MongoDB to fetch the traces. Last 15 days traces can be visualized in the admin panel which is made using React JS with the help of the obtained Aadhaar number of the person.

Outcome:
Efficient Contact Tracing
Faster Response to Outbreaks
Automated & Secure Data Collection
Visual Representation of Traces
Real-Time Monitoring with IoT Integration
Contribution to Public Health & Safety
