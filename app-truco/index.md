---
layout: default
title: Política de Privacidade – Marcador de Truco
lang: pt-BR
description: Política de Privacidade do aplicativo Marcador de Truco, disponível no Google Play Store.
---

# Política de Privacidade

**Aplicativo:** Marcador de Truco  
**Pacote:** com.devgmd.marcadortruco  
**Plataforma:** Android (Google Play Store)  
**Última atualização:** 13 de abril de 2026

---

## 1. Apresentação

O **Marcador de Truco** é um aplicativo gratuito de placar para o jogo de Truco, desenvolvido e mantido por **devgmd**. Esta Política de Privacidade explica de forma transparente quais dados coletamos, por que os coletamos, como os utilizamos e quais são seus direitos como usuário.

Ao instalar ou utilizar o aplicativo, você concorda com as práticas descritas nesta política. Se não concordar, pedimos que não utilize o aplicativo.

Esta política está em conformidade com:
- **Lei Geral de Proteção de Dados (LGPD)** – Lei nº 13.709/2018
- **Regulamento Geral de Proteção de Dados (GDPR)** – Regulamento (UE) 2016/679
- **Políticas do Google Play** para aplicativos que coletam dados de usuários

---

## 2. Responsável pelo Tratamento de Dados

| | |
|---|---|
| **Desenvolvedor** | devgmd |
| **E-mail de contato** | suporte@seusite.com |
| **Política de Privacidade** | Esta página |

---

## 3. Dados que Coletamos

### 3.1 Dados de Conta e Autenticação

O aplicativo oferece autenticação opcional via **Firebase Authentication**. Dependendo do método escolhido, podemos coletar:

| Dado | Método de Login | Finalidade |
|---|---|---|
| ID único anônimo (UID) | Todos (incluindo anônimo) | Identificar a sessão do usuário |
| Endereço de e-mail | E-mail/senha, Google | Autenticação e recuperação de conta |
| Nome de exibição | Google, Apple | Personalização da interface |
| Token de autenticação | Google, Apple | Autenticação segura |

> O login é **totalmente opcional**. O aplicativo funciona normalmente sem conta criada, utilizando autenticação anônima.

### 3.2 Dados de Uso do Jogo

Os dados abaixo são armazenados **localmente no dispositivo** (banco Hive) e não são transmitidos a servidores externos, exceto quando o usuário estiver autenticado:

- Histórico de partidas (formato, variante, placar, times, eventos)
- Data e hora das partidas
- Variante do jogo utilizada (Paulista, Gaúcho ou Mineiro)
- Formato escolhido (1v1 ou 2v2)

### 3.3 Dados de Sugestões da Comunidade

Caso utilize a funcionalidade de sugestões, os seguintes dados são armazenados no **Cloud Firestore**:

- Texto da sugestão enviada
- Votos registrados
- Identificador do autor (`authorId` — UID do Firebase)

### 3.4 Dados de Diagnóstico e Desempenho

Coletamos automaticamente dados técnicos para melhorar a estabilidade do aplicativo:

- Relatórios de falhas e erros (via Firebase Crashlytics)
- Versão do sistema operacional e do aplicativo
- Identificador anonimizado do dispositivo

### 3.5 Dados de Analytics

Utilizamos o **Firebase Analytics** para entender como o aplicativo é usado:

- Eventos de tela (telas acessadas, tempo de uso)
- Eventos de funcionalidades ativadas
- País/região (nível de cidade, de forma agregada)
- Tipo de dispositivo e sistema operacional

Esses dados são **anonimizados e agregados**, sem identificação individual.

### 3.6 Dados de Publicidade

O aplicativo exibe anúncios por meio do **Google AdMob** (ID do editor: `ca-app-pub-9414724009049583`). Para veicular anúncios relevantes, o AdMob pode coletar:

- Identificador de publicidade do dispositivo (Android Ad ID)
- Dados de interação com anúncios (cliques, impressões)
- Informações técnicas do dispositivo
- Localização aproximada (se permitida)

> Usuários com a versão **Pro (sem anúncios)** não estão sujeitos à coleta de dados de publicidade.

### 3.7 Dados de Compras In-App

Gerenciamos compras e assinaturas via **RevenueCat**. Durante uma compra, podem ser coletados:

- Histórico de transações
- Status de entitlement (versão gratuita ou Pro)
- Identificador de compra da loja

Dados de pagamento (cartão, etc.) são tratados exclusivamente pela **Google Play Store** e nunca acessados pelo aplicativo.

---

## 4. Permissões Solicitadas

| Permissão | Finalidade | Obrigatória |
|---|---|---|
| **Internet** (`INTERNET`) | Autenticação, anúncios, analytics, sincronização | Sim |
| **Notificações** | Alertas opcionais do aplicativo | Não |
| **Câmera** | Funcionalidades futuras (ex: foto de perfil) | Não |
| **Localização** | Anúncios regionalizados (se consentido) | Não |
| **Manter tela ativa** (`WAKE_LOCK`) | Evitar que a tela apague durante uma partida | Sim |
| **Vibração** | Feedback tátil em eventos do jogo | Não |

---

## 5. Com Quem Compartilhamos seus Dados

Não vendemos seus dados pessoais. Os dados podem ser compartilhados apenas com as seguintes empresas, estritamente para as finalidades descritas:

| Parceiro | Dados compartilhados | Finalidade | Política |
|---|---|---|---|
| **Google Firebase** | UID, e-mail, eventos, logs de crash | Autenticação, analytics, crashlytics, banco de dados | [Política Google](https://policies.google.com/privacy) |
| **Google AdMob** | Ad ID, interações com anúncios | Exibição de publicidade | [Política AdMob](https://support.google.com/admob/answer/6128543) |
| **Google Sign-In** | E-mail, nome, token | Autenticação social | [Política Google](https://policies.google.com/privacy) |
| **Apple Sign-In** | E-mail (relayado), token | Autenticação social | [Política Apple](https://www.apple.com/legal/privacy/) |
| **RevenueCat** | UID, status de compra | Gerenciamento de assinaturas | [Política RevenueCat](https://www.revenuecat.com/privacy) |

---

## 6. Publicidade e Rastreamento

### Anúncios Personalizados
Por padrão, o AdMob pode veicular **anúncios personalizados** com base no seu histórico de uso. Você pode desativar a personalização nas configurações do seu dispositivo:

- **Android:** Configurações → Google → Anúncios → Cancelar personalização de anúncios

### Consentimento LGPD/GDPR
Ao abrir o aplicativo pela primeira vez, solicitamos seu consentimento explícito antes de inicializar o AdMob. Você pode revogar o consentimento a qualquer momento nas **Configurações do aplicativo**.

---

## 7. Armazenamento e Retenção de Dados

| Tipo de dado | Onde é armazenado | Período de retenção |
|---|---|---|
| Histórico de partidas | Localmente no dispositivo (Hive) | Até o usuário apagar ou desinstalar o app |
| Dados de autenticação | Firebase Auth | Até a exclusão da conta |
| Sugestões | Cloud Firestore | Até a exclusão da conta ou solicitação do usuário |
| Eventos de analytics | Firebase Analytics | 14 meses (padrão Google) |
| Logs de crash | Firebase Crashlytics | 90 dias |
| Dados de compra | RevenueCat | Conforme política da RevenueCat |

Dados armazenados localmente podem ser removidos desinstalando o aplicativo. Para dados nos servidores, veja a seção de Direitos do Usuário.

---

## 8. Segurança

Adotamos as seguintes medidas de segurança:

- Comunicação via **HTTPS/TLS** em todas as transmissões de dados
- Autenticação gerenciada pelo **Firebase Authentication** (padrão da indústria)
- Chaves de API e identificadores sensíveis não são armazenados no código-fonte público
- Acesso ao banco de dados (Firestore) restrito por **Firebase Security Rules**
- Dados locais armazenados no espaço de dados privado do aplicativo (não acessível por outros apps)

Apesar de nossos esforços, nenhum sistema é 100% seguro. Em caso de incidente de segurança, notificaremos os usuários afetados conforme exigido pela LGPD.

---

## 9. Crianças (COPPA e LGPD)

O **Marcador de Truco** **não é direcionado a crianças menores de 13 anos**. Não coletamos intencionalmente dados pessoais de crianças. Se você é responsável por uma criança que utilizou o aplicativo e deseja solicitar a exclusão de dados, entre em contato pelo e-mail indicado na seção de contato.

---

## 10. Seus Direitos (LGPD – Art. 18)

Como titular de dados, você tem os seguintes direitos garantidos pela Lei Geral de Proteção de Dados:

| Direito | Como exercer |
|---|---|
| **Confirmação e acesso** | Solicitar quais dados possuímos sobre você | 
| **Correção** | Solicitar correção de dados incompletos ou incorretos |
| **Anonimização ou exclusão** | Solicitar anonimização ou eliminação de dados desnecessários |
| **Portabilidade** | Solicitar seus dados em formato estruturado |
| **Revogação do consentimento** | Configurações do aplicativo → Privacidade |
| **Exclusão de conta** | Configurações do aplicativo → Conta → Excluir conta |
| **Oposição ao tratamento** | Entrar em contato pelo e-mail abaixo |

Para exercer qualquer direito, envie um e-mail para **suporte@seusite.com** com o assunto `[LGPD] Solicitação de Direitos`. Respondemos em até **15 dias úteis**.

---

## 11. Exclusão de Conta e Dados

Você pode excluir sua conta diretamente pelo aplicativo:

**Configurações → Conta → Excluir conta**

A exclusão de conta implica:
- Remoção permanente do UID e dados associados no Firebase
- Exclusão das sugestões vinculadas ao seu usuário no Firestore
- Cancelamento de entitlements ativos no RevenueCat

> Dados anonimizados de analytics e logs de crash (sem identificação pessoal) podem ser retidos pelos períodos indicados na tabela de retenção.

---

## 12. Alterações nesta Política

Podemos atualizar esta Política de Privacidade periodicamente. Sempre que houver alterações relevantes:

- A data de "Última atualização" será modificada nesta página
- Usuários serão notificados na próxima abertura do aplicativo (para mudanças significativas)

Recomendamos revisar esta página periodicamente. O uso continuado do aplicativo após as alterações constitui aceitação da nova versão.

---

## 13. Contato e Encarregado de Dados (DPO)

Para dúvidas, solicitações de exclusão ou exercício de direitos:

- **E-mail:** suporte@seusite.com
- **Assunto recomendado:** `[Privacidade] Sua solicitação`

Nos comprometemos a responder dentro de **15 dias úteis**.

---

## 14. Lei Aplicável e Foro

Esta Política é regida pelas leis brasileiras. Fica eleito o foro da comarca de domicílio do usuário para resolução de conflitos, conforme o Código de Defesa do Consumidor (Lei nº 8.078/1990).

---

*Esta política foi elaborada em conformidade com a LGPD (Lei nº 13.709/2018), o GDPR (Regulamento UE 2016/679) e as Políticas do Desenvolvedor do Google Play.*

---

<small>© 2026 devgmd · Marcador de Truco · [Política de Privacidade](#) · Versão 1.0</small>
