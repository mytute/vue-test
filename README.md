# 3 Project Structure    

> package.json   

dependencis and the scripts required for the project

> package-lock.json    

this file simply ensure consistent installation of your dependencis.    

> babel.config.js    

babel configuration file. babel is tool which transfroms modern javascript features being used in development code in to older syntax that is more cross browser compatible in production code. 

> node_modules    

folder in which all the dependencis are installed 

> public folder    

contains static assets that are publish when you want to go live with your application.  

> public>index.html    

this is the only html file you'r going to have in your application you are building single page application and you are not going to add any code body tag in this file.    

> src folder    

main.js : starting point we specify root component and dom element which will be controlled by vue. 
App.vue : file where you specify html css and javascript correspoiding to a portion of the UI you see in the browser.   

> assets folder   

folder can use to store images, svg etc 

### controll flow    
when you are run "npm serve" it serve "index.html" file in the browser. It contain root dom node and it entered the main.js 
