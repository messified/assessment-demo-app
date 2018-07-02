# Service Repo Name

Demo application utilizing PHP and React+Redux.

### Depenancies:
 * Vagrant
 * Virtual Box

## Architecture Summary

For the PHP test project, I chose Drupal 8 as the base framework. Then implemented a custom module for the core "Accomodation Booking" business logic.

### Why Drupal?

Before I answer the why, I'll start with the what. Drupal 8 is a CMS framework based on Symfony components and Symfony architecture. Drupal also provides other helpful out of the box functionality, such as user authentication, theming, etc.

## DO THIS FIRST

To build/run this project you'll need to have Vagrant, VirtualBox, and the Vagrant NFS support plugin installed.

NFS Support Command:
```
vagrant plugin install vagrant-bindfs
```

## Setup

### Clone Repo
```
clone repo github

cd <reponame>
```

### Start Vagrant
```
vagrant up
```
...Grab some coffee...

### Run setup script
```
vagrant ssh

cd /var/www

sh setup.sh
```
### Varify Setup Completion

Click link to below to view the app. 

 * [http://demo.test](http://demo.test)

### Login Info for demo customer

 * user: customer
 * pass: password

## Bookings Module (PHP/Symfony2)

## React+Redux Blog