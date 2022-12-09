# Events Manager

### Idea

Instead of many words I just will demonstrate you understandable example:

**Example** : If you are psychologist, you have many clients, and very often you must check your plan and at
the same time your potential clients needs to check your plan to find free areas in it.

This project provide psychologist to show his schedule to anybody and I guess, it actually makes sense!


### Product description

The final product is a web application with time grid and many blocks in it.

Each block is planned event, which you can touch and drug to change time or topic
To plan day, you just should authorize and start creating blocks and topics

Each event has a few properties : time/date, title, link, topic

This is how it seems now: 
 - topic at the left sidebar
 - events without any topic (free events) at the bottom of screen
 - timeline on the top of screen
 - time grid with touchable blocks (events)
 - buttons to zoom time grid at the bottom right

![This is how it seems](/assets/schedule.png)

### Log in/Sign up form

![auth form](/assets/auth.png)

### Other

**Add event / topic**

![add topic](/assets/1.png)
![add event](/assets/2.png)

**Home screen**

![home](/assets/home.png)

### Technologies

**Frontend**:
 - [**nuxt.js (vue.js)**](https://nuxtjs.org/)
 - [**tailwindcss**](https://tailwindcss.com/)

**Backend**:
 - [**python3**](https://www.python.org/)
 - [**flask.py (API)**](https://flask.palletsprojects.com/en/2.2.x/)
 - [**sqlalchemy (sqlite) - database**](https://www.sqlalchemy.org/)