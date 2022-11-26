# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

- White: hsl(0, 0%, 100%)
- Light gray: hsl(212, 45%, 89%)
- Grayish blue: hsl(220, 15%, 55%)
- Dark blue: hsl(218, 44%, 22%)

## Typography

### Body Copy

- Font size (paragraph): 15px

### Font

- Family: [Outfit](https://fonts.google.com/specimen/Outfit)
- Weights: 400, 700





<style>
@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap');
</style>

 :root {
       --white: hsl(0, 0%, 100%);
       --light-gray: hsl(212, 45%, 89%);
       --grayish-blue: hsl(220, 15%, 55%);
       --dark-blue: hsl(218, 44%, 22%);
  }

 body {
        font-family:"Outfit" , sans-serif;
        font-size:15px 
        background-color:var(--light-gray);
        display:flex;
        flex-direction:column ;
        align-items:centre ;
        margin:1.40rem ;
        height:calc(110vh-1px)
  }
  
 container {
             background-color:var(--white);
             padding:1.40rem;
             margin-bottom:1.40rem;
             border-radius:1rem;
  }
  
  
  img {
        max-width:100%;
        margin-bottom:1rem;
        border-radius:1rem;
  }
  
  
  h1{
      text align-items:centre ;
      color:var(--dark-blue);
      margin-bottom:1.40rem ;
  }
  
  
  p{
      
     text align-items:centre ;
     color:var(--grayish-blue);
   }
   
   
   
 {@media(min-width:375px)
      container {
              width:300px;
       }
 }
 






