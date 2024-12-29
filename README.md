# File-Extension-Group

**File-Extension-Group** é um aplicativo desenvolvido em C# utilizando Worker Services que percorre as pastas do Windows dentro da pasta do usuário e agrupa todos os arquivos por suas extensões. A ferramenta organiza os arquivos de forma eficiente, permitindo uma visualização mais clara e facilitando o gerenciamento de arquivos no sistema.

## Funcionalidades

- Percorre automaticamente todas as pastas dentro da pasta do usuário.
- Agrupa arquivos por suas extensões (ex: `.jpg`, `.txt`, `.pdf`, `.docx`, etc.).
- Organiza os arquivos para facilitar a navegação e a gestão no sistema.
- Executa como um serviço de background utilizando Worker Services.

## Tecnologias Utilizadas

- **C#**
- **.NET Core Worker Service**
- **Windows File System API**
- **LINQ** (para agrupamento e manipulação dos arquivos)

## Como Usar

1. **Clone o Repositório:**
  ```bash
  git clone https://github.com/seunome/file-extension-group.git
  ```

2. **Instale as Dependências:**
Navegue até a pasta do projeto e execute o comando para restaurar as dependências:
```bash
dotnet restore
 ```

3. **Compilar o Projeto:**
Para compilar o projeto, execute o seguinte comando:
```bash
dotnet build
```


4. **Executar o Serviço:**
Para rodar o serviço em segundo plano, use o comando:

```bash
dotnet run
```

## O serviço começará a percorrer as pastas do usuário e agrupará os arquivos por extensão.
