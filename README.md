# koa-chalk-logger
Simple logging middleware for Koa, with colours!

## Usage
```js
import Koa from 'koa'
import logger from 'koa-chalk-logger'

const app = new Koa()
app.use(logger())
```

## Example
```
2017-07-06T11:24:24.683+0900 POST HTTP/1.1 401 ::ffff:127.0.0.1 /auth - 1251 ms
2017-07-06T11:24:38.447+0900 POST HTTP/1.1 200 ::ffff:127.0.0.1 /auth - 2180 ms

```

## License
```
MIT License

Copyright (c) 2017 Chalk

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
```
