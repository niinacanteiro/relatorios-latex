# 📐 Relatórios Técnicos em LaTeX

Relatórios e materiais que escrevi em LaTeX (Overleaf) durante o Bacharelado em Engenharia Elétrica no IFMT, Campus Pontes e Lacerda.

Cada pasta tem o código-fonte (`main.tex`), as imagens usadas e o PDF compilado.

| Pasta | O que é | Destaques de LaTeX |
|---|---|---|
| [`circuitos-ii-carga-descarga-rc`](circuitos-ii-carga-descarga-rc) | Carga e descarga de capacitor em circuito RC (Circuitos Elétricos II) | `circuitikz`, `pgfplots`, caixas de cálculo com `tcolorbox` |
| [`circuitos-ii-psim-iii`](circuitos-ii-psim-iii) | Simulações no PSIM (Circuitos Elétricos II) | `circuitikz`, `tcolorbox`, sumário com `tocloft` |
| [`circuitos-motor-gaiola-esquilo`](circuitos-motor-gaiola-esquilo) | Motor de indução tipo gaiola de esquilo | `booktabs`, `longtable`, `hyperref`, macros de metadados |
| [`lista-exercicios-circuitos`](lista-exercicios-circuitos) | Lista de exercícios de circuitos em duas colunas | comandos personalizados, `circuitikz` |
| [`revisao-metodos-computacionais`](revisao-metodos-computacionais) | Revisão de Métodos Computacionais | `amsmath`, documento enxuto |
| [`manual-tinkercad-semaforo-arduino`](manual-tinkercad-semaforo-arduino) | Manual de semáforo com Arduino no Tinkercad (projeto de extensão) | desenho em `TikZ`, código Arduino |

## Como compilar

Abra a pasta no [Overleaf](https://www.overleaf.com) ou compile localmente:

```bash
pdflatex main.tex
pdflatex main.tex
```

> Os trabalhos em grupo foram feitos com colegas de turma. Por privacidade, os nomes deles, o do professor e as fotos de laboratório foram retirados desta versão pública.
