##Inspiration
One common problem among our team was the ability to achieve goals. These goals were feasible, but were not reached due to a lack of motivation. Also, we, being fortunate enough to live in Silicon Valley, have opportunities that many others across the globe don’t have. We wanted to make something that could potentially help those who do not have access to technology. Thus, striving to combine motivation and donation, we created Donation and Motivation Service, or DMS for short.

##What It Does
A user sets a goal, a time limit, and a value online through our website. The value is the amount of money he/she will donate to charity if he/she do not complete the goal before the set deadline. In this system, motivation is both increased and maintained, and if he/she genuinely cannot achieve the goal, it will go towards a good cause. Specifically, that good cause is an established organization called "Computers 4 Africa", in which they use funds to ship computers to African schools for use. Also, through a social aspect of our product, users can draw inspiration from other fellow ambitious users through a real-time chat service. The service is also mobile friendly. Lastly, users get a kick out of our service through the tone of sarcasm throughout the experience.

##How We Built It
We separated our project into two servers with the idea of having microservices. One server serves as a front-end and the other provides a back-end API with database operations. On the backend side, we ran Node.js as well as Express to create routes and endpoints for the frontend to access. For storing the data we used a lightweight and flexible npm module called LowDB, which essentially functions as a JSON file. On the front end side, we built a React application using Redux as a state machine.

For the processing of money, we utilized Stripe’s API to ensure secure transaction through credit card. In the chat server, we utilized AngularJS to process user data and messages, and PubNub API to stream the data in realtime.

##Challenges We Faced
To create the real-time chat server that supports multiple chat channels, We ran into many problems; We had no idea how to start or how to connect to PubNub, had difficulties with visibility of messages, and struggled through limited JavaScript knowledge. While we were all experienced with coding, we were also relatively new to the parts of the application we were working on. For example, Nathan, who is better with electronics, worked on the real-time chat aspect of the app. Meanwhile, Avik, who had never managed state client side, built a state machine on Redux.

##Accomplishments That We’re Proud Of
We are very proud of the way our website turned out aestetically. It is very pleasing to the eye, and it took a long time to develop the styles through CSS.

Instead of having everything on one server we were able to use microservices. This let us split our team into back and front end and work on each part separately making us far more efficient than if we had used only one server.

In the real-time chat, users can either join a general channel or a channel specific to their goal. As previously mentioned, multiple channel server proved to be especially challenging, but we persevered and gained a lot of experience with JavaScript along the way - that is why we are proud of it.

What We Learned
We gained experience in and learned various programming skills. Among these are git, JavaScript, online transactions, proper code structure, node.js, and redux.js. Also, this is the first time we were in a group with each other, and most of us did not know each other. Thus, we had a great time getting to know each other and working as a team.

What's Next for DMS
We believe a lot of potential lies in this idea. We want to expand and improve our chat room, building it into even more of a social network, in addition to connecting it to social media apps such as Facebook and Instagram. Although it focuses on short-term goals at the moment, it can grow to incorporate long-term goals, bigger goals such as studying for the SAT in 6 months or losing 20 pounds in a year, with higher donation stakes. Lastly, it can grow to utilize hardware for users to physically and quantitatively track certain goals, such as motion sensors that add to the accuracy of fitness goals.
