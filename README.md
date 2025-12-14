# Monitoreo con Grafana y Prometheus

## Descripción
En esta práctica se configuró Grafana utilizando Docker y Prometheus como fuente de datos
para el monitoreo de métricas del sistema.

## Herramientas utilizadas
- Docker
- Prometheus
- Grafana

## Panel creado
Se creó un dashboard en Grafana con un panel de tipo *Time series*
utilizando la siguiente métrica:

node_cpu_seconds_total

Esta métrica permite visualizar el uso del CPU del sistema en tiempo real.

## Evidencia
![Panel Grafana](grafana_panel.png)
