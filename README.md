# Desafio Docker e Vagrant

Requisitos:
1. Criar um Vagrantfile com as definições de 4 máquinas virtuais. Sendo uma máquina com o nome de master e as outras com os nomes de node01, node02 e node03; 
1. Cada máquina virtual deverá ter um IP fixo; 
1. Todas as MV deverão possuir o Docker pré-instalado; 
1. A máquina com o nome de master deverá ser o nó manager do cluster. 
1. As demais máquinas deverão ser incluídas no cluster Swarm como Workers. 
## Build

* Up

```sh
$ vagrant up
```

* Access instance

```sh
$ vagrant ssh
```

## Destroy

```sh
$ vagrant destroy
```

