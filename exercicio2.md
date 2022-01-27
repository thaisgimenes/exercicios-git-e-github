## Exercicio do módulo 6 - Aula 2

Para que um repositório seja clonado, primeiramente, eu preciso criar um diretório para onde os arquivos clonados serão armazenados na minha máquina.

### -> Criar uma pasta no diretório:

#### mkdir [nome da pasta]

#### cd [nome da pasta]

Depois, é necessario enviar o comando de clonar:

### -> Clonando um repositório:

#### git clone [url do repositório a ser clonado]

Para se criar uma nova branch para realizar alterações no projeto, é necessário:

### -> Criar uma nova branch:

#### git checkout -b [nome da nova branch]

Realizando alterações no projeto nesta branch. 
Após as modificações, é necessário:

### -> Salvando alterações do arquivo:

#### git status

#### git add .

#### git commit -m "[descrição do commit]"

#### git push

Para que as alterações sejam realizadas também na branch principal, é preciso abrir uma pull request.

Abertura da pull request através do link gerado no push.

Titulo e descrição da ação feita no projeto, designar a quem deve aprovar.

Quem deve aprovar irá realizar a analise da pull request e por fim confirmar o merge das branchs.