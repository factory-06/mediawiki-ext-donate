# Информация

[![Support](https://cdn-storage.github.io/images/badges/info.support.svg)](https://webmasters.community/)
[![Documentation](https://cdn-storage.github.io/images/badges/info.documentation.svg)](https://mediawiki.webmasters.wiki/)
[![Source](https://cdn-storage.github.io/images/badges/info.source.svg)](https://github.com/factory-06/mediawiki-ext-donate)
[![Changelog](https://cdn-storage.github.io/images/badges/info.changelog.svg)](CHANGELOG.md)
[![Code of Conduct](https://cdn-storage.github.io/images/badges/info.coc.svg)](https://metainfo.github.io/coc/)
[![Contributing](https://cdn-storage.github.io/images/badges/info.contributing.svg)](https://metainfo.github.io/contributing/)
[![Authors](https://cdn-storage.github.io/images/badges/info.authors.svg)](AUTHORS)
[![Issues](https://cdn-storage.github.io/images/badges/info.issues.svg)](https://github.com/factory-06/mediawiki-ext-donate/issues)
[![Packagist](https://cdn-storage.github.io/images/badges/info.packagist.svg)](https://packagist.org/packages/metastore/mediawiki-ext-donate)
[![License](https://cdn-storage.github.io/images/badges/license.gpl-3.0.svg)](LICENSE)
[![Liberapay](https://cdn-storage.github.io/images/badges/donate.liberapay.svg)](https://liberapay.com/metadata/donate)
[![Patreon](https://cdn-storage.github.io/images/badges/donate.patreon.svg)](https://patreon.com/metadata)
[![By METADATA](https://cdn-storage.github.io/images/badges/by.metadata.svg)](https://metadata.foundation/)

Система пожертвований на:

- Yandex.Money;
- банковскую карту;
- счёт PayPal;
- кошелёк Bitcoin;
- кошелёк Ethereum;
- кошелёк Monero.

## Синтаксис

```
{{#donate: ya-wallet =
|card =
|paypal =
|bitcoin =
|monero =
|ethereum =
}}
```

## Установка

1. Загрузите папки и файлы в директорию `extensions/MW_EXT_Donate`.
2. В самый низ файла `LocalSettings.php` добавьте строку:

```
wfLoadExtension( 'MW_EXT_Donate' );
```
