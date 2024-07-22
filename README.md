## Sistema de controle de versões
# o sistema de controle de versão são ferramentas de software que ajudam na pratica de 
# rastrear e gerenciar alteraçoes em um codigo de software que ajuda com as equipes de 
# software a gerenciar as alterações ao código fonte ao longo do tempo. O software de controle 
# de versão mantém registro de todas as modificações no código em um tipo de banco de dados 
# usar o software de controle de versão e uma pratica recomendada para software de alto 
# desempenho em equipes de DevOps. E também ajuda os desenvolvedores se mover mais 
# rápido e permite que as equipes de software preservem a eficiência e a agilidade escalada para
# para incluir mais desenvolvedores
## vantagens de controle de versão
# 1. Colaboração de eficiente: Permite que várias pessoas trabalhem simultaneamente em 
# um projeto, facilitando a colaboração
# 2. Histórico de alterações: É possível rastrear todas as alterações feitas em um projeto 
# ao longo do tempo 
# 3. Gerenciamento de conflitos: Recursos para lidar esses conflitos de forma eficiente, 
# permitindo que os desenvolvedores resolvam as diferenças e combinem as alterações
# de maneira adequada 
# 4. Testes de Experimentações: É possível criar ramificações separadas para testar nova 
# funcionalidades ou experimentar alterações
# 5. Backup e recuperação: atua como um backup para o código fonte do projeto. Se 
# ocorrer algum problema, como perda de arquivos ou corrupção de dados 
## Exemplos sistema de controle de 
# versão
# 1. Git: O Git é um sistema de controle de versão distribuído amplamente utilizado. Ele 
# permite que os desenvolvedores rastreiem e gerenciem as alterações feitas em um 
# projeto de software
# 2. SVN (Subversion): O SVN é um sistema de controle de versão centralizado. Ele permite 
# que os desenvolvedores acompanhem as alterações feitas em um projeto de software. 
# E tem um repositório centralizado que armazena todo o histórico de alterações
# 3. Mercurial: Ele oferece recursos semelhantes ao Git, como rastreamento de alterações
# ramificação e mesclagem de código. No entanto, o mercurial possui uma sintaxe e uma 
# estrutura de repositório um pouco diferente do Git

## DESAFIO 2

# Programação orientada a objetos surgiu como uma alternativa a essas características da programação estruturada. O intuito da sua criação também foi o de aproximar o manuseio das estruturas de um programa ao manuseio das coisas do mundo real, daí o nome "objeto" como uma algo genérico, que pode representar qualquer coisa tangível. É a programação estruturada. Quando começamos a utilizar linguagens como JAVA, C#, PYTHON e outras que possibilitam o paradigma orientado a objetos, é comum errarmos e aplicarmos a programação estruturada achando que estamos usando recursos da orientação a objetos. Essas estruturas são usadas para processar a entrada do programa, alterando os dados até que a saída esperada seja gerada. A diferença principal é que na programação estruturada, um programa é tipicamente escrito em uma única rotina (ou função) podendo, é claro, ser quebrado em subrotinas. Mas o fluxo do programa continua o mesmo, como se pudéssemos copiar e colar o código das subrotinas diretamente nas rotinas que as chamam, de tal forma que, no final, só haja uma grande rotina que execute todo o programa.

# Exemplificação dos cenários 

# 1.	ABSTRAÇÃO: A abstração  é um princípio fundamental da Programação Orientada a Objetos que envolve a identificação e a modelagem das características e comportamentos essenciais de um objeto. 
# Exemplo: é como pegar algo real e transformar em uma ideia
# 2.	ENCAPSULAMENTO: O encapsulamento é um princípio no qual garante que partes  do código sejam privados, removendo acesso a partes dele. Ele pode ser chamado, também, de “ocultação de dados”. Ou seja, partes do código ficam dentro de outras partes do código. 
# Exemplo:  Imagine em sua casa, como seria se outras pessoas, que não são seus familiares ou amigos, entrassem sem permissão e usassem suas coisas.
# 3.	POLIMORFISMO: O polimorfismo é um pilar da Programação Orientada a Objetos que, como o nome sugere, é sobre a capacidade de um objeto poder assumir diferentes formas ou comportamentos. Isso ajuda o programador quando ele está trabalhando com coleções de objetos de diferentes tipos, permitindo que operações que trabalham com eles sejam realizadas com maior flexibilidade. 

# Exemplo: exemplo: podemos assumir que uma bola de futebol e uma camisa da seleção brasileira são artigos esportivos, mais que o cálculo deles em uma venda é calculado de formas diferentes.

# 4.	HERANÇA: Esse primeiro pilar fala sobre a transmissão de propriedades e métodos de outros objetos. Esse é um ponto que acelera o processo de programação, pois é possível importar partes do código que já foram utilizadas em outro momento. 
# Exemplo: exemplo pode-se observar as classes 'aluno' e 'professor', onde ambas possuem atributos como nome, endereço e telefone.
## Vantagens do (POO)

# Neste artigo, exploraremos as vantagens da programação orientada a objetos e como ela contribui para a criação de código mais eficiente, reutilizável e fácil de manter.
# 1.	Encapsulamento: ...
# 2.	Reutilização de Código: ...
# 3.	Manutenção Simplificada: ...
# 4.	Colaboração Eficiente: ...
# 5.	Modelagem Realista:

## DESAFIO 3

## Protocolo de comunicação HTTP 

# HTTP é um protocolo que permite a obtenção de recursos, como documentos HTML. É a base de qualquer troca de dados na Web e um protocolo cliente-servidor, o que significa que as requisições são iniciadas pelo destinatário, geralmente um navegador da Web.
# Como Funciona:  informa ao seu navegador como se comunicar com o servidor de um site, a fim de enviar e recuperar informações quando é HTTPS, significa que é o HTTP seguro, que possui alguns padrões de segurança e texto criptografado.
## Oque é Rest 
# Rest é um estilo de arquitetura utilizado para criar serviços web. É um conjunto de princípios e restrições que definem como os recursos são expostos e manipulados em um sistema distribuído.
# Relação do Rest com HTTP: Rest utiliza o protocolo HTTP como meio de comunicação entre o cliente e o servidor. O HTTP é um protocolo de aplicação que permite a transferência de informações na web 
## Oque é web API
# Web API é uma interface de programação de aplicativos que permite a comunicação e interação entre sistemas de software por meio do protocolo HTTP.
# Relação Web Api com o Rest: A relação entre uma Web Api e o Rest é que a Web Api é uma aplicação concreta dos princípios do Rest, permitido a criação de serviços web de forma padronizada. Escalável e interoperável.

# Lista de todos os métodos de solicitações de HTTP com o Rest

## GET
# O método GET solicita a representação de um recurso específico. Requisições utilizando o método GET devem retornar apenas dados.
## HEAD
# O método HEAD solicita uma resposta de forma idêntica ao método GET, porém sem conter o corpo da resposta.
## POST
# O método POST é utilizado para submeter uma entidade a um recurso específico, frequentemente causando uma mudança no estado do recurso ou efeitos colaterais no servidor.
## PUT
# O método PUT substitui todas as atuais representações do recurso de destino pela carga de dados da requisição.
## DELETE
# O método DELETE remove um recurso específico.
## CONNECT
# O método CONNECT estabelece um túnel para o servidor identificado pelo recurso de destino.
## OPTIONS
# O método OPTIONS é usado para descrever as opções de comunicação com o recurso de destino.
## TRACE
# O método TRACE executa um teste de chamada loop-back junto com o caminho para o recurso de destino.
## PATCH
# O método PATCH é utilizado para aplicar modificações parciais em um recurso.

