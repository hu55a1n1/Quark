# Quark

![Ghost version](https://img.shields.io/badge/Ghost-0.11.x-brightgreen.svg?style=flat-square)
[![Donate](https://img.shields.io/badge/donate-paypal-003087.svg?style=flat-square)](https://www.paypal.me/sufialhussaini/10)

> A ghost theme for programmers.



### Description

Quark is a ghost theme for programmers based on ghost's official [Casper theme (v1.3.6)](https://github.com/TryGhost/Casper). 
It is heavily inspired by Andrea Tarquini's [Odin theme (v1.3.0)](https://github.com/h4t0n/odin).
Quark incorporates a few (customizable) appearance tweaks while retaining the minimalistic nature of Casper.



### Demo

[My personal website](http://shoaib-ahmed.com) uses the Quark theme.



### Customizations

Use code injection (specifically the blog footer section) to customize theme appearance.


##### Social networking links

```javascript
var social_link = {
    'linkedin-square': 'https://om.linkedin.com/in/sufialhussaini',
    'github-square': 'https://github.com/Sufi-Al-Hussaini',
    'facebook-square': 'https://www.facebook.com/sufialhussaini',
    'envelope-square': 'mailto:sufialhussaini@gmail.com',
    'rss':'https://shoaib-ahmed.com/rss/'
};
```


##### Blog description (typed.js) animation

Refer to [typed.js](https://github.com/mattboldt/typed.js) documentation.

```javascript
var typed_config = {
    strings: ["Software developer", "Tech freak"],
    typeSpeed: 50,
    startDelay: 500,
    backDelay: 500,
    loop: true
};
```


##### Background (particle.js) animation

Create your own configuration [here](http://vincentgarreau.com/particles.js/).

```javascript
var particles_config = {
    /* Paste your config here. Default config is in <assets>/js/particles.js */
};
```



### TODO

* Add disqus comments
* Add code syntax highlighting
* Add google analytics
