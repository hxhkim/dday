# dday
- Showing how many days are remaining till project d-day.
- Useful tool to set up in your shell.
- view at: https://pypi.org/project/dday/

## INATALL
```bash
pip install dday
```

## USE
```bash
$ dday
프로젝트 마감일까지 41일 남았습니다.
```

## DEV
```bash
$ git clone ...
$ cd dday
$ pdm venv create
$ source .venv/bin/activate
(dday-3.8) $ pdm install
```

## TEST
```bash
$ pdm add -dG test pytest pytest-cov
$ source .venv/bin/activate
(dday-3.8) $ pdm install
$ pytest
$ pytest -s
$ pytest --cov
```

# DEPLOY
```bash
$ pdm publish
```