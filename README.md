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


"Software updater"
