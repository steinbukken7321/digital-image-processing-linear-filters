# Processamento Digital de Imagens: Filtros Lineares

Este repositório contém a implementação e análise de filtros lineares aplicados ao processamento digital de imagens. O foco principal é a restauração de imagens corrompidas por ruído (Gaussiano e Salt & Pepper) utilizando técnicas de filtragem espacial.

## 🚀 Sobre o Projeto

O projeto demonstra como operadores lineares, como a média móvel, podem ser aplicados para suavizar imagens e reduzir artefatos indesejados. Foi desenvolvido como parte dos estudos em Visão Computacional e Processamento de Sinais.

### Principais Funcionalidades:
* **Geração de Ruído:** Implementação de ruído Gaussiano e Salt & Pepper para simular condições reais de degradação.
* **Filtros de Suavização:** Aplicação de filtros lineares de 3 pontos para recuperação de sinais e imagens.
* **Análise Visual:** Comparação lado a lado entre a imagem original, ruidosa e recuperada usando Matplotlib.

## 🛠️ Tecnologias Utilizadas

* **Python 3.x**
* **NumPy:** Manipulação matricial eficiente das imagens.
* **Matplotlib:** Visualização de resultados e gráficos.
* **Scikit-Image (skimage):** Pré-processamento e conversão de escala de cinza.

## 📋 Como Executar

### 1. Pré-requisitos
Certifique-se de ter o Python instalado. Recomenda-se o uso de um ambiente virtual:

```bash
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate

```

### 2. Instalação das Dependências

Instale as bibliotecas necessárias via pip:

```bash
pip install numpy matplotlib scikit-image

```

### 3. Execução

Execute o script principal para processar o dataset de exemplo e visualizar os resultados:

```bash
python filtroslineares_modificado.py

```

## 📈 Resultados

O algoritmo processa imagens em tons de cinza, aplica o ruído selecionado e utiliza um filtro de média local para tentar restaurar a fidelidade visual da imagem original. Este processo é fundamental em sistemas de telecomunicações onde a transmissão de dados pode sofrer interferências eletromagnéticas.

---

Desenvolvido por Rafael Ziani de Carvalho
Gostaria que eu fizesse alguma alteração específica no código ou na explicação para incluir os detalhes sobre o dataset **CARABAS-II** que você mencionou anteriormente?

```
