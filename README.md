---
website: "PRR - Municipio da Madeira - Pack 3"          # Entre as aspas escreve o nome do website
date: "23/02/2026"                    # Entre as aspas escreve a data de criação do 1º relatório. Os restantes estão no histórico
uri: "https://www.cm-sjm.pt/pt/acessibilidade, https://www.museu-do-calcado.pt/pt/acessibilidade, https://www.museudachapelaria.pt/pt/acessibilidade"   # Entre as aspas escreve o domínio do website
owner: "Câmara Municipal de São João da Madeira"         # Entre as aspas escrever o nome do owner do website
seal: "Prata"                          # Entre as aspas escreve Bronze, Prata ou Ouro
---

# {{ page.website }}

- Data de criação: {{ page.date }}
- URL: {{ page.uri }}
- Propriedade: {{ page.owner }}
- Candidatura: {{ page.seal }}

## Relatório de Auditoria

Consulte aqui a última atualização: [Relatório do {{ page.website }}](report.html)

<details>
  <summary>Histórico de atualizações</summary>
  <ul aria-label="lista de relatórios já efetuados">
    <li><a href="ddmmaaaa_report.html">(dd/mm/aaaa). Relatório do {{ page.website }}</a></li>
  </ul>
</details>

## Lista de websites incluídas na análise:
- https://www.cm-sjm.pt/pt/acessibilidade
- https://www.museu-do-calcado.pt/pt/acessibilidade
- https://www.museudachapelaria.pt/pt/acessibilidade
