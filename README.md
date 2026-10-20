# CS360MobileArchitect-Programming

Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
My inventory application was built in order to help various users track items in their inventory. More specifically, the application required a database with two tables, one for users, and one for items. The user table would help store user data and validate user data through a login page. That login page also allowed a user to create an account if they hadn't before. Once logged in, my hope page was a grid filled with inventory items that are stored in the inventory items table. The user needed to be able to delete each item on the home page as well as add or remove inventory quantity. My home page also had a button that connected to an add item page because the user needed to be able to add new items as well. The last feature was a button on the home page that navigated to an SMS notifications page. This allowed the user to enable SMS notifications so when inventory hit 0 it would send a text message. 

What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
My application started with the login and registration screen as it's the natural start point for any application where a user enters their information and it's validated to load user data. The rest of my application was centered around the home page containing the inventory. It was the most natural center of my application.


How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?
When building my application, I focused on user needs and workflow. I thought about what each screen would do and how the user would navigate to and from each screen. Once, I had that I built each object model and database table. I went through an implemented each capability one at a time and reevaluating my objects and processes to ensure the system was still working as intended.

How did you test to ensure your code was functional? Why is this process important, and what did it reveal?
I tested often after each section of code I wrote and then tested for other edge cases. 

Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?
Most of my innovation to overcome challenges came from implementing processes such as where certain methods we implemented. I had quite a few moments where I was connecting each piece together and it didn't quite come together the way I wanted it to.

In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
I think I did a great job building the grid. I worked really hard on the RecyclerView, adapter, and design each little ViewHolder. I spent quite a bit of time on that and I was most proud of how that turned out.
