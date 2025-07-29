# AtendimentoAlfa
Bot de atendimento automatizado via WhtatsApp usando MyZap
# 🤖 AtendimentoAlfa

Automatize conversas no WhatsApp com inteligência e rapidez usando o bot **MyZap** e a infraestrutura da **Railway**.

## 🚀 Funcionalidades

- Envio e recebimento de mensagens pelo WhatsApp
- Integração com Make.com (antigo Integromat)
- Sessões múltiplas e configuração via `.env`
- API REST com endpoints para QR Code e mensagens

## 🔧 Tecnologias Utilizadas

- Node.js
- Express
- MyZap (engine Venom)
- Railway (hospedagem)
- GitHub (versionamento)
- Make.com (automação)

## 🛠️ Como usar

1. Clone este repositório:
   ```bash
   git clone https://github.com/SEUUSUARIO/AtendimentoAlfa.git
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

3. Configure o arquivo `.env` com suas variáveis

4. Inicie o projeto:
   ```bash
   npm start
   ```

5. Escaneie o QR Code via endpoint:
   ```
   /qrcode?sessionName=session1&image=true
   ```

## 📄 Licença

Este projeto está sob a licença [MIT](LICENSE).

---

Feito com 💚 por Adriano
