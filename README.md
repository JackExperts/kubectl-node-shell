# kubectl node-shell
*(formerly known as **kubectl-enter**)*

Start a root shell in the node's host OS running.

## Installation

```
curl -LO https://raw.githubusercontent.com/LabsJAC/kubectl-node-shell/master/kubectl-node_shell
chmod +x ./kubectl-node_shell
sudo mv ./kubectl-node_shell /usr/local/bin/kubectl-node_shell

OR, if rancher

PATH=$PATH:/nonexistent
```

## Usage

```
kubectl node-shell <node>
```

*You need to be able to start privileged containers for that.*
