# libmoji-standalone
Standalone version of the Libmoji repo [https://github.com/matthewnau/libmoji](https://github.com/matthewnau/libmoji)

# Installation
- Move libmoji.js to project root
- Link the libmoji file
```html
# Regular js file
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/cableguyp/libmoji-standalone/libmoji.js" />

# Minified Version
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/cableguyp/libmoji-standalone/libmoji.min.js" />
```
- Initialize the package
```javascript
const libmoji = new libmojiApi();
```
- enjoy!

# Usage
This package behaves the same as [https://github.com/matthewnau/libmoji](https://github.com/matthewnau/libmoji)
```javascript
console.log(libmoji.randOutfit(libmoji.getOutfits(libmoji.randBrand(libmoji.getBrands("male")))));
/* console would print a random male outfit */
```

# Docs
If you're interested in how a Bitmoji image URL is assembled, or need assistance with using Libmoji please visit the [wiki](https://github.com/matthewnau/libmoji/wiki). 

This package behaves the exact same as the npm libmoji package. All of the docs are the same and can be [found here](https://github.com/matthewnau/libmoji/wiki/Libmoji-Docs).

Also, to use the comics portion of Libmoji, you need to first identify your unique avatar ID. This can be done by following the steps in [this](https://github.com/matthewnau/libmoji/wiki/Finding-Your-ID) article. Once you have the ID, you're good to go!

# Product Disclaimer
This code is in no way affiliated with, authorized, maintained, sponsored or endorsed by Bitmoji or any of its affiliates or subsidiaries. This is an independent and unofficial product. Use at your own risk.
