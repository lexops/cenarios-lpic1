# Exercícios Guiados
4. Um administrador deseja experimentar parâmetros diferentes para o módulo do kernel `bluetooth` sem reiniciar o sistema. No entanto, qualquer tentativa de descarregar o módulo com modprobe -r bluetooth resulta no seguinte erro:

```
modprobe: FATAL: Module bluetooth is in use.
```
Qual a possível causa desse erro?

<details>
<summary><strong>Respostas aos Exercícios Guiados</strong></summary>

O módulo `bluetooth` está sendo usado por um processo em execução.

</details>