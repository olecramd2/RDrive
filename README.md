# RDrive - Sistema de Gerenciamento de Arquivos Web

O **RDrive** é um sistema de gerenciamento de arquivos baseado em web, que oferece uma interface moderna e intuitiva para organização, compartilhamento e administração de arquivos pessoais. Ele foi totalmente desenvolvido utilizando linguagem natural com inteligência artifical em ferramentas como Google Gemini e v0.dev, utilizando tecnologias como **PHP, JavaScript, CSS e SQLite**.

<img width="1265" height="753" alt="image" src="https://github.com/user-attachments/assets/543ce5ef-5ee7-4c2e-9b49-23af3624f552" />


## 🎯 Principais Funcionalidades

### 📁 **Gerenciamento de Arquivos**
• **Upload múltiplo** - Envio de vários arquivos simultaneamente com drag-and-drop  
• **Criação de pastas** - Organização hierárquica de documentos  
• **Navegação intuitiva** - Interface similar ao Windows Explorer com breadcrumbs  
• **Pré-visualização** - Visualização direta de imagens, PDFs, vídeos (MP4) e arquivos de texto  
• **Download individual ou em lote** - Geração automática de arquivos ZIP para múltiplos itens

### 🔍 **Busca e Organização**
• **Busca global** - Localização rápida de arquivos por nome  
• **Seleção múltipla** - Operações em lote com checkboxes (download, exclusão)  
• **Renomeação** - Edição de nomes de arquivos e pastas  
• **Movimentação** - Transferência de itens entre pastas com interface visual

### 🗑️ **Sistema de Lixeira**
• **Exclusão segura** - Arquivos movidos para lixeira antes da exclusão definitiva  
• **Recuperação** - Restauração de arquivos excluídos acidentalmente  
• **Limpeza automática** - Opção para esvaziar completamente a lixeira

### 🔗 **Compartilhamento de Arquivos**
• **Links temporários** - Geração de URLs de compartilhamento com expiração em 24h  
• **Gerenciamento de compartilhamentos** - Visualização e controle de todos os links ativos  
• **Acesso público** - Compartilhamento sem necessidade de autenticação via token  
• **Exclusão de links** - Revogação manual de compartilhamentos

### ⚙️ **Configurações e Administração**
• **URL base configurável** - Definição personalizada para links de compartilhamento  
• **Monitoramento de espaço** - Cálculo automático do espaço total ocupado  
• **Sanitização de nomes** - Suporte a acentos e espaços em nomes de arquivos  
• **Banco de dados SQLite** - Armazenamento local sem dependências externas

### 🎨 **Interface e Experiência**
• **Design responsivo** - Compatível com desktop e dispositivos móveis  
• **Tema moderno** - Interface limpa usando Tailwind CSS e ícones Lucide  
• **Notificações toast** - Feedback visual para todas as operações  
• **Navegação por teclado** - Suporte a atalhos para pré-visualização de arquivos  
• **Modo apresentação** - Slideshow em tela cheia para imagens e PDFs

### 🔧 **Recursos Técnicos**
• **Suporte a arquivos grandes** - Configurável até 500MB via .htaccess  
• **Barra de progresso** - Acompanhamento visual de uploads  
• **Validação de segurança** - Proteção contra traversal de diretórios  
• **Estrutura modular** - Código organizado e facilmente extensível  

## 📋 **Casos de Uso**
• **Armazenamento pessoal** - Backup e organização de documentos importantes  
• **Compartilhamento profissional** - Envio de arquivos para clientes e colegas  
• **Gestão de projetos** - Centralização de recursos e materiais de trabalho  
• **Arquivo familiar** - Organização de fotos, vídeos e documentos pessoais

---

O RDrive combina simplicidade de uso com recursos avançados, oferecendo uma solução completa para gerenciamento de arquivos na web, ideal para usuários que precisam de controle total sobre seus dados com a conveniência do acesso remoto.


## 🚩 Limitações

# 🚫 Principais Limitações Conhecidas - RDrive v1.0

Esta seção documenta as limitações atuais do RDrive em comparação com ferramentas de mercado como Dropbox, Google Drive, OneDrive e Nextcloud. Essas limitações representam oportunidades de melhoria para futuras versões.

• **Busca limitada** - Apenas por nome de arquivo, não por conteúdo  
• **Compartilhamento básico** - Apenas links temporários, sem controle granular de permissões  
• **Sem sistema de login** - Qualquer pessoa com acesso à URL do servidor pode usar o sistema (para ambientes copartilhdos recomenda-se utilizar autenticação básica do Apache Web Server)  
• **Sem controle de usuários** - Não há separação de dados por usuário  
• **Sem colaboração em tempo real** - Não permite edição simultânea de documentos  
• **Sem comentários** - Não permite anotações ou feedback em arquivos  
• **Sem versionamento** - Não mantém histórico de versões dos arquivos  
• **Sem notificações** - Usuários não são alertados sobre mudanças  
• **Sem aplicativo móvel** - Apenas interface web responsiva  
• **Sem sincronização automática** - Não sincroniza com pastas locais do computador  
• **Sem cliente desktop** - Não há aplicativo nativo para Windows/Mac/Linux  
• **Sem acesso offline** - Requer conexão com internet sempre

---
**Nota:** O RDrive v1.0 é ideal para **uso pessoal** e **prototipagem rápida**. Antes do uso, considere as limitações listadas acima.

## ✅ Requisitos para funcionamento
• **Servidor Web Apache** - `Versão 2.4.51 ou superior`  
• **PHP** - `Versão 8.3 ou superior`  
• **SQLite** - `Versão 3.37 ou superior`  

## ➡️ Download & Instalação & Contato
• **Veja as notas da versão v1.0** - https://github.com/olecramd2/RDrive/releases/tag/v1.0  

## 📩 Contato
• **Quer trocar uma ideia sobre o projeto?** - olecram@autodashboard.com.br  
