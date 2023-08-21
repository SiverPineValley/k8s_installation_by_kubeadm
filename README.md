# k8s_installation_by_kubeadm

k8s 실습 클러스터를 구성하기 위한 Vagrantfile 및 설정 정보

- Linux Ubuntu 22.04.3 LTS (Jammy Jellyfish)
- Master Node: 1 (kubemaster)
- Worker Node: 2 (kubenode01, kubenode02)

## Prerequisite

- [Virtual Box](https://www.virtualbox.org/)

- [Vagrant](https://www.vagrantup.com/)


## Installation to Virtual Box

```sh
git clone https://github.com/SiverPineValley/k8s_installation_by_kubeadm.git

cd k8s_installation_by_kubeadm

vagrant up
```

## 참조

https://github.com/kodekloudhub/certified-kubernetes-administrator-course