
body,
html {
  height: 100%;  
  font-family: 'Quicksand', sans-serif;
  text-align: center;
}

.bg {
  /* Location of the image */
  background-image: url(Assets/38030.jpg);
  background-position: center center;
  background-repeat: no-repeat;
  background-attachment: fixed;
  
  /* This is what makes the background image rescale based
     on the container's size */
  background-size: cover;
  
  /* Set a background color that will be displayed
     while the background image is loading */
  background-color: #FEC0CD;
  height: 100%;
}


.img {
  display: inline-block;
  margin-left: auto;
  margin-right: auto;
  position: relative;
  top: 20px;
  margin-bottom: 30px;
  width: 350px;
}

#tap {
  display: inline-block;
}

.foto {
  width: 80%;
  max-width: 400px;
  min-width: 300px;
  margin-top: 100px;
  /* margin-left: auto;
  margin-right: auto;
  margin-bottom: 20px; */
  display: inline-block;
  /* vertical-align: middle;
  line-height: normal; */
}



/* Paper */
@import url(https://fonts.googleapis.com/css?family=Roboto);
@import url(https://fonts.googleapis.com/css?family=Handlee);


.paper {
  font-family: 'Roboto', sans-serif;
  position: relative;
  width: 90%;
  max-width: 800px;
  min-width: 300px;
  height: 540px;
  margin: 50px auto;
  display: inline-block;
  vertical-align: middle;
  line-height: normal;
  background: #fafafa;
  border-radius: 10px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, .3);
  overflow: hidden;
}

.paper:before {
  content: '';
  position: absolute;
  top: 0;
  bottom: 0;
  left: 5px;
  width: 45px;
  background: radial-gradient(#616161 6px, transparent 7px) repeat-y;
  background-size: 30px 30px;
  border-right: 3px solid #D44147;
  box-sizing: border-box;
}

.paper-content {
  position: absolute;
  top: 30px;
  right: 0;
  bottom: 30px;
  left: 50px;
  background: linear-gradient(transparent, transparent 28px, #91D1D3 28px);
  background-size: 30px 30px;
}

.paper-content .teks {
  text-align: left;
  width: 100%;
  max-width: 100%;
  height: 100%;
  max-height: 100%;
  line-height: 30px;
  padding: 0 10px;
  border: 0;
  outline: 0;
  background: transparent;
  color: #3f3f44;
  font-family: 'Handlee', cursive;
  font-size: 18px;
  box-sizing: border-box;
  z-index: 1;
}

.kotak {
  position: relative;
  width: 90%;
  max-width: 550px;
  min-width: 200px;
  max-height: 350px;
  min-height: 100px;
  top: 300px;
  padding: 20px 0;
  display: inline-block;
  background: #fafafa;
  border-radius: 10px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, .3);
  overflow: hidden;
}

.btn {
  border-radius: 40px;
}

#slideLima {
  position: relative;
  top: 300px;
}

#trims {
  position: relative;
  top: 300px;
  display: inline-block;
}

h1 {
  font-weight: normal;
}

li {
  display: inline-block;
  font-size: 16px;
  list-style-type: none;
  position: relative;
  left: -20px;
  margin-top: 10px;
  padding: 10px;
  text-transform: uppercase;
}

li span {
  display: block;
  font-size: 24px;
}

body {
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
}

.container {
  color: #333;
  position: relative;
  top: 250px;
  padding: 0;
  text-align: center;
}
