# 🍳 IA Geradora de Receitas

Gerador de receitas utilizando Inteligência Artificial com LangChain e Groq.

O projeto funciona no terminal e cria receitas completas de forma simples, divertida e prática.

---

## 🚀 Tecnologias

- Python
- LangChain
- Groq API
- Llama 3
- Prompt Engineering
- python-dotenv

---

## ⚙️ Funcionalidades

- Geração automática de receitas
- Respostas organizadas e amigáveis
- Receitas completas com ingredientes e preparo
- Interface simples no terminal
- Uso de IA com LangChain + Groq

---

## 🤖 Como a IA funciona

O projeto utiliza a API da Groq junto com o modelo Llama 3 para gerar receitas personalizadas com base no pedido do usuário.

A IA responde como um chef de cozinha experiente, ensinando receitas de maneira leve e prática.

---

## 🔑 Como configurar a API da Groq

1. Acesse o site da [Groq](https://console.groq.com).
2. Crie uma conta ou faça login.
3. Acesse a área de API Keys e clique em **Create API Key**.
4. Copie a chave gerada.

Na pasta principal do projeto, crie um arquivo chamado `.env` e adicione:

```env
GROQ_API_KEY=sua_chave_aqui
```

O arquivo `.env` armazena sua chave em seu computador. Não compartilhe nem publique esse arquivo no GitHub.

---

## ▶️ Como executar

### 1. Instale as dependências

Com o terminal aberto na pasta do projeto, execute:

```bash
pip install -U langchain langchain-core langchain-groq python-dotenv
```

### 2. Configure a chave da API

Verifique se o arquivo `.env` está na mesma pasta do arquivo `main.py` e contém sua chave da Groq.

### 3. Execute o projeto

```bash
python main.py
```

O programa será iniciado no terminal. Digite o que deseja comer para receber uma receita. Para encerrar, digite `x`.

---

## 📷 Exemplo de uso

```text
Você: bolo de chocolate

Receita:

🍫 Bolo de Chocolate Fofinho

Tempo de preparo: 50 minutos

Ingredientes:
- 2 xícaras de farinha
- 1 xícara de açúcar
- ...
```

---

## 📚 Aprendizados

Durante este projeto foram praticados:

- Integração com APIs de IA
- Prompt Engineering
- Uso de LangChain
- Estruturação de aplicações com IA
- Manipulação de entrada do usuário
- Organização de projetos Python

---

## 📄 Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo `LICENSE` para mais informações.
