# scss-pack

a scss pack with mixins, variables and animations

# Installation

1. Run: npm install @flyckt-coding/scss-pack
2. Import the pack to your main scss file: @import "~@flyckt-coding/scss-pack/";
3. To use classes on elements, import it to your react component: import '@flyckt-coding/scss-pack';
4. Start using the features

Featured varaiables:

- Font sizes in:
  - px(2px-54px)
  - em(2px-54px)
  - rem(2px-54px)
  - vw(2px-54px)
  - vh(2px-54px)
- Flex box variants
- Responsive breakpoints
  - mobile()
  - mobile-landscape()
  - tablet()
  - tablet-landscape()
  - desktop()
- Colors
- Mixins

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

@mixin desktop($width) {
@if($width){
@media screen and (min-width: $width) {
@content;
}
}
@
