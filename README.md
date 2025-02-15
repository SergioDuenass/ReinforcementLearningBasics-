# Reinforcement Learning Basics

El código entrena a un agente para jugar al Blackjack utilizando un modelo de red neuronal simple para aproximar los valores Q. El agente usa una política epsilon-greedy, donde al principio explora más y gradualmente comienza a explotar lo aprendido para maximizar las recompensas.

Estructura del Código
* QNetwork: Una clase que define la red neuronal utilizada para aproximar los valores Q.
* epsilon_greedy_policy: Función que implementa la política de exploración y explotación.
* train(): Función principal que entrena al agente utilizando Deep Q-Learning.

Resultados
El agente se entrena durante 5000 episodios. Los resultados pueden verse en los logs, donde se imprime la recompensa total y el valor de epsilon para cada 100 episodios.


## Requisitos

El código requiere las siguientes librerías de Python:

- gymnasium==0.26.1
- numpy==1.21.0
- torch==1.12.1

Puedes instalar estas dependencias usando el archivo `requirements.txt`:

```bash
pip install -r requirements.txt
