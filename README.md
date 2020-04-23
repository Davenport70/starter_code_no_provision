## How to use this repo

## To view the app go to:

```
'development.local'
```
If you wish to see fibonacci then run:

```
development.local/fibonacci
```
If you wish to see posts then run:

```
development.local/posts
```

## To run the app go to:

To run the app go your terminal, find your directory and run the command below on the Vagrantfile:

```
vagrant up
```
After you are inside the machine you need to go to the right directory inside your vm. You want to be in the directory with the package.json.

```
cd /home/ubuntu/app
```
After you need to run npm test to check everything is working.

```
npm test
```

Next run the app and get your app listening with:
```
npm install
```
Or
```
node app.js
```

Finally to ensure your posts display on **development.local/posts** you need to cd into the *seeds* directory and run:

```
node seed.js
```
