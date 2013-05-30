# connect-fonts-kranky

Kranky fontpack for [connect-fonts](https://github.com/shane-tomlinson/connect-fonts).

## Usage

1. Include [connect-fonts](https://github.com/shane-tomlinson/connect-fonts) in a node module.
```js
const font_middleware = require("connect-fonts");
```

2. Include the font packs that you want to serve.
```js
const font_pack  = require("connect-fonts-kranky");
```

3. Add a middleware by calling the `setup` function.
```js
    app.use(font_middleware.setup({
      fonts: [ font_pack ],
      allow_origin: "https://exampledomain.com"
    }));
```

4. Add a link tag to include the font CSS.
```html
<link href="/kranky/fonts.css" type="text/css" rel="stylesheet"/ >
```


Available fonts:
* kranky

Locale-optimised font sets can be served by specifying the locale in the fonts.css URL.
```html
<link href="/latin/kranky/fonts.css" type="text/css" rel="stylesheet"/ >
```

Available subsets:
* latin
* en

5. Set your CSS up to use the new font by using the "Kranky" font-family.
```
    body {
      font-family: 'Kranky', 'sans-serif', 'serif';
    }
```

## Font Info
Kranky

* Description: Copyright (c) 2010 by Font Diner, Inc DBA Sideshow. All rights reserved.
* Copyright: Copyright (c) 2010 by Font Diner, Inc DBA Sideshow. All rights reserved.
* Trademark: Kranky is a trademark of Font Diner, Inc DBA Sideshow.
* Designer: Squid
* Designer URL: http://www.squidart.com 
* Vendor: Font Diner, Inc DBA Sideshow
* Vendor URL: http://www.fontbros.com/sideshow.php

## Development Info
* Homepage: https://github.com/shane-tomlinson/connect-fonts-kranky
* Repo: https://github.com/shane-tomlinson/connect-fonts-kranky
* Bugs: https://github.com/shane-tomlinson/connect-fonts-kranky/issues

## Author
* Shane Tomlinson
* shane@shanetomlinson.com
* stomlinson@mozilla.com
* set117@yahoo.com
* https://shanetomlinson.com
* https://github.com/shane-tomlinson
* https://github.com/stomlinson
* @shane_tomlinson


## License

Software: Licenced under version 2.0 of the MPL

  https://www.mozilla.org/MPL/

Fonts: Licensed under version 2.0 of the Apache

  http://www.apache.org/licenses/LICENSE-2.0

