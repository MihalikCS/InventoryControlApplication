# InventoryControlApplication
Project for SNHU CS360 - Final Project. Design a warehousing/Inventory control application.

- Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The requirements of this application was to desgin a warehousing inventory application that was protected by a login, had the ability to create and delete new products, update the inventory count of those products and have a basic notification system that was opt-in that allowed the user to recieve a text message alert when stock of items were low. This applications was designed to allow users who worked in the industry to keep an up-to-date inventory on there persons, and to identify proactively when an item was low in stock versus running out and being unable to fill an order.

- What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

The biggest need was a datagrid in where the user can actively interact with the inventory. This data grid showed columns like the product name and type, the count of what was on hand, the ability to delete the item via a button postioned on the right most side of every row, and an intutive way of updating an inventory count by clicking on the data row number. Overall my designs were simple, as I didn't want to confuse the user with a very advanced UI that was hard to navigate.

- How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?

I did a lot of experimentation here as this really is the first time I have developed anything in mobile space. So I had alot of R&D and iteratively went over the UI to see what worked and what didn't. I could use this approach in the future with mobile UI as it really did give me the ability to play with the UI and see how the small screen space really affected navigation and actually using the application. 

- How did you test to ensure your code was functional? Why is this process important and what did it reveal?

I did a lot of manual testing to ensure that my code worked. Ideally, given more time and space I would love to take advantage of automated unit testing and UI unit testing to enusre that what I wrote is what i expected the UI to do, and if any future updates broke those results. This process overall took a ton of time and had me saying 'there had to be a better way' the entire time.

- Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?

Believe it or not, the acutal programming. While having a background in development, I hadn't really done much in the mobile sphere. So having to interact with the different android API's to request permissions and then recover data from those services was particullarly challenging in the beginning. Once I got the hang of how those systems worked, it was much easier to develop.

- In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

I think the recycle view (datagrid) is what I am most proud of. It uses an adapter to create a row layout and then applies that to data pumped in from SQL Lite. I really think that area is the strongest area of that application.
