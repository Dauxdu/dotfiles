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

## OBS Studio

| Профиль      | Видео                           | Звук             | Replay buffer |
| ------------ | ------------------------------- | ---------------- | ------------- |
| `REC_GAME`   | 60 fps, HEVC CQP 20, keyint 1 с | PCM, дорожки 1–4 | 120 с, ≤ 2 ГБ |
| `REC_SCREEN` | 30 fps, HEVC CQP 22, keyint 2 с | PCM, дорожки 1–2 | выкл.         |
