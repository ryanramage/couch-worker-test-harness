# couch-worker-test-harness

This module provides shared setup/teardown for couch-worker integration
tests. It starts a local couch instance using multi-couch and clears and
test data from previous runs. It relies on using the same directory
structure for each repository under test for now.

## Usage:

```js
var test = require('couch-worker-test-harness');

// you may now use 'test' as if you had done require('tape');
```
