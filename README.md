# UIMix

> Macaron is rebranding to UIMix and is under active development. The old version is still available at the links below.
>
> - [Old Branch](https://github.com/uimix-editor/uimix/tree/old)
> - [Old Website](https://macaron-elements.com/)

UIMix is a WYSIWYG editor for React components that offers a Figma or Framer-like experience for creating and maintaining React components.

It aims to bridge the gap between modern design tools / no-code web builders and modern front-end development, by combining their strengths.

- [Demo](https://uimix-editor.vercel.app/)
- [Figma File](https://www.figma.com/file/Ec45PJS7toeZIZWXKBYthG/UIMix-editor?node-id=0%3A1&t=5n9xAh34Qj7xe1Pc-1)

🚧 Very work-in-progress, do not use in production!

## Roadmap

- [x] Freehand editing equivalent to Figma / Framer
- [x] Launch the locally-running editor from CLI
- [ ] Emit React components with types that can be easily overridden
- [x] Import React components directly into the editor

## Potential plans

- [ ] Sync with Figma files
- [ ] Collaborative editing
- [ ] Support other frameworks and Web Components
- [ ] Publish as a cloud service, enabling non-developers to utilize the platform
- [ ] Managed website hosting that offers a complete no-code starting point for new projects, with the ability to gradually integrate code as needed
- [ ] Publish as a WYSIWYG editor library

## Build Figma plugin and VSCode extension

```
git clone --recursive git@github.com:uimix-editor/uimix.git
cd uimix
pnpm install
pnpm build
pnpm package
```

- Figma plugin: `packages/figma/uimix-figma-plugin.zip`
- VSCode extension: `packages/vscode/uimix-vscode-{version}.vsix`
