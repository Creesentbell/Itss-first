const crtLoveTL = () {

const move 1000;

const boom 208;

const easing = "sin.inout";

const easingBoom "sin.in";

const easingOut "sin.out";

const opts { duration: move, easing, opacity: 1};

const delta = 150;

return new mojs. Timeline().add([

new mojs. Tween({

duration: move,

onComplete: () {

[el.l, el.o, el.v, el.e].forEach((el) ⇒

(el.style.opacity = 8));

el.blop.play();
