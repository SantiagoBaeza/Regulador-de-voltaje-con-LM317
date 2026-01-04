[⬅️ Volver a "Diseño de PCB"](https://github.com/SantiagoBaeza/Dise-o-de-PCBs-KiCad-/tree/main)

# Regulador de voltaje con LM317 – Diseño de PCB en KiCad

Este proyecto consiste en el diseño de una placa reguladora de voltaje con protección mediante diodos, utilizando el regulador ajustable **LM317**.  
El objetivo es aplicar el flujo completo de trabajo en **KiCad 9.0.2**, desde el esquemático hasta la generación de archivos Gerber para fabricación.

---

## Capturas

| Esquemático inicial | Selección del regulador LM317 | Selección de diodo genérico | Esquema final |
|---------------------|-------------------------------|-----------------------------|----------------|
| ![01 captura regulador de voltaje](https://github.com/SantiagoBaeza/Regulador-de-voltaje-con-LM317/blob/main/01%20captura%20regulador%20de%20voltaje%20con%20proteccion%20de%20diodo%20.jpg) | ![02 LM317_TO-252](https://github.com/SantiagoBaeza/Regulador-de-voltaje-con-LM317/blob/main/02%20captura%20LM317_TO-252.jpg) | ![03 Selección diodo](https://github.com/SantiagoBaeza/Regulador-de-voltaje-con-LM317/blob/main/03%20captura%20Seleccion%20diodo%20generico.jpg) | ![04 esquema listo](https://github.com/SantiagoBaeza/Regulador-de-voltaje-con-LM317/blob/main/04%20captura%20esquema%20listo.jpg) |

> 🔧 Reemplazá `ruta/a/...` por la ruta real de tus imágenes en el repositorio.

---

## Tecnologías utilizadas

- KiCad EDA 9.0.2  
- Regulador LM317 (TO-252)  
- Componentes pasivos: capacitores, resistencias, diodos  
- Electrónica básica / diseño de PCB

---

## Descripción

El circuito permite regular la tensión de salida mediante un potenciómetro conectado al pin ADJ del LM317.  
Se incorporan diodos de protección para evitar daños por polarización inversa o cortocircuitos.  
El diseño incluye conectores de entrada/salida, filtrado capacitivo y layout compacto para futura fabricación.

---

### Objetivo

Diseñar una placa reguladora de voltaje con protección mediante diodos, aplicando el flujo completo de trabajo en KiCad: esquemático, asignación de footprints, ruteo de pistas y generación de archivos Gerber.  
El proyecto busca consolidar conocimientos de electrónica básica y diseño de PCB, y quedará disponible para su reutilización y mejora futura.

---

> 🧩 Este proyecto está en desarrollo y se actualizará con el diseño de PCB, simulaciones y archivos finales.
