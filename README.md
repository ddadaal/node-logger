# @ddadaal/node-logger

A console logger for Node.js.

```
npm install --save @ddadaal/node-logger
```

# Features

- **Log level** with 6 built-in levels (trace, debug, info, warn, error, fatal) 
- Support **PRETTY** and **JSON** log format
  - PRETTY example: `2021-10-27T08:45:30.741Z INFO [orm] string`
  - JSON example: `{"time":"2021-10-27T08:46:04.887Z","level":"INFO","scopes":["orm"],"content":"string"}`
- Support log **scopes** (extra information shown in log info)
- Support child logger with extra scopes
- Auto set log level and log format with `LOG_LEVEL` and `LOG_FORMAT` env
  
| env          | values (case insensitive)               | default |
| ------------ | --------------------------------------- | ------- |
| `LOG_LEVEL`  | trace, debug, info, warn, error, fatal. | info    |
| `LOG_FORMAT` | json, pretty                            | pretty  |

# License 

MIT