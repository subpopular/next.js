# Example app with asset imports

## How to use

Download the example [or clone the repo](https://github.com/zeit/next.js):

```bash
curl https://codeload.github.com/zeit/next.js/tar.gz/master | tar -xz --strip=2 next.js-master/examples/with-asset-imports
cd with-asset-imports
```

Install it and run:

```bash
npm install
npm run dev
```

Deploy it to the cloud with [now](https://zeit.co/now) ([download](https://zeit.co/download))

```bash
now
```

## The idea behind the example

This example shows how to enable the impors of assets (images, videos, etc.) and get a URL pointing to `/static`.

This is also configurable to point to a CDN changing the `baseUri` to the CDN domain, something similar to this:

```json
[
  "transform-assets-import-to-string",
  {
    "baseDir": "/static",
    "baseUri": "https://cdn.domain.com"
  }
]
```
