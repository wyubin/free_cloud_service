[Create your first Knative app](https://opensource.com/article/20/11/knative)
[Serverless Architecture with Knative](https://www.baeldung.com/ops/knative-serverless)
[Knative Tutorial](https://redhat-developer-demos.github.io/knative-tutorial/knative-tutorial/index.html)
## ingress controller
- 目前學到 ingress 是管理怎樣的 domain 跟 path 要到哪些 service  的規則
- 像 k8s 有基於 nginx 的 ingress controller，會產生一個符合設定的 nginx config 塞到 nginx controller pod 來達到指向的控制
- aws 的 ALB 也有實做類似 ingress controller 的功能，但基本上 load banlancing 是在ingrss controller 的前面

## knative
- knative 則是基於k8s 的套件，核心為 event 跟 service，主要是用 event 跟 trigger action (對應的service) 來滿足控制 service mesh 的控制
- 
