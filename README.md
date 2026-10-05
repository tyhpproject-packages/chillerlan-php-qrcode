<!-- tyhp-readme:start -->
# tyhpdef/chillerlan-php-qrcode

Tyhp type definitions for `chillerlan/php-qrcode` `5.0.5`.

```bash
composer require --dev tyhpdef/chillerlan-php-qrcode:5.0.5
```

This is a metapackage. Composer also installs `tyhpdef/chillerlan-php-qrcode-impl` (type files).
Require **this** name, not `tyhpdef/chillerlan-php-qrcode-impl`.

See https://tyhplang.com.

## Maintain `chillerlan/php-qrcode`? Ship the types yourself

If you are a Packagist maintainer of `chillerlan/php-qrcode`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/chillerlan-php-qrcode-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `chillerlan/php-qrcode` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/chillerlan-php-qrcode": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `chillerlan/php-qrcode` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `chillerlan/php-qrcode` with a real constraint,
   `"replace": { "tyhpdef/chillerlan-php-qrcode": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `chillerlan/php-qrcode` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/chillerlan-php-qrcode` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
