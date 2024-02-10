# kubernets-study-plan

N.B <strike> Completed task </strike>
| Date       | Mesfin                                         | Hussen                                             | Eyoel                                                      |
|------------|------------------------------------------------|----------------------------------------------------|------------------------------------------------------------|
| Week 1     | **Introduction to Kubernetes**                 | **Kubernetes Architecture**                        | **Installing Kubernetes**                                   |
| 5/15/2023  | - <strike> Overview of containerization                 | - <strike> Kubernetes control plane and worker nodes        | - Setting up a local cluster                                 |
| 5/17/2023  | - Kubernetes features and use cases             | - Kubernetes API server and etcd                   | - Kubernetes deployment models and manifests                 |
| 5/19/2023  | - Kubernetes vs Docker                          | - Kubernetes networking and service discovery      | - Kubernetes dashboard and kubectl basics                     |
|            | **Project**: Create a simple Kubernetes cluster | **Project**: Deploy a simple application on Kubernetes | **Project**: Deploy a multi-tier application on Kubernetes |
| Week 2     | **Kubernetes Networking**                      | **Kubernetes Storage**                             | **Kubernetes Security**                                      |
| 5/22/2023  | - Kubernetes networking models                   | - Kubernetes storage classes and volumes           | - Kubernetes security overview and security contexts         |
| 5/24/2023  | - Kubernetes services and service types          | - Persistent volumes and claims in Kubernetes      | - Kubernetes role-based access control (RBAC)                 |
| 5/26/2023  | - Kubernetes network policies                    | - StatefulSets and StatefulPods in Kubernetes      | - Kubernetes secrets and Kubernetes Security Policies (Seccomp) |
|            | **Project**: Configure network policies for a simple app | **Project**: Configure stateful sets and persistent volumes | **Project**: Configure RBAC for a multi-tier app       |
| Week 3     | **Kubernetes Applications**                      | **Kubernetes Scaling**                              | **Kubernetes Operations**                                    |
| 5/29/2023  | - Deploying applications in Kubernetes            | - Kubernetes scaling options, including HPA and VPA | - Kubernetes monitoring using Prometheus and Grafana          |
| 5/31/2023  | - Kubernetes pods and pod lifecycles              | - Horizontal and vertical scaling in Kubernetes    | - Kubernetes logging with Fluentd and Elasticsearch         |
| 6/2/2023   | - Kubernetes deployment strategies                | - Cluster autoscaling in Kubernetes                 | - Kubernetes troubleshooting and debugging techniques        |
|            | **Project**: Deploy a complex multi-tier app      | **Project**: Scale a simple app horizontally and vertically | **Project**: Configure monitoring and logging for a multi-tier app |
| Week 4     | **Kubernetes Advanced Topics**                   | **Kubernetes Best Practices**                      | **Kubernetes Project**                                       |
| 6/5/2023   | - Kubernetes ingress and ingress controllers     | - Kubernetes resource limits in pods and containers | - Contributing to Kubernetes and the Kubernetes release process |
| 6/7/2023   | - Kubernetes custom resources and operators      | - Kubernetes rolling updates and blue/green deployments | - Kubernetes community and CNCF landscape                     |
| 6/9/2023   | - Kubernetes multi-tenancy and security models   | - Kubernetes cluster sizing and resource management | - Final project presentations                                |
|            | **Project**: Configure advanced networking and security for a multi-tier app | **Project**: Implement rolling updates and blue/green deployments | **Project**: Contribute to a Kubernetes open source project |


# Topics that are relevant to the Certified Kubernetes Application Developer (CKAD) certification. 
##  Also added CKAD specific exercises and projects for each week

| Date       | Mesfin                                            | Hussen                                            | Eyoel                                                 |
|------------|---------------------------------------------------|---------------------------------------------------|-------------------------------------------------------|
| Week 1     | **Core Concepts**                                 | **Configuration**                                | **Multi-Container Pods**                              |
| 5/15/2023  | - Kubernetes Architecture                          | - Environment variables                           | - Multi-container patterns and anti-patterns          |
| 5/17/2023  | - Pod creation and configuration                    | - ConfigMaps and Secrets                          | - Using initContainers for pre-start initialization    |
| 5/19/2023  | - Pod scheduling                                   | - SecurityContexts and ServiceAccounts            | - Designing for container communication and sharing   |
|           |**Exercise**:   Create, Inspect and Update Pods <br />-In this exercise, you'll create, inspect, and update pods using different methods like creating a pod using an imperative command, creating a pod using a YAML file, inspecting a pod's logs, and updating a pod's configuration. | **Exercise**: ConfigMaps, Secrets and SecurityContexts | **Project**: Multi-Container Application Deployment   |
| Week 2     | **Services and Networking**                        | **Pod Design**                                   | **State Persistence**                                 |
| 5/22/2023  | - Service types and selectors                       | - Labels, Selectors, and Annotations              | - Kubernetes Volumes and PersistentVolumes            |
| 5/24/2023  | - Network Policies and Service Discovery            | - Pod anti-affinity and affinity                   | - StatefulSets and Headless Services                  |
| 5/26/2023  | - Ingress and Ingress Controllers                   | - Taints and Tolerations                           | - Rolling updates and rollbacks                       |
|            | **Exercise**: Services and Networking\ -the excercise is bout | **Exercise**: Pod Affinity and Anti-Affinity       | **Project**: Stateful Application Deployment          |
| Week 3     | **Pod Observability**                              | **Configuration**                                | **Deployments and Rolling Updates**                   |
| 5/29/2023  | - Logging with Kubernetes                           | - ConfigMaps and Secrets                          | - Deployments and ReplicaSets                         |
| 5/31/2023  | - Debugging with Kubernetes                          | - SecurityContexts and ServiceAccounts            | - Rolling updates and rollbacks                       |
| 6/2/2023   | - Monitoring with Kubernetes                        | - Resource Limits and Requests                     | - Job and CronJob Controllers                         |
|            | **Exercise**: Logging, Debugging and Monitoring      | **Exercise**: Resource Limits and Requests         | **Project**: Deployments and Rolling Updates           |
| Week 4     | **ConfigMaps, Security and RBAC**                   | **Advanced Concepts**                            | **Mock Exam and Review**                              |
| 6/5/2023   | - ConfigMaps and Secrets best practices              | - Annotations and Labels                          | - Practice exam with review session                    |
| 6/7/2023   | - SecurityContexts and ServiceAccounts best practices | - Jobs and CronJobs                               | - Practice exam with review session                    |
| 6/9/2023   | - Kubernetes Role-Based Access Control (RBAC)         | - Advanced scheduling concepts and practice        | - Final project presentations with feedback and review |
|            | **Exercise**: ConfigMaps, Security and RBAC           | **Exercise**: Advanced Concepts                    | **Mock Exam and Review**                              |



Taudin nimi | Oireet | Hoito | Jälkitaudit ja vakavat seuraukset | Taudin aiheuttaja | Taudin tarttuminen | Tartunnan ehkäisytoimet
---|---|---|---|---|---|---
Rotavirusinfektio | Ripuli, oksentelu, kuume | Nesteytys, lepo | Dehydraatio, mahdollinen sairaalahoito | Rotavirus | Fekaalinen-oraalinen | Hyvä käsihygienia, rokotus
Kurkkumätä | Kuume, kurkkukipu, nielutulehdus, kalvomaiset peitteet nielussa | Antibiootit, lepo | Hengitysvajaus, sydäntulehdus | Corynebacterium diphtheriae | Pisara- ja kosketustartunta | Rokotus, hyvä hygienia
Jäykkäkouristus | Lihasjäykkyys, krampit, hengitysvaikeudet | Immunoglobuliini, tetanustoksoidi | Hengitysvajaus, kuolema | Clostridium tetani | Haavat, jotka ovat likaisia tai altistuvat maaperälle | Rokotus, puhtaat haavat
Hinkuyskä | Yskäkohtaukset, hengitysvaikeudet, siniset kasvot | Antibiootit, hengitystuki | Keuhkokuume, aivovaurio, kuolema | Bordetella pertussis | Pisara- ja kosketustartunta | Rokotus, hyvä käsihygienia
Polio | Lievät flunssan oireet, lihasheikkous, halvaus | Fysioterapia, tukitoimet | Paralyysi, kuolema | Poliovirus | Fekaalinen-oraalinen | Rokotus, hyvä hygienia
Hib-taudit | Korvatulehdus, aivokalvontulehdus, keuhkokuume | Antibiootit, tukihoito | Kuurous, aivovaurio, kuolema | Haemophilus influenzae b | Pisara- ja kosketustartunta | Rokotus
Pneumokokki-infektio | Keuhkokuume, korvatulehdus, verenmyrkytys | Antibiootit, tukitoimet | Meningiitti, kuolema | Streptococcus pneumoniae | Pisara- ja kosketustartunta | Rokotus
Influenssa | Kuume, lihaskivut, yskä, väsymys | Lepo, kuumelääkkeet | Keuhkokuume, kuolema | Influenzavirus | Pisara- ja kosketustartunta | Rokotus, hyvä hygienia
Tuhkarokko | Kuume, ihottuma, yskä, silmien ärsytys | Tukihoito | Keuhkokuume, kuolema, aivovaurio | Morbillivirus | Pisara- ja kosketustartunta | Rokotus
Vihurirokko | Lievät flunssan oireet, ihottuma, niveltulehdus | Tukihoito | Kuulon heikkeneminen, aivovaurio | Rubellavirus | Pisara- ja kosketustartunta | Rokotus
Sikotauti | Kuume, turvonneet sylkirauhaset, kipu | Tukihoito, kuumelääkkeet | Miehitys, hedelmättömyys | Mumpsivirus | Pisara- ja kosketustartunta | Rokotus
Vesirokko | Ihottuma, kutina, kuume | Tukihoito, kuumelääkkeet | Bakteeritulehdukset, aivotulehdus | Varicella-zoster-virus | Pisara- ja kosketustartunta | Rokotus, eristys
Papilloomavirusinfektio | Sukuelinten syyliä, syövän esiasteita | Paikallishoito, leikkaus | Kohdunkaulan syöpä, sukuelinten syöpä | Papillomavirus | Seksuaalinen kontakti | Rokotus, kondomin käyttö
Tuberkuloosi | Yskä, väsymys, painon lasku, yöhikoilu | Antibiootit, eristys | Keuhkoputkien laajeneminen, kuolema | Mycobacterium tuberculosis | Ilman kautta | Rokotus, eristys, hyvä ilmanvaihto
Hepatiitti A | Kuume, väsymys, ruokahaluttomuus, keltaisuus | Tukihoito, oireenmukainen hoito | Maksan vajaatoiminta, kuolema | Hepatiitti A -virus | Suun kautta | Hyvä hygienia, rokotus
Hepatiitti B | Väsymys, ruokahaluttomuus, keltaisuus | Tukihoito, viruslääkkeet | Maksakirroosi, maksasyöpä | Hepatiitti B -virus | Veren tai kehon nesteiden kautta | Rokotus, steriilien neulojen käyttö
Puutiaisaivotulehdus | Kuume, päänsärky, lihaskivut, ihottuma | Tukihoito, viruslääkkeet | Aivokalvontulehdus, kuolema | Puutiaiset | Punkin purema | Suojautuminen punkilta, tarkastus punkinpuremien jälkeen
Meningokokki | Kuume, päänsärky, pahoinvointi, ihottuma | Antibiootit, tukihoito | Aivovaurio, kuolema | Neisseria meningitidis | Pisara- ja kosketustartunta | Rokotus, hyvä hygienia
Vesikauhu | Kuume, päänsärky, pelko vedestä | Immunoglobuliini, tukihoito | Aivokalvontulehdus, kuolema | Rabiesvirus | Eläimen purema | Rokotus, välttää eläinten lähellä olemista
