# explore_stage03b

## Responsividade

- Introdução à responsividade - 01:06
- Estruturando o HTML - 03:01
- Regra mobile-first - 04:22
- Regra das unidades de medidas flexíveis - 08:08
- Continuando ajustes de textos - 08:58
- Finalizando ajustes da versão mobile - 06:38
- Versão Desktop - 14:24
- Finalizando essa etapa - 02:30

## REM

- REM = Root RM
- 1rem = 16px
<pre>
16px ------ 100%
10px ------  X
X = 10x100/16 = 62.5%

---

:root {
font-size: 62.5%;
}

</pre>

## Media queries

- @media
- (min-width: 500px)