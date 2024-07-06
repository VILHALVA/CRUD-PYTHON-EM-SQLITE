# CRUD PYTHON EM SQLITE
👨‍🏫PROJETO CRIADO PARA O CURSO DE PYTHON COM SQLITE.

<img src="./IMAGENS/FOTO_1.png" align="center" width="500"> <br>
<img src="./IMAGENS/FOTO_2.png" align="center" width="500"> <br>
<img src="./IMAGENS/FOTO_3.png" align="center" width="500"> <br>
<img src="./IMAGENS/FOTO_4.png" align="center" width="500"> <br>
<img src="./IMAGENS/FOTO_5.png" align="center" width="500"> <br>

## DESCRIÇÃO:
Este script Python implementa um sistema simples de gerenciamento de clientes usando SQLite como banco de dados. Ele fornece funcionalidades básicas de CRUD (Create, Read, Update, Delete) para interagir com uma tabela de clientes em um banco de dados SQLite.

Este sistema é útil para demonstrar conceitos básicos de manipulação de banco de dados SQLite em Python e pode ser expandido para aplicativos mais complexos conforme necessário.

## RECURSOS:
1. **Conexão com o Banco de Dados:**
   - A função `conectar()` é responsável por conectar ao banco de dados SQLite. O arquivo do banco de dados é `"database.db"`.

2. **Criação da Tabela de Clientes:**
   - A função `criar_tabela()` cria a tabela de clientes se ela ainda não existir no banco de dados. A tabela possui os campos `id`, `nome`, `telefone` e `email`.

3. **Inserção de Cliente:**
   - A função `inserir_cliente()` permite adicionar um novo cliente ao sistema. Ela solicita nome, telefone e email do cliente, valida os campos e insere os dados na tabela.

4. **Visualização de Clientes:**
   - A função `visualizar_clientes()` exibe todos os clientes cadastrados no sistema, recuperando as informações da tabela de clientes.

5. **Atualização de Cliente:**
   - A função `atualizar_cliente()` permite atualizar as informações de um cliente existente. Solicita o ID do cliente, o novo nome, telefone e email, valida os campos e atualiza os dados na tabela.

6. **Exclusão de Cliente:**
   - A função `deletar_cliente()` permite excluir um cliente do sistema. Solicita o ID do cliente a ser excluído e remove as informações correspondentes da tabela.

7. **Menu de Opções:**
   - O script exibe um menu de opções numeradas onde o usuário pode escolher entre adicionar, visualizar, atualizar ou excluir clientes, além de sair do programa.

## EXECUTANDO O PROJETO:
1. **Instalação das Dependências::**
   - Entre no diretório `CODIGO` e execute o comando:

   ```bash
   pip install -r requirements.txt
   ```

2. Para executar o arquivo Python, utilize o comando abaixo no terminal, dentro do diretório `./CODIGO`:

   ```
   python CODIGO.py
   ```

## SOBRE O EXECUTAVEL:
### 1. EXECUTANDO:
- Este arquivo executável está disponível apenas para `Windows X64`. Para executá-lo, basta dar dois cliques. O executável é bastante útil caso o Python não esteja instalado. Trata-se da mesma aplicação do arquivo `CODIGO.py`. Se desejar, você pode recompilá-lo novamente; é para isso que forneci o arquivo `imagem.ico`.

### 2. GERANDO:
   **1. Instalação do [PyInstaller:](https://pyinstaller.org/en/stable/)**
   - Certifique-se de ter o PyInstaller instalado. Se não tiver, instale usando o comando abaixo:
   ```bash
   pip install pyinstaller
   ```

   **2. Gerando o Executável:**
   - Para gerar o executável, utilize o comando `pyinstaller` seguido de opções:
      - `--icon="imagem.ico"`: Especifica o ícone do executável.
      - `-F`: Gera um único arquivo executável em vez de vários.
      - `CODIGO.py`: Substitua "CODIGO.py" pelo nome do seu arquivo Python principal.
   ```bash
   pyinstaller --icon="imagem.ico" -F CODIGO.py
   ```

## CREDITOS:
- [PROJETO CRIADO PARA CURSO DE PYTHON COM SQLITE](https://github.com/VILHALVA/CURSO-DE-PYTHON-COM-SQLITE)
- [PROJETO CRIADO PELO VILHALVA](https://github.com/VILHALVA)


