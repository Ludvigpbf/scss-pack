# scss-pack
a scss pack with mixins, variables and animations


Featured varaiables:

 - font sizes in:
  - px(2px-54px)
  - em(2px-54px)
  - rem(2px-54px)
  - vw(2px-54px)
  - vh(2px-54px)
 - flex box variants
 - responsive breakpoints
  - mobile()
  - mobile-landscape()
  - tablet()
  - tablet-landscape()
  - desktop()
 - colors
 - 


mixin regular($h1: $f-5xl, $h2: $f-3xl, $p: $f-md){
h1(
font-size: $h1;
)
h2(
font-size: $h2;
)
p(
font-size: $p;
)
}