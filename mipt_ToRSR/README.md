# Репозиторий с заданиями по курсу "Технология воспроизводимых научных исследований"
## by Андрей Гончар.
[![CircleCI](https://circleci.com/gh/ExplosiveJam/mipt_ToRSR.svg?style=svg)](https://circleci.com/gh/ExplosiveJam/mipt_ToRSR)
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/ExplosiveJam/mipt_ToRSR/master)

Чтобы конвертировать task_0.ipynb в .html формат, после скачивания данного репозитория нужно выполнить следующие три команды:
```
cd mipt_ToRSR
chmod +x run.sh
./run.sh
```
Чтобы конвертировать и открыть task_0.ipynb в .html формате (работает при наличии google chrome и linux):
```
cd mipt_ToRSR
chmod +x run_open.sh
./run_open.sh
```
Чтобы запустить из докера:
```
docker run -it explosivejam/mipt_rsr
cd tmp
jupyter nbconvert --execute task_0.ipynb --to html
```
