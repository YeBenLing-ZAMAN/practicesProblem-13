# practicesProblem-13

/** ============  Responsive Part  ============**/

/* Extra large = (Up To 1170px) = XL */
@media (min-width: 1170px) {
    .container {
        max-width: 1170px;
 background:green;
    }
}
@media (max-width: 1170px) {
   .container {
        max-width: 992px;
 background:red;
    }
}
/* Medium large = (992-768) = MD. */
@media (max-width: 992px) {
   .container {
        max-width: 767px;
 background:yellow
    }
}
/* Tablet Devices = (768-576) = SM */
@media (max-width: 767px) {
   .container {
        max-width: 576px;
 background:gray;
    }
} 
/* Big Mobile  = (576-420) = Extra-SM */
@media (max-width: 576px) {
     .container {
        max-width:100%;
 background:purple;
    }
}
/* Small Mobile = (420-320) = Extra-SM  */
@media (max-width: 420px) {
  body{
 background:pink;
}
}
/* ============The  End============  */
