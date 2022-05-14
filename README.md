# Neumorphism_Pagination
一Neumorphism Pagination design for OpenHarmony.

## Download & Install

Install using npm

```npm i hmos-neumorphism ```

Details about OpenHarmony NPM environment configuration, see at [here](https://gitee.com/openharmony-tpc/docs/blob/master/OpenHarmony_npm_usage.md)

## Usage Instructions
# Pagination

<img src="sample_images/pagination.png" width="" height="">

Import:
```html
<element name='neupagination' src='hmos-neumorphism/pagination/pagination.hml'></element>
```

Usage:
```html
<neupagination color="" width="300px" height="50px" border="50px"  @previous-event="previousEvent" @next-event="nextEvent">
  <button>1</button>
  <button>2</button>
  <button>3</button>
  <button>4</button>
  <button>5</button>
</neupagination>
```

## Code Contribution
If you find any problems during usage, you can submit an [Issue](https://gitee.com/openharmony-sig/pagination/issues) to us. Of course, we also welcome you to send us [PR](https://gitee.com/openharmony-sig/pagination/pulls).

## Open source License
This project is based on [Apache License 2.0](https://gitee.com/openharmony-sig/pagination/blob/master/LICENSE.txt) ，please enjoy and participate in open source freely.

# Reference:

<a href="https://neumorphism.io/">neumorphism.io</a>

<a href="https://ismail9k.github.io/neomorphism/">ismail9k.github.io/neomorphism</a>
