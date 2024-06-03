### Триггеры
CI/CD pipeline запускается автоматически при каждом пуше в ветку main.

### Ручная и автоматическая сборка
1) Автоматическая сборка:
   Автоматически запускается при каждом пуше в ветку main благодаря настройке on: push: branches: - main в файле .github/workflows/main.yml.
2) Ручная сборка: Для ручной сборки и деплоя используются скрипты build.sh и deploy.sh.

### Хранение результатов сборки
Docker-образы хранятся в вашем репозитории на Docker Hub. Учетные данные для доступа к Docker Hub конфигурируются через секреты DOCKER_USERNAME и DOCKER_PASSWORD в настройках GitHub репозитория.

### Скрины
<img width="907" alt="Screenshot_23" src="https://github.com/Zinnur41/devops_practika/assets/89980369/b06e97e5-0c56-47ea-bf08-21ae9763fc87">
<img width="610" alt="Screenshot_24" src="https://github.com/Zinnur41/devops_practika/assets/89980369/3ae25f92-38f3-43c7-8c14-28321edc8676">
<img width="690" alt="Screenshot_22" src="https://github.com/Zinnur41/devops_practika/assets/89980369/fca66f8b-b89d-4c53-a94c-d9032cb6b3a1">
<img width="632" alt="Screenshot_25" src="https://github.com/Zinnur41/devops_practika/assets/89980369/93a24988-c387-44b7-811b-797e5d583157">
<img width="596" alt="Screenshot_26" src="https://github.com/Zinnur41/devops_practika/assets/89980369/47a88541-001d-40c7-a0cc-5042564e7931">



