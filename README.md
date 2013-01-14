binstream.js
============

Examples:
```javascript
var stream = new Streams.WriteStream();
var stream.utf8('Hello, World!');
stream.bytes(); // [72, 101, 108, 108, 111, 44, 32, 87, 111, 114, 108, 100, 33]
```

```javascript
var data = [64, 9, 33, 251, 84, 68, 45, 24];
var stream = new Streams.ReadStream(data);
stream.float64(); // 3.141592653589793
```
