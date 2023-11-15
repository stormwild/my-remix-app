# Errors

[TypeError: Cannot destructure property ‘…’ of ‘useLoaderData(…)’ as it is null. – Pinter Computing](https://pinter.org/archives/14369)

```ts
const { incidents } = useLoaderData<typeof loader>() || {} ;
```
