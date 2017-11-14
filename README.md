### What is GroundWatch?

GroundWatch is a mobile responsive web app that allows users to anonymously report violence at protests. You can download the mobile app from the App Store or Google Play.

#### How does it work?

The app maps user reports of violence at protests.

#### Technical Details:
 When the user selects a type of violence (for example, Water Cannons), and clicks “Submit,” the app asks to see their location. When the user gives the app permission, it adds the location to a report along with the type of violence, and submits it to a cloud database. Then, the app pulls down all the reports from the database, and adds them to a Google Map on the website, using the Google Maps API and the Cloudboost SDK. I used JavaScript, JSON, HTML and CSS to build the app.

#### What inspired this project?

The idea for this project came to me at a hackathon in the fall, after reading about incomplete reporting and police violence at Standing Rock, in November 2016. I learned that some influential media had only covered the police’s side of the story, and I wanted to create an outlet for protesters to report what was actually happening.

My team at the hackathon voted against this idea, so I decided to pursue it on my own.

#### How did I research?

When I wanted to know how to make my app the most useful for protesters, I attended two protests, one in New York City and one in Washington, D.C. I decided to add a “Medic Needed” feature that allows protesters to report injuries, after witnessing someone getting hurt at a protest.

#### What are GroundWatch’s key features?

One of the most important features in GroundWatch is the incident map. It maps reports based on location, and clusters them into groups based on their location.

The “Medic Needed” pins are red, to distinguish them from other reports.

The program is web based, because some countries can block apps from the Apple and Google App Stores. Web firewalls are easier to break down, which makes web apps more accessible for protesters in those countries.



#### What’s next for GroundWatch?

I am planning to reach out to a social justice organization to demonstrate the app and receive feedback.
