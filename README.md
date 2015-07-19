AuthProject
===========

## Getting it to run

Before you're able to get it working you have to enter your MongoLab credentials or alter to code to use a local MongoDB database. Copy the `config.example.js` file to `config.js` and enter the following information:

- Username of your dbuser
- Password of that dbuser (dbpassword)
- Replace the first part of the hostname in the url
- Replace the port number in the url

These are all supplied by MongoLab.

After changing these settings don't forget to run
```
npm install
```

to install the dependencies.
