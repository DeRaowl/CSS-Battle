# Missing Slice

```css
 <div class="cirone box"></div>
<div class="cirtwo box"></div>
<div class="cirfour box">
<style>
  .box{
    width: 100px;
    height: 100px;
  }      
  
  .cirone{
    position: absolute;
    background-color: #51B5A9;
    top: 17%;
    left: 25%;
    border-radius: 100% 0% 0 0%
  }
  .cirtwo{
    position: absolute;
    background-color: #FADE8B;
    top: 17%;
    left: 50%;
    border-radius: 0% 100% 0% 0%
  }
  .cirfour{
    position: absolute;
    background-color: #F7F3D7;
    top: 50%;
    left: 25%;
    border-radius: 0% 0% 0 100%
  }
  body{background-color: #E3516E}
  ```
  
  ## Output
  
  ![image](https://user-images.githubusercontent.com/26904087/120144987-78f45880-c200-11eb-964d-9834d0faf85c.png)
