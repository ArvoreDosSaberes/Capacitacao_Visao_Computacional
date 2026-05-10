![visitors](https://visitor-badge.laobi.icu/badge?page_id=arvoredossaberes.Capacitacao_Visao_Computacional.analise_global_local_textura)
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
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1a56db,100:10b981&height=220&section=header&text=Análise%20Global%2C%20Local%20e%20de%20Textura&fontSize=36&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Unidade%2003%20%7C%20Cap%C3%ADtulo%2002&descSize=16&descAlignY=55&descColor=94a3b8" width="100%" alt="Análise Global, Local e de Textura Header"/>
</p>

## Visão Geral

Esta atividade obrigatória da Unidade 3, Capítulo 2, consiste em uma análise comparativa de diferentes estratégias de representação de imagens em três níveis complementares: global, local e de textura. O objetivo é investigar como diferentes descritores se comportam diante de variações reais de captura em um mini dataset próprio.

## Objetivos

- **Análise Global**: Utilizar histogramas e estatísticas da imagem para caracterização
- **Análise Local**: Empregar pontos de interesse, descritores ORB e correspondência entre imagens
- **Análise de Textura**: Aplicar descritores baseados em relações espaciais e padrões locais (GLCM e LBP)
- **Síntese Comparativa**: Identificar qual representação é mais adequada para o mini dataset

## Estrutura da Atividade

### Parte 1 - Preparação do Dataset e Hipótese Inicial
- Reutilização das duas classes do mini dataset
- Apresentação da estrutura de pastas
- Exibição de imagens representativas
- Registro de fatores de aquisição e hipóteses iniciais

### Parte 2 - Análise Global: Histogramas e Estatística
- Cálculo de estatísticas globais (média, variância, desvio padrão, entropia)
- Geração de histogramas de intensidade e cor (RGB/HSV)
- Comparação entre imagens originais e versões derivadas

### Parte 3 - Análise Local: Pontos de Interesse, Descritores e Matching
- Detecção de cantos com Shi-Tomasi
- Detecção de blobs (blob_log)
- Extração de keypoints e descritores ORB
- Matching com BFMatcher
- Teste de robustez com transformações

### Parte 4 - Análise de Textura: GLCM e LBP
- Cálculo da GLCM com diferentes distâncias e ângulos
- Extração de propriedades (contrast, homogeneity, energy, correlation)
- Cálculo do LBP e histograma normalizado
- Interpretação técnica dos resultados

### Parte 5 - Síntese Integradora
- Tabela comparativa final dos descritores
- Conclusão sobre qual descritor foi mais útil
- Análise do impacto da aquisição nos resultados

## Critérios de Avaliação

1. **Reuso e organização do mini dataset** (15 pontos)
2. **Análise global: histogramas e estatística** (25 pontos)
3. **Análise local: pontos de interesse, ORB e matching** (25 pontos)
4. **Análise de textura: GLCM e LBP** (20 pontos)
5. **Síntese técnica e clareza do notebook** (15 pontos)

## Prazo

- **Entrega**: 21/06/2026
- **Feedback**: Análise pelo mentor (sem feedback automático)

## Arquivos da Pasta

- `upload-16988370719659384979.pdf` - Enunciado completo da atividade
- `2026-06-21` - Data de entrega

## Tecnologias Utilizadas

- Python
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
**Resumo:** Atividade obrigatória de análise comparativa de descritores de imagem em três níveis (global, local e textura) utilizando mini dataset próprio.
**Data de Criação:** 2026-05-10
**Autor:** Rapport GenerAtiva
**Versão:** 1.0
**Última Atualização:** 2026-05-10
**Atualizado por:** Rapport GenerAtiva
**Histórico de Alterações:**
- 2026-05-10 - Criado por Rapport GenerAtiva - Versão 1.0
