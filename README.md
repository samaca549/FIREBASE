# Proyecto CRUD con Firebase Realtime Database

Este proyecto demuestra cómo crear una **aplicación de consola (CLI)** en Python que permite realizar **todas las operaciones básicas de una base de datos** (crear, leer, actualizar y eliminar) conectada con **Firebase Realtime Database**.  
El enfoque combina una estructura limpia (arquitectura MVVM) 

---

##  Descripción general

La aplicación simula una pequeña **banca digital**, donde cada usuario puede crear una cuenta, consultar su saldo, depositar dinero, guardar los cambios en la base de datos y cargar cuentas previamente guardadas.

Toda la información se guarda automáticamente en **Firebase**, y el usuario puede interactuar desde la terminal con comandos simples.

---

##  Objetivo del proyecto

- Aplicar la conexión entre Python y Firebase Realtime Database.
- Implementar las operaciones **CRUD** (Create, Read, Update, Delete).
- Demostrar el uso de un diseño modular y ordenado.
- Generar evidencia visual del funcionamiento real.

---

La clase FirebaseService permite gestionar de forma estructurada la conexión y las operaciones CRUD (crear, leer, actualizar y eliminar) con Firebase Realtime Database. Gracias a sus métodos —como create(), read(), update(), delete() y list_all()— es posible manipular datos en Firebase de manera sencilla y controlada, utilizando referencias a nodos específicos. Además, su inicialización automática mediante credenciales seguras (serviceAccountKey.json) y una URL configurada en .env asegura una conexión confiable y escalable para cualquier aplicación Python que requiera persistencia en la nube.


FUNCIONAMIENTO
<img width="1387" height="424" alt="{31570922-C300-4814-910C-F3C3438EA47D}" src="https://github.com/user-attachments/assets/bdac9830-7eac-4248-add6-c40ea0f7ef15" />
new → crea una cuenta local (solo en memoria).

d → realiza un depósito en la cuenta actual.

save → guarda o actualiza la cuenta en Firebase.

load → carga una cuenta existente desde Firebase a memoria.

Este flujo demuestra cómo la app gestiona cuentas bancarias simuladas mediante una arquitectura MVVM conectada a Firebase Realtime Database, permitiendo crear, guardar y recuperar cuentas con comandos simples desde la consola
<img width="1635" height="553" alt="{C865ED89-1CFD-4D00-8EC9-E4C16A6D73DE}" src="https://github.com/user-attachments/assets/461b9a0c-7b6d-4fd2-8850-3645e3536064" />

SE CONFIGURA EL ENV 
<img width="1424" height="236" alt="{47E82177-6D6A-40C3-9548-EE5460972BEB}" src="https://github.com/user-attachments/assets/27c19f95-5532-4f7d-9c84-f4885f0d340f" />
