# CS360

# Module 8 Journal

1. Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

    For the Project I created the Event Tracking application, and the goal of it was to design and develop a mobile application with complete functionality
    that helps users manage and track their future events. The main requirement here was to allow the users to create an account and then log in with it.
    Then, once logged in, they would be able to manage their events by adding them, editing them, or deleting them. They would also be able to opt in to
    receive SMS notifications for their events, but this feature is completely optional. This app was designed to address the need for organization and
    time management, since most users rely on their phones to keep track of things like appointments and their personal events.

2. What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

   To support the needs of the users, I included several screens and features like a login screen, a main event display screen, an add/edit event screen, and an SMS approval screen. 
   The login screen lets users create an account and then securely login to access their data. The main screen is what displays all of their events in a clear, organized layout, 
   which makes it easy for users to view their events. The add event screen is what lets the user input the details of their event like the name, date, time, and a description. And 
   lastly, the SMS approval screen is where users can approve of SMS features or deny them. The design of the UI is focused on simplicity and usability by keeping the overall
   layouts clean and by using clear labels, which is something I learned to do in this course. These design choices were successful because they make it easy for users to understand
   how to use the app without any confusion.

3. How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

   When I started coding the app, I followed the same approach we learned this course by going step by step instead of trying to code it all at once. The first thing
   I started with was the login functionality, making sure the user could create an account and login. Then I needed to work on the database, so users could have their
   information like events saved. I then added features like creating events, and deleting them. Once that was done, I worked on SMS notifications. After the main parts
   of the application were coded, I went through and added additional features like editing events and switching users. The technique I used (breaking the project into
   smaller parts) made the development process a lot smoother and made it more manageable. This is an approach I will continue to use in the future because it will prevent
   me from becoming overwhelmed.

4. How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

   To test my code, I used the Android emulator and my actual Android phone (Samsung Galaxy S23). I tested each feature individually, like creating an account, logging in,
   adding the events, deleting events, and editing them. I also tested the SMS functionality by making sure that the app worked whether or not SMS permissions were granted
   or denied. Testing here was important because it helped me identify and fix issues early on and made sure that each part of my app was working as intended.

5. Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

   For the development process, I faced a few challenges that required me to solve problems and find solutions by looking through the ZyBook lessons. One of my main challenges
   was making sure that the events were tied to specific users. A user could login, but if someone else made an account and logged in, they would see the events of every user.
   So, I had to make it so that each user only saw their own data, and this was done by storing a user ID and linking it to each event in the database. This required me to make
   changes to both the database structure and how the data was retrieved.

6. In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
7. 
