# node-nest

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

- [node](./application/packages/node)
- [nest](./application/packages/nest)
- [common library](./application/packages/common)

## Badges

- [![deploy](https://github.com/the-homeless-god/node-nest/actions/workflows/release.yml/badge.svg)](https://github.com/the-homeless-god/node-nest/actions/workflows/release.yml)
- [![linters](https://github.com/the-homeless-god/node-nest/actions/workflows/pull-request.yml/badge.svg)](https://github.com/the-homeless-god/node-nest/actions/workflows/pull-request.yml)

## Development

```shell
# to install full monorepo
npm i

# pm2-like commands
npm run start -- --only=nest
npm run stop -- 0
npm run drop -- all
```

### Additional info

| Url                                   | Description         |
| ------------------------------------- | ------------------- |
| `/$API_PREFIX/$VERSION/swagger-stats` | swagger performance |
