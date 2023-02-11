# Nebula Squad Snippets

The Nebula extension provides a set of code snippets to help write high-quality solutions with less effort.

## Snippets:

### TanStack Query

| Snippet | Description                  |
| ------- | ---------------------------- |
| `ffn`   | Fetch function               |
| `mkq`   | Make Query identity function |
| `qkf`   | Query Key Factory            |
| `uqy`   | useQuery hook                |

These snippets generate function & object names from the file name they are called in. For example, if you are working in a file named `useGetProducts.ts`, the `uqy` snippet will generate a custom useQuery hook named `useGetProducts`, while the `qkf` snippet will generate a query key factory object named `productsKeys`.

All snippets are designed to work together to minimise the amount of code you need to write to create custom query hooks from scatch.
