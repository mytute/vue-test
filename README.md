# 2 Hello World 

### Four ways to add Vue    

1. CDN Package    

```js  
<script src="https://unpkg.com/vue@next"></script>
```

2. npm    
```bash  
$ npm install vue@next
```
Preferred approach over CDN when building large scale applications with Vue.    

3. Vue CLI    

Vue provides an offical CLI for quickly scaffolding single page applications.   
```bash  
$ npm install -g @vue/cli   
$ vue create <project-name>
```

4. Vite    
An opinionated web dev build tool that serves your code via native ES Module imports.     
Your code is served at a lightning fast speed and you get nearly instant hot module replacement.     
```bash  
$ npm init vite-app <project-name>
```

### Create first project     

```bash  
$ yarn global add @vue/cli
$ vue --version   
$ vue create hello-world  # select vue version 3
```

### Run first project    

```bash 
$ cd hello-world
$ npm run serve
```
