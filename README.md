# vmix-lang-pt-br

Repositório criado para gerenciar a tradução do vMix para português do Brasil.

# Instalando a tradução no vMix

Primeiro você deve acessar a [última tradução disponível](https://github.com/jonatasoliveira/vmix-lang-pt-br/releases/latest), baixar o arquivo `pt.txt.zip` no seu computador e descompactar o arquivo e ter certeza que o nome do arquivo descompactado é `pt.txt`.

Passos para instalar a tradução:

* Feche o vMix antes de começar o processo
* Copie o arquivo recém baixado para a pasta: `C:\Arquivos de Programas (x86)\vMix\languages`
* Abra o vMix e verifique se a tradução foi atualizada
* Se o vMix ainda estiver em inglês, você precisa selecionar o idioma "Português" nas configurações do vMix

Caso no momento da cópia do arquivo de tradução já exista um arquivo chamado `pt.txt` na pasta do vMix você pode substituí-lo, ou, se achar necessário, fazer um backup desse arquivo.

# Frases não traduzidas

Ainda existem várias áreas do vMix que não são possíveis de serem traduzidas no momento, provavelmente por que os desenvolvedores não fizeram a implementação da tradução nesses locais, e por esse motivo mesmo que a tradução dos arquivos do vMix esteja 100% executada ainda existirão algumas janelas ou opções que ficarão em inglês.

Aqui segue uma lista de algumas telas que sabemos não podem se traduzidas atualmente:

* "Configurar" > "Saídas / NDI / SRT" só pode ser parcialmente traduzida
* "Configurar" > "Saídas / NDI / SRT" > ícone de engrenagem em um Output > "Output Settings"
* "Configurar" > "Saídas / NDI / SRT" > "Personalize o layout" dentro de MultiView > "Customise Layout"
* Cabeçalho das abas de "Triggers", "Atalhos" e "Ativadores"
* Tela de adicionar um ativador

# Considerações da tradução

Algumas palavras foram deixadas em inglês pois fazem mais sentido na sua língua padrão e acredito que isso reduz a possibilidade de problemas de comunicação entre as pessoas que usam vMix aqui no Brasil, por exemplo:

* Input
* Overlay
* Master (quando se trata do Bus Master de áudio)
* Fullscreen
* External
* Chroma key / Luma / Key / Fill
* MultiView
* Triggers
* PlayList
* MultiCorder

Algumas outras palavras tiveram que ser adequadas, seja pelo tamanho do lugar onde se encontra ou pelo entendimento:

* "Configurar" ao invés de "Configurações" nos botões superiores
* "Mixer áudio" ao invés de "Mixer de áudio" na janela de mixagem de áudio

# Formato de arquivo de tradução do vMix

O vMix usa o formato TSV (Tab Separated Value) para a sua tradução e no arquivo existe 3 colunas:

```
frmmain.cmdAddInput	Add Input	Adicionar input
```

A primeira coluna contém o identificador interno da tradução para o vMix, a segunda coluna tem o texto original em inglês e a terceira coluna contém a tradução para português que será usada.

Para atualizar a tradução é preciso apenas alterar a última coluna.

# Simplificando o processo de tradução e exportação dos arquivos

Adicionei também um arquivo no formato CSV para facilitar a tradução, eu importo esse arquivo dentro de uma planilha do Google Docs e a partir dela faço toda a tradução necessária, após as alterações eu exporto a planilha no formato TSV e testo no vMix, verificando se as alterações funcionam corretamente para o contexto indicado.

# Contribuição para a tradução

Se você sabe não como usar este repositório você pode iniciar uma contribuição clicando [nesse link](https://github.com/jonatasoliveira/vmix-lang-pt-br/issues/new) e escrevendo a sua contribuição, peço que escreva qual é o texto em inglês e a tradução em português que você gostaria de sugerir uma alteração.

Se você sabe como fazer um Pull Request, você pode abrir um e iniciar a sua contribuição.
