# Домашнее задание 11: TeamCity

## Выполненные шаги

1. ✅ Создан TeamCity Server (4CPU4RAM) в Yandex Cloud — http://89.169.128.127:8111
2. ✅ Создан TeamCity Agent (2CPU4RAM) с SERVER_URL — авторизован
3. ✅ Сделан fork репозитория https://github.com/aragastmatb/example-teamcity
4. ✅ Создана VM (2CPU4RAM) для приложения — 51.250.75.211
5. ✅ Создан проект в TeamCity на основе fork
6. ✅ Выполнен autodetect конфигурации (Maven)
7. ✅ Первая сборка master выполнена (Build #1)
8. ✅ Настроены условия: master → deploy, остальные → test
9. ✅ Загружен settings.xml с кредами Nexus
10. ✅ Изменены ссылки в pom.xml на Nexus
11. ✅ Сборка master прошла, артефакт в Nexus
12. ✅ Конфигурация мигрирована в репозиторий (Kotlin DSL)
13. ✅ Создана ветка feature/add_reply
14. ✅ Добавлен метод sayHunter() с репликой содержащей "hunter"
15. ✅ Добавлен тест на поиск слова "hunter"
16. ✅ Push в новую ветку, сборка запустилась автоматически
17. ✅ Merge feature/add_reply → master
18. ✅ Настроена сборка .jar в артефакты (target/*.jar)
19. ✅ Повторная сборка master успешна, артефакты собраны
20. ✅ Конфигурация в репозитории содержит все настройки (.teamcity/settings.kts)

## Ссылка на репозиторий

https://github.com/DimirDin/example-teamcity
