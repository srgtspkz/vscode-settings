# Настройки Visual Studio Code

**Для Windows 11 и Ubuntu:**

1. Установите [Visual Studio Code](https://code.visualstudio.com/download).
2. Установите Git:
   - **Windows 11:** [Git для Windows](https://git-scm.com/downloads/win).
   - **Ubuntu:** выполните команду `sudo apt install git`.
3. Откройте **VS Code**.
4. Перейдите в **Управление (⚙️) → Параметры**.
5. В правом верхнем углу нажмите **Открыть параметры (JSON)**.
6. Скопируйте содержимое файла `settings.txt` и вставьте в `settings.json`.
7. Сохраните изменения (**Ctrl + S**).
8. **Для Ubuntu:**
   - Удалите из `settings.json` строку: `"terminal.integrated.defaultProfile.windows": "Git Bash"`
