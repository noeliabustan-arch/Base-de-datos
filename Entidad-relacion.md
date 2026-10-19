# 🌸 Colección de Diagramas Entidad-Relación (E-R) ✨

¡Bienvenid@ a mi repositorio de **Bases de Datos**! 💖 Aquí encontrarás una colección organizada de diseños conceptuales y diagramas Entidad-Relación (E-R) desarrollados para diversos escenarios académicos y prácticos[cite: 1].

---

## 📌 Datos de la Estudiante

| Campo | Detalles |
| :--- | :--- |
| **Estudiante** | Noelia Bustan |
| **Institución** | Universidad Nacional de Loja |
| **Facultad** | Energía, las Industrias y los Recursos Naturales No Renovables |
| **Carrera** | Computación |
| **Materia** | Base de Datos |
| **Docente** | Ing. René Guamán |
| **Periodo Académico** | 2026 - 2027 |

---

## 📂 Índice de Ejercicios

- [📚 Ejemplos Guiados](#-ejemplos-guiados)
  - [Ejemplo 1: Sistema de Biblioteca](#ejemplo-1-sistema-de-biblioteca)
  - [Ejemplo 2: Pedidos de Restaurante](#ejemplo-2-pedidos-de-restaurante)
  - [Ejemplo 3: Clínica Médica](#ejemplo-3-clínica-médica)
  - [Ejemplo 4: Sistema de Aerolínea](#ejemplo-4-sistema-de-aerolínea)
- [🧩 Ejercicios Propuestos](#-ejercicios-propuestos)
  - [Ejercicio 5: Empresa Discográfica](#ejercicio-5-empresa-discográfica)
  - [Ejercicio 6: Tienda Informática](#ejercicio-6-tienda-informática)
  - [Ejercicio 7: Discos Musicales](#ejercicio-7-discos-musicales)
  - [Ejercicio 8: Camiones](#ejercicio-8-camiones)
  - [Ejercicio 9: Veterinaria](#ejercicio-9-veterinaria)

---

## 📚 Ejemplos Guiados

### Ejemplo 1: Sistema de Biblioteca
> 📖 **Descripción:**  
> Una biblioteca registra libros y autores. Un libro puede tener varios autores y un autor varios libros. Los socios toman libros prestados; de cada préstamo interesan la fecha de retiro y la de devolución[cite: 1].

<details>
<summary>🔍 <b>Ver Diagrama E-R</b></summary>

<br>

![Diagrama Biblioteca](./img/ejemplo1_biblioteca.png)

</details>

---

### Ejemplo 2: Pedidos de Restaurante
> 🍽️ **Descripción:**  
> Los clientes realizan pedidos que contienen varios platos con distinta cantidad. Los platos se agrupan en categorías. Cada pedido lo atiende un único mesero. El precio del plato debe registrarse tal como estaba al momento del pedido, aunque luego cambie[cite: 1].

<details>
<summary>🔍 <b>Ver Diagrama E-R</b></summary>

<br>

![Diagrama Restaurante](./img/ejemplo2_restaurante.png)

</details>

---

### Ejemplo 3: Clínica Médica
> 🩺 **Descripción:**  
> Los pacientes solicitan citas; cada cita la atiende un médico a un paciente en fecha, hora y consultorio. De algunas citas se genera una receta que incluye medicamentos con dosis y duración. Cada médico pertenece a una especialidad[cite: 1].

<details>
<summary>🔍 <b>Ver Diagrama E-R</b></summary>

<br>

![Diagrama Clinica](./img/ejemplo3_clinica.png)

</details>

---

### Ejemplo 4: Sistema de Aerolínea
> ✈️ **Descripción:**  
> Una aerolínea opera vuelos (cada uno con número, fecha, origen y destino), cada vuelo lo realiza un avión. Los pasajeros realizan reservas para un vuelo específico, indicando asiento y tarifa pagada en el momento de la reserva[cite: 1].

<details>
<summary>🔍 <b>Ver Diagrama E-R</b></summary>

<br>

![Diagrama Aerolinea](./img/ejemplo4_aerolinea.png)

</details>

---

## 🧩 Ejercicios Propuestos

### Ejercicio 5: Empresa Discográfica
> 🎶 **Descripción:**  
> Una empresa discográfica necesita modelar los datos sobre sus diferentes recursos según las siguientes características[cite: 1]:
> - **Manager:** De cada mánager se almacena un identificador de manager y su nombre. Un manager representa a una serie de artistas[cite: 1].
> - **Artista:** Un artista es representado por un manager. De los artistas se almacena su nombre completo (usando un único atributo) y su NIF[cite: 1].
> - **Evento de promoción:** Los artistas participan en eventos de promoción para dar a conocer sus trabajos. En un evento de promoción pueden participar varios artistas. De un evento se almacena un identificador único, la fecha de celebración y el número de asistentes[cite: 1].

<details>
<summary>🔍 <b>Ver Diagrama E-R</b></summary>

<br>

![Diagrama Empresa Discografica](./img/ejercicio5_discografica.png)

</details>

---

### Ejercicio 6: Tienda Informática
> 💻 **Descripción:**  
> Se desea crear una aplicación para la gestión de una tienda informática. La tienda dispone de una serie de productos que se venden a los clientes. De cada producto informático se desea guardar el código, descripción, precio y número de existencias. De cada cliente se desea guardar el código, nombre, apellidos, dirección y número telefónico[cite: 1].  
> Un cliente puede comprar varios productos en la tienda y un mismo producto puede ser comprado por varios clientes. Cada vez que se compre un artículo quedará registrada la compra en la base de datos junto con la fecha en la que se compró el artículo[cite: 1].  
> La tienda tiene contactos con varios proveedores que son los que suministran los productos. Un mismo producto puede ser suministrado por varios proveedores. De cada proveedor se desea guardar el código, nombres, apellidos, dirección, provincia y número de teléfono[cite: 1].

<details>
<summary>🔍 <b>Ver Diagrama E-R</b></summary>

<br>

![Diagrama Tienda Informatica](./img/ejercicio6_tienda.png)

</details>

---

### Ejercicio 7: Discos Musicales
> 🎵 **Descripción:**  
> - La tienda vende discos de diferentes géneros musicales y cantantes[cite: 1].
> - Cada género musical tiene un identificador[cite: 1].
> - Cada disco tiene título, género musical, precio y cantante[cite: 1].
> - De un cantante se registra el nombre y su país. Todo disco pertenece a un cantante y un cantante puede tener muchos discos. Además, un disco tiene un conjunto de canciones (identificador y título)[cite: 1].
> - Un disco tiene muchas canciones y una canción puede estar en varios discos. Interesa conocer la posición de una canción en un determinado disco[cite: 1].

<details>
<summary>🔍 <b>Ver Diagrama E-R</b></summary>

<br>

![Diagrama Discos Musicales](./img/ejercicio7_discos.png)

</details>

---

### Ejercicio 8: Camiones
> 🚛 **Descripción:**  
> Se desea informatizar la gestión de una empresa de transporte que reparte paquetes por toda España[cite: 1].  
> - **Camioneros:** Encargados de llevar los paquetes. Se guarda cédula, nombre, teléfono, dirección, salario y población en que vive. Un camionero distribuye muchos paquetes[cite: 1].
> - **Paquetes:** Interesa código del paquete, descripción, destinatario y dirección del destinatario. Un paquete solo puede ser distribuido por un camionero[cite: 1].
> - **Provincias:** Se guarda el código de provincia y nombre. Un paquete solo puede llegar a una provincia, pero a una provincia pueden llegar varios paquetes[cite: 1].
> - **Camiones:** Se guarda matrícula, modelo, tipo y potencia. Un camionero puede conducir diferentes camiones en fechas diferentes, y un camión puede ser conducido por varios camioneros[cite: 1].

<details>
<summary>🔍 <b>Ver Diagrama E-R</b></summary>

<br>

![Diagrama Camiones](./img/ejercicio8_camiones.png)

</details>

---

### Ejercicio 9: Veterinaria
> 🐾 **Descripción:**  
> - **Propietario:** Interesa cédula, apellidos, nombres, dirección y teléfonos. Un propietario puede llevar una o varias mascotas[cite: 1].
> - **Mascota:** Interesa identificador, nombre, fecha de nacimiento y tipo. Una mascota la lleva uno y solo un propietario[cite: 1].
> - **Personal de la clínica:** Interesa un código, cédula y nombre. Se distingue entre veterinarios (se guarda fecha_alta y especialidad) y auxiliares (interesa base de cotización)[cite: 1].
> - **Consultas:** Las mascotas pasan consulta con los veterinarios. Un veterinario puede pasar consulta a ninguna o a varias mascotas, y una misma mascota puede pasar consulta una o más veces en fechas diferentes con varios veterinarios. Al pasar consulta se realiza un diagnóstico[cite: 1].
> - **Familiar de contacto:** Cada propietario tiene un familiar de contacto para emergencias (cédula, nombre y teléfono). Si el propietario se da de alta en la clínica veterinaria, el familiar ya no interesa. El familiar es contacto de un solo propietario[cite: 1].

<details>
<summary>🔍 <b>Ver Diagrama E-R</b></summary>

<br>

![Diagrama Veterinaria](./img/ejercicio9_veterinaria.png)

</details>

---

<div align="center">

⭐ **Hecho con cariño por Noelia Bustan** ⭐

</div>
