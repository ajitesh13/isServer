## js-runtime-check

A simple utility function to determine if JavaScript code is currently executing on the client or server side.

### Installation

Install via npm:

```bash
npm install js-runtime-check
```

Or via yarn:

```bash
yarn add js-runtime-check
```

### Usage

```javascript
import { isServer } from "js-runtime-check";

// Example usage
if (isServer()) {
  console.log("Code is running on the server side.");
} else {
  console.log("Code is running on the client side.");
}
```

### API

#### `isServer()`

- **Returns**: `boolean` - `true` if code is running on the server side, `false` if running on the client side.

### Example

```javascript
import { isServer } from "js-runtime-check";

if (isServer()) {
  // Code to execute on the server side
} else {
  // Code to execute on the client side
}
```

### Contributing

Contributions are welcome! Please feel free to open issues or submit pull requests on [GitHub](https://github.com/your-username/is-server-check).

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
