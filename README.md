# Designkit Animate

## Install

```bash
npm i designkit-animate
```

## Usage

```html
<!-- Fading from the top with a delay, a duration and a curve -->
<div class="animate-top animate-delay-3 animate-duration-4 animate-motion-2">Top Fade</div>
```

## The CSS

```css
/*
//
// Designkit-Animate
// --------------------------------------------------
*/
.animate-top,
.animate-bottom,
.animate-left,
.animate-right {
  opacity: 0;
  -webkit-animation-duration: 0.6s;
  -moz-animation-duration: 0.6s;
  animation-duration: 0.6s;
  -webkit-animation-fill-mode: forwards;
  -moz-animation-fill-mode: forwards;
  animation-fill-mode: forwards;
}

.animate-top {
  -webkit-animation-name: animate-top;
  -moz-animation-name: animate-top;
  animation-name: animate-top;
  -webkit-transform: translateY(-12.5vh);
  -moz-transform: translateY(-12.5vh);
  -ms-transform: translateY(-12.5vh);
  -o-transform: translateY(-12.5vh);
  transform: translateY(-12.5vh);
}

.animate-bottom {
  -webkit-animation-name: animate-bottom;
  -moz-animation-name: animate-bottom;
  animation-name: animate-bottom;
  -webkit-transform: translateY(12.5vh);
  -moz-transform: translateY(12.5vh);
  -ms-transform: translateY(12.5vh);
  -o-transform: translateY(12.5vh);
  transform: translateY(12.5vh);
}

.animate-left {
  -webkit-animation-name: animate-left;
  -moz-animation-name: animate-left;
  animation-name: animate-left;
  -webkit-transform: translateY(-12.5vh);
  -moz-transform: translateY(-12.5vh);
  -ms-transform: translateY(-12.5vh);
  -o-transform: translateY(-12.5vh);
  transform: translateY(-12.5vh);
}

.animate-right {
  -webkit-animation-name: animate-right;
  -moz-animation-name: animate-right;
  animation-name: animate-right;
  -webkit-transform: translateY(12.5vh);
  -moz-transform: translateY(12.5vh);
  -ms-transform: translateY(12.5vh);
  -o-transform: translateY(12.5vh);
  transform: translateY(12.5vh);
}

@-webkit-keyframes animate-top {
  0% {
    -webkit-transform: translateY(-12.5vh);
    opacity: 0;
  }
  100% {
    -webkit-transform: translateY(0);
    opacity: 1;
  }
}

@-moz-keyframes animate-top {
  0% {
    -moz-transform: translateY(-12.5vh);
    opacity: 0;
  }
  100% {
    -moz-transform: translateY(0);
    opacity: 1;
  }
}

@keyframes animate-top {
  0% {
    -webkit-transform: translateY(-12.5vh);
    -moz-transform: translateY(-12.5vh);
    -ms-transform: translateY(-12.5vh);
    -o-transform: translateY(-12.5vh);
    transform: translateY(-12.5vh);
    opacity: 0;
  }
  100% {
    -webkit-transform: translateY(0);
    -moz-transform: translateY(0);
    -ms-transform: translateY(0);
    -o-transform: translateY(0);
    transform: translateY(0);
    opacity: 1;
  }
}

@-webkit-keyframes animate-bottom {
  0% {
    -webkit-transform: translateY(12.5vh);
    opacity: 0;
  }
  100% {
    -webkit-transform: translateY(0);
    opacity: 1;
  }
}

@-moz-keyframes animate-bottom {
  0% {
    -moz-transform: translateY(12.5vh);
    opacity: 0;
  }
  100% {
    -moz-transform: translateY(0);
    opacity: 1;
  }
}

@keyframes animate-bottom {
  0% {
    -webkit-transform: translateY(12.5vh);
    -moz-transform: translateY(12.5vh);
    -ms-transform: translateY(12.5vh);
    -o-transform: translateY(12.5vh);
    transform: translateY(12.5vh);
    opacity: 0;
  }
  100% {
    -webkit-transform: translateY(0);
    -moz-transform: translateY(0);
    -ms-transform: translateY(0);
    -o-transform: translateY(0);
    transform: translateY(0);
    opacity: 1;
  }
}

@-webkit-keyframes animate-left {
  0% {
    -webkit-transform: translateX(-12.5vh);
    opacity: 0;
  }
  100% {
    -webkit-transform: translateX(0);
    opacity: 1;
  }
}

@-moz-keyframes animate-left {
  0% {
    -moz-transform: translateX(-12.5vh);
    opacity: 0;
  }
  100% {
    -moz-transform: translateX(0);
    opacity: 1;
  }
}

@keyframes animate-left {
  0% {
    -webkit-transform: translateX(-12.5vh);
    -moz-transform: translateX(-12.5vh);
    -ms-transform: translateX(-12.5vh);
    -o-transform: translateX(-12.5vh);
    transform: translateX(-12.5vh);
    opacity: 0;
  }
  100% {
    -webkit-transform: translateX(0);
    -moz-transform: translateX(0);
    -ms-transform: translateX(0);
    -o-transform: translateX(0);
    transform: translateX(0);
    opacity: 1;
  }
}

@-webkit-keyframes animate-right {
  0% {
    -webkit-transform: translateX(12.5vh);
    opacity: 0;
  }
  100% {
    -webkit-transform: translateX(0);
    opacity: 1;
  }
}

@-moz-keyframes animate-right {
  0% {
    -moz-transform: translateX(12.5vh);
    opacity: 0;
  }
  100% {
    -moz-transform: translateX(0);
    opacity: 1;
  }
}

@keyframes animate-right {
  0% {
    -webkit-transform: translateX(12.5vh);
    -moz-transform: translateX(12.5vh);
    -ms-transform: translateX(12.5vh);
    -o-transform: translateX(12.5vh);
    transform: translateX(12.5vh);
    opacity: 0;
  }
  100% {
    -webkit-transform: translateX(0);
    -moz-transform: translateX(0);
    -ms-transform: translateX(0);
    -o-transform: translateX(0);
    transform: translateX(0);
    opacity: 1;
  }
}

.animate-fade {
  opacity: 0;
  -webkit-animation-name: animate-fade;
  -moz-animation-name: animate-fade;
  animation-name: animate-fade;
  -webkit-animation-duration: 0.4s;
  -moz-animation-duration: 0.4s;
  animation-duration: 0.4s;
  -webkit-animation-fill-mode: forwards;
  -moz-animation-fill-mode: forwards;
  animation-fill-mode: forwards;
}

@-webkit-keyframes animate-fade {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}

@-moz-keyframes animate-fade {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}

@keyframes animate-fade {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}

.animate-flash {
  -webkit-animation-duration: 750ms;
  -moz-animation-duration: 750ms;
  animation-duration: 750ms;
  -webkit-animation-name: animate-flash;
  -moz-animation-name: animate-flash;
  animation-name: animate-flash;
}

@-webkit-keyframes animate-flash {
  0%,
  50%,
  100% {
    opacity: 1;
  }
  25%,
  75% {
    opacity: 0;
  }
}

@-moz-keyframes animate-flash {
  0%,
  50%,
  100% {
    opacity: 1;
  }
  25%,
  75% {
    opacity: 0;
  }
}

@keyframes animate-flash {
  0%,
  50%,
  100% {
    opacity: 1;
  }
  25%,
  75% {
    opacity: 0;
  }
}

@-webkit-keyframes animate-zoom {
  0% {
    -webkit-transform: scale(0.9);
    opacity: 0;
  }
  50% {
    -webkit-transform: scale(1.03);
    opacity: 1;
  }
  100% {
    -webkit-transform: scale(1);
    opacity: 1;
  }
}

@-moz-keyframes animate-zoom {
  0% {
    -moz-transform: scale(0.9);
    opacity: 0;
  }
  50% {
    -moz-transform: scale(1.03);
    opacity: 1;
  }
  100% {
    -moz-transform: scale(1);
    opacity: 1;
  }
}

@keyframes animate-zoom {
  0% {
    -webkit-transform: scale(0.9);
    -moz-transform: scale(0.9);
    -ms-transform: scale(0.9);
    -o-transform: scale(0.9);
    transform: scale(0.9);
    opacity: 0;
  }
  50% {
    -webkit-transform: scale(1.03);
    -moz-transform: scale(1.03);
    -ms-transform: scale(1.03);
    -o-transform: scale(1.03);
    transform: scale(1.03);
    opacity: 1;
  }
  100% {
    -webkit-transform: scale(1);
    -moz-transform: scale(1);
    -ms-transform: scale(1);
    -o-transform: scale(1);
    transform: scale(1);
    opacity: 1;
  }
}

.animate-zoom {
  opacity: 0;
  -webkit-animation-name: animate-zoom;
  -moz-animation-name: animate-zoom;
  animation-name: animate-zoom;
  -webkit-animation-duration: 0.2s;
  -moz-animation-duration: 0.2s;
  animation-duration: 0.2s;
  -webkit-animation-fill-mode: forwards;
  -moz-animation-fill-mode: forwards;
  animation-fill-mode: forwards;
}

@-webkit-keyframes animate-highlight {
  0% {
    background-color: rgba(221, 255, 158, 0.5);
    background-color: rgba(191, 255, 71, 0.5);
  }
  100% {
    background-color: rgba(221, 255, 158, 0);
    background-color: rgba(191, 255, 71, 0);
  }
}

@-moz-keyframes animate-highlight {
  0% {
    background-color: rgba(221, 255, 158, 0.5);
    background-color: rgba(191, 255, 71, 0.5);
  }
  100% {
    background-color: rgba(221, 255, 158, 0);
    background-color: rgba(191, 255, 71, 0);
  }
}

@keyframes animate-highlight {
  0% {
    background-color: rgba(221, 255, 158, 0.5);
    background-color: rgba(191, 255, 71, 0.5);
  }
  100% {
    background-color: rgba(221, 255, 158, 0);
    background-color: rgba(191, 255, 71, 0);
  }
}

.animate-highlight {
  -webkit-animation-name: animate-highlight;
  -moz-animation-name: animate-highlight;
  animation-name: animate-highlight;
  -webkit-animation-duration: 2s;
  -moz-animation-duration: 2s;
  animation-duration: 2s;
  -webkit-animation-fill-mode: forwards;
  -moz-animation-fill-mode: forwards;
  animation-fill-mode: forwards;
}

.animate-delay-1 {
  -webkit-animation-delay: 0.1s;
  -moz-animation-delay: 0.1s;
  animation-delay: 0.1s;
}

.animate-delay-2 {
  -webkit-animation-delay: 0.2s;
  -moz-animation-delay: 0.2s;
  animation-delay: 0.2s;
}

.animate-delay-3 {
  -webkit-animation-delay: 0.4s;
  -moz-animation-delay: 0.4s;
  animation-delay: 0.4s;
}

.animate-delay-4 {
  -webkit-animation-delay: 0.6s;
  -moz-animation-delay: 0.6s;
  animation-delay: 0.6s;
}

.animate-delay-5 {
  -webkit-animation-delay: 1s;
  -moz-animation-delay: 1s;
  animation-delay: 1s;
}

.animate-delay-6 {
  -webkit-animation-delay: 2s;
  -moz-animation-delay: 2s;
  animation-delay: 2s;
}

.animate-duration-1 {
  -webkit-animation-duration: 0.1s;
  -moz-animation-duration: 0.1s;
  animation-duration: 0.1s;
}

.animate-duration-2 {
  -webkit-animation-duration: 0.2s;
  -moz-animation-duration: 0.2s;
  animation-duration: 0.2s;
}

.animate-duration-3 {
  -webkit-animation-duration: 0.4s;
  -moz-animation-duration: 0.4s;
  animation-duration: 0.4s;
}

.animate-duration-4 {
  -webkit-animation-duration: 0.6s;
  -moz-animation-duration: 0.6s;
  animation-duration: 0.6s;
}

.animate-duration-5 {
  -webkit-animation-duration: 1s;
  -moz-animation-duration: 1s;
  animation-duration: 1s;
}

.animate-duration-6 {
  -webkit-animation-duration: 2s;
  -moz-animation-duration: 2s;
  animation-duration: 2s;
}

.animate-linear {
  -webkit-animation-timing-function: linear;
  -moz-animation-timing-function: linear;
  animation-timing-function: linear;
}

.animate-ease-in {
  -webkit-animation-timing-function: ease-in;
  -moz-animation-timing-function: ease-in;
  animation-timing-function: ease-in;
}

.animate-ease-out {
  -webkit-animation-timing-function: ease-out;
  -moz-animation-timing-function: ease-out;
  animation-timing-function: ease-out;
}

.animate-ease-in-out {
  -webkit-animation-timing-function: ease-in-out;
  -moz-animation-timing-function: ease-in-out;
  animation-timing-function: ease-in-out;
}

.animate-motion-1 {
  -webkit-animation-timing-function: cubic-bezier(0.62, 0.28, 0.23, 0.99);
  -moz-animation-timing-function: cubic-bezier(0.62, 0.28, 0.23, 0.99);
  animation-timing-function: cubic-bezier(0.62, 0.28, 0.23, 0.99);
}

.animate-motion-2 {
  -webkit-animation-timing-function: cubic-bezier(0.075, 0.82, 0.165, 1);
  -moz-animation-timing-function: cubic-bezier(0.075, 0.82, 0.165, 1);
  animation-timing-function: cubic-bezier(0.075, 0.82, 0.165, 1);
}

.animate-motion-3 {
  -webkit-animation-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
  -moz-animation-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
  animation-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
}

.animate-motion-4 {
  -webkit-animation-timing-function: cubic-bezier(0.19, 1, 0.22, 1);
  -moz-animation-timing-function: cubic-bezier(0.19, 1, 0.22, 1);
  animation-timing-function: cubic-bezier(0.19, 1, 0.22, 1);
}
```

## Author

Jason Melgoza

## License

The MIT License (MIT)

Copyright (c) 2016 RightScale

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
