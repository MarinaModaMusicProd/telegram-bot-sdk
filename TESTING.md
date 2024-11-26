# Testing the Telegram Bot SDK

### Running Tests
To run tests:
```bash
npm test
```

### Writing New Tests
1. Add test cases in the `tests/` directory.
2. Use [Mocha](https://mochajs.org/) and [Chai](https://www.chaijs.com/) for testing.

Example Test:
```javascript
const { expect } = require('chai');

describe('Command: /start', () => {
  it('should respond with a welcome message', () => {
    // Test logic here
    expect(response.text).to.equal('Welcome to the bot!');
  });
});
```