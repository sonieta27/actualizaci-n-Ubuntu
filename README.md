# Actualización Ubuntu
# Actualización del sistema
## Actualización desde línea de comandos
Para actualizar el sistema desde linea de comandos abriríamos una terminal (Gnome-terminal) y escribiríamos los siguientes comandos:

1. Actualizamos los índices de paquetes

---
sudo apt update
---

![](https://user-images.githubusercontent.com/122264807/227210584-9f63cea9-c647-4503-bbbb-d30a59cddcfa.png)

2. Vemos la lista de paquetes que se pueden actualizar:

---
apt list --upgradable
---
![](https://user-images.githubusercontent.com/122264807/227210910-cdeff890-75c7-46c1-ada7-0aca98472fac.png)


3. Actualizamos los paquetes instalados que tienen nuevas versiones en los repositorios

---
sudo apt --upgrade
---
![](https://user-images.githubusercontent.com/122264807/227211016-914b90ab-ba13-4f42-a6f4-54c5ffd3a8da.png)

# Actualización del software
## MEDIANTE LA HERRAMIENTA DE "ACTUALIZACIÓN DE SOFTWARE" o "Software updater"
Le daremos al icono de esta herramienta y le daremos a buscar actualizaciones, al encontrarlas le daremos a instalarlas de manera que automáticamente se actualizará lo necesario:
![](https://user-images.githubusercontent.com/122264807/227882917-2230245a-e6de-4326-8e01-99d98d2e2d41.png)

## MEDIANTE LA HERRAMIENTA DE SYNAPTIC

En primer lugar, debemos comprobar que tenemos la herramienta instalada, podemos usar la siguiente linea de comandos para instalarla:
'''
sudo apt install synaptic
'''
![VirtualBox_Ubuntu2_27_03_2023_10_27_04](https://user-images.githubusercontent.com/122264807/227885248-9a65e339-e3e5-4350-93af-db191da9d809.png)














