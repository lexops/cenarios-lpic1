A linha a seguir faz parte da saída gerada pelo comando `lspci`:

```
03:00.0 RAID bus controller: LSI Logic / Symbios Logic MegaRAID SAS 2208 [Thunderbolt] (rev 05)
```
Qual comando deve ser executado para identificar o módulo do kernel em uso neste dispositivo específico?

<details>
<summary>Respostas</summary>

O comando `lspci -s 03:00.0 -v`{{exec}} ou `lspci -s 03:00.0 -k`{{exec}}

</details>