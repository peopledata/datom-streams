# datom-streams
External implementation of a WriteStream and ReadStream for datom
```bash
npm install datom-streams
```
## Usage
```js
const { WriteStream, ReadStream } = require('datom-streams')

const ws = new WriteStream(feed)
const rs = new ReadStream(feed, {
  start: 0,
  live: true,
  valueEncoding: 'json'
})
```

## License
MIT