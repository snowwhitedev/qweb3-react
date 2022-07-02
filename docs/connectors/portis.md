# `web3-react` Documentation - Portis

- [Install](#install)
- [Arguments](#arguments)
- [Example](#example)

## Install
`yarn add @qweb3/portis-connector`

## Arguments
```typescript
dAppId: string
networks: (number | { chainId: string; [key: string]: any })[]
config?: any
```

## Example
```javascript
import { PortisConnector } from '@qweb3/portis-connector'

const portis = new PortisConnector({ dAppId: '...', networks: [1, 100] })
```

Note: Once the connector has been activated, the Portis SDK instance can be accessed under the `.portis` property.
