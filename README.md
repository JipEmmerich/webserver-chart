# My Webserver Chart

Dit is een Helm chart voor het deployen van een webserver met een PostgreSQL database op Kubernetes.

## Voorbereiding

1. Zorg ervoor dat je Helm geïnstalleerd hebt. Volg de instructies op de [officiële Helm website](https://helm.sh/docs/intro/install/) als je Helm nog niet geïnstalleerd hebt.
2. Zorg ervoor dat je een Kubernetes cluster hebt en dat je `kubectl` correct geconfigureerd is om ermee te communiceren.

## Installatie

Volg deze stappen om de Helm chart te installeren.

### Voeg de Helm repository toe & Installeer de chart

helm repo add webserver-chart https://JipEmmerich.github.io/webserverchart/

helm repo update

helm install my-webserver webserver-chart/webserver-chart
