# python-sample-application

## Pipenv

### Initialization

```bash
PIPENV_IGNORE_VIRTUALENVS=1 PIPENV_VENV_IN_PROJECT=true pipenv --python 3
pipenv shell
```

### Install package for dev

```bash
pipenv install --dev autopep8 flake8
```

### Install package

```bash
pipenv install flask
```

## Docker

```dockerfile
docker build -t practical-lab/python-app:0.1 .
```

## Reference

- [Pipenvを使ったPython開発まとめ](https://qiita.com/y-tsutsu/items/54c10e0b2c6b565c887a)
- [VS CodeによるPython開発環境のテンプレ](https://qiita.com/kazetof/items/870d47d8f6b961e78acc)
- [Pythonで、Pipenvを使う](https://narito.ninja/blog/detail/58/)
- [pipenvを使用したPython開発環境の作り方](https://fereria.github.io/reincarnation_tech/10_Programming/00_PG_setup/pipenv_statup/)

