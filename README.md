
O LaTeXture é uma aplicação web que complementa o editor de xml Texture. 
Seu principal objetivo é gerar pdfs a partir de jats xml.

Trata-se de um projeto de integração de cinco softwares: 
* Texture, 
* jats2tex,
* um display de pdf, 
* texlive (para gerar o pdf),
* git (controlador de versão)

O editor não pode ser confundido com um gestor de projetos. Ele não
cria nem guarda projetos (livros, artigos). Ele tambám não pode ser
confundido com o conversor jats2tex (ferramenta genérica para a conversão
de qualquer xml jats para tex).

Seu fluxo mínimo supõe principalmente a integração 
do Texture (Substance) com o conversor jats2tex. Vale lembrar que na etapa de inserção dos
dados, o usuário terá o opção de escolher um template que está disponível na pasta \templates, no servidor, 
ou nas pastas que estiverem indicadas 
no arquivo de configuração do conversor `xml2tex`.

![Neste fluxo mínimo abaixo supõe-se principalmente a integração 
do Texture (Substance) com o conversor. Vale lembrar que na etapa de inserção dos
dados, o usuário terá o opção de escolher um template qualquer. A lista
do template será a lista das pastas que estiverem indicadas 
no arquivo de configuração do converso `xml2tex`.](02.jpg)



As características básicas do produto são:

* [Botão] Alteração mínima da interface;
* [Metadados] Formulário para coleta de dados sobre o livro; 
* [Integração] Integração com o conversor xml2tex
* [Templates] Menu dropdown para escolhe de templates disponíveis;
* [Display] Abertura do PDF.

Foi feita uma prova de conceito que pode ser acessada no seguinte endereço:
http://editorial.hedra.com.br:8088
