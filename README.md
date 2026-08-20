# GUERRA DE BANDAS INFINITA - BIBLIA TÉCNICA COMPLETA

**Fundador:** Samuel Morales Quintero (Samuel-TKG) - Medellín, Agosto 2026  
**Licencia:** AGPL-3.0 - Proyecto Inmortal Open Source - Prior Art  
**Objetivo:** 1000+ Jugadores Online | Estilo GTA San Andreas | Low-Poly Optimizado  

---

## 1. Manifiesto: Optimización Total, Cero Basura
Este proyecto nace bajo la premisa de rechazar el bloatware visual de la industria actual. 
* **Cero partículas innecesarias:** Una explosión es un **punto de luz amarillo**. El cerebro procesa el impacto al instante; el humo, las chispas masivas y los escombros flotantes solo queman FPS.
* **Geometría Funcional:** Si un elemento no sirve para pelear, conquistar o moverse, no existe. Cero mochilas o accesorios de relleno.
* **Modelos Legibles (Modo Alien y Progresivo):** Personajes flaquitos y limpios. Cada banda lleva un color fijo e inconfundible (gorra, buzo, pantalón, zapatos, tapabocas/pañoleta gánster y guantes del mismo tono). Los equipos de menores recursos pueden usar versiones puramente sólidas sin texturas ni detalles de piel, maximizando el rendimiento del GPU Instancing.
* **Requisito de Rendimiento:** Debe correr fluidamente en una "tostadora" o en un celular de gama baja de 2019. Si corre ahí, soporta los 1,000 jugadores en red.

---

## 2. Core Loop: Guerra Continua y Respawn Instantáneo
* **Cero Esperas:** Si mueres, **no hay pantallas de carga ni tiempos muertos**. 
* **Respawn Inmediato:** Te abaten en medio de la refriega, apareces instantáneamente en tu casa capital y vuelves al combate. La guerra es infinita y constante.

---

## 3. Arquitectura del Mundo y Escalabilidad Infinita
El mapa está diseñado con una estructura modular que permite una **expansión infinita**, donde la cantidad de ciudades y jugadores depende exclusivamente de la capacidad del hardware (tanto en PCs como en Celulares):

* **Mapa Base (Estándar):** 5 Grandes Ciudades estilo *GTA San Andreas* (4 ubicadas en las esquinas del mapa y 1 central), interconectadas por una red de calles de 4 carriles y zonas rurales con pueblitos de bajo poligonaje (aproximadamente 100 polígonos por casa).
* **La Autopista de 12 Carriles:** El eje central que une las zonas urbanas. Es la zona de guerra principal para vehículos rápidos (carros, motos y camionetas con torretas), sin semáforos y con tráfico masivo de colores.
* **Escalabilidad Dinámica por Hardware:**
  * **Servidor Tostadora:** 1 sola ciudad compacta de guerra total (con economía, territorios y policía).
  * **Servidor Medio:** 2 a 3 ciudades conectadas.
  * **Servidor NASA (PC Gamer):** Las 5 ciudades completas + pueblitos periféricos y expansión ilimitada.
* **Arquitectura de Servidores en Enjambre (Servidores Infinitos):** El mundo persiste de forma independiente. Si entras, conquistas barrios y te vas, ese territorio sigue activo en el servidor. Cuando un servidor alcanza su límite de 1,000 jugadores, el sistema crea automáticamente un servidor nuevo y limpio con 0% conquistado, evitando colas y asegurando que siempre haya una guerra fresca.

---

## 4. Facciones, Bandas y Sistema Policial Dinámico

### Bandas y Respawn Táctico
* **Casas Capitales Móviles:** Las bandas pueden reubicar su casa de respawn cada 60 segundos por estrategia táctica y en cada territorio nuevo conquistado, a donde quieran, no está limitada al barrio inicial. La policía no puede hacerlo ya que tiene su gran edifico en la mitad de cada ciudad Con todas sus armas, carros, camionetas y motos también helicópteros y aviones de guerra pequeños pero poderosos. La idea es introducir aviones grandes que si la policía o una banda logran comprar o se lo roban a la policía, muchos jugadores puedan viajar hacia el aeropuerto de cualquier ciudad. 

* **Destrucción de Facciones:** Si una banda pierde su capital, todo su dinero acumulado pasa a manos de la facción vencedora. Los miembros derrotados tienen un margen de 10 segundos para elegir un nuevo bando. Si pasa el tiempo sin elegir, el sistema los reasigna automáticamente a la policía o a otra banda con espacio.

### La Policía (Facción de Élite Escalable)
* **Población Controlada:** Ocupa un máximo fijo del 50% de la población del servidor, dividida entre las ciudades con una Gobernación / Capital Policial fija en el centro.
* **Persecución Progresiva:** Si un miembro roba un banco, la policía persigue inicialmente solo a ese individuo; si logra escapar a su base con el botín y lo deposita allí, la persecución escala a toda la banda, pero si logra guardarlo por un cajero a du cuenta bancaria, es suyo. 
* **Siempre tienen armas:**Si conquistan y mantienen más territorios desbloquean mejoras de Armas más poderosas, helicópteros, jets de guerra y tanques blindados. 

* **Sistema de Expulsión Épico:** Si las bandas logran limpiar de policías una ciudad, la policía **no desaparece**: se repliega y concentra en las ciudades restantes, haciéndo más fuerte a la policía en las demás ciudades y la banda se vuelve muy fuerte, con mucho dinero. Si las bandas logran expulsar a la policía de las 5 ciudades, esta es exiliada al borde del mapa con equipamiento básico, obligándolos a reconquistar el terreno a pie.

---

## 5. Economía, Territorios y Logística
* **Conquista de Barrios:** Cada barrio tiene un punto central. Mantenerse allí durante 60 segundos otorga el control del territorio (tanto para bandas como para la policía).
* **Recolección de Dinero:** con Elección 
  * Manual (lo hacen los jugadores) 
  * Automatizada mediante unidades robóticas: carritos pequeños (rápidos pero frágiles), camionetas blindadas (lentas pero resistentes) o con robots armados (defensivos pero de mayor costo y menor velocidad. 
* O personalizable a carro rápido con hombres armados, o en motos, y todos pueden ir a recolectar dinero de sus barrios. 

* **Asaltos a Bancos con Alerta Global:** Al iniciar un robo bancario, una notificación aparece en todo el servidor (*"Banda X asaltando el banco central"*), provocando que las fuerzas policiales y bandas rivales converjan en el lugar.
* **Capital Privado vs. Dinero de Banda:** Cada usuario posee dinero de facción y dinero privado. A través de cajeros automáticos o bancos, se puede consignar dinero de forma segura para protegerlo en caso de que la banda caiga en bancarrota, permitiendo comprar equipamiento personal de forma independiente.

---

## 6. NPCs, Farmeo y Combate
* **Transeúntes (NPCs):** Calles habitadas por ciudadanos y policías de patrulla. 
* **Regla de Interacción:** Golpear a un NPC no genera repercusiones policiales mayores. Matarlo permite farmear dinero y armas directamente, lo que activa inmediatamente la respuesta letal de la policía cercana.

---

## 7. Hoja de Ruta del Desarrollo (Godot Engine)

### Fase 1: Núcleo Single-Player (Offline Baseline)
- [ ] Implementar movimiento, físicas de vehículos basadas en vectores y cámara en primera/tercera persona.
- [ ] Desarrollar la inteligencia artificial básica de NPCs y patrullaje policial.
- [ ] Construir la economía local (cajeros interactivos, tiendas y persistencia en archivos locales).

### Fase 2: Red y Multijugador Escalable
- [ ] Integración de protocolos de red UDP ligeros y eficientes.
- [ ] Implementación de filtrado y culling del lado del servidor para soportar alta densidad en la autopista de 12 carriles.
- [ ] Pruebas de estrés y rendimiento en entornos de hardware de bajos recursos.

---
*ESTO ES PRIOR ART - PUBLICADO AGOSTO 2026 - SAMUEL-TKG*
