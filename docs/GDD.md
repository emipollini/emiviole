[GDD.md](https://github.com/user-attachments/files/32561802/GDD.md)
SECCIÓN I: ASPECTOS GENERALES DEL PROYECTO  
1\. Título del Videojuego  
Gol de Oro  
2\. Concepto de Alto Nivel (High Concept)  
Gol de Oro es un videojuego deportivo 2D desarrollado para PC utilizando Godot Engine,  
en el que el jugador representa a la Selección Argentina en un mini torneo de penales. El  
objetivo es superar tres rondas consecutivas convirtiendo al menos tres goles de cinco  
intentos en cada una, enfrentando arqueros con una dificultad creciente. El juego utiliza una  
estética simple y colorida, con una única cancha y controles fáciles de aprender.  
3\. Plataforma y Audiencia  
Plataforma  
● PC (desarrollado con Godot Engine).  
Audiencia  
El juego está dirigido a jugadores de todas las edades que disfrutan de partidas rápidas y  
sencillas. Su temática basada en el fútbol y sus controles simples permiten que cualquier  
persona pueda jugar sin experiencia previa.  
SECCIÓN II: CORE GAMEPLAY (REGLAS  
Y MECÁNICAS)  
1\. Condición de Victoria  
El objetivo del juego es ganar el mini torneo de penales.  
Para avanzar de ronda, el jugador debe convertir al menos 3 goles de 5 penales.  
El torneo está compuesto por tres enfrentamientos:  
● Primera Ronda: Argentina vs. México.  
● Semifinal: Argentina vs. Brasil.  
● Final: Argentina vs. Francia.  
Si el jugador supera las tres rondas, se convierte en campeón del torneo.  
2\. Condición de Derrota  
Si el jugador convierte menos de tres goles en una ronda, pierde ese enfrentamiento y  
deberá repetir la misma ronda hasta lograr la clasificación.  
3\. Ciclo de Juego (Core Loop)  
El jugador observa la posición del arquero, elige la dirección del disparo y la potencia,  
ejecuta el penal y espera el resultado. Al finalizar los cinco intentos, el juego verifica si se  
alcanzaron al menos tres goles para avanzar a la siguiente ronda. Este proceso se repite  
hasta ganar el torneo.  
4\. Controles  
Acción Control  
Mover la dirección del disparo A / D o Flechas Izquierda / Derecha  
Cargar la potencia Mantener Barra Espaciadora  
Ejecutar el disparo Soltar Barra Espaciadora  
Descripción del Escenario  
El juego se desarrolla en una única cancha de fútbol vista de frente.  
En la parte inferior se encuentra el jugador junto a la pelota ubicada en el punto penal.  
En la parte superior se encuentra el arquero defendiendo el arco.  
El escenario permanece igual durante toda la partida. Lo único que cambia entre rondas es  
el arquero, cuya velocidad de movimiento aumenta para representar una mayor dificultad.  
No existen cambios de mapa ni generación aleatoria de escenarios, manteniendo un  
alcance reducido y adecuado para el proyecto.  
Mecánicas Principales  
Jugador  
El jugador controla al pateador.  
Puede:  
● Elegir la dirección del disparo.  
● Controlar la potencia.  
● Ejecutar el penal.  
Cada disparo consume uno de los cinco intentos disponibles.  
Pelota  
La pelota sigue la dirección y la potencia elegidas por el jugador.  
Si atraviesa el arco sin ser detenida, se suma un gol.  
Si el arquero la ataja o el disparo sale fuera del arco, el intento se considera fallido.  
Arquero  
El arquero se desplaza horizontalmente sobre la línea del arco intentando detener la pelota.  
Su velocidad aumenta en cada ronda del torneo para incrementar la dificultad.  
● México: velocidad baja.  
● Brasil: velocidad media.  
● Francia: velocidad alta.  
Estética  
Gol de Oro presenta un estilo gráfico simple y minimalista.  
Se utilizarán colores vivos y una interfaz clara para facilitar la lectura de la información  
durante la partida.  
Los elementos principales del escenario serán:  
● Cancha de fútbol.  
● Arco.  
● Arquero.  
● Jugador.  
● Pelota.  
● Marcador de goles.  
● Indicador de penales restantes.  
● Nombre de la selección rival.  
Integrantes del grupo:  
Emiliano Pollini  
Violeta leotta
