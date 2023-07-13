## Reproduction steps

1. Run `npm i`
2. Run `npm run build` and observe warnings for `UNRESOLVED_IMPORT`
3. Run `npm i ionic-core-7.1.1-fix.tgz`
4. Run `npm run build` and observe no more warnings

### Included tarballs

- `ionic-core-7.1.1.tgz`: Build of Ionic Framework using Stencil 4.0.1
- `ionic-core-7.1.1-fix.tgz`: Build of Ionic Framework using a local build of Stencil at [247b948](https://github.com/ionic-team/stencil/pull/4552/commits/247b94853cc25efd7c5ebfa82db4d7133eddc638)
