# designkit-animate
1.0.0

A Sass module for * used in RightScale apps.

## Install
```
npm i --save designkit-animate
```

## CSS

```css
.animate-top,
.animate-bottom,
.animate-left,
.animate-right {
  opacity: 0;
  -webkit-animate-duration: 0.6s;
          animate-duration: 0.6s;
  -webkit-animate-fill-mode: forwards;
          animate-fill-mode: forwards;
}

.animate-top {
  -webkit-animate-name: animate-top;
          animate-name: animate-top;
  -webkit-transform: translateY(-12.5vh);
          transform: translateY(-12.5vh);
}

.animate-bottom {
  -webkit-animate-name: animate-bottom;
          animate-name: animate-bottom;
  -webkit-transform: translateY(12.5vh);
          transform: translateY(12.5vh);
}

.animate-left {
  -webkit-animate-name: animate-left;
          animate-name: animate-left;
  -webkit-transform: translateY(-12.5vh);
          transform: translateY(-12.5vh);
}

.animate-right {
  -webkit-animate-name: animate-right;
          animate-name: animate-right;
  -webkit-transform: translateY(12.5vh);
          transform: translateY(12.5vh);
}

@-webkit-keyframes animate-top {
  0% {
    -webkit-transform: translateY(-12.5vh);
            transform: translateY(-12.5vh);
    opacity: 0;
  }
  100% {
    -webkit-transform: translateY(0);
            transform: translateY(0);
    opacity: 1;
  }
}

@keyframes animate-top {
  0% {
    -webkit-transform: translateY(-12.5vh);
            transform: translateY(-12.5vh);
    opacity: 0;
  }
  100% {
    -webkit-transform: translateY(0);
            transform: translateY(0);
    opacity: 1;
  }
}

@-webkit-keyframes animate-bottom {
  0% {
    -webkit-transform: translateY(12.5vh);
            transform: translateY(12.5vh);
    opacity: 0;
  }
  100% {
    -webkit-transform: translateY(0);
            transform: translateY(0);
    opacity: 1;
  }
}

@keyframes animate-bottom {
  0% {
    -webkit-transform: translateY(12.5vh);
            transform: translateY(12.5vh);
    opacity: 0;
  }
  100% {
    -webkit-transform: translateY(0);
            transform: translateY(0);
    opacity: 1;
  }
}

@-webkit-keyframes animate-left {
  0% {
    -webkit-transform: translateX(-12.5vh);
            transform: translateX(-12.5vh);
    opacity: 0;
  }
  100% {
    -webkit-transform: translateX(0);
            transform: translateX(0);
    opacity: 1;
  }
}

@keyframes animate-left {
  0% {
    -webkit-transform: translateX(-12.5vh);
            transform: translateX(-12.5vh);
    opacity: 0;
  }
  100% {
    -webkit-transform: translateX(0);
            transform: translateX(0);
    opacity: 1;
  }
}

@-webkit-keyframes animate-right {
  0% {
    -webkit-transform: translateX(12.5vh);
            transform: translateX(12.5vh);
    opacity: 0;
  }
  100% {
    -webkit-transform: translateX(0);
            transform: translateX(0);
    opacity: 1;
  }
}

@keyframes animate-right {
  0% {
    -webkit-transform: translateX(12.5vh);
            transform: translateX(12.5vh);
    opacity: 0;
  }
  100% {
    -webkit-transform: translateX(0);
            transform: translateX(0);
    opacity: 1;
  }
}

.animate-fade {
  opacity: 0;
  -webkit-animate-name: animate-fade;
          animate-name: animate-fade;
  -webkit-animate-duration: 0.4s;
          animate-duration: 0.4s;
  -webkit-animate-fill-mode: forwards;
          animate-fill-mode: forwards;
}

@-webkit-keyframes animate-fade {
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
  -webkit-animate-duration: 750ms;
          animate-duration: 750ms;
  -webkit-animate-name: animate-flash;
          animate-name: animate-flash;
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
            transform: scale(0.9);
    opacity: 0;
  }
  50% {
    -webkit-transform: scale(1.03);
            transform: scale(1.03);
    opacity: 1;
  }
  100% {
    -webkit-transform: scale(1);
            transform: scale(1);
    opacity: 1;
  }
}

@keyframes animate-zoom {
  0% {
    -webkit-transform: scale(0.9);
            transform: scale(0.9);
    opacity: 0;
  }
  50% {
    -webkit-transform: scale(1.03);
            transform: scale(1.03);
    opacity: 1;
  }
  100% {
    -webkit-transform: scale(1);
            transform: scale(1);
    opacity: 1;
  }
}

.animate-zoom {
  opacity: 0;
  -webkit-animate-name: animate-zoom;
          animate-name: animate-zoom;
  -webkit-animate-duration: 0.2s;
          animate-duration: 0.2s;
  -webkit-animate-fill-mode: forwards;
          animate-fill-mode: forwards;
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
  -webkit-animate-name: animate-highlight;
          animate-name: animate-highlight;
  -webkit-animate-duration: 2s;
          animate-duration: 2s;
  -webkit-animate-fill-mode: forwards;
          animate-fill-mode: forwards;
}

.animate-delay-1 {
  -webkit-animate-delay: 0.1s;
          animate-delay: 0.1s;
}

.animate-delay-2 {
  -webkit-animate-delay: 0.2s;
          animate-delay: 0.2s;
}

.animate-delay-3 {
  -webkit-animate-delay: 0.4s;
          animate-delay: 0.4s;
}

.animate-delay-4 {
  -webkit-animate-delay: 0.6s;
          animate-delay: 0.6s;
}

.animate-delay-5 {
  -webkit-animate-delay: 1s;
          animate-delay: 1s;
}

.animate-delay-6 {
  -webkit-animate-delay: 2s;
          animate-delay: 2s;
}

.animate-duration-1 {
  -webkit-animate-duration: 0.1s;
          animate-duration: 0.1s;
}

.animate-duration-2 {
  -webkit-animate-duration: 0.2s;
          animate-duration: 0.2s;
}

.animate-duration-3 {
  -webkit-animate-duration: 0.4s;
          animate-duration: 0.4s;
}

.animate-duration-4 {
  -webkit-animate-duration: 0.6s;
          animate-duration: 0.6s;
}

.animate-duration-5 {
  -webkit-animate-duration: 1s;
          animate-duration: 1s;
}

.animate-duration-6 {
  -webkit-animate-duration: 2s;
          animate-duration: 2s;
}

.animate-linear {
  -webkit-animate-timing-function: linear;
          animate-timing-function: linear;
}

.animate-ease-in {
  -webkit-animate-timing-function: ease-in;
          animate-timing-function: ease-in;
}

.animate-ease-out {
  -webkit-animate-timing-function: ease-out;
          animate-timing-function: ease-out;
}

.animate-ease-in-out {
  -webkit-animate-timing-function: ease-in-out;
          animate-timing-function: ease-in-out;
}

.animate-motion-1 {
  -webkit-animate-timing-function: cubic-bezier(0.62, 0.28, 0.23, 0.99);
          animate-timing-function: cubic-bezier(0.62, 0.28, 0.23, 0.99);
}

.animate-motion-2 {
  -webkit-animate-timing-function: cubic-bezier(0.075, 0.82, 0.165, 1);
          animate-timing-function: cubic-bezier(0.075, 0.82, 0.165, 1);
}

.animate-motion-3 {
  -webkit-animate-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
          animate-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
}

.animate-motion-4 {
  -webkit-animate-timing-function: cubic-bezier(0.19, 1, 0.22, 1);
          animate-timing-function: cubic-bezier(0.19, 1, 0.22, 1);
}

```

## Author

Jason Melgoza

## License

MIT
