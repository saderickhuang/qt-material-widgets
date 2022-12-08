# Qt Material Design Desktop Widgets [![Language](https://img.shields.io/badge/language-c++-brightgreen.svg)]() [![Join the chat at https://gitter.im/qt-material-widgets/Lobby](https://badges.gitter.im/qt-material-widgets/Lobby.svg)](https://gitter.im/qt-material-widgets/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

This is a Qt6 version fork from [original repo](https://github.com/laserpants/qt-material-widgets).

Works on Qt 6.4.1

basically nothing changed except:
1. qstatemachine related classes moved from qt core to qtStateMachine.
2. some stuff were obsolete like QPalette::Foreground(use QPalette::WindowText now)  and layout->setmargin now use layout->setContentMargins
