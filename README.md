# 🌐 Leni Multiplayer

**Jogue Minecraft Bedrock online com amigos, grátis e sem complicação.**

O **Leni Multiplayer** é um aplicativo que permite jogar **Minecraft Bedrock Edition online com amigos** sem precisar de Xbox Live Gold, Realms, servidores pagos ou configurações complicadas de roteador. Eleconecta jogadores de qualquer lugar do mundo.

- 🌍 **Site oficial:** [https://leni.ddns.net](https://leni.ddns.net)
- 💬 **Discord:** [https://dsc.gg/leni](https://dsc.gg/leni)

> **Em uma frase:** O Leni transforma o mundo do seu Minecraft em uma sala online que seus amigos podem entrar usando apenas um código de 6 letras.

---

## 📖 Sumário

- [O que é o Leni Multiplayer?](#-o-que-é-o-leni-multiplayer)
- [Como funciona](#-como-funciona)
- [Funcionalidades](#-funcionalidades)
- [O Site (leni.ddns.net)](#-o-site-leniddnsnet)
- [Plataformas suportadas](#-plataformas-suportadas)
- [Contas e privacidade](#-contas-e-privacidade)
- [Idiomas](#-idiomas)
- [Arquitetura Técnica](#-arquitetura-técnica)
- [Estrutura do Repositório](#-estrutura-do-repositório)
- [FAQ](#-perguntas-frequentes)
- [Licença e Créditos](#-licença-e-créditos)

---

## 🎮 O que é o Leni Multiplayer?

O **Minecraft Bedrock** foi feito para jogar apenas com quem está na mesma rede Wi-Fi (modo LAN). O Leni quebra essa barreira e funciona como um **túnel mágico** que conecta jogadores de qualquer lugar do mundo.


## ✨ Funcionalidades

### 🏠 Tela Inicial (Feed)
- Feed de publicações da comunidade (conquistas, posts)
- Prévia da loja e destaques
- Notícias e anúncios oficiais

### 🎮 Aba "Jogar"
- **Lobby global:** navegue por salas ativas em tempo real
- **Filtros:** por versão do Minecraft, esconder salas cheias, etc.
- **Hospedar:** crie sua própria sala com PIN de 6 letras
- **Salas com senha:** tranque a sala (só entra quem sabe a senha)
- **Servidores:** lista de servidores da comunidade
- **Torneios:** participe de torneios com prêmios

### 👥 Aba "Social"
- **Amigos:** adicione, veja quem está online e converse
- **Chat privado:** conversas 1:1, grupos e comunidades
- **Chamadas de voz** (overlay de chamada integrado)
- **Ranking global:** XP, moedas, seguidores e doadores
- **Feed:** publique conquistas e interaja com posts de outros jogadores
- **Perfil:** personalize avatar, banner, insígnias e tema
- **Visualizador de skin 3D**
- **Notificações** (push via Firebase)

### 🏪 Loja
- Compre itens exclusivos com moedas do jogo
- **Plano VIP (DIAMOND):**
  - Salas de até **30 jogadores** (15 no gratuito)
  - Frames de avatar especiais
  - Temas de perfil personalizados
  - Badges (insígnias) exclusivas
- **Moedas** para usar na loja

### 🧩 Addons
- **Mercado de addons:** baixe e instale addons/mods de Minecraft
- Upload e gerenciamento de addons pela comunidade


## 🌍 O Site (leni.ddns.net)

O site é o **hub oficial** do Leni Multiplayer, servido pelo próprio backend em `leni.ddns.net`:

- **Landing page** com hero, slogan e botão de download
- **Estatísticas em tempo real:** usuários registrados, salas ativas, jogadores online, total doado e notícias publicadas
- **Notícias:** últimas novidades do projeto
- **Downloads:** tabela dinâmica com as versões mais recentes:
  - Android 64-bit (APK)
  - Android 32-bit (APK)
- **Multi-idioma** (PT, EN, ES, RU, VI) com seletor de idioma
- **Deep links:** links de `leni.ddns.net` abrem direto no app instalado (web-to-app)

---

## 📱 Plataformas suportadas

| Plataforma | Suporte | Formato |
|-----------|---------|---------|
| 📱 Android | ✅ Estável | APK (64-bit e 32-bit) |
| 🖥️ Windows | 🚧 Em desenvolvimento | — |
| 🍏 iOS | 🚧 Em desenvolvimento | — |

**Requisitos:** Minecraft **Bedrock Edition** (qualquer dispositivo que rode a versão Bedrock).

---

## 🔒 Contas e privacidade

### Criar conta
- **Gratuito** — não precisa de email se não quiser
- Escolha um **nick** (apelido) e uma senha
- Jogue como **convidado** sem criar conta (algumas funções ficam limitadas)
- Login com **Google** (opcional)

### Privacidade
- Controle quem vê seu status online
- Escolha se aparece ou não no ranking
- Esconda suas moedas do perfil público
- Verificação de email (opcional)
- Opção de excluir sua conta

---

## 🌐 Idiomas disponíveis

- 🇧🇷 Português (Brasil)
- 🇺🇸 Inglês (EUA)
- 🇪🇸 Espanhol
- 🇷🇺 Russo
- 🇻🇳 Vietnamita
- 🇮🇩 Indonésio


## ❓ Perguntas Frequentes

**Precisa de Xbox Live Gold?**
Não! O Leni funciona completamente fora do ecossistema Xbox.

**Funciona no iPhone?**
Atualmente o app está disponível apenas para **Android**. O iOS está em desenvolvimento.

**Quantos jogadores podem jogar?**
Até **30 jogadores**.

**O jogo fica lento?**
A latência depende da internet de cada um, mas por ser **P2P** (conexão direta), costuma ser tão rápida quanto uma partida local.

**Precisa ter o Minecraft aberto para hospedar?**
Sim! O Leni espelha o mundo que está rodando no seu Minecraft.

**Meus dados passam pelo servidor de vocês?**
Não. O tráfego de jogo é **P2P direto** entre os jogadores. O servidor faz apenas a negociação inicial da conexão.

---

## 📝 Notas da Versão

**Versão atual:** `1.0.71` (Beta)

O app está em **desenvolvimento ativo** — novas funcionalidades são adicionadas regularmente.

---

## 🆘 Precisa de ajuda?

- Acesse o menu **"Apoiar"** (coração vermelho) dentro do app
- Entre no [Discord](https://dsc.gg/leni)
- Acesse o site em [leni.ddns.net](https://leni.ddns.net)

---

## 📄 Licença e Créditos

- **Leni Multiplayer** © 2024–2026 — Feito por jogadores para jogadores 🎮
- *Minecraft* é uma marca registrada da Mojang Studios. Este projeto não é afiliado à Mojang ou Microsoft.
- Imagens, fontes e recursos de terceiros pertencem aos seus respectivos donos.

---

*Leni Multiplayer — Transformando Minecraft LAN em diversão online global.* 🌎
