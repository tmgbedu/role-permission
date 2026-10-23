# Changelog

## 3.2.0

### Added
- Support for Laravel 12 and 13.
- Verified on PHP 8.4 and 8.5.

### Internal
- Test suite migrated to PHPUnit attributes; runs on PHPUnit 10.5, 11 and 12 (Testbench 8–11).
- CI matrix covers PHP 8.1–8.5 against Laravel 10–13, with lowest and stable dependencies
  (replaces the per-version L7/L8/L9 workflows).
- Psalm upgraded to `^5.26|^6.0`, runs on PHP 8.3, with a baseline for existing findings.

No breaking changes. Existing constraints for older Laravel versions are kept as-is.

## 3.1.3

- Laravel 11 support.
