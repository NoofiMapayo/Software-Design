/* Master styles */
body {
    font-family: "Lato", sans-serif;
    margin: 0px;
}
  
  .container {
    display: grid;
    grid-template-columns: 1fr;
}

/* Nav styles */
  .nav-wrapper {
    display: flex;
    justify-content: space-between;
    padding: 38px;
}
  
  .left-side {
    display: flex;
}
  
  .nav-wrapper > .left-side > div {
    margin-right: 20px;
    text-transform: uppercase;
    font-size: 0.9rem;
}
  
  .nav-link-wrapper {
    height: 22px;
    border-bottom: 1px solid transparent;
    transition: border-bottom 0.5s;
}

.nav-link-wrapper a {
    color: #8a8a8a;
    text-decoration: none;
    transition: color 0.5s;
}
  
  .nav-link-wrapper:hover {
    border-bottom: 1px solid black;
}
  
  .nav-link-wrapper a:hover {
    color: black;
}
.active-nav-link {
    border-bottom: 1px solid black;
}
 .active-nav-link a {
    color: black !important;
}


/*Portfolio styles */

  .portfolio-items-wrapper {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
}
  
  .portfolio-item-wrapper {
    position: relative;
}
  
  .portfolio-img-background {
    height: 350px;
    width: 100%;
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
   
}
  
  .img-text-wrapper {
    position: absolute;
    top: 0;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 100%;
    text-align: center;
    padding-left: 100px;
    padding-right: 100px;
}
  
  .logo-wrapper img {
    width: 50%;
    margin-bottom: 20px;
}
 
/*Needs to be more specific */

.img-text-wrapper .subtitle {
    transition: 1s;
    font-weight: 600;
    color: transparent;
}

.img-text-wrapper:hover .subtitle {
    font-weight: 600;
    color: lightseagreen;
    
} 
  
.image-darken {
    transition: 1s;
    filter: brightness(10%);
}
  
/* About Page */ 
  
  .two-column-wrapper {
    display: grid;
    grid-template-columns: 1fr 1fr;
}
  
  .profile-image-wrapper img {
    width: 100%;
}
  
  .profile-content-wrapper {
    padding: 30px;
}
  
  .profile-content-wrapper h1 {
    color: lightseagreen;
}
