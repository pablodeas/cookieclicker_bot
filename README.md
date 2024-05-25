# Cookie Clicker Automator com Selenium

Este projeto utiliza o Selenium para automatizar o jogo Cookie Clicker, permitindo que o usuário acumule quantos cookies possível e compre produtos automaticamente quando os cookies suficientes estiverem disponíveis.

## Requisitos

- Python 3.x
- Selenium
- ChromeDriver (versão compatível com o seu navegador Google Chrome instalado)

## Instalação

1. Certifique-se de ter o Python 3.x instalado em sua máquina.
2. Instale o Selenium executando `pip install selenium` no terminal.
3. Baixe o ChromeDriver correspondente à versão do seu navegador Google Chrome e coloque-o no diretório do projeto (`./chromedriver`).

## Uso

Para executar o script, abra um terminal na pasta do projeto e execute o comando `python click.py`.

O script faz o seguinte:

- Abre o navegador Chrome e acessa o site do Cookie Clicker.
- Alterna o idioma para inglês.
- Clica no cookie grande repetidamente.
- Compra os produtos disponíveis sempre que tem cookies suficientes.

## Notas

- O script assume que você está jogando em modo não bloqueador de anúncios.
- A automação pode ser detectada pelo jogo, resultando em restrições ou bloqueio da conta.
- É recomendável rodar o script durante períodos curtos para evitar suspeitas de atividade automatizada.
