# Arquitectura y componentes

![Arquitectura](https://geekflare.com/wp-content/uploads/2019/06/ansible-architecture-1.png)

## Controlar Nodos:
Son los servidores desde los que se ejecuta Ansible y lanza los comando a los servidores que gestiona.
Funciona en entornos Linux, pero se puede configurar para Windows Server.

## Administrar Nodos:
Son los servidores que van a ser gestionados, se encuentran en un inventario que nos permite agruparlos y manipularlos.

## Inventario:
Son los ficheros donde incluimos los nodos gestionados, sus agrupaciones y otras características.

## PlayBooks y Plays:
Un "Play" ejecuta una serie de tareas en los nodos gestionados, son ficheros YAML de tipo declarativo. Puedes agrupar varios plays, playbooks

## Módulos:
Son scripts independientesque podemos ejecutar dentro de los playbooks, son librerias de acciones. Se copian y ejecutan en cada nodo gestionado.

## Colecciones:
Son un formato de distribucion que puede contener Playbooks, modulos, roles... Se cargan a medida que se necesiten. Tenemos Ansible Galaxy, que es un repositorio centralizado.

## Ansibe-core:
Nucleo de Ansible

## Ansible project:
Ansible y sus modulos