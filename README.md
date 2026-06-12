# mephi-session-project-2026

**Сессионный проект по курсу “Операционные системы семейства Unix”**

## Описание

Настройка Fedora 43 Server в VirtualBox: статический IP, веб-сервер nginx, SELinux, PAM и capabilities.

## Содержимое репозитория

| Файл | Описание |
|------|----------|
| `project_history.txt` | История всех выполненных команд |
| `network_check.txt` | Результаты ping до шлюза и 8.8.8.8 |
| `nginx_recent_logs.txt` | Логи nginx за последние 5 минут |
| `fstab.txt` | Файл /etc/fstab с автоматическим монтированием |
| `selinux_status.txt` | Режим SELinux (Enforcing) |
| `file_contexts.txt` | Контекст SELinux для /data/mephi-web |
| `tcpdump_capabilities.txt` | Настройки capabilities для tcpdump |
| `permissions.txt` | Права доступа на /data/mephi-web |
| `users_groups.txt` | Пользователь mephi-admin и группа mephi-devs |
| `index.html` | Персонифицированная веб-страница |
| `curl_output.txt` | Результат проверки веб-сервера |
| `mephi-nginx-screenshot.png` | Скриншот с результатом curl |
| `tcpdump.rpm` | Локальный RPM-пакет tcpdump |

## Проверка работы

```bash
curl http://192.168.1.100
# Вывод: Hello from Student: M2551154
