# Volar + Emacs LSP Troubleshooting

## Steps to reproduce

- Clone this repository
- Run `yarn` to install dependencies
- Open `src/components/HelloOtherWorld.vue` in Emacs and make sure LSP is connected to Volar server(s).
- Attempt an import statement

## Expected behavior:
Import statement is auto-completed as normal

## Observed behavior:
Imported variable is duplicated
