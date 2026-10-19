# Storefront Template Library

Repositório de temas estáticos (HTML5 e CSS3) para produtos e serviços, construídos para integração dinâmica com o nosso backend.

Templates contam com padronização de IDs para integração e manipulação de DOM via backend

## Como visualizar os templates

a visualização não exige configuração de ambiente.

1. **Baixe o projeto:**
   Faça o clone via terminal:
   ```bash
   git clone https://github.com/SEU-USUARIO/storefront-template-library.git
   ```
   *(Ou baixe o arquivo .zip clicando no botão "Code" > "Download ZIP" no GitHub e extraia em seu computador).*

2. **Abra no navegador:**
   Navegue pelo seu explorador de arquivos até a pasta do template desejado (dentro de `/templates/produtos/` ou `/templates/servicos/`). Dê um duplo clique no arquivo `index.html` e ele abrirá perfeitamente em qualquer navegador web.

3. **Recomendação para edição (Live Server):**
   Caso vá editar o código, abra a pasta do projeto no **VS Code** e instale a extensão **Live Server**. Clique com o botão direito no arquivo `index.html` e selecione *"Open with Live Server"* para visualizar as alterações de CSS e HTML em tempo real ao salvar.

## Estrutura de Pastas

- `/templates/produtos/`: Catálogos para venda de produtos físicos ou digitais.
- `/templates/servicos/`: Páginas para prestadores de serviços, clínicas, consultorias.
- `/docs/universal-ids.md`: Documento fundamental contendo a lista de todos os `IDs` universais (ex: `id="buy-button"`, `id="product-price"`) que o backend lê para ocultar, mostrar ou editar os elementos conforme a configuração do cliente.

> **Nota:** Dentro da pasta de cada template, você encontrará um arquivo `author.txt` indicando o responsável pela criação daquele layout.