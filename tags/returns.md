---
layout: "guide"
tags: tag
title: "@returns"
---

# @returns

{% include 'tag-info', kind: 'Block', tsdoc: 'returns' %}

The `@returns` tag can be used to document the return value of a function.

## Example

```ts
/**
 * @param a - the first number
 * @param b - the second number
 * @returns The sum of `a` and `b`
 */
export function sum(a: number, b: number): number;
```

## See Also

-   The [`@param`](/tags/param/) tag
