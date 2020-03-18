# B and Breakfast
This was the first of my group projects at Makers. The time frame was 5 days to complete, and the brief was to build a clone of AirBnb. To see a list of User Stories, please check out the userstories.md file in this directory!

This is a single page web app built in Javascript, Ruby, Sinatra, PostgreSQL and JQuery. It was my first group project, and my first time using Javascript, and my first time building a single page app! It was a steep learning curve, but overall was a very enjoyable experience. it was a pleasure working with the Team, you can find the original repo [*here*](https://github.com/shadz22/MakersBnB). Huge shout out to them members Ben, Meghan and Shadi. I enjoyed the weeks project and learnt so much in such a short space of time. 

---

## Functionalities:
- A user can Register, or can Log-in if already registered (checked and authenticated via the PostgreSQl database )
- Any registered user can list a new space.
- Registered users can list multiple spaces.
- Registered users are able to name their space, provide a short description of the space, and a price per night.
- Registered users can able to offer a range of dates where their space is available.
- Any registered user can request to hire any space for multiple nights, and this can be approved by the user that owns that space.
- Nights for which a space has already been booked are not available for users to book (shown by the dates in the calender vanishing).

---

## How to Run:

Clone this repo, and in the command line run:

```
bundle install
```

Then run the following command:

```
rackup
```

Then click on [*localhost:9292*](http://localhost:9292/) to open this up in your browser and start using!

__Add Database:__

To save state and add the database to the app so users, listing and bookings can be saved, first install PostreSQL. In the command line type:

```
brew install postgres
```

Then from the command line, cut and paste the text from each of the 5 files located in the __db/migrations__ folder in this directory, this will create the tables for your database, and set up the necessary rows and columns.

---

## Homepage
<img src="./images/homepage.png">

## Listings 
<img src="./images/listing.png">

## Calender in Listings
<img src="./images/calender.png">

## Create Listing
<img src="./images/create-listing.png">

