Refatoracao de Codigo

Este projeto passou por uma refatoração significativa para melhorar a estrutura, acessibilidade e funcionalidade do código. Abaixo estão listadas os problemas encontrados 

Refatoração código

Pagina index.html

falta definição da linguagem "<html lang="en">"

No corpo do "<!DOCTYPE html> faltam "<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">" 

existem um link de CSS totalmente inutil

existem código duplicado de css interno 

não existe tag <header>

Para o formulário não existe tag <form>

não existe tag <label> para os campos nome e email
 
Input de Nome e email o type esta errado

existem 2 botões duplicados, os dois botões estão sem type 

Muitos scripts de JS sem utilização

=============================================================================

Pagina CONTATO.HTML

Corpo de pagina em lugar Errado

Css interno repetido

Form com uma action inexistente'

Button sem rota 
script JS errado

=============================================================================

Pagina sobre.html

apenas atributo "alt" está errado e atributo width não possui valor definido






Abaixo estão listadas as alterações realizadas em cada página.

Index.html

Alteracoes Realizadas

Definição da linguagem: Adicionada a tag <html lang="en"> para melhor acessibilidade e SEO.

Metadados essenciais: Adicionados <meta charset="UTF-8"> e <meta name="viewport" content="width=device-width, initial-scale=1.0"> para garantir uma melhor responsividade e codificação correta de caracteres.

Remoção de link CSS inútil: Excluído para melhorar a performance.

Eliminação de código CSS duplicado: Consolidado em um único arquivo ou bloco de estilo.

Adicionada a tag ****<header>: Para melhorar a semântica e organização da estrutura HTML.

Inclusão da tag ****<form>: Envolvendo os campos do formulário para maior conformidade com padrões web.

Adicionadas tags ****<label>: Associadas aos campos "Nome" e "E-mail" para melhorar a acessibilidade.

Correção dos tipos de input: Ajustados os campos "Nome" e "E-mail" para type="text" e type="email", respectivamente.

Remoção de botões duplicados: Mantido apenas um botão e adicionado type="submit" para garantir o comportamento correto.

Exclusão de scripts JavaScript não utilizados: Removidos para otimização do código.

==============================================================================================================================================================
Contato.html

Alteracoes Realizadas

Reestruturação do corpo da página: O conteúdo foi reposicionado corretamente dentro da tag <body>.

Eliminação de CSS interno repetido: Consolidado em um único arquivo ou bloco de estilo.

Correção da action do form: Definida uma action válida para o formulário.

Ajuste no botão: Definida uma rota ou funcionalidade adequada.

Correção de script JavaScript: Revisado e corrigido para garantir seu correto funcionamento.
====================================================================================================================================================================
Sobre.html

Alteracoes Realizadas

Correção do atributo ****alt: Agora as imagens possuem descrições adequadas para acessibilidade.

Definição do atributo ****width: Foi definido um valor coerente para padronizar o tamanho das imagens.

Consideracoes Finais

Essa refatoração teve como objetivo melhorar a qualidade do código, padronizar a estrutura HTML e garantir boas práticas de desenvolvimento web. Caso encontre algum problema ou tenha sugestões, por favor, entre em contato.

=======================================================================================================================================================================
Modo de uso
O site começa na pagina index.html, o index é como se fosse um registro

ele possui no cabeçalho um botão que leva para a proxima pagina esse botão funciona como uma lista encadeada ela só vai, não volta

depois temos a pagina contato.html, o contato serve para o usuario entrar em contato com a pagina 

e logo a seguir temos a pagina sobre.



