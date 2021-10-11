---
title: useLatest
nav:
  title: Hooks
  path: /hooks
group:
  title: Advanced
  path: /advanced
---

# useLatest

<Tag lang="en-US" tags="ssr&crossPlatform"></Tag>

A Hook that returns the latest value, effectively avoiding the closure problem.

## Examples

### Basic usage

<code src="./demo/demo1.tsx" />

## API

```typescript
const latestValueRef = useLatest<T>(value: T): MutableRefObject<T>;
```