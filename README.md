
# 🚗 Sistema de Alquiler de Vehículos

### Taller de Composición y Herencia – Java

Proyecto académico desarrollado en **Java** como parte de un taller práctico enfocado en los principios de **Programación Orientada a Objetos (POO)**.

El sistema simula el proceso de **alquiler de vehículos** mediante una aplicación de **consola**, aplicando conceptos clave como herencia, composición, interfaces y estrategias de cálculo de precios.

---

## 📌 Descripción general

El proyecto permite visualizar distintos tipos de vehículos disponibles para alquiler y realizar un proceso completo de selección, cálculo de precio y confirmación del alquiler desde la consola.

Cada vehículo implementa diferentes capacidades (interfaces), lo que permite demostrar el uso correcto de **polimorfismo y composición** dentro del diseño del sistema.

---

## 🧠 Conceptos aplicados

* 🧬 **Herencia**
* 🧩 **Composición**
* 🔌 **Interfaces**
* 🔄 **Polimorfismo**
* 🧠 **Patrón Strategy** para el cálculo del precio de alquiler
* 📦 Organización de paquetes (`com.alquiler`)

---

## 🚙 Tipos de vehículos

* 🚗 Auto
* 🏍️ Moto
* 🚙 Camioneta
* ⚡ Auto Eléctrico
* ⚡ Camioneta Eléctrica

Cada tipo de vehículo puede implementar una o varias interfaces como:

* `Rentable`
* `Asegurable`
* `Electrico`

---

## 💰 Estrategias de precio

El sistema permite seleccionar distintas estrategias de cálculo del costo del alquiler:

* 💵 **Tarifa estándar**
* 📆 **Fin de semana** (10% de descuento si los días ≥ 2)
* 🗓️ **Largo plazo** (15% de descuento si los días ≥ 10)

---

## 🖥️ Funcionamiento por consola

Ejemplo de flujo del sistema:

* Visualización de vehículos disponibles
* Selección del vehículo
* Ingreso de días de alquiler
* Selección de estrategia de precio
* Cálculo y visualización del total a pagar
* Presentación de condiciones del alquiler

---

## 🛠️ Tecnologías utilizadas

* ☕ **Java (JDK 21)**
* 🖥️ Aplicación de consola
* 📁 Eclipse / VS Code

---

## 🎯 Objetivo del proyecto

* Reforzar los conceptos fundamentales de **POO**
* Aplicar buenas prácticas de diseño orientado a objetos
* Simular un escenario real de negocio de forma estructurada
* Evaluación académica

---

## 🚀 Estado del proyecto

✔️ Proyecto finalizado
📚 Uso exclusivamente académico
