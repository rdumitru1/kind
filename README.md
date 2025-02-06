This terraform code deploys kind (kubernetes on Docker) on linux/mac/wsl2
References for:
kind-cluster.tf => kubeadm_config_patches are from here: [kube_adm_patches(https://kind.sigs.k8s.io/docs/user/configuration/#kubeadm-config-patches)]
kind-cluster.tf => extra_port_mappings are from here: [extra_port_mappings(https://kind.sigs.k8s.io/docs/user/ingress/#option-2-extraportmapping)]
nginx-ingress.tf => null_resource are from here: [null_resource(https://kind.sigs.k8s.io/docs/user/ingress/#ingress-nginx)]
