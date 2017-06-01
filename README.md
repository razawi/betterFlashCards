# See the [Demo](https://flash-notes-admin.herokuapp.com/#/profile)
click on Curricula and move to category and card

# See the code
[server](https://github.com/razawi/flash-cards-server)

[angular client](https://github.com/razawi/angular-flashCards-client)

react native app

[mini skelaton](https://github.com/razawi/flashCards-client-mini-skelaton)


# betterFlahCards
a nodejs server with angular client to manage better flahs cards.

### What is this project?
This project aims to provide a repository + server + web page + smartphone app for better flash crads.

### Why do I need flash cards?
flash cards are possibly the best way to memorize and learn new Information weather Its a definitions list for an academic course or a list of words for your vocabulary in your native language or a new foreign language.     

### But why "better" flash cards? what's better about them?
Beside the obvious advantages of digital vs a pile of papers (distributable, doesn't get lost, access from anywhere...)
there is also one GREAT edge. a digital flash card can have more than just 2 sides!    

### Use case scenario
The basic need for this project came from my attempt to Improve my Arabic vocabulary.    
on every single flash card I would like to have 3 "faces":

1) A word written in Arabic :
```
شكر
```

2) Since my reading in Arabic is far from fluent I also need the Arabic word in letters I can understand. in this case:
```
"Shukra" (pernounced "Shukran").
```

3) The meaning of the word in a langugae I understand in this case.
```
Thanks
```

If I was to do that with paper flash cards I'd have to either give up on one of those 3 valuesor or I would need 2 seperate
paper cards for each word! the current repository holds some 2,250 words so I'd need 2,250 PAIRS of cards and each pair has to be kept as a pair. that's just unmanagable.

### The displayed Data
The first data here which is used both as an example and for development purposses is a list of common words in spoken Arabic
In the Palastinian dialect and the matching transcript in English and meaning in Hebrew. hopefully in the future more people will donate flash cards for
any type of use. SAT words, foreign languages, academic classes terminology etc...


## Technology
the server is a node js server using express 4.x for its routing and mongodb 3.x + mongoose 4.x for the data. cards data is managed
by the dataController module while users data Is managed via passport.js.
client side is partially ejs templates (Views) while the cards are currently being converted from jquery to angular.

### Architecture
server side uses express and a straightforward MVC architecture,
Client Is currently an angular app with ui.route.
The angular directory tree is feature based Instead of the traditional partials/models/
directives directory structure. It makes the code more easy to navigate and thereby more scalable and loose-coupled.

### The server side
a full REST API In node, mocha tests, and utils to maintain the db

### Client
There [angular client](https://github.com/razawi/flashCards-client) project in still in early development.
other clients will be added soon


### Credentials and credits

It's open source (MIT license)

Feel free to whatever you want to do with it.
