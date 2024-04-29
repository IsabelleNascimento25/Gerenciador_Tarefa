# Gerenciador_Tarefa
# Índice
[Projeto ](#projeto)  
[Descrição](#descrição)  
[Funcionalidades](#funcionalidades)  
[Tecnologias ultilizadas](#tecnologias-ultilizadas)    
[Fontes consultadas](#fontes-consultadas)  
[Autores](#autores)  

# Projeto 
O objetivo desta tarefa é utilizar um vídeo tutorial proposto pelo professor do canal do YouTube "MonolitoPHP" como base para criar uma lista de passos detalhados para construir um aplicativo de gerenciamento de tarefas. <br>
<br>
Disciplina:Programação Web I. <br>
Professor: Leonardo Santiago Sidon da Rocha.


## 📰Descrição
`PHP Inicialização:`
<br>
O código PHP começa com session_start(), que inicia ou resume uma sessão existente. Isso é importante para manter o estado da sessão entre diferentes requisições HTTP. <br>
Em seguida, verifica-se se a variável de sessão $_SESSION['tasks'] existe. Se não existir, é inicializada como um array vazio.<br>
`Receber e Manipular Dados do Formulário:`
<br>
Verifica-se se há uma variável $_GET['task_name']. Se existir, significa que um novo nome de tarefa foi submetido pelo formulário. Nesse caso, o nome da tarefa é adicionado ao array $_SESSION['tasks'] usando array_push(). Após a adição da tarefa, a variável $_GET['task_name'] é removida usando unset().<br>
Verifica-se também se há uma variável $_GET['clear']. Se existir, significa que o botão "Limpar Tarefas" foi clicado. Nesse caso, o array $_SESSION['tasks'] é removido da sessão usando unset().<br>
`HTML Formulário e Exibição das Tarefas:`
<br>
O HTML exibe um formulário simples para adicionar novas tarefas. O formulário envia os dados para a própria página usando o método GET.<br>
Abaixo do formulário, a lista de tarefas é exibida usando um laço foreach. Ele itera sobre o array $_SESSION['tasks'] e exibe cada tarefa como um item de lista <li> No final da lista de tarefas, há um segundo formulário com um botão "Limpar Tarefas". Este formulário é usado para limpar todas as tarefas quando o botão é clicado.<br>
`Estilo CSS e Rodapé:`
<br>
O código HTML inclui um link para um arquivo de estilo CSS externo para estilizar a página.<br>
Um rodapé simples exibe o crédito do desenvolvedor.<br>
<br>
Em resumo, este código PHP e HTML cria uma aplicação web básica de gerenciamento de tarefas que permite adicionar novas tarefas, exibir uma lista de tarefas existentes e limpar todas as tarefas. As tarefas são armazenadas na sessão do usuário para persistência entre as requisições.
<br>
<br>
![image](exemplodeuso.gif)

## ⚙️Funcionalidades
| Métodos PHP | Funcionalidade |
|--------------------|----------------|
| isset | é um método em JavaScript usado para verificar se um objeto possui uma propriedade específica.|
| $ ||Cria uma variável|
| echo |	A função `echo` exibe dados ou variáveis na saída padrão do PHP.|
|$_GET | usada para coletar dados enviados para o servidor via método GET em um formulário HTML ou na URL. |
|$SESSION| usada para armazenar variáveis de sessão, permitindo que dados persistam entre diferentes páginas durante uma sessão do usuário.|
|array()|Um array é uma estrutura de dados que pode conter uma coleção de elementos, cada um identificado por um índice.|
|unset()| usada para remover uma variável específica ou elementos de um array.|
|foreach | usado para iterar sobre arrays ou objetos. Ele executa um bloco de código para cada elemento do array ou propriedade do objeto.|
|array_push() |utilizada para adicionar um ou mais elementos no final de um array.|
<br>

### 📱Tecnologias utilizadas
 * <img alt="Rafa-Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-plain.svg"> <br>
  PHP <br>
 * <img alt="Rafa-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg"><br>
  HTML<br>
 * <img alt="Rafa-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg"><br>
  CSS<br>
  

## 🔠Fontes consultadas
     * https://developer.mozilla.org/pt-BR/docs/Learn/JavaScript/First_steps/Arrays
     
     * https://g.co/kgs/E1D83Uw

     * https://cursos.alura.com.br/forum/topico-array-130461


## ✒️Autores
 <img src="isabelle.png" width="20px"> Isabelle Nascimento de Oliveira <br>

