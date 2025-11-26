# CS2340_F25_gitHub_page
# CS2340\_F25\_Team20 Hi, We are Team 20!

# Introduction:
SpendWise is a personal finance and savings management mobile app designed to help
users take control of their spending and build better money habits. The app enables
users to log expenses, set and track budgets, and visualize their progress through
intuitive dashboards. With a focus on simplicity and clarity, SpendWise provides users
with the tools to understand where their money goes, stay on top of their financial goals,
and be motivated to save.
# Design and Architecture:
Our project follows the MainViewModel View Model otherwise known as the MVVM architecture which often use quite commonly in android app development. This was our initial base of our app we developed following a structure where the view components visible to the user cannot directly interact with the model controlling the business logic. We use a MainViewModel that acts as a control point allowing for the view components to send signals to MainViewModel which then sends those requests to the business model controlling all the while maintaining encapsulation behind the idea that none of the components are directly controlling and simply just relaying messages which allow the models to act out their ideas.
We also used the factory pattern with the development and creation of our fragments and used the observer pattern in the creation of our FireStoreModel, the main object observing all changes to the firestore. These design helped crucially sculpt the idea of app into something we can all be proud of.
# User Interface:
<img width="345" height="582" alt="image" src="https://github.com/user-attachments/assets/f41114ee-7609-41b7-8417-00e7fadb2d33" />
<img width="219" height="387" alt="image" src="https://github.com/user-attachments/assets/2b5b098e-55eb-4171-9cb7-cb9a7d7dee75" />
<img width="324" height="694" alt="image" src="https://github.com/user-attachments/assets/dff0aad4-c978-48c6-8688-e2dd85d235a3" />
<img width="327" height="726" alt="image" src="https://github.com/user-attachments/assets/01049711-72f6-4b64-8d34-eeefc4be764d" />
Instead of choosing to use activities in this app, our group decided to implement the use of Android Studio Fragments. We chose to use fragments over the average use of implenting activities because of their reusuability and organization. Instead of swtiching between multiple fragments we were allowed to simply fit the contents of multiple fragments within the space of one activity making for a more effectively appealing and attractive user interface. 
We also chose to implement Ui Fragment adapters as they are better when it comes to receiving realtime live updates from active users. The use of adapters make the ui also more reusable because we simply did have to recreate ui components over and over again instead we could simply recycle their previous use and build new and better Ui adapters out of them.
# Functionality:

# Conclusions and Reflections:
Amari Owens: This was a truly enriching experience that taught me about the realistic qualities you have to have as software engineer working in a large scale project. From coordinating with your team, to understanding each one and another's thought process to operating in unison. This project has completely changed my way of thinking in the design format of simply building code just to make it work and has evolved my thought process into more how can we improve this project further down the line of development. Thank you 2340 TAs, I am so glad that I took this course.
# Contributors:
* DAVIS ONDIEKI
* Ifeanyi Ezegbo
* Subomi Ajayi
* Gabriel Menghisteab
* Amari Owens
* Noah Buchanan
