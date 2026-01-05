# 📊 MyFitnessPal - Ads Performance Dashboard

# Marketing Analytics Dashboard

[![Link para Dashboard](https://img.shields.io/badge/Acesse_o_Dashboard-Looker_Studio-blue?style=for-the-badge&logo=google)](https://lookerstudio.google.com/s/tAUBswv5mRM)

![Preview do Dashboard](./imagens/dashboard.png)

## 📝 Descrição do Projeto
Este painel analítico foi desenvolvido para monitorar e otimizar a performance de campanhas de mídia paga (Social Ads) do aplicativo **MyFitnessPal**. O objetivo central é analisar o funil de aquisição de usuários, desde a impressão do anúncio até a instalação do aplicativo e conversão final, permitindo ajustes estratégicos de investimento e criativos.

## 🎯 Objetivos de Negócio
* **Monitoramento de User Acquisition (UA):** Acompanhar o volume de instalações do aplicativo em relação às metas estabelecidas.
* **Eficiência de Custos:** Analisar a relação entre Investimento (Cost) e Instalações para controlar o CPA (Custo por Aquisição).
* **Otimização de Criativos:** Identificar quais temas (Themes) e CTAs (Call to Actions) geram maior engajamento e conversão.

## 📈 KPIs e Métricas Principais
O dashboard apresenta um funil de conversão linear com comparativos percentuais (YoY ou MoM):
1.  **Impressions:** Alcance total dos anúncios (Topo de funil).
2.  **Video Views:** Consumo de conteúdo em vídeo.
3.  **Clicks:** Interesse direto no anúncio.
4.  **App Installs:** Ação principal (Fundo de funil).
5.  **Conversions:** Eventos pós-instalação (ex: registro, assinatura).
6.  **CPA (Cost per Action):** Custo médio por resultado obtido.
7.  **Target Gauge:** Medidor de atingimento da meta de instalações.

## 🔎 Estrutura Visual e Análises

### 1. Visão Temporal (Time Series)
* **Cost vs App Install:** Gráfico combinado (Combo Chart) relacionando o volume diário de investimento (barras) com o número de instalações (linha). Permite identificar se o aumento de *bid/budget* está correlacionado com o aumento de usuários.
* **CPA Performance:** Acompanhamento da flutuação do custo por aquisição ao longo do tempo.

### 2. Análise de Segmentação
* **App Install by Tema:** Gráfico de barras horizontal rankeando a performance dos diferentes temas de campanha (ex: Influencer, AI Tools, Pets), facilitando a decisão de onde alocar verba.
* **Call to Action (CTA):** Gráfico de rosca (Donut Chart) exibindo a distribuição de conversões por tipo de botão (ex: "Learn More" vs "Install Now"), testando a eficácia da chamada para ação.

### 3. Performance Granular (Tabela)
* **Creative Performance:** Tabela detalhada listando os anúncios individuais (Ad Name).
    * **Métricas:** CPA, Variação percentual (%), Frequência (Frequency) e variação de frequência.
    * **Uso:** Identificar fadiga de anúncios (alta frequência com baixo retorno) ou "campeões" de baixo custo.

## 🛠️ Ferramentas Utilizadas
* **Visualização:** Looker Studio (Google).
* **Fontes de Dados:** Conectores de plataformas de anúncios (ex: Meta Ads, TikTok Ads, Google Ads).

---
