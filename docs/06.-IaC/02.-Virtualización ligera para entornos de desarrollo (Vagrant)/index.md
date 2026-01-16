# 02.-Virtualización ligera para entornos de desarrollo (Vagrant)

Vagrant es una herramienta que facilita la creación y gestión de entornos virtuales de forma automatizada, asegurando entornos de desarrollo reproducibles y consistentes. Su configuración se basa en el **Vagrantfile**, donde se definen aspectos como el sistema operativo, red y recursos asignados.

Su instalación en **Linux** es sencilla y compatible con proveedores como **VirtualBox** y **KVM/QEMU**. Una vez configurado, Vagrant permite crear y gestionar máquinas virtuales con comandos básicos como `vagrant up`, `vagrant ssh` y `vagrant destroy`.

Además, Vagrant admite configuraciones avanzadas como redes personalizadas, sincronización de carpetas y entornos multi-máquina. Su integración con **Ansible** permite automatizar la configuración del software y servicios en las VMs, mejorando la eficiencia y escalabilidad de los entornos de desarrollo.

Esta combinación de herramientas es clave en la **Infraestructura como Código (IaC)**, optimizando la gestión y despliegue de entornos virtuales.