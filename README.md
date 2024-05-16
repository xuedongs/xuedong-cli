# xuedong-cli

monorepo with pnpm

pnpm recursive install

## Use Cases

#### link package globally

pnpm link --global

### link foo to my-project

pnpm link --global package

### remove a link made with pnpm link --global <package>

pnpm uninstall --global package

### removes unnecessary packages

pnpm prune

pnpm -F 子包名 add 需要下载的包名
