## Introdução

O projeto Rango é voltado para jovens que moram sozinhos e desejam aprender a cozinhar refeições simples e saborosas para si ou para amigos. O objetivo é fornecer uma plataforma que ofereça receitas praticas e econômicas, assim como dicas de culinária para esse publico que recém saiu da casa dos pais e responsáveis.

## Problema

Muitos jovens que vivem sozinhos enfrentam o desafio de cozinhar para si mesmos devido à falta de conhecimentos culinários, o que pode gerar uma dieta desequilibrada, dependência de alimentos processados, problemas de saúde e gasto excessivo com refeições prontas. Ou seja, esse projeto busca ajudar essas pessoas.

## Objetivos

O objetivo do Rango é ser um site responsivo e fácil de usar que hospede receitas simples e baratas para que o jovem aprenda a cozinhar, tenha uma alimentação boa e que economize dinheiro, de modo que seja possível:

    - Acessar receitas simples que tenham ingredientes acessíveis.
    - Permitir pesquisas e comentários em receitas adequadas para refeições individuais e/ou coletivas.
    - Oferecer aos usuários a possibilidade de enviar suas próprias receitas.
    - Implementar recursos de classificação e/ou favoritismo de receitas, destacando as mais populares.

## Justificativa

Baseado na necessidade de resolver o problema de falta de conhecimento culinário enfrentado por jovens que moram sozinhos, que pode causar dietas pouco saudáveis, gastos econômicos excessivos e baixa qualidade de vida, o Projeto Rango visa abordar esse problema fornecendo um recurso centralizado que ajuda os jovens a cozinhar refeições saudáveis, práticas, saborosas e econômicas melhorando assim sua independência e qualidade de vida.

## Público-alvo

O publico-alvo do Projeto Rango são jovens recém saídos da casa dos pais, isso inclui:

    - Estudantes universitários;
    - Profissionais recém inseridos no mercado de trabalho;
    - Jovens em transição que precisam de se sustentar de forma independente;

## Personas

1. Eduardo Silva, 18 anos, recentemente aprovado na faculdade federal do estado vizinho. Em busca de um curso mais especializado e de correr atrás de seu sonho tomou a difícil decisão de sair da casa dos pais e morar sozinho em um ambiente completamente desconhecido. Eduardo possui muita ambição, porém é acompanhado de pouca experiência de se cuidar sozinho e busca informação para não passar tanta dificuldade.

2. Mariana Freitas, 25 anos, formada em letras pela USP. Mora sozinha a dois anos e leciona língua portuguesa em duas escolas diferentes. Possui uma vida muito corrida e raramente tem disposição e tempo para cozinhar, para remediar isso acaba pedindo delivery com grande frequência, mas nunca acaba o mês com o saldo positivo.

## Histórias de Usuários

Eu, como cliente Eduardo, quero sugestões de receitas mais difíceis para fazer. Como estou morando sozinho e estudo na parte da manhã, tenho tempo livre durante a tarde e a noite. Minha ideia são refeições para o dia-a-dia, gosto de pratos que levam como ingredientes, carne vermelha, frutos-do-mar, especiarias de outras culturas, assim podendo ter a culinária como minha terapia.

Eu, como cliente Mariana, quero sugestões de receitas práticas de se fazer. Como dou aula em duas escolas diferentes, não tenho muito tempo para cozinhar, preciso que sejam refeições práticas para o meu dia-a-dia e que se encaixam na minha dieta. Tenho em mente pratos que levam, frango, peixe e salada.

## Requisitos

Essa documentação visa detalhar a identificação de documentação precisa dos requisitos funcionais e não funcionais de um sistemas, contribuindo para a definição precisa do escopo, avaliação de viabilidade e comunicação eficaz entre todas as partes envolvidas em um projeto.

Diante disso, considerando as Histórias de Usuário fornecidas como entrada, elaboramos uma lista de requisitos que abrange tanto os aspectos funcionais quanto os não funcionais da solução proposta.

### Requisitos Funcionais (RF)

- |RF-001| Permitir que o usuário cadastre receitas.
- |RF-002| Permitir que o usuário edite as receitas postadas.
- |RF-003| Permitir que o usuário exclua receitas.
- |RF-004| Permitir que o usuário favorite as receitas.
- |RF-005| Permitir que o usuário deixe comentários.
- |RF-006| Fornecer uma interface de usuário intuitiva para cadastro e filtragem de receitas.

### Requisitos Não Funcionais (RNF)

- |RNF-001| O site deve ser fácil de usar, com uma interface intuitiva que permita aos usuários navegar facilmente pelas receitas, comentar e favoritar receitas sem dificuldades.
- |RNF-002| As páginas do site devem carregar rapidamente, com um tempo de resposta curto para proporcionar uma experiência de usuário ágil.
- |RNF-003| Deve ser implementada segurança básica para proteger os dados dos usuários, como senhas e informações pessoais, contra acessos não autorizados.
- |RNF-004| O site deve estar disponível a maior parte do tempo, com tempo de inatividade planejado mínimo para manutenção regular.
- |RNF-005| O site deve funcionar bem nos navegadores mais comuns, como Chrome, Firefox e Safari.
- |RNF-006| O site deve ser acessível para pessoas com deficiências, seguindo as diretrizes básicas de acessibilidade da Web.

Essa documentação de requisitos serve como um guia para o desenvolvimento, teste e validação da plataforma. A clareza e a abrangência desta especificação é importante para evitar retrabalho e problemas de escopo ao longo do ciclo de vida do projeto. Ela contribui para que o desenvolvimento da plataforma seja feito de modo estruturado e que a entrega atenda às expectativas dos usuários e aos critérios de qualidade estabelecidos.

## Restrições

| ID  | Restrição                                                                                                                                                                                                                                                                                |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01  | Em analogia ao fato de que a plataforma é voltada para um público onde, a maioria recém se tornou independente, e que grande parte não é familiarizado com o ambiente culinário, a plataforma se restringe a receitas de simples execução. Podendo ser executadas por todos os usuários. |
| 02  | Seguindo a ideia de que muitas vezes o público alvo ainda não tem uma vida financeira estabelecida, o projeto é voltado para receitas de baixo custo, se tornando assim, abrangente para a maioria das classes sociais.                                                                  |
| 03  | Pensando no bem-estar dos usuários, a plataforma é composta por uma biblioteca focada em receitas saudáveis, priorizando sempre que possível, o uso de ingredientes orgânicos e de baixo teor calórico.                                                                                  |
