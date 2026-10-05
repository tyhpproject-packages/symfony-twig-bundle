<!-- tyhp-readme:start -->
# tyhpdef/symfony-twig-bundle

Tyhp type definitions for `symfony/twig-bundle` `7.4.15`.

```bash
composer require --dev tyhpdef/symfony-twig-bundle:7.4.15
```

This is a metapackage. Composer also installs `tyhpdef/symfony-twig-bundle-impl` (type files).
Require **this** name, not `tyhpdef/symfony-twig-bundle-impl`.

See https://tyhplang.com.

## Maintain `symfony/twig-bundle`? Ship the types yourself

If you are a Packagist maintainer of `symfony/twig-bundle`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/symfony-twig-bundle-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `symfony/twig-bundle` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/symfony-twig-bundle": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `symfony/twig-bundle` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `symfony/twig-bundle` with a real constraint,
   `"replace": { "tyhpdef/symfony-twig-bundle": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `symfony/twig-bundle` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/symfony-twig-bundle` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
