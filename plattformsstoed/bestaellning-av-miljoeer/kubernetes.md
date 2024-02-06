---
description: Kubernetes erbjuds genom VMWare Tanzu med ett tjänstepaket.
---

# Kubernetes

### Kubernetesleverans <a href="#kubernetesleverans" id="kubernetesleverans"></a>

Kubernetes levereras från datacentret i Skövde där vi har två miljöer. En för test och en för produktion. Leveransen består av kluster, ett container-registry och ett paket med tjänster som ofta behövs.&#x20;

Paketet med tjänster består av följande komponenter:

* **Nginx**, är en ingress för att ta emot inkommande trafik.
* **Certmanager**, för att få certifikat till ingressen.&#x20;
* **Argo-CD**, för att installera och hantera tjänster enligt GitOps-pattern.
* **Prometheus**, metrikinsamling och alerting.
* **Grafana**, för att visualisera metrik.
* **Loki** för att titta på loggar.

### **Beställning av kuberneteskluster**

Efter du har beställt ett kluster kommer vi att skapa upp det och ge en person i ditt team cluster-admin rättigheter. Ni kommer även att få tillgång till Harbor som är ett container-registry.\
\
Skicka ett mail till [robert.forsstrom@vgregion.se](mailto:robert.forsstrom@vgregion.se) så börjar vi processen där.

### Länkar

[Infrastruktur & Cybersäkerhet - Containerplattform](https://vgregion.sharepoint.com/sites/IOC/SitePages/DP-containerplatform.aspx) (SharePoint)
