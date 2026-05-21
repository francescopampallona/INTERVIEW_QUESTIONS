# KUBERNETES

---

## FONDAMENTA DI KUBERNETES

- Cos’è Kubernetes?
- Quale problema risolve Kubernetes?
- Differenza tra Docker e Kubernetes?
- Cos’è un cluster Kubernetes?
- Quali sono i componenti principali di Kubernetes?
- Cos’è un nodo (Node)?
- Differenza tra Master Node e Worker Node?
- Cos’è il Control Plane?
- Cos’è kubelet?
- Cos’è kube-proxy?
- Cos’è etcd?
- Come funziona il scheduling dei pod?
- Perché Kubernetes è utile nei microservizi?
- Quando NON useresti Kubernetes?

---

## POD

- Cos’è un Pod?
- Perché Kubernetes usa i Pod invece dei container direttamente?
- Quanti container possono esserci in un Pod?
- Quando useresti più container nello stesso Pod?
- Cos’è un init container?
- Come si crea un Pod?
- Come si elimina un Pod?
- Cosa succede se un Pod crasha?
- Differenza tra Pod e Deployment?
- Come visualizzi i log di un Pod?
- Come entri dentro un container di un Pod?
- Cos’è un Pod lifecycle?
- Differenza tra restartPolicy Always, Never e OnFailure?

---

## DEPLOYMENT E REPLICASET

- Cos’è un Deployment?
- Perché usare un Deployment invece di creare Pod manualmente?
- Cos’è un ReplicaSet?
- Come funziona lo scaling?
- Come aumenti il numero di repliche?
- Cos’è un rolling update?
- Come funziona il rollback?
- Cos’è una strategia Recreate?
- Come controlli lo stato di un Deployment?
- Come aggiorni un’immagine Docker in un Deployment?

---

## SERVICE E NETWORKING

- Cos’è un Service?
- Perché i Pod non vengono esposti direttamente?
- Differenza tra ClusterIP, NodePort e LoadBalancer?
- Quando useresti Ingress?
- Cos’è un Ingress Controller?
- Differenza tra Service e Ingress?
- Come funziona il networking tra Pod?
- Cos’è CoreDNS?
- Come comunicherebbero due microservizi in Kubernetes?
- Cos’è una NetworkPolicy?
- Come limiteresti il traffico tra Pod?

---

## CONFIGURAZIONE

- Cos’è un ConfigMap?
- Quando useresti un Secret?
- Differenza tra ConfigMap e Secret?
- Come monti una ConfigMap dentro un Pod?
- Come inietti variabili d’ambiente?
- Come gestisci credenziali database?
- Come aggiorni configurazioni senza rebuildare l’immagine?

---

## STORAGE

- Cos’è un volume in Kubernetes?
- Differenza tra volume effimero e persistente?
- Cos’è PersistentVolume (PV)?
- Cos’è PersistentVolumeClaim (PVC)?
- Come funziona il binding tra PV e PVC?
- Cos’è una StorageClass?
- Quando useresti storage dinamico?
- Come monteresti un disco persistente in un Pod?
- Differenza tra ReadWriteOnce e ReadWriteMany?

---

## SCALING E ALTA DISPONIBILITÀ

- Come funziona l’Horizontal Pod Autoscaler?
- Cos’è il Vertical Pod Autoscaler?
- Come Kubernetes garantisce alta disponibilità?
- Cosa succede se un nodo muore?
- Come vengono redistribuiti i Pod?
- Come funziona il self-healing?
- Cos’è un readiness probe?
- Cos’è una liveness probe?
- Differenza tra readiness e liveness probe?
- Come configureresti un health check?

---

## RESOURCE MANAGEMENT

- Differenza tra requests e limits?
- Cosa succede se un container supera il limite RAM?
- Cos’è OOMKilled?
- Come assegni CPU e memoria?
- Come eviti che un Pod consumi troppe risorse?
- Cos’è QoS in Kubernetes?
- Differenza tra BestEffort, Burstable e Guaranteed?

---

## SICUREZZA

- Come proteggeresti un cluster Kubernetes?
- Cos’è RBAC?
- Differenza tra Role e ClusterRole?
- Cos’è un ServiceAccount?
- Come limiti permessi ai Pod?
- Cos’è un namespace?
- Come isoli ambienti diversi?
- Cos’è un Secret encryption?
- Come gestiresti immagini Docker non sicure?
- Cos’è Pod Security Admission?

---

## HELM

- Cos’è Helm?
- Perché Helm è utile?
- Cos’è un chart?
- Cos’è values.yaml?
- Come installi un chart?
- Come aggiorni una release Helm?
- Come funziona il rollback in Helm?
- Differenza tra Helm e kubectl apply?

---

## MONITORAGGIO E LOGGING

- Come monitoreresti un cluster Kubernetes?
- Cos’è Prometheus?
- Cos’è Grafana?
- Come raccogli i log?
- Cos’è Fluentd?
- Come faresti troubleshooting di un Pod?
- Quali comandi kubectl useresti per debugging?
- Come analizzi eventi Kubernetes?

---

## CI/CD E DEVOPS

- Come integreresti Kubernetes in una pipeline CI/CD?
- Come deployeresti automaticamente un microservizio?
- Cos’è GitOps?
- Differenza tra ArgoCD e Flux?
- Come gestiresti ambienti dev/test/prod?
- Come implementeresti blue-green deployment?
- Come implementeresti canary deployment?

---

## ARCHITETTURA E SCENARI REALI

- Progetta un’architettura microservizi su Kubernetes.
- Come deployeresti un’applicazione Spring Boot su Kubernetes?
- Come collegheresti frontend, backend e database?
- Come gestiresti database stateful?
- Come migreresti un sistema monolitico verso Kubernetes?
- Come garantiresti zero downtime deployment?
- Come organizzeresti namespace in una grande azienda?
- Come gestiresti multi-tenant Kubernetes?

---

## COMANDI KUBECTL

- Come visualizzi tutti i Pod?
- Come visualizzi i log di un Pod?
- Come descrivi una risorsa?
- Come elimini un Pod?
- Come esegui una shell dentro un container?
- Come applichi un file YAML?
- Come fai scaling di un Deployment?
- Come controlli eventi del cluster?
- Come visualizzi namespace?
- Come controlli utilizzo CPU/RAM dei Pod?

---

## DOMANDE AVANZATE

- Cos’è un Operator in Kubernetes?
- Cos’è Custom Resource Definition (CRD)?
- Come funziona il scheduler interno?
- Cos’è taint e toleration?
- Cos’è affinity e anti-affinity?
- Cos’è un DaemonSet?
- Quando useresti uno StatefulSet?
- Differenza tra StatefulSet e Deployment?
- Cos’è un Job?
- Cos’è un CronJob?
- Come funziona il container runtime?
- Differenza tra Docker Shim e containerd?
- Come funziona il processo di bootstrap del cluster?