# shadcn/ui monorepo template

This repo is only to lock the current version so that it can be shown as an example on how to use AI Chatbot(like Claude) to pair learning new things. You don't need to run this code, this just serve as a example to how do I learn new things. Refer to [tutorial](?) on how to use it.

This template is for creating a monorepo with shadcn/ui, created by [shadcn-ui](https://github.com/shadcn-ui) team.

## Usage

```bash
pnpm dlx shadcn@latest init
```

## Adding components

To add components to your app, run the following command at the root of your `web` app:

```bash
pnpm dlx shadcn@latest add button -c apps/web
```

This will place the ui components in the `packages/ui/src/components` directory.

## Tailwind

Your `tailwind.config.ts` and `globals.css` are already set up to use the components from the `ui` package.

## Using components

To use the components in your app, import them from the `ui` package.

```tsx
import { Button } from "@workspace/ui/components/button"
```
