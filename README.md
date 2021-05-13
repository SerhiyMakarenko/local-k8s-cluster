# local-k8s-cluster
Local Kubernetes cluster for testing

## Configuration
Installed version of the K8s can be controlled using `kubernetes-setup/vars/main.yml` file under `kube_packages` section.

## Starting the K8s cluster
Within the repo please run the following command:
```
vagrant init
vagrant up
```

## Stopping the cluster
Within the repo please run the following command:
```
vagrant destroy
```

## Related
- [Kubernetes Setup Using Ansible and Vagrant](https://kubernetes.io/blog/2019/03/15/kubernetes-setup-using-ansible-and-vagrant/)
- [Vagrant: running Ansible provisioning after all VMs booted, Ansible cannot connect to all hosts](https://stackoverflow.com/questions/59678447/vagrant-running-ansible-provisioning-after-all-vms-booted-ansible-cannot-conne)
