---
aggregation:
    sisyphus: wike
    flatpak: 
        id: com.github.hugolabe.Wike
        build: offical
    snap: 
        id: wike
        build: unoffical
appstream:
    id: alacarte.desktop
    name: Wike
    icon: /wike/wike-logo.svg
    summary: Программа для чтения Википедии для рабочего окружения GNOME. 
    keywords: 
        - adaptive
        - circle
        - dontthemes
    developer: 
        name: GNOME
        avatar: https://gitlab.gnome.org/uploads/-/system/group/avatar/8/gnomelogo.png?width=48
    metadata_license: 
        name: GNU GPLv3
        link: https://choosealicense.com/licenses/gpl-3.0/
    url: 
        homepage: https://apps.gnome.org/Wike/
        bugtracker: https://github.com/hugolabe/Wike/issues
--- 

# Wike

Wike - программа для чтения Википедии для рабочего окружения GNOME. Предоставляет доступ ко всему содержимому этой онлайн-энциклопедии в собственном приложении с более простым и не отвлекающим от просмотра статей интерфейса.

<!--@include: @apps/_parts/install/content-repo.md-->
<!--@include: @apps/_parts/install/content-flatpak.md-->
<!--@include: @apps/_parts/install/content-snap.md-->

## Язык поиска статей Википедии

По умолчанию Wike ищет на английском языке, для переключения языка необходимо:

- В боковом баре нажмите кнопку «Поиск»
- В баре поиска нажмите на интерфейс выбора языков, добавьте русских язык и выберите его по умолчанию

![Выбор языка](/wike/wike-1.png)