# Archival Network Analysis - APEES

Este repositório contém dados, scripts e documentação relacionados ao estudo "Análise de Vínculo Arquivístico por Meio de Análise de Redes de Informação: Um Estudo de Caso em um Acervo Histórico de Inquéritos Policiais Custodiado pelo Arquivo Público do Estado do Espírito Santo".

## Conteúdo do Repositório

Os dados que constam neste repositório pertencem ao estudo de caso do APEES. A fonte de informação está no documento em formato `.xlsx` nomeado **"[Base de dados] APEES Fundo Inqueritos Policiais [possui código GML e tabela do vocabulário controlado]"**, que contém várias abas:
- **Base de Dados Final dos Inquéritos**: Dados finais utilizados para a análise.
- **Vocabulário Controlado**: Tabela contendo o vocabulário controlado utilizado no estudo.
- **GML**: Código GML relevante para a análise de redes.

Além da base de dados, o repositório inclui os arquivos do GEPHI nas suas versões desenvolvidas.

## Estrutura do Repositório

```
archival-network-analysis-apees/
│
├── data/
│   ├── APEES-Fundo-Inqueritos-Policiais-[final]-xlsx.openrefine.tar.gz
│   ├── [Base de dados] APEES Fundo Inqueritos Policiais [possuí código GML e tabela do vocabulário controlado].xlsx
│   ├── Rede de Inquéritos.txt
│   ├── Rede de Inquéritos.gml
│   ├── Rede de Inquéritos [vitima-acusado].gephi
│   ├── Rede de Inquéritos.gephi
│   ├── Rede de Inquéritos_v2.gephi
│   ├── Rede de Inquéritos_v3.gephi
│   ├── Rede de Inquéritos_v4.gephi
│   └── Rede de Inquéritos_v5.gephi
│
└── README.md
```

## Como Utilizar

1. **Clonar o Repositório**:
   ```bash
   git clone https://github.com/usuario/archival-network-analysis-apees.git
   cd archival-network-analysis-apees
   ```

2. **Explorar os Dados**:
   - Abra o arquivo `data/[Base de dados] APEES Fundo Inqueritos Policiais.xlsx` para acessar as diferentes abas com os dados dos inquéritos, vocabulário controlado e GML.
   - Os arquivos GEPHI nas versões desenvolvidas estão disponíveis.

## Contato

Para mais informações, entre em contato:
- **Autor**: Filipe Carneiro da Silva
- **Instituição**: Universidade Federal do Espírito Santo
- **E-mail**: filipecarneirodasilva@gmail.com
