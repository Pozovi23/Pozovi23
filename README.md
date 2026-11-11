# Всем привет 👋

Я разработчик с опытом развёртывания и сопровождения серверной инфраструктуры. Развиваюсь в сторону SRE/DevOps: мониторинг, разбор инцидентов, автоматизация рутины и надёжность сервисов.

- Занимаюсь поддержкой Linux-серверов и сервисов, настраиваю мониторинг и алерты.
- Автоматизирую сбор данных и ML-пайплайны: Python, Docker, DVC, MLflow, CI/CD в GitHub Actions.
- Интересуюсь робототехникой, CV и ML и применяю их в реальных задачах.


## 💻 Мои проекты

| Проект | Описание |
| --- | --- |
| [Система мониторинга парка 3D-принтеров](https://github.com/Pozovi23/PrintWatch) | Развернул стек мониторинга на Prometheus, Grafana и Alertmanager в Docker. Написал на Python кастомный Prometheus-экспортёр для опроса API принтеров с прошивкой Klipper и сбора метрик: температуры, прогресс печати. Настроил алерты и оповещения в Telegram через Alertmanager при сбоях печати, перегреве или отключении оборудования. Собрал интерактивный дашборд в Grafana. Настроил CI/CD в GitHub Actions: unit-тесты, линтинг и проверка сборки Docker-образов при открытии MR. |
| [Обнаружение утечек трубопроводов](https://vk.ru/wall-195770864_708) | Принимал участие в создании ПО, которое анализирует данные с оптоволоконных систем мониторинга и в реальном времени детектирует температурные аномалии, что позволяет обнаружить утечки жидкости. Отвечал за серверную часть инфраструктуры: автоматическую отправку данных с удалённых объектов на сервер для тренировки ML-модели и развёртывание Telegram-ботов для автоматизации мониторинга объектов. Разработано совместно с компанией ООО «СибСенсор», продемонстрировано на реальных объектах на форуме «Прибориум 2026». |
| [ROS2 AutoRace](https://github.com/Pozovi23/my_robot) | Реализация функционала робота в ROS2 для прохождения модернизированной трассы испытаний AutoRace 2025. |
| [Автоматизированный мини-ПВЗ](https://github.com/Pozovi23/Pick-up-point-automation) | Создание конвейерной системы и робота-кладовщика для прототипа автоматизации пункта выдачи заказов. <br>[▶ видео с демонстрацией](https://youtu.be/E9XQAeJRJnU?si=D68Upd1gI2q3Ge20) |
| [Детекция людей с дронов](https://github.com/Pozovi23/People-detection-from-drone) | В основе лежит YOLOv8. Проводились эксперименты с оптимизацией времени инференса на CPU (фреймворк OpenVINO) и GPU (SAHI). Лучший результат по метрике mAP50 = **0.724**. |
| [Сегментация дорог](https://github.com/Pozovi23/Segmentation) | В основе лежит U-Net (бэкбон ResNet34), дообученная для использования на датасете Massachusetts Roads. IoU = **0.516**. |

## 🔧 Технологический стек

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
![ROS2](https://img.shields.io/badge/ros-%2322314E.svg?style=for-the-badge&logo=ros&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge&logo=yolo&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/-RaspberryPi-C51A4A?style=for-the-badge&logo=Raspberry-Pi)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/Pozovi23/Pozovi23/main/dino-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/Pozovi23/Pozovi23/main/dino.svg"
  />
  <img alt="Running dino" src="https://raw.githubusercontent.com/Pozovi23/Pozovi23/main/dino.svg" width="560" />
</picture>
