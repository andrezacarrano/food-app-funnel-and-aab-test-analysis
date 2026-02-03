# Análise de Funil de Conversão e Teste A/A/B para Aplicativo de Alimentos

## Objetivo do Projeto
O projeto visava analisar o comportamento dos usuários no aplicativo de uma startup de alimentos, respondendo às seguintes perguntas de negócio:
- Como os usuários chegam à etapa de compra?
- Quantos usuários realmente chegam a essa etapa?
- Quantos ficam presos nas fases anteriores e quais etapas em particular?
- Avaliar o impacto de uma mudança no design (alteração das fontes) através de um teste A/A/B, comparando grupos de controle e teste.

## Resultado
A análise revelou que aproximadamente 48% dos usuários que acessam a tela principal completam uma compra. O maior ponto de abandono ocorre entre a tela principal e a tela de ofertas, com uma perda de 38% dos usuários nessa transição. O teste A/A/B mostrou que a alteração das fontes não influenciou significativamente o comportamento dos usuários: as taxas de conversão variaram entre 46,7% e 48,9% entre os grupos, sem diferenças estatisticamente significativas (p-valores > 0,05 após correção de Bonferroni). Isso permite implementar a mudança por razões estéticas sem riscos métricos.

## Ferramentas Utilizadas
- **Bibliotecas Python**:
  - Pandas: Manipulação e análise de dados.
  - NumPy: Operações numéricas e arrays.
  - Matplotlib e Seaborn: Visualização de dados (gráficos de barras, histogramas).
  - Plotly: Criação de gráficos interativos (funil de conversão).
  - Statsmodels: Testes estatísticos (inicialmente Z-test).
  - Scipy: Fisher Exact Test para proporções.
- **Tecnologias**:
  - Jupyter Notebook: Ambiente de desenvolvimento e documentação.
  - Python: Linguagem principal para análise.

## O que Aprendeu
Neste projeto, adquiri habilidades em:
- Construção e análise de funis de conversão, identificando gargalos no fluxo do usuário.
- Aplicação de testes estatísticos para validação de experimentos A/A/B, incluindo correção para múltiplos testes (Bonferroni).
- Manipulação de dados temporais e categóricos, limpeza e pré-processamento.
- Visualização de dados para comunicar insights de forma clara e impactante.
- Interpretação de resultados estatísticos para tomada de decisões de negócio.

## Melhorias Futuras
- **Segmentação Avançada**: Analisar o funil por segmentos de usuários (ex.: novos vs. recorrentes) para insights mais granulares.
- **Análise de Coorte**: Avaliar retenção e comportamento ao longo do tempo.
- **Testes Adicionais**: Implementar testes A/B focados no gargalo identificado (tela principal → ofertas), como variações em CTAs ou layouts.
- **Integração com Outras Fontes**: Incorporar dados de CRM ou feedback de usuários para enriquecer a análise.
- **Automatização**: Desenvolver scripts para monitoramento contínuo do funil pós-implementação.