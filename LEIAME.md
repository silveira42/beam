# Beam

[![en](https://img.shields.io/badge/lang-en-red.svg)](https://github.com/silveira42/beam/blob/main/README.md)
[![pt-br](https://img.shields.io/badge/lang-pt--br-green.svg)](https://github.com/silveira42/beam/blob/main/LEIAME.md)

Beam é uma aplicação web super simples que permite que você faça upload de arquivos numa pasta específica em seu dispositivo host e compartilhe-os com clientes através de um servidor HTTP. Você pode expor esse servidor através de uma VPN pessoal ou publicá-lo na internet. Tenha em mente que esta é uma solução muito simplista, **sem medidas de segurança incluídas**, então hospede por sua própria conta e risco.

## Veja ao vivo
[Um Beam está hospedado aqui](https://beam.thesilver.com.br)

## Modo de uso
1. Crie uma pasta chamada Beam em sua pasta home do Linux.
2. Adicione os arquivos que você deseja compartilhar nesse diretório.
3. Clone o repositório no diretório de sua escolha.
4. Execute `docker compose up -d` na raiz do projeto.
5. Abra `http://localhost:25113` em seu navegador da web.
6. Insira o nome do arquivo desejado no campo de entrada.
7. Clique no botão "Baixar" para baixar o arquivo.
8. Você pode hospedar isso fora de sua rede local por sua própria conta e risco.

## Estrutura do Projeto
```
.
├── index.html
├── README.md
├── LEIAME.md
├── docker-compose.yml
├── nginx.conf
└── LICENSE
```

## Dependências
Este projeto não possui dependências externas. É construído usando HTML, CSS e JavaScript puros.

## Contribuindo
1. Faça um fork do repositório.
2. Crie um novo branch (`git checkout -b feature-branch`).
3. Faça suas alterações.
4. Faça commit de suas alterações (`git commit -m 'Adicionar nova funcionalidade'`).
5. Faça push para o branch (`git push origin feature-branch`).
6. Abra um pull request.

## Licença
Este projeto está licenciado sob a Licença GNU GPLv3. Consulte o arquivo `LICENSE` para obter mais detalhes.

## Agradecimentos
- [JustBeamIt](https://justbeamit.com) por fornecer um serviço rápido de upload de arquivos.

## Contato
Para mais informações, visite [The SilverHub](https://thesilver.com.br).

