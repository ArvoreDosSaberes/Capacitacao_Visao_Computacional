![visitors](https://visitor-badge.laobi.icu/badge?page_id=arvoredossaberes.Capacitacao_Visao_Computacional.atividade_pratica_unidade3)
[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC_BY--SA_4.0-blue.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
![Language: Portuguese](https://img.shields.io/badge/Language-Portuguese-brightgreen.svg)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Prática-green)
![Status](https://img.shields.io/badge/Status-Educa%C3%A7%C3%A3o-brightgreen)
![Repository Size](https://img.shields.io/github/repo-size/arvoredossaberes/Capacitacao_Visao_Computacional)
![Last Commit](https://img.shields.io/github/last-commit/arvoredossaberes/Capacitacao_Visao_Computacional)

<!-- Animated Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1a56db,100:10b981&height=220&section=header&text=Atividade%20Pr%C3%A1tica&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Unidade%203%20%7C%20Cap%C3%ADtulo%201&descSize=18&descAlignY=55&descColor=94a3b8" width="100%" alt="Atividade Prática Header"/>
</p>

## Visão Geral

Esta atividade prática obrigatória da Unidade 3, Capítulo 1, consiste na implementação de um pipeline simples de análise de imagens utilizando Python no Google Colab. O objetivo é aplicar conceitos fundamentais de visão computacional relacionados à segmentação de imagens, operações morfológicas e extração de características.

## Objetivos

- **Segmentação de Imagens**: Separar objetos ou regiões de interesse
- **Operações Morfológicas**: Refinar resultados da segmentação
- **Identificação de Objetos**: Utilizar análise de componentes conectados
- **Extração de Características**: Extrair atributos quantitativos dos objetos
- **Análise de Resultados**: Interpretar a eficácia do pipeline implementado

## Estrutura da Atividade

### Parte 1 - Aquisição da Imagem

Escolha de uma imagem contendo múltiplos objetos ou padrões de textura, obtida de:
- Biblioteca skimage.data
- Repositórios públicos de imagens
- Imagem capturada pelo próprio estudante

### Parte 2 - Segmentação da Imagem

Implementação de método de segmentação:
- Limiarização global
- Limiarização adaptativa
- Detecção de bordas seguida de segmentação
- Outro método adequado

### Parte 3 - Operações Morfológicas

Aplicação de pelo menos duas operações:
- Erosão
- Dilatação
- Abertura
- Fechamento

### Parte 4 - Identificação de Objetos

Utilização de análise de componentes conectados para identificar objetos presentes na imagem segmentada.

### Parte 5 - Extração de Características

Extração de pelo menos três características para cada objeto:
- Área
- Perímetro
- Centroide
- Momentos de Hu
- Descritores de textura (LBP ou GLCM)

### Parte 6 - Análise dos Resultados

Interpretação dos resultados obtidos:
- Capacidade de distinção dos objetos pelas características
- Identificação das características mais informativas
- Sugestões de melhoria do pipeline

## Estrutura do Notebook

O notebook deve conter as seguintes seções:

1. Introdução
2. Aquisição da imagem
3. Segmentação
4. Operações morfológicas
5. Identificação de objetos
6. Extração de características
7. Análise dos resultados
8. Conclusão

## Critérios de Avaliação

- Implementação correta das etapas
- Clareza na apresentação dos resultados
- Capacidade de análise dos resultados
- Organização do notebook
- Qualidade das explicações

## Prazo

- **Entrega**: 07/06/2026
- **Feedback**: Análise pelo mentor (sem feedback automático)

## Arquivos da Pasta

- `upload-10234012705628750391.pdf` - Enunciado completo da atividade
- `Atividade 07-06-2026.ipynb` - Notebook da atividade
- `2026-06-07` - Data de entrega

## Tecnologias Utilizadas

- Python
- Google Colab
- OpenCV (cv2)
- scikit-image
- NumPy
- Matplotlib

## Referências

- Material didático do curso de Visão Computacional
- Documentação do OpenCV e scikit-image

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:10b981,50:1a56db,100:0f172a&height=120&section=footer" width="100%" alt="Footer"/>
</p>

---
**Resumo:** Atividade prática obrigatória implementando pipeline de segmentação, operações morfológicas e extração de características em imagens.
**Data de Criação:** 2026-05-10
**Autor:** Rapport GenerAtiva
**Versão:** 1.0
**Última Atualização:** 2026-05-10
**Atualizado por:** Rapport GenerAtiva
**Histórico de Alterações:**
- 2026-05-10 - Criado por Rapport GenerAtiva - Versão 1.0
