# НВО Математика 7 — официално изтегляне

Това хранилище съдържа публичните файлове за изтегляне на приложението **НВО Математика 7**.

## Последна официална версия

**Версия:** v0.4.0  
**Платформа:** Windows x64  
**Статус:** официална стабилна версия

### Изтегляне

[⬇️ Изтегли НВО Математика 7 за Windows](https://github.com/zhol/nvo-matematika-7-downloads/releases/latest/download/NVO-Matematika-7-Windows-x64-v0.4.0-unsigned.zip)

[🔐 Изтегли SHA-256 файла](https://github.com/zhol/nvo-matematika-7-downloads/releases/latest/download/NVO-Matematika-7-Windows-x64-v0.4.0-unsigned.zip.sha256)

[📦 Отвори страницата на последната версия](https://github.com/zhol/nvo-matematika-7-downloads/releases/latest)

## Инсталиране

1. Изтеглете Windows ZIP файла.
2. Натиснете с десния бутон върху него.
3. Изберете **Extract All / Извлечи всички**.
4. Отворете разархивираната папка.
5. Стартирайте:

   `PROVERI-NVO-PAKETA.bat`

6. Изчакайте успешната SHA-256 проверка.
7. Изберете локална папка за инсталиране.
8. Следвайте указанията на екрана.

Не стартирайте приложението директно от вътрешността на ZIP файла.

## Проверка на изтегления файл

Към Windows пакета е публикуван отделен SHA-256 файл:

`NVO-Matematika-7-Windows-x64-v0.4.0-unsigned.zip.sha256`

За ръчна проверка отворете PowerShell в папката с изтегления ZIP файл и изпълнете:

```powershell
Get-FileHash -LiteralPath '.\NVO-Matematika-7-Windows-x64-v0.4.0-unsigned.zip' -Algorithm SHA256
