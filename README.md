# Where-sMyBall

# Notes

## CSS

### Starry Background 

    The starry background was found in a medium tutorial at https://medium.com/@jensaxena/css-tutorial-animated-geometric-galaxy-background-ad3835c36ce1*/

    The background gradient class

```CSS
.space{
    background: rgba(128, 0, 128, 0.1) center / 200px 200px round;
    /* border: 1px dashed rgb(27, 210, 143); */
    bottom: 0;
    left: 0;
    position: absolute;
    right: 0;
    top: 0;
}
```

    These .stars# classes can be repeated to add depth

```CSS
.stars1{
    animation: space 120s ease-in-out infinite;
    background-image: element();
    background-image: 
    radial-gradient(
        1px 1px at 25px 5px, white, rgba(255,255,255,0)
    ),
    radial-gradient(
        1px 1px at 50px 25px, white, rgba(255,255,255,0)
    ),
    radial-gradient(
        1px 1px at 125px 20px, white, rgba(255,255,255,0)
    ),
    radial-gradient(
        1.5px 1.5px at 50px 75px, white, rgba(255,255,255,0)
    ),
    radial-gradient(
        2px 2px at 15px 125px, white, rgba(255,255,255,0)
    ),
    radial-gradient(
        2.5px 2.5px at 110px 80px, white, rgba(255,255,255,0)
    );
}
```

```CSS
.stars2 {
    animation: space 180s ease-in-out infinite;
    background-image:
      radial-gradient(
        1px 1px at 75px 125px, 
        white, 
        rgba(255, 255, 255, 0)
      ),
      radial-gradient(
        1px 1px at 100px 75px, 
        white, 
        rgba(255, 255, 255, 0)
      ),
      radial-gradient(
        1.5px 1.5px at 199px 100px, 
        white, 
        rgba(255, 255, 255, 0)
      ),
      radial-gradient(
        2px 2px at 20px 50px, 
        white, 
        rgba(255, 255, 255, 0)
      ),
      radial-gradient(
        2.5px 2.5px at 100px 5px, 
        white, 
        rgba(255, 255, 255, 0)
      ),
      radial-gradient(
        2.5px 2.5px at 5px 5px, 
        white, 
        rgba(255, 255, 255, 0)
      );
}
```

```CSS
.stars3 {
    animation: space 240s ease-in-out infinite;
    background-image:
      radial-gradient(
        1px 1px at 10px 10px, 
        white, 
        rgba(255, 255, 255, 0)
      ),
      radial-gradient(
        1px 1px at 150px 150px, 
        white, 
        rgba(255, 255, 255, 0)
      ),
      radial-gradient(
        1.5px 1.5px at 60px 170px, 
        white, 
        rgba(255, 255, 255, 0)
      ),
      radial-gradient(
        1.5 1.5px at 175px 180px, 
        white, 
        rgba(255, 255, 255, 0)
      ),
      radial-gradient(
        2px 2px at 195px 95px, 
        white, 
        rgba(255, 255, 255, 0)
      ),
      radial-gradient(
        2.5px 2.5px at 95px 145px, 
        white, 
        rgba(255, 255, 255, 0)
      );
  }
  ```
  
  ```CSS
  @keyframes space {
      40% {
          opacity: 0.75;
      }
      50% {
          opacity: 0.25;
      }
      60% {
          opacity: 0.75;
      }
      100% {
          transform: rotate(360deg);
      }
  }
```