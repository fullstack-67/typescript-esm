# Typescript ESM

## Usage

- `pnpm install`
- `npm run dev`
- `npm run build`
- `npm run start`

# Testing

- Try using `tsconfig.cjs.json` and rebuild to see the output.

## Note

- I installed these pacakges:
  - `npm init -y`
  - `pnpm install -D typescript @types/node nodemon`
  - `pnpm install -D @tsconfig/node-lts @tsconfig/recommended` ([Option](https://github.com/tsconfig/bases))
  - `pnpm install tsx`
- I added in `package.json`:

```json
{
  "type": "module"
}
```

- I ran code by
  - `npx tsx ./src/index.ts`
  - I no longer used `ts-node` [(Ref)](https://stackoverflow.com/a/76343394).

## References

- https://gist.github.com/slavafomin/cd7a54035eff5dc1c7c2eff096b23b6b
