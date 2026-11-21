# 📺 YouTube

[![Open in Hanzo](https://hanzo.app/badges/open-in-hanzo.svg)](https://hanzo.app/dev/open?repo=github.com/zeekay/zos-youtube&ref=main&action=open) [![Edit with Hanzo](https://hanzo.app/badges/edit-with-hanzo.svg)](https://hanzo.app/dev/open?repo=github.com/zeekay/zos-youtube&ref=main&action=edit)

Video streaming platform

## Category
`media`

## Installation

```bash
npm install @anthropic/youtube
# or
pnpm add @anthropic/youtube
```

## Usage

```tsx
import App from '@anthropic/youtube';

function MyComponent() {
  return <App onClose={() => console.log('closed')} />;
}
```

## Development

```bash
# Install dependencies
pnpm install

# Build
pnpm build

# Watch mode
pnpm dev
```

## zOS Integration

This app is designed to run within zOS, a web-based operating system. It follows the zOS app specification with:

- Standalone React component
- TypeScript support
- Tailwind CSS styling
- Window management integration

## License

MIT
