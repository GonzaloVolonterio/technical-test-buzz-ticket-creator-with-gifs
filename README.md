# Technical test Buzz creator ticket with gifs
  
## Built With
 ```
React
Nextjs
JavaScript
Tailwind
```

### Install 🔧

```
npm install
```

```
npm run dev
```

### Clone repo 🔧

```
https://github.com/GonzaloVolonterio/technical-test-buzz-ticket-creator-with-gifs

```

### Create Database

```
.Go to Mongodb 

https://www.mongodb.com/atlas

.Login or create user

.Choose free databa base "MO FREE" and provider

.Create

.Create Username and password

.Connect from "Add My Current ip Adress" -> finish close

.Network access -> Add Ip Access -> confirm

.Go to Database -> Browse Collections -> Add my own Database -> choose database name and collection name

.Go to Overview -> Drivers -> there you can see mongodb+srv... copy go to your project 

.In your project create .env -> go to .gitignore -> add .env

.Create a .env -> MONGO_URI= Put your MONGODB_URI=mongodb+srv://username:password@cluster0.b2jrhmx.mongodb.net/databasename

```


### .Add

```
 In app/page

.Add in fetch

'http://localhost:3000/api/Tickets'

---

In app/components/DeleteBlock

.Add in fetch

`http://localhost:3000/api/Tickets/${id}`

---

In app/Ticket/[id]/page

.Add in fetch

`http://localhost:3000/api/Tickets/${id}`

---

.In app/models/Ticket

MONGODB_URI -> same to .env

---





