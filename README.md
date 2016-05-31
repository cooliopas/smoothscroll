# Smooth Scroll behavior polyfill

As an extension of the `Window` interface, `Scroll Behavior` specification has been introduced to allow the developer wants to scroll to certain part of a site progressively. By this date the standard has only being implemented in _Firefox_.

Go to the demo site to see it in action https://iamdustan.github.io/smoothscroll


## Install

Download the distribution file from this repository and include it in your project.

You can also find it in **npm** as **smoothscroll-polyfill** or **bower** as **smoothscroll**.

```js
require('smoothscroll-polyfill').polyfill();
```

_Requires requestAnimationFrame polyfill for browsers which don't support it!_


## Contribute

Fork the repository and run **npm install**.

After any modification make sure it doesn't break in any of the supported browsers, check linting and build running **npm run build** and then open a pull request.


## Browser Support

Successfully tested in:

- Safari 6+
- iOS Safari 6+
- Chrome (last version)
- _natively supported in Firefox_
- Internet Explorer 9+
- Microsoft Edge
- Opera Next

If you have tested this and worked as expected in a different browser let us know so we can add it to the list, if not [open an issue](https://github.com/iamdustan/smoothscroll/issues) providing browser, browser version and a good description about it.

## Standards documentation

- http://dev.w3.org/csswg/cssom-view
- http://lists.w3.org/Archives/Public/www-style/2013Mar/0314.html
