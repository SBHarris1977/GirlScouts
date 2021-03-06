# Girl scout troop
A blogging/sharing site for a girl scout troop.  Requirements:

Example of a terrible site with some basic functions:
https://gstroop1690.shutterfly.com/


Minimum viable product:
1) user/logins to get in
2) Some nice photos of the troop.  This can just be 3-4 photos manually served for MVP.
3) Some "news" from the leaders (upcoming events, announcements etc).  This can be manually written for MVP.
4) A calendar showing upcoming events.  Either a Box or a list of events.  This should be created from the calendar database items.
5) A simple Blogging feature where users can enter new comments, and other users can respond to those items.  This is very similar to the blogging assignments from class.
6) A nice looking site with some branding borrowed from Girl scouts of america or some other example.

Nice to have features:
1) photo sharing.  uploading, downloading, browsing
2) better calendar.  3rd party integration?  Best experience would be Google calendar just integrated so that members could sync to the troop calendar.
3) admin page.  See incoming membership requests, manage membership list, etc.
4) Sign up sheets.  A common need is a list of people signing up for cookie booths, camping trips etc.  So a table made from a SQL table that shows who is going etc.  
5) generic file sharing.  A way to upload/download pdf's or whatever.  This seems really hard.

Technologies Used:

1. Handlebars
2. NodeJS
3. Express
4. MySQL
5. Sequelize
6. JQuery
7. Google Calendar API
8. Materialize

Deployed: https://enigmatic-mesa-65313.herokuapp.com

Working the Application
1. To add news to the site simply click the News link.
2. Enter text in the news post.
3. Enter title, name and date (the date can be manually entered or use up and down arrows).
4. Click the "Post" button and the data is saved.

When you return to the Home page the news post as been added to the bottom.

To enter comments into the discussion you will need to login with Facebook or Twitter.

![](https://github.com/SBHarris1977/GirlScouts/blob/master/public/images/Girl%20Scouts%20Photo.JPG)
