# Ferramenta Excel para Organização de IR

Este repositório contém os dados e (potencialmente) scripts relacionados a uma ferramenta desenvolvida no Excel para auxiliar na **organização e reunião de informações essenciais para a declaração de Imposto de Renda (IR)**. O objetivo é simplificar o processo de coleta e consolidação dos dados necessários para preencher a declaração anual.

## Estrutura dos Dados

Os arquivos CSV contidos neste repositório representam diferentes seções ou tipos de informações que seriam consolidadas pela ferramenta Excel. Eles são derivados de abas de uma planilha mestra (`Ferramenta_IR.xlsx`, por exemplo).

* `Ferramenta_IR - TITULAR.csv`: Contém informações pessoais e cadastrais do titular da declaração.
* `Ferramenta_IR - INFORMES.csv`: Pode incluir dados de informes de rendimentos, extratos bancários, demonstrativos de investimentos, etc.
* `Ferramenta_IR - NOTAS.csv`: Possivelmente abrange informações de notas fiscais de serviços médicos, recibos de despesas dedutíveis, notas de corretagem (para investimentos), etc.
* `Ferramenta_IR - TABELAS.csv`: Provavelmente contém tabelas de referência, como códigos de bens e direitos, tipos de rendimentos, despesas dedutíveis, ou outras classificações úteis para o IR.

## Objetivo do Projeto

O principal objetivo deste projeto é:

* **Centralizar e organizar** dados dispersos em diferentes documentos e fontes para a declaração de Imposto de Renda.
* **Simplificar a coleta** de informações cruciais, como rendimentos, bens, dívidas, pagamentos e recebimentos.
* **Facilitar a conferência** e a preparação dos dados antes do preenchimento da declaração oficial da Receita Federal.
* (Adicione outros objetivos específicos aqui, como "Automatizar cálculos básicos de IR", "Identificar oportunidades de dedução", etc.)

## Como Usar (Exemplo - Adapte se houver scripts ou análises)

1.  **Acesso aos Dados:** Os arquivos CSV fornecidos são a base de dados que a ferramenta Excel (não incluída neste repositório como um arquivo .xlsx executável, mas como uma representação de seus dados) processaria.

2.  **Pré-requisitos:**
    * Microsoft Excel (ou software compatível para abrir e manipular planilhas).
    * (Se houver scripts Python para pré-processamento/análise) Python 3.x
    * (Se houver scripts Python) Bibliotecas Python como `pandas` (para manipulação de dados).

3.  **Estrutura de Pastas (Sugestão para o projeto completo, se aplicável):**
    * `data/`: Onde os arquivos CSV brutos (como os presentes neste repositório) seriam armazenados.
    * `excel_tool/`: Onde o arquivo `.xlsx` da ferramenta Excel propriamente dita (se for adicionado) ficaria.
    * `scripts/`: Onde quaisquer scripts de automação, limpeza ou análise de dados seriam colocados.
    * `documentation/`: Para manuais de uso ou outras documentações da ferramenta.

4.  **Uso da Ferramenta Excel (Conceptual):**
    A ferramenta Excel seria projetada com abas e fórmulas para importar ou referenciar estes dados, permitindo a organização visual e a consolidação das informações para o IR. Os usuários preencheriam ou importariam seus próprios dados para a planilha.
