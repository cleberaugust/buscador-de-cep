# 🔍 Buscador de CEP

Um projeto Java moderno para consulta de endereços utilizando a API ViaCEP, manipulação de JSON com a biblioteca Gson e persistência de dados em arquivos locais.

## 🛠️ Tecnologias e Conceitos Utilizados
* **Java 17+**: Uso de Records para imutabilidade de dados.
* **HttpClient**: Requisições assíncronas e modernas para consumo de APIs.
* **Gson (Google)**: Serialização e desserialização de objetos JSON.
* **Tratamento de Exceções**: Robustez no fluxo de erro de busca.
* **Manipulação de Arquivos**: Geração dinâmica de arquivos JSON personalizados.

## 🚀 Como funciona
O sistema solicita um número de CEP ao usuário, realiza uma consulta HTTP na API ViaCEP e, caso o CEP seja válido:
1. Retorna um objeto `Endereco`.
2. Exibe os dados no console.
3. Gera um arquivo `.json` nomeado com o próprio CEP contendo as informações formatadas.

## 📦 Como executar
1. Clone o repositório.
2. Certifique-se de ter o JDK 17 ou superior.
3. Adicione a dependência do **Gson** ao seu projeto.
4. Execute a classe `Main`.
