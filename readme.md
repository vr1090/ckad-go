## devSecOps
- introduce .. security on our pipeline
- dulu:
    - deployment ... dah CI/CD ... 
    - terus security check in the end
    - lama ...
    - deployment baru ini dan itu...
- sekarang:
    - masukin beberapa tools during pipeline
    - sonarqube
    - k10
    - backup k8s lu dulu, sebelum execute everything

## istio
- istio is service mesh
- service mesh ... maging communication between microservices
- envoy proxy
- istiod ... dulu banyak komponen, sekarang setelah 1.5 tinggal 1 component

## cloud native
- promise: 
    - avaliable and scalable
    - agility and developer centric
- cloud computing:
    - running apps on cloud provider
    - monolithic to microservices
    - scaling should effortless
- simply running is not a cloud native
- tenets:
    - microservices
    - containers
    - devops
        - high level collaboration dev and ops
        - development practice
        - CI/CD ... automate software deployment
        - merging code changes, running automated test
    - cloud native open standards
        - standarize
        - using best practice as they become avaliable
- open stadard:
    - open telemetry
    - service mesh
- when should adopt?:
    - small .. no need
    - large .. offer wide range of benefit, faster development cycle

