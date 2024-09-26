# Portfolio

Este é um projeto de portfólio desenvolvido usando Flask. O objetivo deste projeto é fornecer uma página simples e estilosa para exibir suas informações profissionais e projetos.

## Estrutura do Projeto

- **app.py**: Arquivo principal da aplicação Flask.
- **requirements.txt**: Arquivo contendo as dependências do projeto.
- **static/**: Pasta onde estão armazenados os arquivos estáticos, como CSS e imagens.
  - **index.css**: Estilos personalizados para a página HTML.
  - **logo.png**: Logo utilizada no site.
  - **photo.png**: Foto usada no site.
- **templates/**: Pasta onde estão os templates HTML.
  - **index.html**: Página principal da aplicação.

## Como Executar o Projeto

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/seu-usuario/Portfolio.git
   cd Portfolio
   ```

2. **Crie um ambiente virtual e ative-o:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/MacOS
   venv\Scripts\activate  # Windows
   ```

3. **Instale as dependências:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Execute a aplicação:**

   ```bash
   python app.py
   ```

5. **Acesse a aplicação no seu navegador:**

   Abra o navegador e vá para `http://127.0.0.1:5000`.

## Uso de Bootstrap

O projeto utiliza o [Bootstrap](https://getbootstrap.com/) para estilização e layout responsivo. O Bootstrap é uma biblioteca de CSS que facilita a criação de layouts modernos e responsivos sem muito esforço.

### Onde o Bootstrap é Utilizado:

- **index.html**: O Bootstrap é importado diretamente no `<head>` da página HTML para fornecer classes utilitárias usadas em diversos elementos da página, como containers, grids e botões.
- **index.css**: O arquivo `index.css` pode conter customizações adicionais ou sobreposições às classes do Bootstrap para ajustar a aparência conforme necessário.

## Personalização

Você pode personalizar o conteúdo da página editando o arquivo `index.html` na pasta `templates`. Para mudar os estilos, edite o arquivo `index.css` na pasta `static`. Se precisar alterar algo relacionado ao layout, considere o uso das classes do Bootstrap ou adicione suas próprias classes CSS.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.

