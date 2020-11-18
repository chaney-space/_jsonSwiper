

#### CSS 디바이스별 폰트 크기 vw 활용 참고

`
.swiper-slide {
  padding: 16px;
  font-size: 16px;
  font-size: 4vw;
}
@media only screen 
and (min-device-width: 736px)
and (min-device-height: 414px)
and (orientation: landscape) {
  .swiper-slide {
    font-size: 2vw;
  }
}
@media only screen 
and (min-device-width: 960px)
and (min-device-height: 600px)
and (orientation: landscape) {
  .swiper-slide {
    font-size: 2.2vw;
  }
}
@media only screen 
and (min-device-width: 1024px)
and (min-device-height: 768px)
and (orientation: landscape) {
  .swiper-slide {
    font-size: 2.4vw;
  }
}
@media only screen 
and (min-device-width: 768px)
and (min-device-height: 1024px)
and (orientation: portrait) {
  .swiper-slide {
    font-size: 3.3vw;
  }
}

@media only screen 
and (min-device-width: 600px)
and (min-device-height: 960px)
and (orientation: portrait) {
  .swiper-slide {
    font-size: 3.4vw;
  }
}
@media only screen 
and (min-device-width: 1280px)
and (min-device-height: 800px)
and (orientation: landscape) {
  .swiper-slide {
    font-size: 2.2vw;
  }
}
`


#### References Link

https://codepen.io/dannievinther/pen/GNExxb
https://qastack.kr/programming/15649244/responsive-font-size-in-css
