Famous Examples
===============

This repo contains a bunch of examples for the famous modules. 

To use clone this repo with the recursive option

    git clone git@github.com:Famous/examples.git --recursive

Once you've successfully cloned this repo, just serve the root folder of this repo as a static site with a tool like serve, apache or nginx. We recommend using serve since it is pretty simple to get started with:

    # install serve
    npm install -g serve
    
    # go to your clone and type:
    serve

Once you've done that, you can open up the current example in your browser. The default example is `src/examples/views/Scrollview/example.js`. If you want to change the current example, just edit the `src/main.js` file to point at a different example.


## License

All the code in the `src/examples` folder is licensed under the [MIT license][mit-license]. This is basically a better MIT license since it removes the ambiguous language from the original MIT.

The famous framework source code found in `/src/famous` is a git submodule cloned from the [famous/famous][famous-repo] git repo, and is licensed only under the MPL-2.0 license. More information about the licensing of that code can be found in the original repo.


### MIT License (everything in `src/examples`)

Copyright (c) 2014 Famous Industries, Inc.
 
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


### MPL-2.0 (everything in `src/famous`)

Copyright (c) 2014 Famous Industries, Inc.

This Source Code Form is subject to the terms of the Mozilla Public License, v. 2.0. If a copy of the MPL was not distributed with this file, You can obtain one at http://mozilla.org/MPL/2.0/.


[famous-repo]: https://github.com/famous/famous
[mit-license]: https://spdx.org/licenses/MIT#licenseText