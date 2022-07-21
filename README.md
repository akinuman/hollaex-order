# Order Book

An Order Book app built with React/Typescript and powered by WebSockets.

## Tech stack

- React / Typescript
- SASS / styled-components
- WebSockets / react-use-websocket

## Application features:

### III. Toggle Feed Button

1. Toggles the selected market between PI_XBTUSD and PI_ETHUSD.
2. Supports dynamic grouping logic - handles groupings for XBT (0.5, 1, 2.5) and groupings for ETH (0.05, 0.1, 0.25).

### IV. Kill Feed Button

1. Clicking this button stops the feed.
2. Clicking this button second time renews the feed.

### Demo

:star: [orderbook-mihailgaberov.vercel.app](https://orderbook-mihailgaberov.vercel.app/) :star:

### Running the app locally

To run the app, follow these steps.

1. Ensure that [NodeJS](http://nodejs.org/) is installed.
2. Install [yarn](https://classic.yarnpkg.com/en/docs/install/#windows-stable/).
3. From the project folder, execute the following commands:

To install dependencies:

```shell
  yarn
```

To run the app:

```shell
  yarn start
```

To run the tests:

```shell
  yarn test
```
