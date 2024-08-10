@wymjs/support-webp
===

> 檢測是否支持 webp

## 安裝

```shell
$ pnpm i @wymjs/support-webp
```

## 使用

```typescript
import { supportWebp } from '@wymjs/support-webp'

;(async () => {
  // return boolean, true 表示支持，反之不支持
  const isSupportWebp = await supportWebp()
})()
```
