_[Demo and API docs](http://captaincodeman.github.io/sign-here/)_

##&lt;sign-here&gt;

`sign-here` is a polymer element that provides smooth signature drawing with HTML5 Canvas by wrapping
the [signature_pad](https://github.com/szimek/signature_pad) library.

Example:

    <sign-here width="400" height="200" image="{{image}}"></sign-here>

The `image` property will be updated after any interaction with the data-uri encoded value of the image.
The encoding method and quality can be controlled, as can the color of the paper and ink.
