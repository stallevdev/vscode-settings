# Установка настроек VS Code

Этот репозиторий содержит пользовательские настройки для Visual Studio Code. Следуйте инструкции ниже, чтобы применить их у себя.

## 🖥️ Установить Visual Studio Code

Если VS Code ещё не установлен, скачайте и установите его с официального сайта: [Visual Studio Code](https://code.visualstudio.com/)

## 📁 Структура проекта

```
vscode-settings
├──.vscode/
│  └──settings.txt
```

## 🛠️ Инструкция по установке

1. Убедитесь, что VS Code установлен.
2. Перейдите в папку `.vscode`, где находится файл `settings.txt`.
3. Скопируйте файл и переименуйте его в `settings.json`:

```
copy .vscode\settings.txt settings.json
```

4. Переместите файл `settings.json` в папку настроек пользователя Visual Studio Code:

```
C:\Users\<ИМЯ_ПОЛЬЗОВАТЕЛЯ>\AppData\Roaming\Code\User\
```

Пример для пользователя <ИМЯ_ПОЛЬЗОВАТЕЛЯ>:

```
move settings.json "C:\Users\<ИМЯ_ПОЛЬЗОВАТЕЛЯ>\AppData\Roaming\Code\User\"
```

5. Перезапустите Visual Studio Code, чтобы изменения вступили в силу.

## 🧩 Установить расширения

Рекомендуется установить следующие расширения:

- Russian Language Pack for Visual Studio Code
- GitHub Theme
- Material Icon Theme
- Fluent Icons
- Live Server
- Prettier - Code formatter
- Auto Rename Tag
- indent-rainbow
- ESLint
- Python
- Pylint
- Flake8
- Mypy Type Checker
- autopep8
- Black Formatter
- Django
- SQLite Viewer
- GitHub Actions
- Docker
- Dev Containers

Откройте VS Code, перейдите в меню расширений и найдите их по названию.
