# SoundBTC
@import url(https://fonts.googleapis.com/css?family=Nunito);

html {
  height: 100%;
  overflow: hidden;
}

body { 
  margin:0;
  padding:0;
	perspective: 1px;
	transform-style: preserve-3d;
  height: 100%;
  overflow-y: scroll;
  overflow-x: hidden;
  font-family: Nunito;
}

h1 {
   font-size: 250%
}

p {
  font-size: 140%;
  line-height: 150%;
  color: #333;
}

.slide {
  position: relative;
  padding: 25vh 10%;
  min-height: 100vh;
  width: 100vw;
  box-sizing: border-box;
  box-shadow: 0 -1px 10px rgba(0, 0, 0, .7);
	transform-style: inherit;
}

img {
  position: absolute;
  top: 50%;
  left: 35%;
  width: 320px;
  height: 240px;
  transform: translateZ(.25px) scale(.75) translateX(-94%) translateY(-100%) rotate(2deg);
  padding: 10px;
  border-radius: 5px;
  background: rgba(240,230,220, .7);
  box-shadow: 0 0 8px rgba(0, 0, 0, .7);
}

img:last-of-type {
  transform: translateZ(.4px) scale(.6) translateX(-104%) translateY(-40%) rotate(-5deg);
}

.slide:before {
  content: "";
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  box-shadow: 0 0 8px 1px rgba(0, 0, 0, .7);
}

.title {
  width: 50%;
  padding: 5%;
  border-radius: 5px;
  background: rgba(240,230,220, .7);
  box-shadow: 0 0 8px rgba(0, 0, 0, .7);
}

.slide:nth-child(2n) .title {
  margin-left: 0;
  margin-right: auto;
}

.slide:nth-child(2n+1) .title {
  margin-left: auto;
  margin-right: 0;
}

.slide, .slide:before {
  background: 50% 50% / cover;  
}

.header {
  text-align: center;
  font-size: 175%;
  color: #fff;
  text-shadow: 0 2px 2px #000;
}

#title {
  background-image: url("https://lorempixel.com/640/480/abstract/6/");
  z-index:2;
}

#title h1 {
 transform: translateZ(.25px) scale(.75);
 transform-origin: 50% 100%;

}

#slide1:before {
  background-image: url("https://lorempixel.com/640/480/abstract/4/");
  transform: translateZ(-1px) scale(2);
}

#slide2 {
  background-image: url("https://lorempixel.com/640/480/abstract/3/");
  z-index:2;
}

#slide3:before {
  background-image: url("https://lorempixel.com/640/480/abstract/5/");
  transform: translateZ(-1px) scale(2);
}

#slide4 {
  background: #222;
}
