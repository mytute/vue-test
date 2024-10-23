# 4 single file components    

### vue file    
A *.view file is a custom file format that uses HTML like syntax to describe a portion of the UI.    

Each *.vue file consists of three types of top-level language blocks   
1. <template></template>    
2. <script></script>
3. <style></style>

The template block is like the HTML of your UI.    
The script block is where the logic and functionality of your app can be maintained.    
The CSS block is where you specify the styles related to the mark up in the template block.    

In vue *.vue file is called a single file component(SFC).    

1. delete .vue file inside the component folder and remove related code insdie App.vue file.    

```vue 
<template>
  <p>Samadhi</p>
</template>

<script>

export default {
  name: 'App',
  components: {
  }
  data (){
      return {
          name: "Samadhi Laksahan"
      }
  }
}
</script>

<style>
</style>
```
