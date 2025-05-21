# ⚡⚡ Análise Descritiva de Dados com o Dataset Pokémon 

Este repositório contém um Jupyter Notebook (`atividade1.ipynb`) e o dataset (`Pokemon.csv`) utilizado para uma aula introdutória sobre estatística descritiva em Python. O objetivo é guiar os alunos através da exploração de dados, cálculo de medidas de tendência central e dispersão, criação de tabelas de frequência, visualização de dados e análise de correlações.

## 🎯 Objetivos de Aprendizagem

Ao final desta atividade, os alunos serão capazes de:
* Carregar e inspecionar um conjunto de dados usando a biblioteca Pandas.
* Calcular e interpretar médias, medianas e modas.
* Calcular e interpretar variância, desvio padrão, amplitude e intervalo interquartil.
* Gerar e analisar tabelas de frequência para variáveis categóricas e numéricas (com classes).
* Criar e interpretar histogramas e boxplots para visualizar distribuições.
* Calcular e interpretar coeficientes de correlação e visualizar relações com gráficos de dispersão.
* Compreender o conceito básico de amostragem aleatória simples.
* Responder a perguntas analíticas baseadas nas estatísticas descritivas geradas.

## 📁 Arquivos no Repositório

Ao aceitar esta atividade, seu repositório conterá:
* `atividade1.ipynb`: O Jupyter Notebook com todas as instruções, código base para as análises e questões que você precisa responder.
* `Pokemon.csv`: O conjunto de dados com informações sobre 800 Pokémon.
* `README.md`: Este arquivo que você está lendo.

## 🛠️ Ferramentas e Bibliotecas Utilizadas

* Python 3.x
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy (para `stats.mode`)

## 🚀 Como Começar e Trabalhar na Atividade

1.  **Aceite a Atividade:**
    * Clique no link da atividade fornecido no GitHub Classroom.
    * Isso criará seu próprio repositório privado para esta tarefa, já com todos os arquivos necessários.

2.  **Acesse e Execute o Notebook:** Você tem algumas opções:

    * **Opção A: Ambiente Jupyter Local (na sua máquina)**
        1.  Copie a URL do SEU repositório da atividade no GitHub.
        2.  Clone o repositório para sua máquina:
            ```bash
            git clone URL_DO_SEU_REPOSITORIO_DA_ATIVIDADE
            ```
        3.  Navegue até a pasta criada:
            ```bash
            cd nome-do-repo-da-atividade
            ```
        4.  Certifique-se de ter o Jupyter Notebook ou JupyterLab instalado, junto com as bibliotecas Python necessárias (Pandas, Matplotlib, Seaborn, NumPy, SciPy). Se não tiver, instale-as (geralmente com `pip install pandas matplotlib seaborn numpy scipy jupyterlab`).
        5.  Inicie o Jupyter:
            ```bash
            jupyter lab
            # ou
            jupyter notebook
            ```
        6.  No navegador, abra o arquivo `atividade1.ipynb`. O arquivo `Pokemon.csv` já estará na mesma pasta, então o comando `pd.read_csv('Pokemon.csv')` no notebook deve funcionar diretamente.

    * **Opção B: GitHub Codespaces (mais fácil)**
        1.  Na página do SEU repositório da atividade no GitHub.
        2.  Clique no botão verde `<> Code`.
        3.  Selecione a aba "Codespaces".
        4.  Clique em "Create codespace on main" (ou similar).
        5.  O ambiente Jupyter já estará configurado, e o `Pokemon.csv` estará acessível diretamente.


3.  **Trabalhe no Notebook:**
    * Siga as instruções dentro do `atividade1.ipynb`.
    * Execute as células de código.
    * Analise os resultados e gráficos.
    * **Responda às questões dentro do notebook, criando células para cada questão. Explique seu pensamento.**


## 提交 Submissão da Atividade

Para submeter sua atividade, você precisa fazer `commit` e `push` do seu arquivo `atividade1.ipynb` **modificado** para o GitHub.

1.  **Salve suas alterações no Notebook:** Certifique-se de que todas as suas respostas e execuções estão salvas no arquivo `.ipynb`.
2.  **Adicione suas alterações ao staging (no terminal ou interface do Codespaces/Git):**
    ```bash
    git add atividade1.ipynb
    ```
3.  **Faça o commit das suas alterações:**
    ```bash
    git commit -m "feat: solution"
    ```

4.  **Envie suas alterações para o GitHub:**
    ```bash
    git push
    ```

**Importante:**
* O arquivo `Pokemon.csv` não deve ser alterado, apenas o notebook `.ipynb` com suas respostas e análises.
* Você pode fazer múltiplos commits e pushes até o prazo final.

## 🛠️ Ferramentas e Bibliotecas Utilizadas

* Python 3.x
* Jupyter Notebook / JupyterLab / Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy

## 📅 Prazo

Consulte o Google Classroom.

## ❓ Dúvidas?

Se tiver dúvidas sobre o conteúdo, o uso das ferramentas ou o processo de submissão, me procure.

---

## ✨ Contribuições

Sugestões e melhorias são bem-vindas! Sinta-se à vontade para abrir uma *issue* ou um *pull request*.

---
*Este README foi inspirado em boas práticas de documentação de projetos.*