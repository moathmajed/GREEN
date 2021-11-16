# GREEN

.room__container::after {
  background: transparent;
 }
.room__image, .room__video {
  position: fixed;
  top: 50%;
  left: 50%;
  width: 100%;
  height: auto;
  z-index: -100;
  transform: translateX(-50%) translateY(-50%);
  will-change: transform;
  transition: 1s opacity;
  filter: blur(0.01px);
  -webkit-filter: blur(0.01px);
  -moz-filter: blur(0.01px);
  -o-filter: blur(0.01px);
  -ms-filter: blur(0.01px); 
    
}

.room__container::before {
  background-size: 100%;
  height: 100%;
  width: 100%;
  position: absolute;
  content: "";
  z-index: -1;
  filter: blur(0.01px);
 -webkit-filter: blur(0.01px);
  -moz-filter: blur(0.01px);
  -o-filter: blur(0.01px);
  -ms-filter: blur(0.01px); 
    
}



.room__container--available .room__container__status__countdown__hours__number,
.room__container--available .room__container__status__countdown__minutes__number {
  background: #3cf799;
  background: -webkit-linear-gradient(#3cf799, #57f171);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent; }

.room__container--available .room__container__status__countdown__hours__number::after,
.room__container--available .room__container__status__countdown__minutes__number::after {
  color: transparent;
  text-shadow: -0.1px 0 0.1px #3cf799, 0 -0.1px 0.1px #3cf799, 0.1px 0 0.1px #3cf799, 0 0.1px 0.1px #3cf799; }



.room__container--reserved .room__container__status__countdown__hours__number,
.room__container--reserved .room__container__status__countdown__minutes__number {
  background: #ff2c55;
  background: -webkit-linear-gradient(#ff2c55, #f5317b);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent; }

.room__container--reserved .room__container__status__countdown__hours__number::after,
.room__container--reserved .room__container__status__countdown__minutes__number::after {
  color: transparent;
  text-shadow: -0.1px 0 0.1px #ff2c55, 0 -0.1px 0.1px #ff2c55, 0.1px 0 0.1px #ff2c55, 0 0.1px 0.1px #ff2c55; }

  
.screensaver__container::after {
  background-color: #0a0a0a;
  opacity: 0.1; }

.screensaver_flash {
  background-color: #0a0a0a; }
  
/** BACKGROUD COLORS ***/



.bg__theme-color-7 {
  background-color: #5AB947; }


/* Background and border color for the timeline events created in the past */
.timeline__content__event__content--finished {
border-color: rgba(130,255,100,.3);
background-color: rgba(130,255,100,.05);
}
/* Background color for the timeline events created in the future */
.bg__main-color-1 {
background-color: rgba(130,255,100,.3);
}
/* Border color for the timeline events created in the future */
.border__main-color-1 {
border-left-color: #82FF64;
}
/* Background and border color for the active event from timeline */
.timeline__content__event__content--active,
.timeline__content__event__content--selected {
border-color: #82FF64;
background-color: rgba(130,255,100,.8);
}
/* Current time pin color when available */
.bg__main-color-2,
.timeline__content__now::before {
background-color: #387146;
}
/* Current time pin color when reserved */
.timeline__content__now--reserved,
.timeline__content__now--reserved::before {
background-color: #387146;
}
/** END BACKGROUD COLORS ***/

  
