# 🩸 Guía Técnica de Supervivencia: Mecánicas y Optimización en Bloodborne

![Imagen Bloodborne](https://cdna.artstation.com/p/assets/images/images/037/696/352/large/alhin-row-horsemoonglowstickbuttholeheadwitheyesinitv3.jpg?1621069158)

Esta documentación técnica tiene como **objetivo principal** instruir a los nuevos jugadores en los sistemas mecánicos internos, matemáticos y operativos de *Bloodborne*. A través de este manual, el usuario aprenderá a gestionar los recursos de combate, optimizar los atributos de su personaje y dominar el sistema de contraataques para garantizar su supervivencia en la ciudad de Yharnam.

---

## 📌 Índice de Contenidos
1. [Glosario de Atributos del Cazador](#1-glosario-de-atributos-del-cazador)
2. [Protocolo Operativo de Combate](#2-protocolo-operativo-de-combate)
3. [El Sistema de Regresión de Salud](#3-el-sistema-de-regresión-de-salud)
4. [Gestión y Peligros de la Lucidez](#4-gestión-y-peligros-de-la-lucidez)
5. [Recursos de Referencia Externa](#5-recursos-de-referencia-externa)

---

## 1. Glosario de Atributos del Cazador

Para estructurar una *build* eficiente, es fundamental comprender el impacto exacto de cada estadística y sus límites de rendimiento decreciente conocidos como *soft caps* (punto donde la estadística empieza a aportar menos beneficio por nivel invertido):

| Atributo | Límite Técnico (*Soft Cap*) | Impacto Directo en el Personaje |
| :--- | :--- | :--- |
| **Vitalidad** | 30 / 50 Puntos | Incrementa la barra de Puntos de Salud (PS) totales. |
| **Brío** | 40 Puntos | Aumenta la barra de energía (*Stamina*) y resistencias. |
| **Fuerza** | 25 / 50 Puntos | Multiplica el daño físico escalado en armas pesadas. |
| **Habilidad** | 25 / 50 Puntos | Multiplica el daño físico rápido y el daño crítico visceral. |
| **Viveza de Sangre** | 25 / 50 Puntos | Determina el daño de los proyectiles y armas de sangre. |
| **Arcano** | 25 / 50 Puntos | Modifica el daño de fuego, rayo y herramientas mágicas. |

---

## 2. Protocolo Operativo de Combate

El sistema de combate está diseñado bajo un algoritmo de agresión donde la defensa pasiva es penalizada. Para ejecutar la técnica avanzada de interrupción (*Parry*) y su posterior ataque crítico, debes seguir estos pasos de manera secuencial:

### Pasos para realizar un Ataque Visceral:
1. Equipa un arma de fuego en tu mano izquierda (por ejemplo, la *Pistola de cazador*).
2. Fija el objetivo enemigo presionando el botón `R3` en el mando de control.
3. Espera a que el enemigo inicie la fase activa de su animación de golpe (cuando el ataque va hacia ti).
4. Presiona el botón `L2` para disparar el proyectil de mercurio de forma precisa.
5. Escucha el efecto de sonido metálico que indica la interrupción exitosa del rival.
6. Acércate inmediatamente al enemigo de pie y ejecuta un golpe crítico pulsando `R1`.

---

## 3. El Sistema de Regresión de Salud

Una de las mecánicas más innovadoras del software de juego es el *Regain System*. Cuando un enemigo logra infligir daño a tu barra de vida, esta no se reduce de manera permanente al instante.

![Mecánica de combate en Bloodborne](https://unsplash.com)

### Características del sistema:
* **Ventana de respuesta:** Se activa una barra de color naranja temporal que dura exactamente **5 segundos**.
* **Recuperación dinámica:** Cada golpe exitoso que devuelvas con tu arma principal rellenará una fracción del espacio naranja.
* **Optimización:** Esto permite ahorrar consumibles médicos como los viales de sangre si juegas de manera ofensiva.

---

## 4. Gestión y Peligros de la Lucidez

La Lucidez (*Insight*) es una divisa e indicador dinámico en la esquina superior derecha que altera el renderizado y los scripts del mundo físico del videojuego. 

> ⚠️ **ADVERTENCIA DE SEGURIDAD:** Acumular un valor excesivo de Lucidez (superior a 15 puntos) reduce críticamente la resistencia al estado de *Frenesí* y añade modificadores de dificultad secreta a los enemigos comunes del mapa.

Si necesitas vaciar el contador debido a este riesgo informático, debes ejecutar el siguiente comando lógico en el menú de la tienda del Sueño del Cazador:

> IF (Lucidez >= 10) THEN
> Comprar_Bloque_Material(Pedazo_Bloque_Sangre);
> Reducir_Contador_Lucidez(10);
> ENDIF
---

## 5. Recursos de Referencia Externa

Para profundizar en los datos numéricos y las hojas de cálculo optimizadas de todas las armas y mazmorras generadas por el juego, puedes consultar los siguientes portales de la comunidad:

* Visita la enciclopedia de la comunidad en la [Bloodborne Wiki Oficial en Fandom](https://fandom.com).
* Consulta los foros de análisis en Reddit mediante la etiqueta `r/bloodborne`.
---

*Documentación técnica elaborada bajo la licencia del Taller de los Viejos Cazadores.*

