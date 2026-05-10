![visitors](https://visitor-badge.laobi.icu/badge?page_id=arvoredossaberes.Capacitacao_Visao_Computacional.filtragem_imagens_ruido)
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
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1a56db,100:10b981&height=220&section=header&text=Filtragem%20de%20Imagens%20e%20An%C3%A1lise%20de%20Ru%C3%ADdo&fontSize=34&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Unidade%202%20%7C%20Cap%C3%ADtulo%201%20%7C%20Tarefa%203&descSize=16&descAlignY=55&descColor=94a3b8" width="100%" alt="Filtragem de Imagens e Análise de Ruído Header"/>
</p>

## Visão Geral

Esta atividade computacional obrigatória da Unidade 2, Capítulo 1, Tarefa 3, consiste na aplicação de técnicas fundamentais de filtragem no domínio da frequência. O objetivo é explorar filtros passa-baixa gaussianos, filtros passa-alta, inserção de ruído gaussiano e sal e pimenta, e avaliar o impacto desses processos em imagens utilizadas em Visão Computacional.

## Objetivos

- **Filtros Passa-Baixa**: Aplicar filtros gaussianos para suavização
- **Filtros Passa-Alta**: Realçar bordas e detalhes
- **Inserção de Ruído**: Adicionar ruído gaussiano e sal e pimenta
- **Avaliação de Impacto**: Analisar como ruídos e filtros afetam a qualidade da imagem
- **Reutilização de Dataset**: Utilizar mini-dataset criado na atividade anterior

## Estrutura da Atividade

### Parte 1 - Seleção das Imagens

Escolha de duas imagens do mini dataset:
- 1 imagem da Classe A
- 1 imagem da Classe B

Apresentação de características (resolução, formato do arquivo).

### Parte 2 - Inserção de Ruído

Geração de duas versões ruidosas de cada imagem:

1. **Ruído Gaussiano**
   - Registro de parâmetros (média e desvio padrão)
   - Análise do impacto visual

2. **Ruído Sal e Pimenta**
   - Registro de porcentagem de pixels alterados
   - Comparação visual com ruído gaussiano

### Parte 3 - Aplicação de Filtro Passa-Baixa Gaussiano

Aplicação de filtro gaussiano de suavização com diferentes níveis:
- Kernel pequeno (ex: 3x3)
- Kernel maior (ex: 7x7)

Comparação entre imagem com ruído e imagem após filtragem.

### Parte 4 - Aplicação de Filtro Passa-Alta

Aplicação de filtro passa-alta para realçar detalhes:
- Laplaciano
- High-pass kernel clássico

Comparação entre imagem original e imagem com filtro passa-alta.

### Parte 5 - Comparação Final

Montagem de tabela comparativa contendo:
- Imagem original
- Imagem com ruído gaussiano
- Imagem com ruído sal e pimenta
- Imagem filtrada com gaussian
- Imagem com filtro passa-alta

## Critérios de Avaliação

1. **Aplicação de Ruídos** (20 pontos)
2. **Aplicação dos Filtros** (30 pontos)
3. **Análise Técnica** (25 pontos)
4. **Organização do Notebook** (15 pontos)
5. **Clareza das Explicações** (10 pontos)

## Prazo

- **Entrega**: 31/05/2026
- **Feedback**: Análise pelo tutor do curso (sem feedback automático)

## Arquivos da Pasta

- `upload-3119314479011947762.pdf` - Enunciado completo da atividade
- `2026-05-31` - Data de entrega

## Tecnologias Utilizadas

- Python
- Jupyter Notebook
- OpenCV (cv2)
- NumPy
- Matplotlib
- scikit-image

## Referências

- Material didático do curso de Visão Computacional
- Documentação do OpenCV
- Fundamentos de processamento de imagens no domínio da frequência

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:10b981,50:1a56db,100:0f172a&height=120&section=footer" width="100%" alt="Footer"/>
</p>

---
**Resumo:** Atividade computacional obrigatória aplicando técnicas de filtragem no domínio da frequência e análise de ruído em imagens.
**Data de Criação:** 2026-05-10
**Autor:** Rapport GenerAtiva
**Versão:** 1.0
**Última Atualização:** 2026-05-10
**Atualizado por:** Rapport GenerAtiva
**Histórico de Alterações:**
- 2026-05-10 - Criado por Rapport GenerAtiva - Versão 1.0
