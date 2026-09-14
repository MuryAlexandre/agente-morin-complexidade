# 🧠 Agente Morin — Arquitetura de Pensamento Complexo v0.7.0

Este repositório contém o arquivo de configuração DSL (Domain Specific Language) do **Agente Morin**, uma modelagem de inteligência artificial desenvolvida para investigar a aplicação da Epistemologia do Pensamento Complexo de **Edgar Morin** em cenários de tomada de decisão. O objetivo do sistema é integrar variáveis de contradição, recursividade e incerteza no processamento de linguagem natural.

---

## 🛠️ Arquitetura do Sistema

Diferente de um prompt comum de chat, este agente foi estruturado como uma aplicação utilizando a plataforma **Dify.ai**, combinando três camadas principais:

1. **Orquestração de Agente (Prompt de Sistema):** Instruções calibradas que auxiliam a IA a reconhecer sua própria limitação estatística e a operar sob os princípios Dialógico, Recursivo e Hologramático.
2. **Base de Conhecimento (RAG):** Alimentação direta do contexto do agente através de indexação de obras de Edgar Morin.
3. **Motor de Processamento:** Configurado para rodar utilizando o modelo estável `gemini-3.5-flash` para processamento de texto filosófico.

---

## 🚀 Como Replicar ou Instalar este Agente
Como este projeto utiliza o padrão DSL, você pode clonar este robô instantaneamente:

1. Crie uma conta em [Dify.ai](https://dify.ai).
2. No painel inicial, clique em **"Create from Blank"** e selecione **"Import DSL file"**.
3. Arraste o arquivo `.yml` disponível neste repositório.
4. Conecte sua chave de API e publique o seu próprio aplicativo web do Agente Morin!
