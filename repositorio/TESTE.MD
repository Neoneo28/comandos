# comandos básico dos terminais :computer:

##	Vamos aprender :

### - Mudar de pastas

### - Listar as pastas 

### - Criar pastas/arquivos

### - Deletar pastas/arquivos

-----

**cd** **=** _**Encaminhar em uma pasta especifica**_   **_exemplo :_ ** **( cd /c ) - ( cd/d ) - (cd .....] )**  **{WINDOWS/UNIX}**  

**cd .. =** _**Voltar uma vez atrás**_  **{WINDOWS/UNIX}** 

**cls =** _**Limpar o terminal**_ **{WINDOWS}**

**clear - ctrl+L =** _**Limpar o terminal**_ **{UNIX}** 

**dir** **=** _**Listar arquivos dentro do(a) repositório/pasta **_ **{WINDOWS}** 

**ls=**  _**Listar arquivos dentro do(a) repositório/pasta **_ **{UNIX}**

**mkdir** **=** _**Criar repositório** **{WINDOWS/UNIX}**

**echo ..... =** _**Criar um texto **_ **{WINDOWS/UNIX}**

**echo ....>....txt =** _**Criar um arquivo texto para o texto mencionado no**_ **{echo}**  **{WINDOWS/UNIX}**

**del ...**  **=** _**Excluir arquivos dentro do repositório**_ **{WINDOWS}**

**rmdir .... /S /Q = ** _**Excluir o repositório com todos os arquivos dentro dele**_ **{WINDOWS}**

**rm =** _**Excluir arquivos dentro do repositório**_ **{UNIX}** 

**rm -rf .... = **_**Excluir repositório com todos os arquivos dentro dele **_ **{UNIX}**  

# Comandos para o terminal do GIT/usando os comandos do LINUX no lugar do WINDOWS :computer: ​   

**git --version =** _**Descobrir qual a versão do GIT**_  

**echo  "...." > "....txt "=** _**Criar um arquivo texto para o texto mencionado no**_ **{echo}** **{"..."} ** _**Modifica o **_ **{echo}** _**para um algoritmo de encriptação**_  

**openssl sha1 {nome do arquivo que esta sendo usado} =** _**passamos o arquivo para o algoritmo de encriptação usando o**_ **{sha1}**  

**OBS : Openssl sha1 + {nome do arquivo usado}, cria uma chave/código de encriptação de 40 characteres, qualquer mudança no arquivo que esteja representado pelo sha1 apresentara mudanças no código de encriptação, avisando que foi modificado algo no arquivo e quando voltar o arquivo a ser igual o original o ** **{sha1} volta a apresentar o mesmo código do anterior**  

**echo '.........' | git hash-object --stdin =**  _**Apresentara o**_ **{sha1}** _**do arquivo informado usando o GIT**_

**echo '.........' | openssl sha1 =** _**Apresentara o**_ **{sha1}** _**do arquivo informado**_   

 **echo -e 'blob 9\0.......' | openssl sha1 =**  _**Apresentara o**_ **{sha1}** _**do arquivo informado**_ 

**git config --global user.email "fakihallouche@gmail.com" =** _**Informações necessária para conectar nosso Git local ao nosso GitHub **_ 

**git config --global user.name "Neoneo28" =** _**Informações necessária para conectar nosso Git local ao nosso GitHub **_    

**git init =** _**Inicializa o Git criando uma pasta oculta .git**_      

**ls -a =** _**Mostra  a pasta oculta .git**_    

**git add  =** _**Adiciona todos arquivos modificado pro Git reconhecer**_

**git add ..... =** **_Adiciona um arquivo específico ao Git dependendo do nome que acompanha o git add_**  

**git commit -m "adiciona ......" =** _**Adiciona o repositório ao link do GitHub**_

**git status =** _**Mostra o status dos arquivos dentro do repositório**_ 

**git remote add origin https://github.com/Neoneo28/.......git =** _**Puja o repositório criado para o link do GitHub**_  

**git push origin master =** _**Puja o Git local para o GitHub **_

**git config --list = ** **Usamos esse comando para saber se as configurações do Git Local é igual ou diferente ao nosso GitHub **

**git config --global --unset user.email =** _**Caso as informações estiver diferente ou queremos mudar**_

**git config --global --unset user.name =** _**Caso as informações estiver diferente ou queremos mudar**_

 

# _No momento são os comandos que sei manipular por enquanto_, adicionarei mais comandos com o tempo _.........._

