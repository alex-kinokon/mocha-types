# @types/mocha

> without globals

This is just official version of [`@types/mocha`](https://unpkg.com/browse/@types/mocha/index.d.ts) package with [`globals`](https://github.com/mochajs/mocha/issues/956) stripped away.

# Usage

```ts
import { describe, it, beforeEach, after } from "mocha";

// without explicit import typescript will show errors
describe("Some test", () => {
  it("should work", () => {});
});
```
