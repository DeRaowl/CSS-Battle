# Fidget Spinner

```css
<p></p><i id="up" class="c"></i><i id="center"></i><i id="d" class="c"></i><p>
<style>
  body{
    background: #09042A;
    display: flex;
   	justify-content: center;
    align-items: center;
  }

  p {
    display: inline-block;
    width: 60;
    height: 60;
    border-radius: 50%;
    box-shadow: 0 0 0 10px #E78481;
    margin: 30;
  }
  
  #center{
    display: inline-block;
    box-shadow: 0 0 0 30px#E78481;
  }
  
  #up{
    transform: translateY(-89%);
  }
  .c{
    position: absolute;
    border: 30px solid #F5BB9C;
    border-radius: 50%;
    box-shadow: 0 0 0 10px#09042A; 
  }
  
  #d{
    transform: translateY(89%);
  ```
  
  
## Output

![image](https://user-images.githubusercontent.com/26904087/121185851-1c3e1100-c884-11eb-975c-c61962d02238.png)

