# docker-kubernetes_docker-day-piracicaba-2026-09
Conteúdos da apresentação "Docker e Kubernetes: dicas e truques para descomplicar sua vida ao trabalhar com containers!". Tecnologias abordadas: Kubernetes, Docker, Linux, Azure Kubernetes Service, Grafana, Prometheus, OpenTelemetry, Azure DevOps, KEDA, Visual Studio Code...

## Algumas dicas e truques

### Container Tools for Visual Studio Code

Uma alternativa a ferramentas licenciadas.

Link: **https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-containers**

Testes:

```bash
docker run -e "EndpointRequest=https://httpbin.org/get" -d renatogroffe/dotnet10-worker-httprequest:2
```

### Kor - objetos em desuso num cluster Kubernetes

Link: **https://github.com/yonahd/kor**

Pipeline de exemplo: **https://github.com/renatogroffe/azuredevops-kubernetes-kor**

### k9s - Monitoramento e gerenciamento de objetos do Kubernetes via interface + linha de comando

Link: **https://k9scli.io/**

### Escalabilidade com KEDA

Link: https://keda.sh/

Exemplo de uso do Cron Scaler: https://github.com/renatogroffe/kubernetes-keda-cron_worker-fake-dotnet

### Scanning de vulnerabilidades com Trivy

Link: **https://trivy.dev/**

Exemplo: **https://github.com/renatogroffe/trivy_operator-aks-managed_prometheus** 

### Guias de Segurança

- OWASP Kubernetes Top Ten: **https://kubernetes-top10.owasp.org/**
- Docker Security Cheat Sheet - OWASP: **https://cheatsheetseries.owasp.org/cheatsheets/Docker_Security_Cheat_Sheet.html**
- Kubernetes Security Cheat Sheet - OWASP: **https://cheatsheetseries.owasp.org/cheatsheets/Kubernetes_Security_Cheat_Sheet.html**

### Certificações gratuitas

* Linux Foundation: **https://training.linuxfoundation.org/full-catalog/?_sfm_price=0**

* Grafana: **https://learn.grafana.com/**

---

público: 48 pessoas
