# varejinho
# 🤖 Bot de Consultoria - Varejão Rejunte

Este é um assistente virtual inteligente desenvolvido para o **Varejão Rejunte**. O bot utiliza a API do **Telegram** e o modelo de linguagem **Llama 3 (via Groq)** para realizar uma consultoria de vendas personalizada de pisos laminados.

## 🚀 Objetivo do Projeto
Diferente de um bot de vendas comum, este assistente atua como um **consultor técnico**. Ele foi treinado para:
- Entender a necessidade do cliente antes de oferecer preços.
- Valorizar produtos de alto padrão (**Max Elegance** e **New Evidence**).
- Manter o histórico da conversa (memória) para evitar perguntas repetitivas.
- Direcionar casos complexos para as lojas físicas de Pelotas e Rio Grande.

## 🛠️ Tecnologias Utilizadas
* **Python 3.14**
* **python-telegram-bot**: Integração com a API do Telegram.
* **Groq Cloud SDK**: Acesso ao modelo Llama 3.3 70B para processamento de linguagem natural.
* **Logging**: Para monitoramento de eventos e erros no terminal.

## 📋 Funcionalidades
- **Memória de Usuário**: O bot armazena as últimas 10 mensagens de cada cliente para manter o contexto.
- **Venda Consultiva**: Foca em durabilidade (AC4) e design (réguas de 21cm) antes de falar de valores.
- **Tratamento de Objeções**: Segura a informação de preço até entender o ambiente de instalação, garantindo que o cliente veja o valor do produto premium.
- **Suporte a Redes Instáveis**: Configuração preparada para rodar em ambientes com proxy ou oscilações de conexão.

## 🔧 Como Instalar e Rodar

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/seu-usuario/bot_varejao.git](https://github.com/seu-usuario/bot_varejao.git)
   cd bot_varejao
