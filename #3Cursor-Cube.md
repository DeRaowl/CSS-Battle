# Cube

```css
<p class="box"><p class="s"><p class="t">
<style>body{
   display: flex;
   justify-content: center;
   align-items: center;
   background: #0B2429
  }
  .box {
    position: absolute;
    top: 40%;
    width: 100px;
    height: 100px;
    background: #F3AC3C;
    transform: rotate(45deg);
  }
  
  .box::before{
    content:"";
    position: absolute;
    width: 100px;
    height: 50px;
    background: #998235;
    left: -75%;
    transform: rotate(-90deg) skew(-45deg);
  }
  
   .box::after{
    content:"";
    position: absolute;
    width: 100px;
    height: 50px;
    background: #1A4341;
    top: -50%;
    left: -25px;
    transform: skew(45deg);
  }
  
  
</style>
  ```
  
  
## Output

![image](https://user-images.githubusercontent.com/26904087/121185670-ed279f80-c883-11eb-91c3-6345e01cb89c.png)

