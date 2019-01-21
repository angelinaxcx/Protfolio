# Protfolio
This landing page was made to introduce skills and knowledge I obtain from the Web Development course .
# Built Using 
- HTML
- CSS
# Main elments of the landing page 
- Site is built with alot of the traingle shapes using (clip-path) .
- All pictures are used with background attachment tag.
- Alot of hover effects.
# Explaintation on how it was DONE 
-Traingles' shape were made using amazing code generator  https://bennettfeely.com/clippy/ and placed using positions 
```tri1{
    width:400px;
    height: 800px;
    clip-path: polygon(100% 0, 0 0, 50% 100%);
    background-image: url(a.jpg);
    background-attachment: fixed;
    position: absolute;
    left: 100px;
   
}
```

-Background Image's were all used by background attachment tag so when the user scroll along with the containing block the image stayed.
```
.container1{
    width: 100%;
    height: 1300px;
    background-image: url(bg8.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    background-attachment: fixed;
    position: relative;

}
```

-Hover effects were used on menu and buttons to make more effect on the page .
```
.dropbtn {
    width: 60px;
    height:60px;
    background-image: url(menu1.png);
    background-size: cover;
    color: black;
    padding: 20px;
    font-size: 16px;
    border: none;
    z-index: 100px;
   
  }
  
  .dropdown {
    
    left: 30px;
    top: 30px;;
    position: fixed;
    display: inline-block;
    z-index: 100px;


  }
  
  .dropdown-content {

    display: none;
    position: absolute;
    background-color: #f1f1f1;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
   
  }
  
  .dropdown-content a {
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
  }
  
  .dropdown-content a:hover {background-color: #ddd;}
  
  .dropdown:hover .dropdown-content {display: block;}
  
  .dropdown:hover .dropbtn {background-image: url(menu.jpg);

}

```

```

.twitter{
    width: 50px;    
    height: 50px;
    background-color: white;
    background-image: url(twitter.jpg);
    display: inline-block;
    position: absolute;
    right: 295px;
    top: 150px;
}

.twitter:hover{
    background-color: #00ffd8;
}

.facebook{
    width: 50px;
    height: 50px;
    background-color: white;
    background-image: url(facebook.jpg);
    display: inline-block;
    position: absolute;
    right: 350px;
    top: 150px;
}

.facebook:hover {
    background-color: #00ffd8;
}

```
# All credits and idea goes to
- Alee Foroughi for his amazing creativity and work on his site (http://www.aleeforoughi.com/)
