# 5 Binding Text    

### Bind script to the template       

1. to App.vue file add static text into "template" with "div" tag and see the code.
```vue  
<template>
  <div>Samadhi Laksahan</div>
</template>
```

2. to make dynamic add some text from the script block and bind the data to the html block. for that we use mustache syntax(pair of curly braces) in vue. 

```vue 
<template>
  <div>Samadhi Laksahan</div>
  <div>{{greet}} {{name}}</div>
</template>

<script>

export default {
  name: 'App',
  components: {
  },
  data() {
    return {
      name: "Piyasiri",
      greet: "Hello"
    }
  }
}
</script>

<style>
</style>
```

3. show how to bind data proterty using directives.   
directive nothing but special html attribute and in view each directive has a v-prefix.    
directive for bindding text : "v-text"(rarely used)    
here "div" tag empty and "v-text" replaces the data property value as inner text of the html element.    
show when we use "v-text" we can't add value to the tag and it show error.

```vue 
<template>
  <div>Samadhi Laksahan</div>
  <div>{{greet}} {{name}}</div>
  <div v-text="channel"></div>
  <!-- <div v-text="channel">Hello</div>  show error-->

</template>

<script>

export default {
  name: 'App',
  components: {
  },
  data() {
    return {
      name: "Piyasiri",
      greet: "hello",
      channel: "code"
    }
  }
}
</script>

<style>
</style>
```
