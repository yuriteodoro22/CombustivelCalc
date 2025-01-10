# Gasolina ou Álcool? 🚗⛽

Este é um aplicativo React desenvolvido para ajudar os usuários a decidir qual combustível é mais vantajoso, gasolina ou álcool, com base nos preços informados. A decisão é baseada no cálculo econômico: se o valor do álcool dividido pelo da gasolina for menor ou igual a **0.7**, o álcool é a melhor opção; caso contrário, a gasolina compensa mais.

## Funcionalidades

- **Cálculo de viabilidade econômica**:
  - Determina se é mais vantajoso utilizar álcool ou gasolina com base nos preços fornecidos.
- **Interface intuitiva**:
  - Formulário simples para inserir os preços.
  - Resultado exibido em destaque, mostrando a melhor escolha e os valores inseridos formatados em reais (R$).
- **Feedback visual interativo**:
  - O resultado é exibido em uma caixa com animação ao passar o mouse.

## Tecnologias Utilizadas

- **React**
- **TypeScript**
- **Vite** como ferramenta de build
- **CSS Modules** para estilização

## Estrutura do Projeto

- **App.tsx**: Componente principal que realiza os cálculos e gerencia o estado do formulário.
- **main.tsx**: Ponto de entrada do projeto.
- **CSS**: Estilização customizada para o layout da aplicação.

## Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/gasolina-ou-alcool.git
   ```

2. Acesse o diretório do projeto:
   ```bash
   cd gasolina-ou-alcool
   ```

3. Instale as dependências:
   ```bash
   npm install
   ```

4. Execute a aplicação:
   ```bash
   npm run dev
   ```

5. Acesse no navegador:
   ```
   http://localhost:5173
   ```

## Estrutura de Diretórios

```plaintext
src/
├── assets/
│   └── logo.png
├── styles/
│   ├── App.css
│   └── index.css
├── App.tsx
├── main.tsx
├── vite-env.d.ts
```

## Estilo e Layout

- **App.css**: Define o layout principal, incluindo a responsividade, estilos do formulário e resultado interativo.
- **index.css**: Configura o estilo global da aplicação, como fontes e cores de fundo.

## Licença

Este projeto está licenciado sob a MIT License. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

**Desenvolvido por Yuri Teodoro**
