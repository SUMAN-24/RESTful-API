### LICENSE
MIT

# RESTful-API
A fake RESTful API for testing purposes,running using the npm module **json-server**. Ready to deploy to services like Cyclic.sh.

## Installation (using any of the two below methods)
Run npm to install RESTful-API:
   ### Method 1: using npm package below

```sh
npm i restful-api-for-easy-deploy-to-services-like-cyclic
```
1. `go to node_modules and you will find a folder with name (restful-api-for-easy-deploy-to-services-like-cyclic)`
2. `cut the whole folder and paste the contents in your repo`---(note-> first you have to create your own repo)
                    
    ### Method 2: cloning of my repo from github

 `clone it and the total structure will be at your end. Then do npm install`
 ```sh
    npm install
```

Having completed the above process follow the below process:

Now you are ready to deploy to Cyclic.sh:

1. `create your endpoints in db.json`
2. `git add .`
3. `git commit`
4. `git push`

## Create account in Cyclic
1. `Go to Cyclic.sh`
2. `Click on sign up`
3. `Click on (Continue with GitHub)`

## After Successfull Login
1. Click on Deploy button
2. `Click on (Link Your Own) tab`
3. `In search box type your repo that you created for deployment`
4. `If your repo is in private mode---it will show Add a private repo option below----click on it`
5. `It will ask for a password confirmation of github`
6. `Enter the password of your github account`
7. `It will redirect to a page where you have to select Repository access`.
8. `Select option called (Only select repositories) --best according to my view.`
9. `Then choose the repo from the dropdown`
10. `Click on (Appove and install)`
11. `Cyclic will start its build and deploying process`
12. `After successful build scroll down the page and click on the dashboard button`

## On dashboard page
1. `Head on to (Environments) tab and click it`
2. `In Custom subdomain you can write the name you want and it will create an additional subdomain for you`
3. `Initially it takes 1-2 minutes for change of domain`
4. `Refresh the page and you will see your custom url`
5. `Hurray! you are ready with your deployment now`
6. `Now you don't need to worry even you change the data as it will automatically deploy after each commit to that repo`

## Editing the initial data

The database is in the file **[db.json](db.json)**. You can edit the JSON information there.

## HTTP Requests & Endpoints

Refer to the [json-server documentation](https://github.com/typicode/json-server) for how to use your API.