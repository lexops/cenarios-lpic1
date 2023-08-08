# Exercícios Exploratórios
4. Em 2018, a vulnerabilidade de hardware conhecida como Meltdown foi descoberta. Ela afeta quase todos os processadores de diferentes arquiteturas. As versões mais recentes do kernel Linux podem informar se o sistema atual está vulnerável. Como obter essas informações?

<details>
<summary><strong>Respostas aos Exercícios Guiados</strong></summary>

O arquivo `/proc/cpuinfo` tem uma linha que mostra os bugs conhecidos para a CPU correspondente, como por exemplo 
```
bugs: cpu_meltdown
```

</details>