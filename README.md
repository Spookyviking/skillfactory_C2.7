# Задание C2.7 (HW-03)

1. Разверните Prometheus Stack через docker-compose, в котором будет:

- Prometheus;
- Grafana;
- Node Exporter;
- Blackbox Exporter;
- AlertManager.

2. Соберите метрики с https://lms.skillfactory.ru через Blackbox, соберите метрики с вашего сервера через Node Exporter.

3. Создайте dashboard в Grafana, в котором будут отображены следующие метрики:

На вашем сервере (или локальной машине):
- время работы (Uptime);
- нагрузка на процессор (CPU) в %;
- использование памяти (RAM) в %;
- использование диска в %.

На lms.skillfactory.ru:
- возвращаемый статус-код;
- задержка ответа сайта;
- срок действия сертификата.

4. Добавьте алерты в AlertManager на следующие события:

- изменился статус-код сайта lms.skillfactory.ru;
- задержка превышает 5 секунд lms.skillfactory.ru;
- сервер перезагрузился (через метрику Uptime).
  
В Телеграм алерты можно не отправлять. Если есть желание, в качестве дополнительного задания можно кидать их себе на почту.


![Безымянный](https://github.com/Spookyviking/skillfactory_C2.7/assets/95276551/d217dcca-b2a0-4c68-9554-f9ee78cb215e)


![Безымянный2](https://github.com/Spookyviking/skillfactory_C2.7/assets/95276551/d78ddbb7-d3ea-4987-80fd-b7b1c5e1d931)


