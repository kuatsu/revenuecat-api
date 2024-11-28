# 🐈 revenuecat-api

A RevenueCat REST API v1 client for JavaScript.

![npm bundle size](https://img.shields.io/bundlephobia/min/revenuecat-api?style=flat-square) ![GitHub](https://img.shields.io/github/license/kuatsu/revenuecat-api?style=flat-square) ![GitHub last commit](https://img.shields.io/github/last-commit/kuatsu/revenuecat-api?style=flat-square)

> [!WARNING]
> This project is still considered unstable and under active development. The API might change drastically in new versions. Please proceed with caution.

- ⚡ Intuitive API
- 📦 Low bundle size
- 🔋 TypeScript support out of the box

## Installation

```sh
npm install revenuecat-api
```

## Quick Start

```tsx
import RevenueCat from 'revenuecat-api';

const revenuecatClient = new RevenueCat({
  secretKey: process.env.REVENUECAT_SECRET_KEY,
  iosKey: process.env.REVENUECAT_IOS_KEY,
  androidKey: process.env.REVENUECAT_ANDROID_KEY,
});

revenuecatClient.getCustomer('$RCAnonymousID:...').then((res) => {
  console.log(res.data);
});
```

## Documentation

A documentation is work in progress.

## Contributing

See the [contributing guide](CONTRIBUTING.md) to learn how to contribute to the repository and the development workflow.

## License

MIT