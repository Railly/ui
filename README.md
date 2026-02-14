# Railly UI

personal registry

## Usage

Add components from this registry using the shadcn CLI:

```bash
npx shadcn@latest add "https://Railly.github.io/ui/r/{component-name}.json"
```

Or configure as a namespace in your `components.json`:

```json
{
  "registries": {
    "railly-ui": {
      "url": "https://Railly.github.io/ui/r"
    }
  }
}
```

Then install components by name:

```bash
npx shadcn@latest add railly-ui/{component-name}
```

## Development

Build the registry locally:

```bash
npx shadcn@latest registry:build
```

Built files will be output to `public/r/`.

## Deployment

This registry auto-deploys to GitHub Pages on every push to `main`.

Registry URL: https://Railly.github.io/ui

---

Built with [Elements Studio](https://tryelements.dev/studio)
