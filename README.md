# ucdn

Tool for uploading assets to AWS S3.

## Installation

```sh
$ yarn global add @umbrellio/ucdn
```

or

```sh
$ npm i -g @umbrellio/ucdn
```

## Usage

### Upload

```sh
$ ucdn upload -c /path/to/config/file.yaml -C production
```

## Options

All following options except `config` and `config-key` can be configured using the config file.

```
--config, -c                            path to config file
--config-key, -C                        root config key
--dir, -d                               assets directory
--bucket, -b                            AWS bucket for upload
--exclude, -e                           excluded extenstions
--accessKeyId, --access-key-id          AWS access key ID
--secretAccessKey, --secret-access-key  AWS secret access key
```

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/umbrellio/ucdn.

## License

Released under MIT License.

## Authors

Created by [Aleksei Bespalov](https://github.com/nulldef).

<a href="https://github.com/umbrellio/">
<img style="float: left;" src="https://umbrellio.github.io/Umbrellio/supported_by_umbrellio.svg" alt="Supported by Umbrellio" width="439" height="72">
</a>