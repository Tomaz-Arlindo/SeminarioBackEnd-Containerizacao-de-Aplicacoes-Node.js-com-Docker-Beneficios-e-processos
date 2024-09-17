# Seminário: Containerização de Aplicações Node.js com Docker

## Descrição
Este repositório contém os materiais e a apresentação do seminário sobre **Containerização de Aplicações Node.js com Docker**. Durante o seminário, discutimos os benefícios e os processos envolvidos na containerização, destacando como o Docker simplifica a gestão de ambientes e torna o desenvolvimento mais eficiente.

## Estrutura do Repositório
- **Dockerfile**: Arquivo utilizado para criar o container da aplicação Node.js.
- **Apresentação.pdf**: Slides utilizados durante a apresentação.
- **LICENSE**: Licença GNU
- **CONTRIBUTING.md**: Guia para contribuir com o projeto.

## Benefícios da Containerização
- **Portabilidade**: Aplicações podem ser executadas em qualquer ambiente, independentemente da infraestrutura.
- **Escalabilidade**: Facilidade em replicar e distribuir containers conforme a demanda.
- **Consistência**: Ambientes de desenvolvimento, teste e produção são idênticos.
- **Isolamento**: Cada container opera de forma independente, garantindo mais segurança.

## Tecnologias Utilizadas
- **Node.js**: Plataforma para execução de JavaScript no lado do servidor.
- **Docker**: Tecnologia de containerização usada para encapsular a aplicação e suas dependências.

## Como Executar o Projeto
1. Clone o repositório:
   ```bash
   git clone https://github.com/seuusuario/SeminarioBackEnd-Containerizacao
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd SeminarioBackEnd-Containerizacao
   ```
3. Construa a imagem Docker:
   ```bash
   docker build -t node-app .
   ```
4. Execute o container:
   ```bash
   docker run -d -p 3000:3000 node-app
   ```
5. Acesse a aplicação no navegador:
   - `http://localhost:3000`
