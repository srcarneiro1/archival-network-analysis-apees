# Archival Network Analysis — APEES

**PT-BR** | [English](#english)

## Sobre a pesquisa

Este repositório reúne materiais de pesquisa associados ao estudo **“A manutenção do vínculo arquivístico e do vínculo informacional a partir da análise de redes de informação: um estudo aplicado no acervo histórico de inquéritos policiais do Arquivo Público do Estado do Espírito Santo — APEES”**.

O acervo de trabalho inclui uma planilha de dados, arquivos de redes e diferentes versões de projetos do Gephi, além de um arquivo de projeto do OpenRefine. A documentação descreve os materiais disponibilizados, sem afirmar que os resultados são integralmente reproduzíveis apenas com estes arquivos.

## Materiais disponíveis

Os arquivos estão **na raiz do repositório**, e não em uma pasta `data/`.

| Arquivo ou grupo | Formato | Finalidade |
| --- | --- | --- |
| `[Base de dados] APEES Fundo Inqueritos Policiais [possuí código GML e tabela do vocabulário controlado].xlsx` | XLSX | Planilha de dados da pesquisa, com abas descritas na documentação original como base final dos inquéritos, padronização de termos e GML |
| `Rede de Inquéritos.gml` | GML | Representação de rede para análise em ferramentas compatíveis |
| `Rede de Inquéritos.txt` | TXT | Arquivo textual relacionado à rede |
| `Rede de Inquéritos.gephi`, `Rede de Inquéritos_v2.gephi`, `Rede de Inquéritos_v3.gephi` a `Rede de Inquéritos_v7.gephi` | GEPHI | Versões dos projetos de análise e visualização de redes |
| `Rede de Inquéritos [vitima-acusado].gephi` | GEPHI | Projeto identificado pelo recorte vítima–acusado no nome do arquivo |
| `APEES-Fundo-Inqueritos-Policiais-[final]-xlsx.openrefine.tar.gz` | TAR.GZ | Arquivo de projeto associado ao OpenRefine |

> Os nomes e extensões acima refletem os arquivos existentes no repositório. A descrição das abas da planilha deriva do README anterior e não substitui a conferência direta dos dados.

## Acesso e exploração

Clone o repositório:

```bash
git clone https://github.com/srcarneiro1/archival-network-analysis-apees.git
cd archival-network-analysis-apees
```

- **Planilha:** abra o arquivo `.xlsx` em um aplicativo compatível e examine as abas e seus dicionários ou padronizações disponíveis.
- **Rede:** importe o arquivo `.gml` em uma ferramenta de análise de redes compatível, como o Gephi.
- **Projetos:** abra os arquivos `.gephi` no Gephi, observando que diferentes versões podem representar etapas distintas do trabalho.
- **Tratamento de dados:** consulte o arquivo de projeto do OpenRefine em ambiente compatível; a disponibilidade do arquivo não comprova, por si só, a reexecução integral das transformações.

## Metodologia e reprodutibilidade

Os materiais se relacionam à organização de dados arquivísticos, padronização terminológica e análise de redes de informação. Para reproduzir ou avaliar os resultados com rigor, consulte também a publicação acadêmica correspondente e verifique as definições de nós, arestas, relações, filtros, versões de software e procedimentos de tratamento de dados. Esses parâmetros **não estão integralmente documentados neste README**.

## Uso responsável dos dados

O acervo envolve registros históricos de inquéritos policiais. Antes de redistribuir, combinar ou reutilizar dados individualizados, avalie a proveniência, as condições de acesso, os direitos aplicáveis e eventuais implicações de privacidade. **Nenhuma licença de reutilização é declarada neste repositório por este README.**

---

<a id="english"></a>
## English

### Research overview

This repository contains research materials associated with the study **“A manutenção do vínculo arquivístico e do vínculo informacional a partir da análise de redes de informação: um estudo aplicado no acervo histórico de inquéritos policiais do Arquivo Público do Estado do Espírito Santo — APEES.”**

The repository includes a research spreadsheet (`.xlsx`), a network exchange file (`.gml`), text data (`.txt`), multiple Gephi project versions (`.gephi`), and an OpenRefine-related project archive (`.tar.gz`). All files are stored at the repository root.

### Getting started

```bash
git clone https://github.com/srcarneiro1/archival-network-analysis-apees.git
cd archival-network-analysis-apees
```

Open the spreadsheet with a compatible application, inspect the GML network in a network-analysis tool such as Gephi, and open the Gephi project files to examine the saved project versions. The OpenRefine archive may require a compatible environment.

### Methods and reproducibility

The materials support the examination of archival records, terminology standardization, and information-network analysis. **Full computational reproducibility is not established by this README.** Consult the associated publication and verify node/edge definitions, filters, software versions, and data-processing procedures before drawing conclusions.

### Responsible data use

The dataset concerns historical police inquiry records. Review provenance, access conditions, applicable rights, and privacy implications before redistributing or reusing person-level data. This README does not grant a data-reuse license.
