# Buscador de CEP

Este projeto é uma aplicação em React que permite a busca de um CEP (Código de Endereçamento Postal) e retorna a localidade exata consumindo uma API de dados de endereço.

## Funcionalidades

- Busca de CEP
- Exibição de informações da localidade (cidade, estado, bairro, etc.)
- Interface amigável e responsiva

## Tecnologias Utilizadas

- **React**: Biblioteca JavaScript para construção de interfaces de usuário.
- **API de CEP**: A aplicação consome uma API que fornece os dados de endereço a partir de um CEP.
- **Axios**: Biblioteca usada para realizar as requisições HTTP.
- **CSS/Styled Components**: Para estilização da interface.

## Como Funciona

1. Digite um CEP válido no campo de busca.
2. A aplicação faz uma requisição à API de CEP.
3. A API retorna os dados da localidade relacionados ao CEP informado.
4. Os dados são exibidos na tela, incluindo:
   - Logradouro
   - Bairro
   - Cidade
   - Estado
