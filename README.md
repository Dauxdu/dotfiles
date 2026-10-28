# dotfiles

## Новое устройство

```sh
chezmoi init --apply Dauxdu
```

## Повседневное

```sh
chezmoi update       # git pull + применить
chezmoi diff         # что изменится в системе
```

## Пакеты

Список в [`.chezmoidata/packages.yaml`](.chezmoidata/packages.yaml): `repo` ставится через pacman, `aur` через yay.
`chezmoi apply` запускает установку заново при каждом изменении списка. Скрипт только ставит пакеты, ничего не удаляет.

## OBS Studio

| Профиль      | Видео                           | Звук             | Replay buffer |
| ------------ | ------------------------------- | ---------------- | ------------- |
| `REC_GAME`   | 60 fps, HEVC CQP 20, keyint 1 с | PCM, дорожки 1–4 | 120 с, ≤ 2 ГБ |
| `REC_SCREEN` | 30 fps, HEVC CQP 22, keyint 2 с | PCM, дорожки 1–2 | выкл.         |
