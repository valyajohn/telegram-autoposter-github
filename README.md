# Автопостинг видео из Google Drive в Telegram через GitHub Actions

Бот автоматически проверяет папку на Google Drive, скачивает новые видео, парсит название и хэштеги из имени файла и публикует их в ваш Telegram канал каждые 20 минут.

## Настройка секретов в GitHub (Settings -> Secrets and variables -> Actions):
- TELEGRAM_BOT_TOKEN
- TELEGRAM_CHANNEL_ID (обязательно указывать через @, например @my_channel)
- DRIVE_FOLDER_ID
- YT_CLIENT_ID (или GOOGLE_CLIENT_ID)
- YT_CLIENT_SECRET (или GOOGLE_CLIENT_SECRET)
- YT_REFRESH_TOKEN (или GOOGLE_REFRESH_TOKEN)
