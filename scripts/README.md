# Instructions for using the **kubeplugin**

1 Download the **kubeplugin** script to your computer using the commands:

```bash
  curl -O https://github.com/Njrk/demopractice/blob/main/scripts/kubeplugin
```

2 Add execute permission to the file:

```bash
  chmod +x kubeplugin
```

3 Install the plugin using:

```bash
  sudo cp kubeplugin /usr/local/bin/kubectl-kubeplugin
```

4 Check for installed plugin:

```bash
  kubectl plugin list
```

5 Usage:

```bash
  kubectl kubeplugin [<resource_type>] [<namespace>]
```

6 Example:

```bash
root@demo:~# kubectl kubeplugin pods kube-system
Resource: pods, Namespace: kube-system, Name: coredns-59b4f5bbd5-g8jbw, CPU: 3m, Memory: 21Mi
Resource: pods, Namespace: kube-system, Name: local-path-provisioner-76d776f6f9-rp7rr, CPU: 1m, Memory: 17Mi
Resource: pods, Namespace: kube-system, Name: metrics-server-7b67f64457-8f6sw, CPU: 11m, Memory: 15Mi
Resource: pods, Namespace: kube-system, Name: svclb-traefik-615ff127-hghmh, CPU: 0m, Memory: 0Mi
Resource: pods, Namespace: kube-system, Name: traefik-56b8c5fb5c-ghz5s, CPU: 1m, Memory: 25Mi
```
