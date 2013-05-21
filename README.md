Animate_Catch
=============
CSS keyframe animations have a property called animation-timing-function and one of the options is to
use the steps() feature like in this example:

.innerRight {
    -webkit-animation: playright 0.5s steps(5);
  -moz-animation: playright 0.5s steps(5);
}
@-webkit-keyframes playright { 
      0% { background-position:    0px 0; } 
    100% { background-position: -250px 0; }
}
