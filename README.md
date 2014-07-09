# CSS WORD BREAK

  Mobile-first classes for css-word-break.
  Set the desired css-word-break on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install --save-dev css-word-break
```
or download the css on github and include in your project.

## File Size


## The Code
```
.wb-nor { word-break: normal; }
.wb-ba {  word-break: break-all; }
.wb-ka {  word-break: keep-all; }
.wb-i {   word-break: inherit; }

@include break(not-small) {
  .wb-nor-ns { word-break: normal; }
  .wb-ba-ns {  word-break: break-all; }
  .wb-ka-ns {  word-break: keep-all; }
  .wb-i-ns {   word-break: inherit; }
}

@include break(medium) {
  .wb-nor-m { word-break: normal; }
  .wb-ba-m {  word-break: break-all; }
  .wb-ka-m {  word-break: keep-all; }
  .wb-i-m {   word-break: inherit; }
}

@include break(large) {
  .wb-nor-l { word-break: normal; }
  .wb-ba-l {  word-break: break-all; }
  .wb-ka-l {  word-break: keep-all; }
  .wb-i-l {   word-break: inherit; }
}

```

## Author

[http://mrmrs.cc](http://mrmrs.cc - Entire internet gateway to all things mrmrs)
[http://mrmrs.io](http://mrmrs.io - Open source projects)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

