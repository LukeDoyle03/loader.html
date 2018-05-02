main {
  width: 100vw;
  height: 100vh;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
      -ms-flex-pack: center;
          justify-content: center;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  background: #090707;
}

.dank-ass-loader {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
      -ms-flex-direction: column;
          flex-direction: column;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
}
.dank-ass-loader .row {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
}

.arrow {
  width: 0;
  height: 0;
  margin: 0 -6px;
  border-left: 12px solid transparent;
  border-right: 12px solid transparent;
  border-bottom: 21.6px solid #fd7000;
  -webkit-animation: blink 1s infinite;
          animation: blink 1s infinite;
  -webkit-filter: drop-shadow(0 0 18px #fd7000);
          filter: drop-shadow(0 0 18px #fd7000);
}
.arrow.down {
  -webkit-transform: rotate(180deg);
          transform: rotate(180deg);
}
.arrow.outer-1 {
  -webkit-animation-delay: -0.05556s;
          animation-delay: -0.05556s;
}
.arrow.outer-2 {
  -webkit-animation-delay: -0.11111s;
          animation-delay: -0.11111s;
}
.arrow.outer-3 {
  -webkit-animation-delay: -0.16667s;
          animation-delay: -0.16667s;
}
.arrow.outer-4 {
  -webkit-animation-delay: -0.22222s;
          animation-delay: -0.22222s;
}
.arrow.outer-5 {
  -webkit-animation-delay: -0.27778s;
          animation-delay: -0.27778s;
}
.arrow.outer-6 {
  -webkit-animation-delay: -0.33333s;
          animation-delay: -0.33333s;
}
.arrow.outer-7 {
  -webkit-animation-delay: -0.38889s;
          animation-delay: -0.38889s;
}
.arrow.outer-8 {
  -webkit-animation-delay: -0.44444s;
          animation-delay: -0.44444s;
}
.arrow.outer-9 {
  -webkit-animation-delay: -0.5s;
          animation-delay: -0.5s;
}
.arrow.outer-10 {
  -webkit-animation-delay: -0.55556s;
          animation-delay: -0.55556s;
}
.arrow.outer-11 {
  -webkit-animation-delay: -0.61111s;
          animation-delay: -0.61111s;
}
.arrow.outer-12 {
  -webkit-animation-delay: -0.66667s;
          animation-delay: -0.66667s;
}
.arrow.outer-13 {
  -webkit-animation-delay: -0.72222s;
          animation-delay: -0.72222s;
}
.arrow.outer-14 {
  -webkit-animation-delay: -0.77778s;
          animation-delay: -0.77778s;
}
.arrow.outer-15 {
  -webkit-animation-delay: -0.83333s;
          animation-delay: -0.83333s;
}
.arrow.outer-16 {
  -webkit-animation-delay: -0.88889s;
          animation-delay: -0.88889s;
}
.arrow.outer-17 {
  -webkit-animation-delay: -0.94444s;
          animation-delay: -0.94444s;
}
.arrow.outer-18 {
  -webkit-animation-delay: -1s;
          animation-delay: -1s;
}
.arrow.inner-1 {
  -webkit-animation-delay: -0.16667s;
          animation-delay: -0.16667s;
}
.arrow.inner-2 {
  -webkit-animation-delay: -0.33333s;
          animation-delay: -0.33333s;
}
.arrow.inner-3 {
  -webkit-animation-delay: -0.5s;
          animation-delay: -0.5s;
}
.arrow.inner-4 {
  -webkit-animation-delay: -0.66667s;
          animation-delay: -0.66667s;
}
.arrow.inner-5 {
  -webkit-animation-delay: -0.83333s;
          animation-delay: -0.83333s;
}
.arrow.inner-6 {
  -webkit-animation-delay: -1s;
          animation-delay: -1s;
}

@-webkit-keyframes blink {
  0% {
    opacity: 0.1;
  }
  30% {
    opacity: 1;
  }
  100% {
    opacity: 0.1;
  }
}

@keyframes blink {
  0% {
    opacity: 0.1;
  }
  30% {
    opacity: 1;
  }
  100% {
    opacity: 0.1;
  }
}
