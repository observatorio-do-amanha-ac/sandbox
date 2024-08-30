# Sandbox para aprendermos alguns conceito de ENGENHARIA DE DADOS, SQL e Python


## Instruções

### Clonando o repositório do projeto

Podemos escolher duas maneiras de trabalharmos com os notebooks: 

1. Clonando o repositório do GitHub no ambiente do Google Colab
2. Clonando o repositório na sua máquina local. 

Para ambos os casos, utilizamos os comandos `git`, por exemplo, para o desenvolvimento local basta digitar no seu terminal (no vscode ou no terminal da sua máquica) o comando `git clone <link do repo>`.

Contudo, quem optar pela opção 1, deve seguir o seguintes passos: 

1. Acesse o Google Colab
2. Normalmente, o Colab apresenta um pop-up para você selecionar um novo notebok. Caso esse pop-up não apareça, clique em **Arquivo** > **Abrir Notebook** no menu superior.
3. Na janela do pop-up, no canto esquerdo, existem algumas opções para abertura de um novo notebook, escolha **GitHub**.
4. Copie o endereço (URL) desse repositório (https://github.com/observatorio-do-amanha-ac/sandbox/) e cole na caixa de texto que o solicita.
5. Caso o google peça permissão para se conectar com sua conta do **GitHub**, siga o fluxo de permissões normalmente.
6. O Colab irá exibir uma lista dos notebooks desse repostório. Clique duas vezes no link "notebooks/create_ac_fake_oltp_db.ipynb"
7. O notebook `create_ac_fake_oltp_db.ipynb` pode ser acessado. A instruções para clonar o repositório estão descrita no próprio notebook. Divirta-se!

## Desenvolvendo Localmente

Se você quer desenvolver usando sua própria máquica, estes passoas te orientarão a criar um ambiente virtual Python, instalar o JupyterLab e as bibliotecas Faker, Pandas e DuckDB.

### **Passo 1**: Instalar o Python

Antes de começar, lógico, certifique-se de ter o Python instalado no seu sistema. Você pode baixar a versão mais recente do Python [aqui](https://python.org.br/instalacao-windows/).

- Verifique a instalação:

Abra um terminal (vscode ou do seu sistema) e digite:

```bash
python --version
```

Ou, se estiver usando python3:

```bash
python3 --version
```
Se o Python estiver instalado corretamente, você verá a versão instalada no terminal.

### **Passo 2**: Criar um Ambiente Virtual

Um ambiente virtual isola as dependências do Python usadas em seu projeto. Isso garante que as bibliotecas instaladas não interfiram em outros projetos ou outros programas da sua máquina.

- Criar o ambiente virtual:

```bash
python -m venv myenv
```
Substitua `myenv` pelo nome que você deseja dar ao seu ambiente virtual.

- Ativar o ambiente virtual:

**Windows**:

```bash
myenv\Scripts\activate
```
**MacOS/Linux**:

```bash
source myenv/bin/activate
```
Após ativar, o nome do ambiente aparecerá no início da linha de comando, indicando que o ambiente virtual está ativo.

### **Passo 3**: Atualizar o Pip

É sempre uma boa prática atualizar o pip, o gerenciador de pacotes do Python, dentro do ambiente virtual.

```bash
pip install --upgrade pip
```

### **Passo 4**: Instalar o JupyterLab e Bibliotecas Necessárias

Instalar o JupyterLab:

```bash
pip install jupyterlab
```

- Instalar o Ipython_sql

```bash
pip install ipython_sql
```

- Instalar o Faker, Pandas e DuckDB:

```bash
pip install faker pandas duckdb
```
Esses comandos instalarão o JupyterLab, bem como as bibliotecas faker, pandas e duckdb no ambiente virtual ativo.

### **Passo 5**: Iniciar o JupyterLab

Após a instalação, você pode iniciar o JupyterLab dentro do ambiente virtual.

- Iniciar o JupyterLab:

```bash
jupyter-lab
```
Isso abrirá o JupyterLab em seu navegador padrão.

Pronto, agora você deve estar pronto ou pronta para brincar! :D