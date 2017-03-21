# {{cookiecutter.project_name}}

{{cookiecutter.short_description}}

[![Code Climate](https://codeclimate.com/github/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}/badges/gpa.svg)](https://codeclimate.com/github/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}})
[![GitHub issues](https://img.shields.io/github/issues/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}.svg)](https://github.com/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}/issues)
[![GitHub stars](https://img.shields.io/github/stars/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}.svg)](https://github.com/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}})
[![Issue Count](https://codeclimate.com/github/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}/badges/issue_count.svg)](https://codeclimate.com/github/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}})
[![license](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)](LICENSE)
[![Test Coverage](https://codeclimate.com/github/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}/badges/coverage.svg)](https://codeclimate.com/github/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}/coverage)

## Install

### Requeriments

* [Python 2.7.x](http://python.org/download/)

### Install Requeriments

```bash
make install
```

### Slides

Es necesario instalar [landslide](https://github.com/adamzap/landslide) para poder generar los slides.

```bash
make generate
```

Open index.html

### Documentation

Es necesario instalar [Grip](https://github.com/joeyespo/grip) para poder visualizar la documentación, ejecutando lo siguiente:

```bash
grip 5000
```

ir a un navegador y colocar:

```bash
http://localhost:5000
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Credits

Made with :heart: :coffee: and :pizza: by [{{cookiecutter.company}}][link-company]

- [All Contributors][link-contributors]


[link-company]: https://github.com/{{cookiecutter.company}}
[link-contributors]: AUTHORS