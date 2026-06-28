![visitors](https://visitor-badge.laobi.icu/badge?page_id=arvoredossaberes.Capacitacao_Visao_Computacional.suavizacao_ruido_bordas)
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
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1a56db,100:10b981&height=220&section=header&text=Suaviza%C3%A7%C3%A3o%2C%20Remo%C3%A7%C3%A3o%20de%20Ru%C3%ADdo%20e%20Detec%C3%A7%C3%A3o%20de%20Bordas&fontSize=30&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Unidade%202%20%7C%20Cap%C3%ADtulo%201%20%7C%20Tarefa%201&descSize=14&descAlignY=55&descColor=94a3b8" width="100%" alt="Suavização, Remoção de Ruído e Detecção de Bordas Header"/>
</p>

## Visão Geral

Esta atividade obrigatória da Unidade 2, Capítulo 1, Tarefa 1, consiste na aplicação de técnicas de filtragem espacial para suavização, remoção de ruído e detecção de bordas em imagens reais coletadas pelo próprio aluno. O objetivo é analisar criticamente o tipo de degradação presente e justificar a escolha do filtro mais adequado.

## Objetivos

- **Identificação de Degradações**: Reconhecer ruído do sensor, granulação e artefatos
- **Filtros de Suavização**: Aplicar filtro da média, gaussiano e mediana
- **Detecção de Bordas**: Utilizar operadores Sobel, Prewitt e Canny
- **Análise Comparativa**: Comparar diferentes métodos e parâmetros
- **Justificação Técnica**: Fundamentar escolhas com base teórica

## Estrutura da Atividade

### Parte 1 - Seleção das Imagens

Seleção de imagens do mini dataset:

- 2 imagens da Classe A
- 2 imagens da Classe B

Critérios: imagens com granulação, variações de intensidade, baixa qualidade ou compressão visível.

Registro de:

- Nome da imagem
- Classe
- Tipo de degradação observada
- Hipótese sobre a origem do ruído

### Parte 2 - Aplicação de Filtros de Suavização

Para cada imagem selecionada:

**Filtro da Média**

- Kernel 3×3
- Kernel 5×5

**Filtro Gaussiano**

- σ=1
- σ=3

**Filtro da Mediana**

- Kernel 3×3
- Kernel 5×5

Análise de:

- Qual filtro reduziu mais o ruído
- Qual preservou melhor as bordas
- Variação da variância dos níveis de cinza

### Parte 3 - Detecção de Bordas (sem suavização prévia)

Aplicação direta na imagem original:

**Operador de Sobel**

- Gradiente em X
- Gradiente em Y
- Magnitude do gradiente

**Operador de Prewitt**

- Gradiente em X
- Gradiente em Y
- Magnitude

**Detector de Canny**

- Teste com diferentes limiares

Análise de:

- Presença de bordas falsas
- Sensibilidade ao ruído
- Comparação visual entre métodos

### Parte 4 - Detecção de Bordas após Suavização

1. Escolher o filtro de suavização mais adequado
2. Aplicar o filtro
3. Reaplicar Sobel, Prewitt e Canny

Comparação de:

- Quantidade de bordas detectadas
- Redução de bordas falsas
- Continuidade das bordas reais

## Critérios de Avaliação

1. **Aplicação correta dos filtros e operadores** (30 pontos)
2. **Análise comparativa e estatística** (25 pontos)
3. **Qualidade das justificativas técnicas** (25 pontos)
4. **Organização e clareza do notebook** (10 pontos)
5. **Conclusão crítica e sistêmica** (10 pontos)

## Prazo

- **Entrega**: 17/05/2026
- **Feedback**: Análise pelo tutor (sem feedback automático)

## Arquivos da Pasta

- `upload-14525446732474592702.pdf` - Enunciado completo da atividade
- `..\dataset` - Dataset de imagens a ser usado nas analises
- `2026-05-17` - Data de entrega

## Tecnologias Utilizadas

- Python
- Jupyter Notebook
- OpenCV (cv2)
- NumPy
- Matplotlib
- scikit-image

## Referências

- Material didático do curso de Visão Computacional
- Linear System Theory and Design - Chen, Chi-Tsong
- Documentação do OpenCV
- Fundamentos de filtragem espacial

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:10b981,50:1a56db,100:0f172a&height=120&section=footer" width="100%" alt="Footer"/>
</p>

---

**Resumo:** Atividade obrigatória aplicando técnicas de filtragem espacial para suavização, remoção de ruído e detecção de bordas em imagens reais.
**Data de Criação:** 2026-05-10
**Autor:** Rapport GenerAtiva
**Versão:** 1.0
**Última Atualização:** 2026-05-10
**Atualizado por:** Rapport GenerAtiva
**Histórico de Alterações:**

- 2026-05-10 - Criado por Rapport GenerAtiva - Versão 1.0
