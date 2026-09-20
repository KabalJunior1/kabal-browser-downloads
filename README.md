# Kabal Browser — downloads

Repositório público que hospeda **apenas os instaladores** do Kabal Browser e a página de download.
O código-fonte fica em um repositório privado separado.

- Página: https://kabaljunior1.github.io/kabal-browser-downloads/
- Instaladores: aba [Releases](../../releases)

## Como funciona

O workflow `Build & Release` do repositório privado compila macOS e Windows nos runners do GitHub
e publica um Release aqui a cada tag `v*`. A `index.html` lê a Release mais recente pela API pública
do GitHub, detecta o sistema de quem está visitando e oferece o arquivo certo.

Nada aqui precisa ser editado à mão para lançar uma versão nova.
