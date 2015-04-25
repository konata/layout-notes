[position](http://learnlayout.com/position.html)
===

  possible values are
  `static` `relative` `fixed` `absolute`


#### static
  static is the default value, an element with static is said to be `not positioned` and anything else is said tobe `positioned`

#### relative
   **relative behave the same as static unless adding other property**,
   the properties are `top` `right` `bottom` `left`
   the element will be adjusted from its normal position,other content will not be affected


#### fixed
  fixed is relative to the viewport, it stays the same even when page is scrolled,also  `top,right,bottom,left` can be used


#### absolute
  absolute is like fixed but relative to the `nearest` positioned
  ancestor instead of the viewport , if no ancestor is positioned,
  it uses the document body,and still move along the page scroll
  ***absolute 是脱离文档流的，不给父元素撑起height和width***