## object management
- imperative
    -kubectl run
- declarative
    - kubectl create
    - kubectl apply
- hybrid
    - kubctl run -o yaml --dry-run=client
- edit
    - kubectl edit pod frontend
- pod lifecycle
    - pending
    - running
        - success
        - failed
    - unknown
- logs
    - kubectl logs podName 
    - f buat bilang stream
- env variable:
    - key value pair
    - name and value
    



## node
- kumpulan node jadi cluster
- master ... orchetration of the nodes
- install:
    - api server
    - kubelet
    - controller
- controller .. yg cek .. kalau ada pod goes down
- container runtime .. ini yg jalanin image
- kubelete .. agent yg jalan di tiap cluster
- kubectl ... kube command line tools

