# Shared Renovate Config

Shared presets for [Renovate](https://github.com/singapore/renovate) tool.

## Usage

Add `renovate` property into `package.json`:

```json
{
  "renovate": {
    "extends": ["@shareable-configs"]
  }
}
```

or add this into `renovate.json`:

```json
{
  "extends": [
    "@shareable-configs"
  ]
}
```

## Useful Links

- [Configuration Options](https://renovatebot.com/docs/configuration-options)
- [Renovatebot Presets](https://github.com/renovatebot/presets/tree/master/packages)

## License

MIT - TechnoWong [(GitHub)](http://github.com/TechnoWong)
