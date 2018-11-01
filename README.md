# Redmine WBS

[![Latest Release](https://img.shields.io/github/release/eXolnet/redmine-wbs.svg?style=flat-square)](https://github.com/eXolnet/redmine-wbs/releases)
[![Software License](https://img.shields.io/badge/license-MIT-8469ad.svg?style=flat-square)](LICENSE)
[![Build Status](https://img.shields.io/travis/eXolnet/redmine-wbs/master.svg?style=flat-square)](https://travis-ci.org/eXolnet/redmine-wbs)
[![Maintainability](https://api.codeclimate.com/v1/badges/1bb2d6f3a1f380dddd21/maintainability)](https://codeclimate.com/github/eXolnet/redmine-wbs/maintainability)

Display a WBS view of a project’s issues.

## Compatibility

This plugin version is compatible only with Redmine 3.4 and later.

## Installation

1. Download the .ZIP archive, extract files and copy the plugin directory to `#{REDMINE_ROOT}/plugins/redmine_wbs`.

2. Restart Redmine.

3. Login and enable the "WBS" module on projects you want to use it.

### Uninstall

1. Remove the plugin's folder from `#{REDMINE_ROOT}/plugins`.

2. Restart Redmine.

## Usage

Explain how to use your package.

## Testing

Run tests using the following command:

```bash
bundle exec rake redmine:plugins:test NAME=redmine_wbs RAILS_ENV=development
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) and [CODE OF CONDUCT](CODE_OF_CONDUCT.md) for details.

## Security

If you discover any security related issues, please email security@exolnet.com instead of using the issue tracker.

## Credits

- [Alexandre D'Eschambeault](https://github.com/xel1045)
- [All Contributors](../../contributors)

## License

This code is licensed under the [MIT license](http://choosealicense.com/licenses/mit/).
Please see the [license file](LICENSE) for more information.