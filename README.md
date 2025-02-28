# TG-CHAT-BOT-LLM
Телеграмм бота для анализа промптов с помощью LLaMA3

Функционал :

/start - запуск бота и регистрация пользователя
/theme - выдает рандомную тему для изучения
/test - проводит тестирование по изученным темам
/stats - показывает общую статистику пользователя
/profile - показывает профиль, опыт, уровень, достижения пользователя
/create_prompt - команда для анализа вашего промпта
/best_prompts - ваши лучшие промпты
/leaderboard  - список лидеров по опыту


Запуск :

1. Так как LLaMA3 используется как локальное решение нам нужно установить ollama : после ее установки в в консоли ollama прописать (ollama pull llama3)
2. Бот запускается через файл main.py
3. Базы данных хранятся в типе .json

Используемые библиотеки :
1. PyTelegramBotAPI
2. SentenceTransformers
3. time
4. requests
5. json
6. os
7. random
8. feedparser
9. translate
10. xml.etree.ElementTree
11. faiss-cpu
12. numpy
13. bs4
14. Wikipedia API
