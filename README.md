






# Наш DevOps проект

## Описание проекта
Данный проект предназначен для автоматизации процессов CI/CD с использованием современных инструментов контейнеризации и оркестрации.

## Команда
Здесь список участников:
* **Eldos Kubatov** - Lead DevOps Engineer & Pipeline Developer
* **Kasymbek Gairatbekov** - DevOps Engineer, Backend Developer & System Architect

## Стек технологий
* **Docker**: Для контейнеризации микросервисов.
* **Kubernetes**: Для оркестрации контейнеров.
* **Jenkins**: Для построения CI/CD пайплайнов.
* **Terraform**: Для управления инфраструктурой (IaC).
* **Linux**

## Инструкции по запуску
1. Клонировать репозиторий с GitHub: `git clone <repo-url>`
2. Создать файл `.env` на основе шаблона `.env.example`
3. Запустить контейнеры с помощью Docker Compose: `docker-compose up -d`
4. Развернуть приложение в кластере Kubernetes, используя файлы из папки `/k8s`

