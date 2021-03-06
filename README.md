#Introduction

Extremely fast implementation of the [node strftime module](https://github.com/samsonjs/strftime).

    npm install fast-strftime

#Benchmarks

Results using node 0.11.13

    $ node ./benchmark/fast.js
    2014-05-20 08:15:18 PM +0300
    2898550 op/s

    $ node ./benchmark/slow.js
    2014-05-20 08:15:22 PM +0300
    99522 op/s

-> Up to 29x faster than original

#License

MIT License:

    Copyright (c) 2014 Petka Antonov

    With parts by Sami Samhuri
    Copyright 2010 - 2014 Sami Samhuri under the terms of the MIT license found
    at http://sjs.mit-license.org/

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
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.  IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
    THE SOFTWARE.
