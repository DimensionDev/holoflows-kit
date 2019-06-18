<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@holoflows/kit](./kit.md) &gt; [LiveSelector](./kit.liveselector.md) &gt; [filter](./kit.liveselector.filter.md)

## LiveSelector.filter() method

Select the elements of a LiveSelector that meet the condition specified in a callback function.

<b>Signature:</b>

```typescript
filter(f: (value: T, index: number, array: T[]) => any): LiveSelector<NonNullable<T>>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  f | <code>(value: T, index: number, array: T[]) =&gt; any</code> | The filter method |

<b>Returns:</b>

`LiveSelector<NonNullable<T>>`

## Example


```ts
ls.filter(x => x.innerText.match('hello'))

```
