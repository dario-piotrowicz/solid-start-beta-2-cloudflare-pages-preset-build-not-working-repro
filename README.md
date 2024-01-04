# solid-start beta-2 cloudflare-pages preset build not working repro

To reproduce the issue:
```
npm i
npm run build
npx wrangler pages deploy dist/
```

The above should produce the following error:
![error](./error.png)
