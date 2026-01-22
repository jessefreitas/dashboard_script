# 🛠️ Dashboard Scripts & Chatwoot Customizations

Este repositório contém uma coleção de scripts JavaScript, CSS e HTML desenvolvidos para personalizar, estender e adicionar novas funcionalidades ao frontend do Chatwoot (versão OmniForge/MEGA).Estes scripts são projetados para serem injetados no painel do Chatwoot (via Dashboard Apps ou injeção direta de script), proporcionando funcionalidades avançadas como dashboards personalizados, modais de agendamento e melhorias de UI/UX.

## 📂 Lista de Arquivos e Funcionalidades

Abaixo está a descrição detalhada de cada módulo contido nesta pasta:

- **`mensagemNãoLidas`** (Dashboard): Painel de Monitoramento que exibe uma tabela com conversas não lidas, indicadores de urgência e tempo de espera. Integra-se via Webhook com n8n para permitir resolver conversas diretamente da interface.
- **`Botões Contatos`** (UI Feature): Injeta botões de ação rápida diretamente no painel lateral do contato para facilitar o fluxo de trabalho dos agentes.
- **`Compartilhar contato`** (Modal): Adiciona uma funcionalidade que abre um modal para compartilhar os dados do contato atual com outros departamentos ou usuários.
- **`Painel OmniForge`** (Support): Adiciona um painel de suporte dedicado da OmniForge contendo botões utilitários e links rápidos.
- **`Tags de Contato`** (Automation): Script para gerenciamento aprimorado e visualização de etiquetas (tags) nos contatos.
- **`agenda`** (Feature): Implementa um painel de agendamento e injeta botões para criação rápida de eventos ou lembretes.
- **`chat_general_capitão`** (Chat): Customização específica para o canal "General Capitão" (criação e regras específicas).
- **`dash_crm_botão_modal_lateral`** (CRM): Adiciona um botão lateral que abre um modal de negociação (CRM), permitindo gerenciar leads sem sair da conversa.
- **`extrator_campos`** (Utility): Script utilitário para atualizar e extrair campos personalizados (custom attributes) das conversas.
- **`layout_labels`** (CSS/JS): Script para estilização personalizada das labels (etiquetas) dentro do Chatwoot, melhorando a distinção visual.
- **`mega_front_whatsapp`** (CSS): Estilos CSS avançados para a interface de conversação, focados na experiência visual estilo WhatsApp.
- **`modo_visualizador`** (Debug): Adiciona um visualizador de estrutura completa (Modo Raio-X) para depuração e análise de elementos em tela.
- **`Tela de login`** (Page): Código para customização completa da página de login do sistema.
- **`README.md`** (Docs): Arquivo de documentação e correção do README atual.

## 💻 Como Utilizar

### 1. Dashboard scripts
1. Clique na sua foto de perfil e vá em ` Console do super admin `.
2. Vá em **DashboardScripts**.
3. Clique em `New dashboard script`:
   - Adicione o Nome do script em **Name** (ou o nome que preferir).
   - Cole o script desejado em **Content**.

Pronto, agora é só repetir o processo pra qualquer script que queira adicionar ao seu **MEGA**

## 📋 Requisitos

- **Mega/** (4.10.3 ou superior recomendado).
- **n8n** (Necessário para alguns dos scripts de dashboard e automação).
- Acesso de **Administrador** para configuração de *Dashboard Apps*.

---

> **Desenvolvido por:** Carlos Mourão & Jessé Freitas
> **Projeto:** OmniForge
