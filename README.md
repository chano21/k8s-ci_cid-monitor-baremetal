# k8s-ci_cid-monitor-baremetal
kubernetes cicd(with socketxp) + kubernetes_dashboard(http) + baremetal(metalLB)

Run step : 

1. into /baremetal // get for ip
2. into /ingress // declare ingress
3. into /ingress-controller // config ingress resource
4. into /moniotring/metics // make metric server for dashboard.
5. into /monitoring // I edited recommeded.yaml for local dashboard. 180~236 line
6. into /namespace // My namespace is "pco" . All resource use "pco" namespace. (dashboard not use pco)
7. into /service // for ok , hello service
8. into /socketxp // use for webhook. look "https://www.socketxp.com/webhookrelay/github-webhook-localhost-jenkins"
