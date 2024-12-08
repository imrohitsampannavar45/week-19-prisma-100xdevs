<h1>Steps to initialise the TypeScript Project </h1>


```sh
npm intsall -y
```

```sh
npm install typescript
```


```sh
npx tsc --init
```

```sh
Change the rootdir to ./src
Change the Outdir to  ./dist
```

```sh
Add a src/index.ts and put a simple console.log("hello world");
Program
```

```sh 
Add the dev script  "dev": "tsc -b && node dist/index.js"
```

```sh
npm run dev 
```



```sh 
run the prisma model after changes 
npx prisma migrate dev
```
````sh
npx prima generate 
```