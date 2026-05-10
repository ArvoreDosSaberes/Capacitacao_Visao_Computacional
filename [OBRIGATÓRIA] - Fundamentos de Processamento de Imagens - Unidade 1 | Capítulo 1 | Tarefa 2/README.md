![visitors](https://visitor-badge.laobi.icu/badge?page_id=arvoredossaberes.Capacitacao_Visao_Computacional.fundamentos_processamento_imagens)
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
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1a56db,100:10b981&height=220&section=header&text=Fundamentos%20de%20Processamento%20de%20Imagens&fontSize=32&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Unidade%201%20%7C%20Cap%C3%ADtulo%201%20%7C%20Tarefa%202&descSize=14&descAlignY=55&descColor=94a3b8" width="100%" alt="Fundamentos de Processamento de Imagens Header"/>
</p>

## Visão Geral

Esta atividade computacional obrigatória da Unidade 1, Capítulo 1, Tarefa 2, consiste na construção de um mini dataset com 2 classes e 10 imagens no total, aplicando na prática os fundamentos discutidos em aula sobre processamento de imagens digitais. A atividade simula etapas reais de um projeto profissional.

## Objetivos

- **Construção de Dataset**: Criar mini dataset próprio com 2 classes e 10 imagens
- **Resolução e Profundidade de Cor**: Aplicar conceitos de resolução espacial e radiométrica
- **Conversões de Espaço de Cor**: Implementar RGB, HSV e escala de cinza
- **Aquisição**: Controlar condições de captura
- **Armazenamento e Formatos**: Analisar RAW/JPEG/PNG
- **Análise de Impacto**: Avaliar impacto visual e funcional das escolhas

## Estrutura da Atividade

### Parte 1 - Definição das Classes

Escolha de tema simples com boa distinção visual:
- Exemplos: Folha/Flor, Copo/Garrafa, Teclado/Mouse, Porta/Janela
- Regras: classes coerentes, imagens capturadas pelo estudante

### Parte 2 - Aquisição de Imagens

Captura de 5 imagens por classe (total de 10):

Requisitos mínimos:
- Pelo menos 2 cenários de iluminação
- Pelo menos 2 distâncias/ângulos diferentes
- Evitar filtros automáticos

Registro técnico:
- Dispositivo usado
- Condição de iluminação
- Distância aproximada
- Observações de ruído e desfoque

### Parte 3 - Transformações de Imagens

Para 1 exemplo de cada classe:

**A. Análise de Resolução**
- Versão em resolução original
- Versão com redução em 50%
- Versão com redução em 20%

**B. Espaço de Cor**
- Visualização em RGB
- Visualização em HSV
- Visualização em escala de cinza

**C. Quantização**
- 256 níveis de cinza
- 64 níveis de cinza
- 32 níveis de cinza
- 2 níveis de cinza

**D. Formato de Arquivo**
- JPEG com compressão
- PNG sem perdas

### Parte 4 - Estrutura do Mini Dataset

Organização em pastas com padrão de ML:
```
dataset/
  classe_A/
    img001_original.jpg
    ...
  classe_B/
    img006_original.jpg
    ...
```

## Critérios de Avaliação

1. **Aquisição das Imagens** (20 pontos)
2. **Aplicação Correta dos Fundamentos** (30 pontos)
3. **Análise Técnica e Reflexão Crítica** (25 pontos)
4. **Estruturação do Mini Dataset** (15 pontos)
5. **Organização e Clareza do Notebook** (10 pontos)

## Prazo

- **Entrega**: 10/05/2026
- **Feedback**: Análise pelo tutor do curso

## Arquivos da Pasta

- `upload-17373056349219283473.pdf` - Enunciado completo da atividade
- `Atividade_FPI_U1_C1_T2.ipynb` - Notebook da atividade
- `requirements.txt` - Dependências Python
- `docs/` - Documentação adicional
- `venv/` - Ambiente virtual Python

## Tecnologias Utilizadas

- Python 3.8+
- Jupyter Notebook
- OpenCV (cv2)
- NumPy
- Matplotlib
- scikit-image
- Pillow (PIL)

## Instalação

```bash
# Criar ambiente virtual
python -m venv venv
source venv/bin/activate  # Linux/Mac
# ou
venv\Scripts\activate  # Windows

# Instalar dependências
pip install -r requirements.txt
```

## Referências

- Material didático do curso de Visão Computacional
- Documentação do OpenCV e scikit-image
- Fundamentos de Processamento Digital de Imagens

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:10b981,50:1a56db,100:0f172a&height=120&section=footer" width="100%" alt="Footer"/>
</p>

---
**Resumo:** Atividade computacional obrigatória construindo mini dataset próprio aplicando fundamentos de processamento de imagens digitais.
**Data de Criação:** 2026-05-10
**Autor:** Rapport GenerAtiva
**Versão:** 1.0
**Última Atualização:** 2026-05-10
**Atualizado por:** Rapport GenerAtiva
**Histórico de Alterações:**
- 2026-05-10 - Criado por Rapport GenerAtiva - Versão 1.0
