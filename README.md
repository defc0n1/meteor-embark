# Meteor Embark

### Streamlined Ethereum Integration for Meteor

#### ️*Only compatible with Meteor 1.2 +*

```
meteor add hitchcott:embark
```

## What does it do?

1. (TODO, optional) Automatically starts the embark blockchian in the background. For now, run `embark blockchain;`
1. Check to see if any `.sol` files for each platform have changed before we try to redeploy
3. Use `embark deploy` on `.sol` files, which deploys them if they need to be (the 'embark way')
4. Adds `web3` and it's contracts to platforms as global objects

## Configuration

* Use environment variable `EMBARK_ENV` to specify environment - defaults to `development`

## TODO

```
- Automatic Blockchain Starting

- Test integration
- Configurable config file locations
- Configurable embark output (e.g. configurable `Contracts` namespace)
```

## License

MIT 2015, Chris Hitchcott
