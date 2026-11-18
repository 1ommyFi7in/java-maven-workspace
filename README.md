# Подготовка рабочего цикла

Подготовь чистый репозиторий магазина, который коллега соберёт из терминала.

**Этап 04 · Старт** · Java 21 · Maven Wrapper · Git

[Этап 04](https://github.com/1ommyFi7in/java-backend-roadmap/blob/main/%D0%9E%D0%B2%D0%B5%D1%80%D0%B2%D1%8C%D1%8E.md#04-%D0%BA%D0%BB%D0%B8%D0%B5%D0%BD%D1%82-%D1%81%D0%B1%D0%BE%D1%80%D0%BA%D0%B0-%D0%B8-postgresql) · [Техническое задание](SPECIFICATION.md) · [Весь маршрут](https://github.com/1ommyFi7in/java-backend-roadmap)

> [!NOTE]
> Учебное задание. В репозитории находятся постановка, примеры и критерии приёмки. Реализацию добавляй по мере прохождения этапа.

## Результат этапа

| Что собрать | Что отработать |
| --- | --- |
| Минимальный Maven-проект, Wrapper и команды для чистой копии. | Java release, фазы Maven, воспроизводимость без IDE. |

## Как выглядит результат

```powershell
.\mvnw.cmd verify
java -cp target/classes app.Main check
```

Сборка завершается строкой `BUILD SUCCESS`, программа выводит `READY`. В Unix используется `./mvnw verify`.

## Проверка перед сдачей

- [ ] Сборка и запуск воспроизводятся из новой рабочей копии с JDK 21. Команды выполняются в терминале, `target/` отсутствует в Git.

## Начать работу

```sh
git clone https://github.com/1ommyFi7in/java-maven-workspace.git
cd java-maven-workspace
```

Открой [техническое задание](SPECIFICATION.md), подготовь входные данные и начни с основного сценария. Команды запуска и проверок добавь после первого рабочего прогона.

[← Анализатор журнала запросов](https://github.com/1ommyFi7in/java-request-log-analyzer) · [Модель магазина в PostgreSQL →](https://github.com/1ommyFi7in/shop-postgres)
