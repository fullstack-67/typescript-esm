# Typescript ESM - Test with `nanoid`

The latest version of `nanoid` is V5 and it does not support `commonjs`.

## Usage

- `pnpm install`
- `npm run dev`
- `npm run build`
- `npm run start`

## Testing

- Try using `tsconfig.cjs.json` and rebuild to see the output.

## Note

- I can run the code even though the module is `commonjs`. This is because in `tsconfig.json`, there is an option.

```json
{
  "esModuleInterop": true
}
```

- If I delete the lines with

```js
Object.defineProperty(exports, "__esModule", { value: true });
```

in `js` files, I will see ESM error.

> ReferenceError: require is not defined in ES module scope...
