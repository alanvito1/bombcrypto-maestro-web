# ⚡ Bombcrypto Maestro Web

> Um painel web de altíssimo nível, 100% client-side e descentralizado, desenvolvido para o ecossistema de Bombcrypto. Projetado para as redes BNB Smart Chain (BSC) e Polygon, unindo estética glassmorphism premium com automação on-chain ultra-eficiente.

---

## 💎 Funcionalidades de Elite

### 1. 🦊 Integração Multi-Chain Nativa e Segura
*   Suporte completo a **BSC (Mainnet/Testnet)** e **Polygon (Mainnet/Testnet)**.
*   Conexão client-side segura via MetaMask (Ethers.js v6).
*   Detecção inteligente de rede com troca automática (auto-switch) ou alertas intuitivos na interface.
*   Zero banco de dados centralizado — privacidade total dos seus ativos.

### 2. ⚡ Mint e Processamento Totalmente Automático
*   Compre seus Mints em lote com estimativa de custos de BCOIN atualizada em tempo real.
*   **Autoclaim Integrado**: Assim que você assina e confirma a solicitação de mint, a ferramenta aguarda a inclusão na blockchain e **dispara a transação de processamento automaticamente**!
*   **Reveal Showcase Premium**: Um modal deslumbrante com efeitos de iluminação e brilhos (glow) temáticos específicos de acordo com a raridade do herói gerado (do Comum ao Super Lendário!).

### 3. 🌀 Fusão Inteligente em Lote (Mass Fusion)
*   Selecione dezenas de heróis diretamente na interface e realize fusions com apenas um clique.
*   Lógica otimizada para consolidar transações e economizar taxas de gás (taxas de transação) de forma massiva.
*   Controles de segurança para evitar queimar heróis com raridades elevadas acidentalmente.

### 4. 📦 Envio em Lote (Mass Transfer)
*   Envie múltiplos heróis de forma segura para outras carteiras em uma transação limpa.
*   Interface fluida com grids responsivos e seleção visual rápida.

---

## 🛠️ Arquitetura e Tecnologia

A interface foi projetada seguindo padrões modernos de Web Design e engenharia de DApps:
*   **Frontend**: HTML5 Semântico e Vanilla Javascript puro, garantindo velocidade de carregamento instantânea e zero dependências pesadas.
*   **Estilização**: Vanilla CSS customizado com variáveis CSS dinâmicas, tema escuro nativo (*Dark Mode*), desfoques de fundo (*Glassmorphism*) e micro-animações de alto desempenho.
*   **Web3 Integration**: Ethers.js v6 para comunicação direta com os nós RPC e com a extensão MetaMask.

---

## 🚀 Como Executar Localmente

Como a aplicação é totalmente estática e roda no lado do cliente, você pode iniciá-la em segundos:

1. Clone ou baixe este repositório.
2. Navegue até a pasta do projeto:
   ```bash
   cd bombcrypto-maestro-web
   ```
3. Inicie um servidor HTTP local simples (por exemplo, usando Python):
   ```bash
   python -m http.server 8000
   ```
4. Abra o seu navegador e acesse:
   ```
   http://localhost:8000
   ```

*(Nota: É necessário abrir a página através de um servidor local para que o provedor Web3 MetaMask injete o objeto de conexão corretamente e de forma segura).*

---

## 🗺️ Como Hospedar Grátis no GitHub Pages

Para disponibilizar seu painel na web de forma 100% gratuita e integrada ao seu repositório:

1. Acesse o seu repositório no GitHub.
2. Vá em **Settings** > **Pages**.
3. Na seção **Build and deployment**, selecione a branch `main` e a pasta `/ (root)`.
4. Clique em **Save**.
5. Em poucos minutos, seu site estará no ar no endereço `https://<seu-usuario>.github.io/bombcrypto-maestro-web/`!

---

## 🔒 Segurança e Transparência

Este repositório é dedicado exclusivamente à interface visual e comunicação Web3 direta com contratos públicos:
*   **Zero Segredos**: O código não possui servidores intermediários, chaves privadas hardcoded ou logs externos. Toda e qualquer interação on-chain exige a sua assinatura explícita na MetaMask.
*   **Auditoria Amigável**: Todo o fluxo lógico está concentrado no arquivo `index.html`, permitindo leitura fácil e auditoria por qualquer desenvolvedor da comunidade.

---

## 📄 Licença

Distribuído sob a licença **MIT**. Veja o arquivo `LICENSE` para mais informações.
