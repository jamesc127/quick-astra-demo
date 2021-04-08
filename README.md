# Quick Astra Demo
### Quick public demo on Astra &amp; Stargate REST API
[Sign up and download Postman here](https://identity.getpostman.com/signup?continue=https%3A%2F%2Fgo.postman.co%2Fbuild) (you'll only have to do this once)
- Click Import
![](./screens/01_step.png)


- Copy this URL
```
https://raw.githubusercontent.com/jamesc127/quick-stargate-demo/main/postman/quick-astra-demo.postman_environment.json
```
- Click Link, Paste URL, Click Import
![](./screens/02_step.png)


- Click Import again
- Copy this URL and repeat the above process
```
https://raw.githubusercontent.com/jamesc127/quick-stargate-demo/main/postman/quick-astra-demo.postman_collection.json
```


- Create an Auth Token on the Astra website
![](./screens/06_step.png)
![](./screens/08_step.png)


- Copy your cluster ID
![](./screens/09_step.png)


- Fill in your database information to Postman's variables
![](./screens/05_step.png)
![](./screens/07_step.png)
  

- If everything is filled out correctly, 
you should be able to use the `GET` request called `Get A Movie` 
and see a response