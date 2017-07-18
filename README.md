# [Nomster](http://nomster-tyna-huynh.herokuapp.com/)
A Yelp clone that integrates with the Google Maps API and includes features like user comments, star ratings, image uploading, and user authentication.


![alt tag](https://user-images.githubusercontent.com/14388583/28289609-1e8e2e74-6af8-11e7-8fe2-c736119b8c79.png)

## Running Locally
Make sure you have Ruby installed.
Clone or download the repository.

Run the following code to install the application's dependencies:
```
bundle install
```
Create initial database:
```
rake db:create
```
Run the migration:
```
rake db:migrate
```

The application should now be running on your localhost.

## Deployment
To deploy on Heroku. Adjust the APP_NAME to your project name.
```
heroku create APP_NAME
```
Now push it up to Heroku with the following command:
```
git push heroku master
```
It should take a few moments to run, and when it finishes it should say "Launching..." along with a URL.

To easily see you heroku url you can type:
```
heroku apps:info
```
The application can now be found at the URL returned.
