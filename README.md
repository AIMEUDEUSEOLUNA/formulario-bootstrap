# Formulário Bootstrap

## Objetivo

Criar um formulário de inscrição para uma Mostra de Tecnologia e Inovação do Lunao utilizando HTML, CSS, Bootstrap e GitHub Pages.

## Tecnologias utilizadas

- HTML5
- CSS3
- Bootstrap 5
- GitHub Pages

## Tipos de input utilizados

- **text:** usado para digitar textos, como o nome.
- **email:** usado para digitar um endereço de e-mail e faz uma validação básica do formato.
- **password:** usado para digitar uma senha, escondendo os caracteres. No formulário existe um aviso para não utilizar uma senha real.
- **number:** usado para inserir números. Foi utilizado para a idade, com valor mínimo de 14 e máximo de 100.
- **tel:** usado para inserir telefone. Foi utilizado junto com `pattern` para exigir um formato específico.
- **url:** usado para inserir o endereço de um site ou portfólio.
- **search:** usado para criar um campo de pesquisa.
- **date:** usado para escolher uma data.
- **month:** usado para escolher um mês e um ano.
- **week:** usado para escolher uma semana do ano.
- **time:** usado para escolher um horário.
- **datetime-local:** usado para escolher uma data e um horário.
- **color:** permite que o usuário escolha uma cor.
- **range:** cria uma barra para escolher um valor dentro de um intervalo. Foi utilizado para o nível de experiência, de 0 a 10.
- **file:** permite escolher um arquivo do computador. Foi configurado para aceitar arquivos PDF, ZIP e RAR.
- **checkbox:** permite marcar várias opções ao mesmo tempo.
- **radio:** permite escolher uma opção entre várias opções do mesmo grupo.
- **hidden:** guarda uma informação no formulário sem mostrar o campo para o usuário.
- **submit:** cria um botão para enviar o formulário.
- **reset:** cria um botão para limpar os campos preenchidos.
- **button:** cria um botão comum, que não envia nem limpa o formulário automaticamente.
- **image:** funciona como um botão de envio utilizando uma imagem.

## Outros elementos utilizados

- **select:** cria uma lista onde o usuário pode escolher uma opção.
- **option:** representa cada opção dentro de um `select`.
- **textarea:** cria uma área maior para escrever textos, como a descrição do projeto.
- **datalist:** fornece sugestões para um campo de entrada, mas permite que o usuário digite outra coisa.
- **fieldset:** usado para agrupar campos relacionados do formulário.
- **legend:** funciona como o título de um grupo criado com `fieldset`.

## Validações

Foram utilizadas algumas validações e atributos nativos do HTML:

- **required:** obriga o preenchimento de determinados campos.
- **min:** define o menor valor permitido.
- **max:** define o maior valor permitido.
- **pattern:** define um formato que o valor digitado deve seguir. Foi utilizado no telefone.
- **placeholder:** mostra um exemplo ou uma dica dentro do campo antes de o usuário preenchê-lo.
- **maxlength:** define o número máximo de caracteres que podem ser digitados.
- **accept:** define quais tipos de arquivo podem ser selecionados no campo de arquivo.
- **step:** define de quanto em quanto um valor pode variar. Foi utilizado no campo de nível de experiência.

## Investigação

### O que é um formulário HTML?

É uma parte da página usada para receber informações que o usuário digita ou seleciona. É possível utilizar campos para textos, números, e-mails, arquivos, opções e outros tipos de informação.

### O que é o Bootstrap?

É uma ferramenta que possui várias classes CSS prontas. Ele pode ser usado para deixar a página mais organizada e facilitar a criação de layouts responsivos para diferentes tamanhos de tela.

### O que é o atributo required?

Faz com que o usuário seja obrigado a preencher aquele campo antes de enviar o formulário.

### O que é o atributo pattern?

É usado para definir um formato que o texto precisa seguir. No telefone, por exemplo, foi utilizado para exigir um formato parecido com `(11)99999-9999`.

### O que é o atributo step?

Define de quanto em quanto um valor pode aumentar ou diminuir. No campo de experiência, foi usado `step="1"` para permitir valores inteiros de 0 a 10.

### O que é o select?

É usado para criar uma lista de opções onde o usuário pode escolher uma delas.

### O que é o option?

É uma das opções disponíveis dentro de um `select`. O texto mostrado ao usuário pode ser diferente do valor armazenado no atributo `value`.

### O que é o textarea?

É parecido com um campo de texto, mas possui uma área maior para escrever. Foi utilizado para a descrição do projeto.

### O que é o datalist?

É usado para mostrar sugestões enquanto o usuário preenche um campo de entrada. Diferente do `select`, o usuário também pode digitar uma opção que não esteja nas sugestões.

### O que é o fieldset?

É usado para agrupar campos que têm relação entre si. No formulário, foi usado para agrupar a forma de participação e as áreas de interesse.

### O que é o legend?

É o título que identifica um grupo criado com `fieldset`.

### O que é o atributo value?

É o valor que representa uma opção do formulário. Por exemplo, a opção mostrada como `Graduação` pode ter `value="graduacao"`.

### O que são rows e maxlength?

No `textarea`, `rows` define o tamanho inicial da área de texto em quantidade aproximada de linhas. Já `maxlength` define a quantidade máxima de caracteres que podem ser digitados.

## Aluno

JOÃO PEDRO LUNA

## GitHub Pages

[Link para o site](https://aimeudeuseoluna.github.io/formulario-bootstrap/)

## Repositório

[Link para o repositório](https://github.com/AIMEUDEUSEOLUNA/formulario-bootstrap)
