# JWT Authentication Tutorial

[YouTube Video](https://www.youtube.com/watch?v=mbsmsi7l3r4&t=519s)

```
> npm run devStart
> npm run devStarAuth
```

## Generate random secret

```
$ node
> require('crypto').randomBytes(64).toString('hex')
```

## REST Client

REST Client is a VSCode plugin for sending REST request for test/development, see file - "request.reset"