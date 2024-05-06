# Acompanhamento_Vendas
link: https://docs.google.com/spreadsheets/d/1eLT42_yI3NUQt2w0fWJXJjRpxeF8qEy7eQ-H-zqrQKg/edit?usp=sharing

Planilha do Google Sheets para acompanhar o faturamento diário por vendedor.
Trabalho em uma loja de varejo que vende produtos eletrônicos e alguns serviços como seguros, garantias estendidas e aplicações de películas. 
Meu papel como gerente é cuidar de toda a parte administrativa da loja e também acompanhar o faturamento, minha planilha serve como uma ferramentam de apoio para analisar os principais indicadores como meta, tendências, ticket médio, desconto médio, conversão de vendas e número serviços adicionais vendidos.
Nossa equipe é composta por 6 vendedores, é importante saber quem está na meta, quem está muito abaixo do resultado para gerir de uma forma mais eficiente. 
Quando iniciei na empresa já existiam planilhas com essa finalidade, porém era apenas uma ideia inicial que não exibia todas os indicadores necessários e a maior parte dos meus colegas tinham dificuldades para usá-las, alguns com mais familiriades criaram variações. Após meses trabalhando fui conhecendo proposta da ferramenta e alinhando com meus superiores quais indicadores eram mais relevantes então criei um novo modelo, com fórmulas mais elaboradas, busquei automatizar todos os cálculos possíveis e criar uma interface simples para qualquer um utilizar.
Consegui aprovação dos meus superiores e apresentei meu trabalho para toda a equipe de gestão da empresa e desde este dia esse modelo passou a ser um padrão. Criei um cópia para cada gestor em uma pasta do Google Drive e compartilhei os links, atribui permissões de segurança para que fosse possível editar apenas os campos necessários para garantir a integridades das fórmulas e layout. 

Na planilha existem as seguintes abas: ESCALA DE FOLGAS, ENTRADA DE DADOS, TRATAMENTO DADOS (OCULTA), RELATÓRIO INDIVIDUAL e RELATÓRIO GERAL. 

ENTRADA DE DADOS: Nessa tabela o usuário deve inserir todos os dados pertinentes a cada vendedos, como, meta mensal, ticket médio, desconto médio, faturamento realizado, quantidade de aparelhos vendidos, quantidades de serviços vendidos, etc. Essas informações são fornecidas pelo sistema da empresa, porém não existe uma dashboard para acompanhar os indicadores com mais eficiencia.

ESCALA DE FOLGAS: Nessa tabela o usuário deve inserir a escala de folgas mensal de cada vendedor, com esses dados será possível calcular sua meta diária e tendência com base nos dias trabalhados até a data atual. Aqui tem uma informação adicional, o sistema da empresa fornece os dados sempre até o dia anterior a data atual, então as fórmulas estão ajustadas para terem o mesmo comportamento para ficarem coerentes com o contexto do negócio. Exemplo: Hoje são 05 de maio, no sistema as vendas registradas estão até dia 04 de maio.

TRATAMENTO DADOS: Aqui é onde a análise de dados acontece. Usando os dados de ENTRADA DE DADOS e ESCALA DE FOLGAS são calculados todos os indicadores necessários para a operação daquela loja no contexto de vendas. 
Na operação temos 5 metas (Produto, Venda de B/C, Seguros, Garantias Estendidas e Películas) para cada meta é criada uma tabela, em cada linha temos um vendedor e nas colunas temos os indicadores como meta mensal, faturamento realizado até o momento, tendência, déficit ou superávit, quanto falta para meta, etc. 
Ao final da página temos uma tabela chamada Meta diária, contendo o objetivo diária de cada vendedor para cada uma das 5 metas.

RELATÓRIO GERAL: Aqui os indicadores são praticamente idênticos ao de TRATAMETNO DADOS, a diferença é que os dados são ordenados pelos vendedores como maior faturamento para criar um ranking e também esconder as maior parte das fórmulas e tornar a visualização mais amigável para o usuário. 
Essa tabela foi projetada para ser impressa em A4 para os gestores que gostam de ter os números no papel, basta um Ctrl + P.

RELATÓRIO INDIVIDUAL: Nessa tabela os indicadores são filtrados para exibirem apenas um vendedor, o objetivo é ter um relatório mais específico para o gestor da loja ter todos os dados na palpa da mão e chegar preparado para um feedback individual com seus vendedores. Aqui além das informações já conhecidas em RELATÓRIO GERAL também adicionei a previsão de premiação de algumas metas, com base no faturamento realizado. 


Considerações finais: Apesar de ser uma planilha grande o usuário só irá preencher diariamente a aba de ENTRADA DE DADOS para atualizar os indicadores, a ESCALA DE FOLGAS é atualizada uma vez por mês e a aba TRATAMENTO DADOS fica oculta.
Basta atualizar os dados e seguir para a aba de relatório para ter todas as informações prontas.
