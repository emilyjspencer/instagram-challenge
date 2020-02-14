Instagram Challenge
===================

## Instructions

* Challenge time: one weekend
* Feel free to use Google, your notes, books, etc., but work on your own
* If you refer to the solution of another coach or student, please put a link to that in your README
* If you have a partial solution, **still check in a partial solution**
* You must submit a pull request to this repo with your code by 9am Monday morning

## Task

Build Instagram: Simple huh!

Your challenge is to build Instagram using Rails. You'll need **users** who can post **pictures**, write **comments** on pictures and **like** a picture. Style it like Instagram's website (or more awesome).

Bonus if you can add filters!

## How to start

1. Produce some stories, break them down into tasks, and estimate
2. Fork this repo, clone, etc
3. Initialize a new rails project

Remember to proceed in small steps! Getting confused? Make the steps even smaller.

## Code Quality

For linting, you can use the `.rubocop.yml` in this repository (or your own!).
You'll need these gems:

```ruby
gem "rubocop", "0.79.0", require: false
gem "rubocop-rails"
```

You can also lint Javascript, CSS, and ERB — feel free to research this. These
will help you to train yourself to produce cleaner code — and will often alert
you to mistakes or mishaps!


User Stories

(Subject to change)

```
Sign-up

As a non-registered user,
So I can start to make posts,
I'd like to see a sign-up form on the homepage

As a non-registered user,
So I can make a post,
I'd like to sign up using my email address, password, username, first name and last name

As a non-registered user,
So others can't guess my password,
I'd like the password to be valid only if it is between 6 and 10 characters

As a product owner
So as to reduce the likelihood of people creating false accounts,
The email addresses used to sign up must be valid 

As a newly registered user,
So I know I have successfully signed up,
I'd like to see a "Sign up has been successful" message on the homepage 

As a product owner
So as to protect the website's content
I'd like users to be redirected to the log-in page if they try to access another url before signing in
```

```
Login and logout


As a registered user
So that only I can post to my account
I'd like to be able to log in using my credentials

As a registered user
So as to prevent others from accessing my account and making posts on my behalf,
I'd like to be able to log out

```

```
Posting

As a registered user,
So I can post a picture,
I'd like to see an option to make a post

As a registered user,
So I can start to make posts,
I'd like to be directed to my feed once I've signed in

As a registered user,
So others can find my pictures,
I'd like to be able to add hashtags to my post

As a registered user,
So I know how long ago I made a post,
I'd like to see the date and time that the post was made

As a registered user,
So I can give my posts context,
I'd like to be able to give my post a caption

As a registered user,
In addition to adding a caption to my posts,
I'd like to be able to write comments under the post

As a registered user,
So I can remove pictures I don't like,
I'd like to be able to delete posts

As a registered user,
So I can make my pictures look better,
I'd like to be able to add filters to my posts
```


