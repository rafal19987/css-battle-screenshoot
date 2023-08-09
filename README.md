# css-battle-screenshoot

![css-battle-screenshot](https://github.com/rafal19987/css-battle-screenshoot/assets/6312438/37445e85-9856-46ec-b62b-6af76d575411)

```html
<div class="background">
  <div class="green-item"/>
  <div class="yellow-item"/>
</div>
<style>
  * {
    margin: 0;
    padding: 0;
  }
  
  .background {
    position: relative;
    width: 100wv;
    height: 100vh;
    background-color: #998235;
  }
  
  .green-item, .green-item:before, .yellow-item, .yellow-item:before {
    position: absolute;
  }

  .green-item, .yellow-item:before  {
    border-top-right-radius: 50px;
    border-bottom-left-radius: 50px;
  }

  .green-item:before, .yellow-item {
    border-top-left-radius: 50px;
    border-bottom-right-radius: 50px;
  }

  .green-item:before, .yellow-item:before {
    content: '';
  }

  .green-item, .green-item:before {
    width: 80px;
    height: 100px;
    background-color: #1A4341;
  }

  .yellow-item, .yellow-item:before {
    width: 80px;
    height: 60px;
    background-color: #F3AC3C;
  }
  
  .green-item {
    top: 60px;
    left: 110px;
  }

  .green-item:before {
    top: 80px;
    left: 100px;
  }

  .yellow-item {
    top: 0px;
    left: 100px;
  }

  .yellow-item:before {
    top: 120px;
    right: 100px;
  }
</style>
```
