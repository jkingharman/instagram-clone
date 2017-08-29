
## Instagram Mock ##

A rails-based rebuild of Instagram.

As an unregistered user you can:

* Search for and view other users' photos.

As a registered user you can:

* Sign-in and -out
* Add photos and comments
* Edit and delete photos and comments
* Filter photos by tag

## Run ##

Steps to run the app:

```
$ git clone git@github.com:jkingharman/instagram-challenge
$ cd instagram
$ bundle
$ rails server
Visit your assigned local host in the browser
```

## Test ##

```
$ rspec
```

## Major Dependencies ##

* Paperclip so that users can work with photos.
* AWS so that photos are stored on the cloud.
* Devise so that users can sign-in and out.

## Example Image ##
![alt text](https://user-images.githubusercontent.com/24657744/29845042-4b15e85a-8d09-11e7-8115-9083ad0fb313.png)
