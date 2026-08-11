# Niri Dotfiles

Моя личная конфигурация для Niri + Noctalia Shell + Kitty.

## Зависимости
Для корректной работы всех конфигов необходимо установить следующие пакеты:

- **Окружение:** `niri`
- **Оболочка:** `noctalia`
- **Терминал:** `kitty`
- **Блокировщик экрана:** `swaylock`
- **Файловый менеджер:** `nemo`
- **Курсор:** `qogir-manjaro-white-cursors`

## Установка

1. Склонируй репозиторий:

     git clone [https://github.com/skamzyy-01/niri-dotfiles.git](https://github.com/skamzyy-01/niri-dotfiles.git) ~/niri-dotfiles

2. Скопируй файлы конфигурации:
     mkdir -p ~/.config/niri ~/.config/noctalia ~/.config/kitty
     cp ~/niri-dotfiles/niri/config.kdl ~/.config/niri/config.kdl
     cp -r ~/niri-dotfiles/noctalia/* ~/.config/noctalia/
     cp ~/niri-dotfiles/kitty/kitty.conf ~/.config/kitty/kitty.conf

3. Чтобы все сохранилось:
     
     1. В 'nano' нажми **"Ctrl + O"**, потом **"Enter"** (сохранить) 
     2. Теперь **"Ctrl + X"** (выйти)
