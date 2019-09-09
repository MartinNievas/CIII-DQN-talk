# Deep Reinforcement Learning talk and calibration
Slides de la charla sobre DRL y calibración dada en el CIII.

Parte de los slides son sacados de los cursos de la ECI 2019, y adaptados para una charla de 1 hora.

Material original DRL: [Juan Gomez Romero](https://github.com/jgromero/eci2019-DRL)

## Práctica
Los notebook contienen ejemplos de un agente que "aprende" a resolver tareas.
### CartPole
El primero es cartpole, es un ejemplo clásico de teoría de control (péndulo invertido).
El entorno virtual será [CartPole-v0](https://github.com/openai/gym/blob/master/gym/envs/classic_control/cartpole.py) de [OpenAI](https://openai.com). 

![](https://github.com/martinnievas/CIII-DQN-talk/blob/devel/cartpole.gif?raw=true)

```bash
$ DQN_cartpole.ipynb
```
### LunaLander
El segundo es lunalander. Una nave espacial "aprende" a estabilizar su vuelo y aterrizar en la zona indicada.

En este ejercicio utilizamos el entorno virtual [LunarLander-v2](https://gym.openai.com/envs/LunarLander-v2/) de [OpenAI](https://openai.com). 

![](https://github.com/martinnievas/CIII-DQN-talk/blob/devel/lunarlander.gif?raw=true)

```bash
$ DQN_lunalander.ipynb
```
