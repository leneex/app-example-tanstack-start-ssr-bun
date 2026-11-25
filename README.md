# TanStack Start SSR on Bun

Example [TanStack Start](https://tanstack.com/start) app with server-side rendering (SSR) running on [Bun](https://bun.sh/). TanStack Start is a full-stack React framework built on TanStack Router. Bun is a fast all-in-one JavaScript runtime and package manager compatible with Node.js.

## Deploy settings

| Field | Value |
| --- | --- |
| Build | Railpack |
| Project directory | `/` |
| Install command | leave empty |
| Build command | leave empty |
| Start command | leave empty |
| Application port | `3000` |
| Health check path | `/` |

## <a name="dev"></a>Run locally

```bash
# install dependencies
bun install

# run in development mode
bun run dev

# build for production
bun run build

# run the built server app
bun run start
```
