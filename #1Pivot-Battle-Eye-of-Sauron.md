# Eye of Sauron

```css
<p></p><div style="transform: translate(-100px,25px) rotate(180deg)"><p></p></div><div style="transform: translate(100px,-25px)"><p></p></div>
<style>
  body{
    display: flex;
	justify-content: center;
    align-items: center;
    background-color: #191210;
  }
  p{
    height: 0;
    width: 0;
    border: 25px solid #84271C;
    border-radius: 50%;
    box-shadow: 0 0 0 25px #191210,0 0 0 45px #ECA03D
  }
  div{
    width: 100px;
    height: 50px;
    position: absolute;
    overflow: hidden;
  }
  div p{
    margin: 20px;
    border: 30px solid #191210;
    box-shadow: 0 0 0 20px #ECA03D;
  }
  ```
  
  
## Output

![image](https://user-images.githubusercontent.com/26904087/120143258-688eae80-c1fd-11eb-9d6e-f92433547db8.png)

