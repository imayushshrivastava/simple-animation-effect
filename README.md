# Website Animation Effect

 Simple lite weight css to animation effect on your website.
 
## Demo

* https://imayushshrivastava.github.io/simple-animation-effect/
 
## Usage

To use animate.css in your website, simply drop the stylesheet into your document's <head>, and add the class animated to an element, along with any of the animation names. That's it! You've got a CSS animated element. Super!

```
<head>
  <link rel="stylesheet" href="assets/css/animate.css">
</head>
```
or use a CDN hosted version by CDNJS

```
<head>
  <link rel="stylesheet" href="Update Soon!">
</head>
```

# Usage with Javascript

You can do a whole bunch of other stuff with animate.css when you combine it with Javascript. A simple example:

```
</script>
    <!--Animation JavaScript -->
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
      AOS.init({
        duration: 1200,
      })
    </script>
``` 

# Animations

To animate an element, add the class animated to an element. You can include the class infinite for an infinite loop. Finally you need to add one of the following classes to the element:

## Data AOS Class Name	( data-aos="effect" )
```
bounce	flash	pulse	rubberBand
shake	headShake	swing	tada
wobble	jello	bounceIn	bounceInDown
bounceInLeft	bounceInRight	bounceInUp	bounceOut
bounceOutDown	bounceOutLeft	bounceOutRight	bounceOutUp
fadeIn	fadeInDown	fadeInDownBig	fadeInLeft
fadeInLeftBig	fadeInRight	fadeInRightBig	fadeInUp
fadeInUpBig	fadeOut	fadeOutDown	fadeOutDownBig
fadeOutLeft	fadeOutLeftBig	fadeOutRight	fadeOutRightBig
fadeOutUp	fadeOutUpBig	flipInX	flipInY
flipOutX	flipOutY	lightSpeedIn	lightSpeedOut
rotateIn	rotateInDownLeft	rotateInDownRight	rotateInUpLeft
rotateInUpRight	rotateOut	rotateOutDownLeft	rotateOutDownRight
rotateOutUpLeft	rotateOutUpRight	hinge	jackInTheBox
rollIn	rollOut	zoomIn	zoomInDown
zoomInLeft	zoomInRight	zoomInUp	zoomOut
zoomOutDown	zoomOutLeft	zoomOutRight	zoomOutUp
slideInDown	slideInLeft	slideInRight	slideInUp
slideOutDown	slideOutLeft	slideOutRight	slideOutUp
heartBeat	
```		


# Full example:

```
<h1 data-aos"fade-up">Example</h1>
```
