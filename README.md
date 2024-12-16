# Chatbot

Este projeto implementa um chatbot utilizando Python. Abaixo estão as instruções para configurar e executar o projeto no seu ambiente local, utilizando o VS Code.

## 🛠 Pré-requisitos

1. **Python 3.13**

   - Certifique-se de que o Python está instalado e configurado no PATH do sistema.
   - Você pode verificar a versão instalada executando o comando:
     ```bash
     python --version
     ```

2. **Visual Studio Code**

   - Instale o VS Code a partir do [site oficial](https://code.visualstudio.com/).
   - Certifique-se de instalar a extensão "Python" no VS Code.

3. **Gerenciador de Pacotes (pip)**

   - O pip já vem incluído em versões modernas do Python. Verifique se está funcionando:
     ```bash
     pip --version
     ```

## ⚙️ Configuração

1. **Clone ou Extraia o Projeto**

   - Se você recebeu o projeto como um arquivo ZIP, extraia o conteúdo para uma pasta local.

2. **Instale as Dependências**

   - Navegue até o diretório do projeto no terminal:
     ```bash
     cd caminho/para/pasta/Chatbot
     ```
   - Caso o projeto possua um arquivo `requirements.txt`, instale as dependências com:
     ```bash
     pip install -r requirements.txt
     ```

3. **Configuração do Ambiente Virtual (opcional, mas recomendado)**

   - Crie um ambiente virtual:
     ```bash
     python -m venv venv
     ```
   - Ative o ambiente virtual:
     - **Windows**:
       ```bash
       .\venv\Scripts\activate
       ```
     - **Linux/Mac**:
       ```bash
       source venv/bin/activate
       ```
   - Instale as dependências dentro do ambiente virtual (caso ainda não tenha feito):
     ```bash
     pip install -r requirements.txt
     ```

## ▶️ Executando o Projeto

1. Abra a pasta do projeto no VS Code:

   - No menu do VS Code, clique em **File > Open Folder** e selecione a pasta do projeto.

2. Configure o interpretador Python:

   - Pressione `Ctrl+Shift+P` (ou `Cmd+Shift+P` no Mac) para abrir a paleta de comandos.
   - Digite e selecione **Python: Select Interpreter**.
   - Escolha o interpretador correspondente à sua versão do Python ou ao ambiente virtual criado.

3. Execute o arquivo principal do projeto:

   - Identifique o arquivo principal (geralmente `main.py`, `app.py` ou outro indicado na documentação).
   - No terminal do VS Code, execute o comando:
     ```bash
     python nome_do_arquivo_principal.py
     ```

## 🛠 Personalizações e Debug

1. Para depuração, configure o **launch.json** no VS Code:

   - Vá em **Run and Debug > Create a launch.json file**.
   - Escolha Python e ajuste as configurações conforme necessário.

2. Adicione logs ou use breakpoints para depurar o código.

## 🤝 Contribuição

Sinta-se à vontade para contribuir com melhorias ou relatórios de bugs. Para isso:

1. Faça um fork do repositório.
2. Crie uma nova branch para suas alterações:
   ```bash
   git checkout -b minha-feature
   ```
3. Envie suas alterações via pull request.

## 📬 Contato

Caso tenha dúvidas ou precise de suporte, entre em contato com o responsável pelo projeto.

