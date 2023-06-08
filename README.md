# typescript-cli-template
Typescript CLI template

## Development

### Build & Run

```sh
npm i
npm run build
node .
```

### Add Commands

Add commands to `src/commands/`. The CLI automatically picks up any non-test .ts
file that default-exports a `yargs.CommandModule`. See existing commands for
example.
