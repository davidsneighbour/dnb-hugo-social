<!--- CARD BEGIN --->

![DNB-Hugo/HEAD](.github/github-card-dark.png#gh-dark-mode-only)
![DNB-Hugo/HEAD](.github/github-card-light.png#gh-light-mode-only)

<!--- CARD END --->

# DNB GoHugo Component / Social

Social Media functions for Hugo

## Installing

Step 1: enable modules in your own repository (skip if already done)

```shell script
hugo mod init github.com/username/reponame
```

Step 2: add this module to your required modules in config.toml

```
[module]
[[module.imports]]
path = "github.com/dnb-org/dnb-hugo-social"
```

The next time you run hugo it will download the latest version of the module.

## Updating

To update this module:

```
hugo mod get -u github.com/dnb-org/dnb-hugo-social
```

To update all modules:

```
hugo mod get -u ./...
```

## Usage

... to be written ...
