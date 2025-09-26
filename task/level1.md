# Level 1: Basic rendering of columns with type safety

At a minimum the table should be type safe and use generics and type inference for the dataset provided. Ideally the interface will look something like this:

```tsx
<SavvyGrid
  dataset={myData} // Record<string, any>[]
  columns={[{}]} // SavvyColumn[]
/>
```
