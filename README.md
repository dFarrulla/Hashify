# Hashify

Este projeto é uma ferramenta em Java para verificar a integridade de arquivos por meio de cálculo de hashes MD5.

## Descrição

A ferramenta percorre uma pasta no computador e calcula o hash MD5 de cada arquivo presente nessa pasta. O resultado é armazenado em um arquivo de saída chamado "listaDeHash.txt". O cálculo de hash MD5 é usado para verificar se houve alguma alteração nos arquivos desde a última execução do programa.

## Requisitos

- Java Development Kit (JDK) 8 ou superior
- Eclipse IDE (opcional)

## Como usar

1. Faça o download ou clone o repositório para o seu computador.

2. Abra o projeto no Eclipse (ou outro ambiente de desenvolvimento Java, se preferir).

3. Abra a classe "Hash" no pacote "com.example".

4. No método `main`, atualize a variável `folderPath` com o caminho da pasta que você deseja verificar a integridade.

5. Execute o programa. Os hashes dos arquivos na pasta especificada serão calculados e salvos no arquivo "listaDeHash.txt".

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para enviar pull requests ou relatar problemas no repositório.

## Licença

Este projeto está licenciado sob a licença [MIT](https://opensource.org/licenses/MIT).

