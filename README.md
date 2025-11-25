# 🔬 Scientific Validation Hub

> **O Arsenal Definitivo para Validação Científica em IA e Data Science.**
> Um hub modular de ferramentas ("Legos") para garantir rigor, reprodutibilidade e densidade semântica em projetos de pesquisa.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Scientific Validation](https://img.shields.io/badge/Validation-Rigor_1.0-blue)](https://doi.org/10.5281/zenodo.XXXXXXX)

---

## ✨ Inovações Nativas (SLE Tools)

Ferramentas exclusivas desenvolvidas sob o framework **Semantic Latent Engineering (SLE)** para validação de agentes e prompts. Estas ferramentas não existem no mercado tradicional.

| Ferramenta | Descrição | Status de Validação | Executar Agora |
| :--- | :--- | :---: | :---: |
| **🔍 Semantic Density (SD)** | Valida a densidade informacional e precisão vetorial de prompts e agentes. | ![Pass](https://img.shields.io/badge/Scientific_Validation-PASSING-success) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aleeepassarelli/scientific-validation-hub/blob/main/notebooks/sd_validator.ipynb) |
| **🧠 Behavior Contract (CCC)** | Auditoria de aderência à missão e consistência de persona (Mission Adherence). | ![Pass](https://img.shields.io/badge/Adherence_Status-PASS-success) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aleeepassarelli/scientific-validation-hub/blob/main/notebooks/behavior_validator.ipynb) |

---

## 🏗️ O Arsenal (Padrão de Indústria)

Uma curadoria "Ultra Hard" (Rigor 1.0) das melhores ferramentas do mercado, organizadas por função. Use como módulos independentes.

### ✅ Experiment Tracking ML/AI
* **[MLflow](https://mlflow.org)** (General) - Gerenciamento de ciclo de vida completo.
* **[Weights & Biases](https://wandb.ai)** (Collaboration) - Visualização e tracking para times.
* **[ClearML](https://clear.ml)** (Autologging) - Orquestração e automação mágica.
* **[Sacred](https://github.com/IDSIA/sacred)** (Academic) - Configuração estrita para papers.

### ✅ Workflow Management
* **[Nextflow](https://www.nextflow.io)** (Bioinformatics/HPC) - Pipelines escaláveis baseados em dataflow.
* **[Snakemake](https://snakemake.readthedocs.io)** (Python-centric) - Reprodutibilidade via regras Python.
* **[CWL](https://www.commonwl.org)** (Interoperability) - Standard para portabilidade de workflows.

### ✅ Data Versioning & Provenance
* **[DVC](https://dvc.org)** (Git-like) - Versionamento de dados grandes em cima do Git.
* **[ReproZip](https://www.reprozip.org)** (OS-level) - Empacotamento de todo o ambiente OS.
* **[RO-Crate](https://www.researchobject.org/ro-crate)** (Packaging) - Metadata FAIR para objetos de pesquisa.

### ✅ Peer Review & Reproducibility
* **[OpenReview](https://openreview.net)** (Conferences) - Revisão por pares aberta e transparente.
* **[Zenodo](https://zenodo.org)** (Archiving) - DOIs permanentes para datasets e código.
* **[nbval](https://github.com/computationalmodelling/nbval)** (Testing) - Validação unitária de Jupyter Notebooks.

---

## 🚀 Como Usar (Conceito Lego)

Este hub foi desenhado para ser consumido de duas formas:

### 1. Uso Imediato (Colab)
Para ferramentas nativas (SD e Behavior), clique no botão **Open in Colab** na tabela acima. Isso abrirá um notebook configurado pronto para validar seus inputs sem instalação local.


## ⚡ Quick Start: O Protocolo Zero-Barreira

Não sabe programar? Sem problemas.
Utilize o **Gemini Assistant** embutido no Google Colab para validar os testes e gerar suas badges automaticamente.

**O Fluxo de 4 Passos:**

1.  **Abra o Notebook:** Clique no botão `Open in Colab` da ferramenta desejada (tabela acima).
2.  **Cole o Código:** O código já estará lá, ou cole o bloco fornecido na documentação.
3.  **Invoque o Auditor:** Clique no ícone do Gemini (✨) no canto do Colab e cole o **Prompt de Validação** (abaixo).
4.  **Receba o Badge:** O Gemini executará os testes, interpretará os logs e te entregará o código Markdown do badge se for aprovado.

---

### 🤖 O Prompt de Validação (Copie e Cole no Gemini)

Para validar qualquer ferramenta deste hub, use este comando padrão no assistente do Colab:

> "Atue como um Engenheiro de Validação Científica (QA).
> 1. Analise o código da célula ativa.
> 2. Execute o código e capture os outputs (logs de SD, Aderência ou Métricas).
> 3. Interprete os resultados:
>    - Se o status for 'PASS' ou 'EXCELLENT', confirme a validação.
>    - Se for 'FAIL', explique resumidamente o motivo matemático (ex: entropia alta, deriva vetorial).
> 4. Se aprovado, gere um snippet de código Markdown com um Badge verde escrito 'SCIENTIFIC VALIDATION: PASSING'."

### 2. Integração Modular (Git Submodule)
Para incorporar o arsenal completo em seu projeto de pesquisa:

```bash
git submodule add [https://github.com/aleeepassarelli/scientific-validation-hub.git](https://github.com/aleeepassarelli/scientific-validation-hub.git) arsenal
```
A Estratégia dos Notebooks ("Self-Driving Notebooks")
Para os seus notebooks .ipynb no repositório (notebooks/sd_validator.ipynb, etc.), sugiro que a primeira célula não seja código, mas sim uma Célula de Texto (Instrução).

Isso garante que, assim que a pessoa abrir, ela saiba o que fazer.

Exemplo de Cabeçalho para o Notebook sd_validator.ipynb:

# 🔬 Validador de Densidade Semântica (SD)

**Autor:** Scientific Validation Hub
**Status:** Ready for Audit

### 🛑 Instruções para Não-Programadores
Você não precisa rodar isso manualmente. Deixe a IA fazer o trabalho pesado.

1.  Certifique-se de que o **Gemini** está ativado neste notebook (ícone ✨ no topo direito).
2.  Vá até a célula de código abaixo onde estão as variáveis `name_to_test` e `domain_to_test`.
3.  Altere os textos entre aspas para o seu Agente/Prompt.
4.  Abra o chat do Gemini e digite:
    > *"Valide este teste para mim, execute o código e me diga se meu agente tem densidade suficiente para produção."*


