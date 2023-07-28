***CRIAÇÃO DO FORMULÁRIO EM HTML***
- O que é formulário?
  São campos que o usuário colocam suas informações, ele está conectado no servidor para serem processados. 

  ***_Tags HTML dos formulários_***
  - Tag < form >
  - tag < input >
  - tag < checkbox > e < radio >
  - tag < button >

***Tag < form >***

Essa tag é usada para criar o formulário e é a responsável por conter os demais elementos.

***Tag < input >***

É o comando mais usado, ele pode ser exebido de várias maneira, dependendo do type do atributo

- ***< input type="text" >*** define um campo de entrada de texto de linha única
- ***< input type="password" >*** define um campo de senha
- ***< input type="checkbox" >*** define uma caixa de seleção 
- O ***< input type="date" >*** é usado para campos de entrada que devem conter uma data
- O ***< input type="email" >*** é usado para campos de entrada que devem conter um endereço de e-mail
- O ***< input type="file" >*** define um campo de seleção de arquivo e um botão
- O ***< input type="hidden" >*** define um campo de entrada oculto (não visível para um usuário)
- O ***< input type="number" >*** define um campo de entrada numérica
- O ***< input type="range" >*** define um controle para inserir um número cujo valor exato não é importante (em formato deslizante) o intervalo pode ser de 1 a 10 por exemplo.
- O ***< input type="tel" >*** é usado para campos de entrada que devem conter um número de telefone.
- O ***< input type="radio" >*** define um botão de opção. O usuário só consegue selecionar UMA opção
- O ***< input type="checkbox" >*** define uma caixa de seleção. O usuário consegue escolher MAIS que uma opção 
- O ***< input type="submit" >*** define um botão para enviar os dados do formulário para um manipulador de formulário.
  
  ***_Atributos do < input >_***

 ***Value:*** É atributo de entrada especifica um valor inicial para um campo de entrada
 ***Disabled:***Um campo de entrada desabilitado é inutilizável e não clicável.
 ***Size:***É atributo de entrada especifica a largura visível, em caracteres, de um campo de entrada
 ***maxlength:***É atributo de entrada especifica o número máximo de caracteres permitidos em um campo de entrada.
 ***Min e Max:*** Define o número mínimo e máximo para um campo de entrada
 ***multiple:*** É atributo de entrada especifica que o usuário pode inserir mais de um valor em um campo de entrada.

 ***_Atriputos < form >_***

 ***Action:*** Este atributo define para onde a informações devem a ser enviadas.
 ***method:*** Este atributo especifica o método HTTP a ser usado ao enviar os dados do formulário, ele normalmente é acompanhado pelo "post" e pelo "get"

  _Observações sobre GET:_
- Anexa os dados do formulário ao URL, em pares de nome/valor
- NUNCA use GET para enviar dados confidenciais! (os dados do formulário enviado são visíveis na URL!)
- O comprimento de um URL é limitado (2048 caracteres)
- Útil para envios de formulários em que um usuário deseja marcar o resultado como favorito
- GET é bom para dados não seguros, como strings de consulta no Google
  
_Observações sobre o POST:_
- Anexa os dados do formulário dentro do corpo da solicitação HTTP (os dados do formulário enviado não são mostrados na URL)
- O POST não tem limitações de tamanho e pode ser usado para enviar grandes quantidades de dados.
Os envios de formulário com POST não podem ser marcados
 
 ***Elemento < lambel >***
 A < label >tag define um rótulo para muitos elementos de formulário.

***Elemento < selected >***
O < select > elemento define uma lista suspensa com pré-seleções, a onde o < option > define os elementos que poderão ser selecionadas 

***O elemento < button >***
O < button > é o elemento que define um botão clicável, você sempre têm que definir o ***Type*** do butão.

***_Type de Button_***
- ***< input type="submit" >*** define um botão para enviar dados de formulário para um manipulador de formulário
- ***< input type="reset" >*** define um botão de redefinição que redefinirá todos os valores do formulário para seus valores padrão
  