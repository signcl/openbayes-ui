# OpenBayes UI

OpenBayes UI Library

## Development

If you need to update one of the libraries and see live result in corrsesponding project. For example, if you want to update the `@openbayes/docsearch-css` library and see the changes in `signcl/openbayes-docs` project. You can:

Link locally (recommended):

```bash
$ cd packages/docsearch-css
$ pnpm i
$ cd ~/projects/openbayes-docs
$ pnpm link ~/projects/openbayes-ui/packages/docsearch-css
```

Or link globally:

```bash
$ cd packages/docsearch-css
$ pnpm i
$ pnpm link --global
$ cd ~/projects/openbayes-docs
$ pnpm link --global @openbayes/docsearch-css
```

## License

MPL-2.0
