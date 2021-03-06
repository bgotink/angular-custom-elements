# Polymer in Angular 1.x tests

This repository contains a small angular directive to bind values on Angular's scope
to Polymer elements.
This script is based on the idea of [@jshcrowthe](https://github.com/jshcrowthe/polymer-angular-demo), though the actual binding of variables is completely different.

## What can it do?

The bind-polymer directive binds variables from Angular to Polymer
It supports not only "simple" variables like String or Number, but also Objects, even if those objects have functions that access variables in another JS scope.

## Pages

- `pages/object.html`: tests variable binding to an object
- `pages/functions.html`: tests variable binding to function calls
- `pages/scoped.html`: tests variable binding to object with getters
- `pages/dom-if.html`: tests behavior of angular code inside of a `dom-if` template inside a Polymer element's light DOM (only works with ShadowDOM, use `?dom=shadow`)
- &hellip; more to come?

## License

Files in this repository fall under the MIT license, unless the file itself states otherwise.

The MIT License (MIT)

Copyright (c) 2015-2016 Bram Gotink <github.com/bgotink>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
