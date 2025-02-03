# Desafio: Construção de Esquema Conceitual

### Objetivo: Treinar e desenvolver habilidades/conhecimento em modelagem de banco de dados.

Neste desafio, foi utilizado o conhecimento de modelagem conceitual e como ferramenta para essa implementação MySQL Workbench. O modelo conceitual é uma parte imprecindível para o projeto,  pois é o diagrama do BD, nos servindo como referência.

O desafio segue a seguinte narrativa:
 * Sistema de contreole e gerenciamento de execução de ordens de serviço em uma oficina mecânica
 * Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões periódicas
 * Cada Veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS(Ordem de serviço) com datat de entrega
 * A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra
 * O valor de cada peça também irá comporo OS o cliente autoriza a execução dos serviços
 * Os mecânicos possuem código, nome, endereço e especialidade
 * Cada OS possui: n°. data emissão, um valor, status e uma data para conclusão dos trabalhos

Segue abaixo imagem do desafío:

![Conceitual Mecânica](<Projeto Conceitual Mecanica.png>)
