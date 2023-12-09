# <p align="center">**Aluga Auto**</p>
![Logo](https://github.com/ICEI-PUC-Minas-PMV-SI/2023-Eixo-2-Grupo-2-LocacaodeCarros/blob/main/Imagens%20do%20Doc/Logo%20Projeto.png "Logo")

---

Allan Spaviero Alpoim, 

Caio Ignatz Martins, 

Denis Alves da Silva Leite, 

Giulia Fernandes Donato de Mattos, 

Isadora Aparecida Cardoso Carvalho, 

Raphael Lucas Oliveira dos Santos, 

Rômulo Ferraz Chaves. 

---

### Instituto de Informática e Ciências Exatas – Pontifícia Universidade Católica de Minas Gerais (PUC MINAS) 
### Belo Horizonte – MG – Brasil

aalpoim@sga.pucminas.br 

dasleite@sga.pucminas.br 

caioignm@gmail.com 

gfdmattos@sga.pucminas.br 

iaccarvalho@sga.pucminas.br 

raphaellucasoliveira557@gmail.com 

romulochavesferraz@gmail.com 

---

**_Resumo:_** _Este estudo visa analisar a importância da modelagem de processos na otimização das operações de empresas de locação de veículos, considerando a competitividade do mercado e as mudanças nas demandas dos clientes. Utilizando uma abordagem de estudo de caso em uma empresa fictícia do setor, a pesquisa explora conceitos, métodos e ferramentas de modelagem de processos, destacando as particularidades e desafios específicos do ramo. A metodologia inclui a análise de processos existentes, identificando gargalos e oportunidades de melhoria através de técnicas como Business Process Model and Notation. Os resultados almejados envolvem a proposição de um modelo otimizado para aumentar a eficiência operacional, reduzir custos e aprimorar a experiência do cliente, contribuindo para a literatura acadêmica e fornecendo insights práticos para gestores e profissionais de sistemas de informação no setor de locação de veículos._

---

**1. Introdução**

&nbsp;&nbsp;&nbsp;&nbsp;Vivemos a era da mobilidade e através de sua rápida evolução ocorreram transformações fundamentais sobre a forma como interagimos, trabalhamos e desfrutamos de momentos de lazer. As mudanças que antes aconteciam de maneira gradual e sutil deram lugar a um dinamismo quase diário. Diversos setores da economia foram afetados, novos modelos de negócios surgiram e os que se mantiveram vivos precisam de adaptação constante. Não seria diferente com um negócio tradicional e que apesar de todas as mudanças, se manteve firme: o aluguel de automóveis. 

&nbsp;&nbsp;&nbsp;&nbsp;Fontes divergem sobre o primeiro carro alugado da história mundial, mas no Brasil "o primeiro automóvel alugado foi de fabricação da Volkswagen, o antigo Fusca" (ASSOCIAÇÃO BRASILEIRA DAS LOCADORAS DE AUTOMÓVEIS, 2023), registrado pela empresa "Auto Drive S.A. Indústria e Comércio, a primeira empresa criada no Brasil exclusivamente com a finalidade de alugar carros" (ASSOCIAÇÃO BRASILEIRA DAS LOCADORAS DE AUTOMÓVEIS, 2023). Desde então, a locação de veículos se tornou um modelo de negócio ainda mais atrativo, através de incentivos governamentais, do aluguel de grandes frotas para empresas, da criação de empresas de transporte individual de passageiros e mercadorias (ex.: Uber, Mercado Livre, etc.), o aumento dos preços de aquisição de veículos novos e usados nos últimos anos e a mudança de hábitos gerada pela chegada da pandemia do Covid-19 (QUINTELLA, 2023). 

&nbsp;&nbsp;&nbsp;&nbsp;Tendo em vista a popularidade do aluguel de veículos, é necessário se atentar a outras mudanças na cadeia de negócio, como o avanço tecnológico. A sociedade busca soluções rápidas, eficazes e que diminuam o custo do negócio, tanto para as empresas como para os clientes. Dessa forma, automatizar os processos e negócios das locadoras de veículos se tornou imprescindível para qualquer empresa que deseja manter sua competitividade no mercado, diminuindo burocracias e melhorando seus preços e margens. 

**1.1. Objetivos geral e específicos**

&nbsp;&nbsp;&nbsp;&nbsp;O objetivo geral do trabalho é elaborar uma aplicação em que os clientes possam encontrar os veículos da locadora e efetuar o processo de reserva e locação de uma forma intuitiva e segura. 

&nbsp;&nbsp;&nbsp;&nbsp;Para os objetivos específicos, o projeto visa: 

+ Permitir que os funcionários cadastrem todas as informações e características dos veículos necessárias para que o cliente possa fazer a melhor escolha de acordo com suas necessidades individuais;
  
+ Criar um cadastro de clientes eficiente e que solicite do usuário todos os dados necessários para gerar o contrato;
  
+ Esquematizar um processo de reserva de veículos de fácil usabilidade, permitindo que os usuários selecionem as datas de início e fim da locação, de acordo com a disponibilidade dos veículos, acessem o valor e o contrato da locação e ofereçam métodos e verifiquem os métodos de pagamentos oferecidos aos clientes.

**1.2. Justificativas**

&nbsp;&nbsp;&nbsp;&nbsp;Com o avanço tecnológico cada vez mais crescente, nos vemos com uma inevitável necessidade da utilização da tecnologia para a automatização de processos, tendo em vista que praticidade e rapidez são indispensáveis nos dias de hoje. 

&nbsp;&nbsp;&nbsp;&nbsp;A automatização de processos além de facilitar a relação entre cliente e empresa, é capaz de diminuir a necessidade de pessoal para realização desses processos, ocasionando, assim, uma considerável diminuição de custos financeiros e uma redução de atividades no âmbito de gestão de pessoas. Outra vantagem da automatização de processos, é a menor chance de erro na execução uma vez que a tecnologia é mais eficaz e precisa que nós humanos. 

---

**2. Participantes do processo de negócio**

&nbsp;&nbsp;&nbsp;&nbsp;Clientes: Os clientes são o principal stakeholder de uma empresa de locação de veículos. Eles são as pessoas que adquirem os serviços da empresa e, portanto, são os responsáveis por sua receita. Sendo eles pessoas ou empresas que têm necessidade de carros para algum serviço como por exemplo necessidade de um veículo em se mover dentro da cidade ou em viagens, substituição de veículos, evento de festas que necessitam de algum veículo, conhecer algum veículo antes da compra. A idade varia entre 21 anos e 65 anos, tendo carteira nacional de habilitação, sendo ela pessoa física ou jurídica. O papel dos clientes é essencial para o sucesso do projeto de locação de veículos. Sem eles, o projeto não teria nenhum negócio. 

&nbsp;&nbsp;&nbsp;&nbsp;Funcionários: Desempenham um papel fundamental dentro de uma empresa de locação de veículos, irão ajudar no processo de locação. Idade entre 21 anos e 40 anos. O nível de educação é cursando algum curso superior. O papel dos funcionários é essencial para o sucesso de uma empresa de locação de veículos. Sem eles, a empresa não seria capaz de fornecer o serviço que seus clientes precisam. 

&nbsp;&nbsp;&nbsp;&nbsp;Fornecedores: O papel dos fornecedores de veículos é essencial para o sucesso da empresa de locação de veículos. Sem eles, a empresa não seria capaz de fornecer o serviço que seus clientes precisam. Sendo de pessoa física ou jurídica. Podendo fornecer uma variedade de veículos, desde carros compactos até SUVs e vans. Os fornecedores também podem fornecer serviços relacionados a veículos, como manutenção, reparo e seguro. 

---

**3. Modelagem do processo de negócio**

**3.1. Análise da situação atual (AS-IS)**

&nbsp;&nbsp;&nbsp;&nbsp;O principal problema que justifica nossa proposta é improdutividade causada pelo não uso das tecnologias apropriadas no setor de locação de veículos. Acreditamos que ao utilizar as ferramentas oferecidas pela tecnologia da informação seja possível melhorar o atendimento e o relacionamento com os clientes.  

&nbsp;&nbsp;&nbsp;&nbsp;Os processos utilizados nesta análise são: gerenciamento de veículos, gerenciamento de clientes e locação de veículos. Nos próximos parágrafos segue a descrição de cada um desses processos. 

&nbsp;&nbsp;&nbsp;&nbsp;O processo de gerenciamento de veículos é executado manualmente, de forma que um funcionário é incumbido de registrar as especificações dos carros disponíveis. São exemplos de descrições válidas: se possui ou não ar-condicionado, se possui ou não airbag, quantas portas tem e quantas pessoas transporta. Podemos citar como desvantagens do modelo atual, o risco de perda de arquivo, a duplicidade de cadastros e possíveis incoerências em relação ao estado real do veículo. 

| ![Imagem1](https://github.com/ICEI-PUC-Minas-PMV-SI/2023-Eixo-2-Grupo-2-LocacaodeCarros/blob/main/Imagens%20do%20Doc/1.%20Processo%20AS%20IS%20Gerenciar%20Veiculos.png "Imagem1")|
|:--:| 
| *<sub>Figura 1 - Representação AS-IS do processo de Gerenciamento de Veículos.  </sub>* |

&nbsp;&nbsp;&nbsp;&nbsp;No processo de gerenciamento de clientes, a empresa utiliza um sistema para arquivar as informações. No entanto, esse sistema não é adequado ao processo de locação, pois os dados solicitados podem ser preenchidos de maneira incorreta. Considerando que a partir das informações dos clientes é gerado um contrato para formalizar o aluguel, a empresa corre riscos em relação ao seu patrimônio, uma vez que, em caso de danos ao carro por parte do cliente, a organização não terá o respaldo necessário em uma ação judicial. 

| ![Imagem2](https://github.com/ICEI-PUC-Minas-PMV-SI/2023-Eixo-2-Grupo-2-LocacaodeCarros/blob/main/Imagens%20do%20Doc/2.%20Processo%20AS%20IS%20Gerenciar%20Clientes.png "Imagem2")|
|:--:| 
| *<sub>Figura 2 - Representação AS-IS do processo de Gerenciamento de Clientes.  </sub>* |

&nbsp;&nbsp;&nbsp;&nbsp;A imagem acima esquematiza o processo atual utilizado para cadastro de clientes, através do qual o atendente solicita as informações pessoais - como nome completo, CPF, RG, endereço completo, data de nascimento e outras informações, ao cliente - que precisa estar presente na loja. Após isso, o funcionário deve incluir os dados do cliente no sistema e finaliza a operação. 

&nbsp;&nbsp;&nbsp;&nbsp;Já o processo de locação de veículo, ainda que apoiado pelo sistema de cadastro, ainda exige disponibilidade de um funcionário e de trabalho manual. Um funcionário precisa acessar e verificar o cadastro do cliente e o cadastro do veículo, para que sejam checadas disponibilidade de datas para a locação para posterior conclusão de orçamento com valor final, confecção de contrato, além da verificação do método de pagamento.  

| ![Imagem3](https://github.com/ICEI-PUC-Minas-PMV-SI/2023-Eixo-2-Grupo-2-LocacaodeCarros/blob/main/Imagens%20do%20Doc/3.%20Processo%20AS%20IS%20Loca%C3%A7%C3%A3o%20de%20Ve%C3%ADculos.png "Imagem3")|
|:--:| 
| *<sub>Figura 3 - Representação AS-IS do processo de Locação de Veículos.   </sub>* |

&nbsp;&nbsp;&nbsp;&nbsp;Esse processo é realizado de maneira ineficiente e excessivamente burocrática, com a reunião de diversos relatórios impressos, a presença indispensável de um funcionário para preencher toda documentação necessária para o cliente e de outro funcionário para verificar a disponibilidade real do veículo locado e sua respectiva vistoria pré-locação. A presença obrigatória de pelo menos dois funcionários e o excesso burocrático não digitalizado tornam a operação onerosa, tanto financeiramente, quanto operacional, principalmente em relação aos Recursos Humanos. 

&nbsp;&nbsp;&nbsp;&nbsp;Sobre os impactos da ineficiência da empresa no oferecimento do serviço de locação de veículos: 
> "[...] Mais de 90% das 2000 pessoas entrevistadas em uma pesquisa da Opinion Box consideram a experiência um fator importante ou muito importante em um processo de compra. Porém, 77% do total acredita que a maioria das empresas precisam melhorar a experiência que oferecem para os seus clientes. De acordo com dados do estudo, a experiência é tão importante que 82% dos respondentes gastam mais em empresas que oferecem uma boa experiência. Além disso, 76% já deixaram de fazer uma compra por causa de uma experiência negativa (VIEIRA, 2022)."

&nbsp;&nbsp;&nbsp;&nbsp;Assim, é perceptível que o modelo atual carece da automatização adequada nos processos em benefício da empresa e dos clientes. Mostra-se necessário produzir um sistema que otimize os processos e melhore a experiência do cliente. 

**3.2. Modelagem dos processos aprimorados (TO-BE)**

&nbsp;&nbsp;&nbsp;&nbsp;Tendo em vista as deficiências atuais do negócio, foram pensadas algumas soluções, que proporcionam automação dos processos, com o objetivo de tornar a rotina de trabalho mais dinâmica e eficiente. 

&nbsp;&nbsp;&nbsp;&nbsp;Iniciando com o procedimento de registro de veículos, a implementação desse processo proporcionará celeridade na execução de diversas ações, abrangendo não apenas a criação de um novo registro veicular, mas também a sua subsequente atualização no sistema e a possibilidade de exclusão, quando necessário. Adicionalmente, esse sistema contribuirá significativamente para a consulta eficiente de veículos disponíveis em tempo real. A mitigação de duplicidades no cadastro de veículos será efetivada mediante a alocação de um identificador único gerado pelo sistema para cada veículo registrado.

<!--Figura 4-->
| ![Imagem4](https://github.com/ICEI-PUC-Minas-PMV-SI/2023-Eixo-2-Grupo-2-LocacaodeCarros/blob/main/Imagens%20do%20Doc/4.%20Processo%20TO%20BE%20Gerenciar%20Veiculos.png "Imagem4")|
|:--:| 
| *<sub>Figura 4 - Representação TO-BE do processo de Gerenciamento de Veículos.  </sub>* |

&nbsp;&nbsp;&nbsp;&nbsp;Na sequência, foi realizada uma análise visando solucionar os desafios encontrados no processo de registro de clientes. A automação dos procedimentos emergiu como a solução viável para aprimorar a eficácia das operações subsequentes, incluindo o registro de novos clientes, a atualização dos registros de clientes no sistema e a possibilidade de exclusão de cadastros. 

&nbsp;&nbsp;&nbsp;&nbsp;Essa abordagem proporciona uma resolução para o problema de registros de clientes com informações incompletas. Os registros serão preenchidos de forma abrangente, permitindo garantir uma maior segurança para a empresa, uma vez que esses dados constituem a base para a elaboração de contratos entre as partes. Adicionalmente, facilitará a resolução de questões legais, uma vez que as informações pessoais estarão atualizadas e prontas para agilizar quaisquer procedimentos jurídicos necessários. 

<!--Figura 5-->
| ![Imagem5](https://github.com/ICEI-PUC-Minas-PMV-SI/2023-Eixo-2-Grupo-2-LocacaodeCarros/blob/main/Imagens%20do%20Doc/5.%20Processo%20TO%20BE%20Gerenciar%20Clientes.png "Imagem5")|
|:--:| 
|*<sub>Figura 5 - Representação TO-BE do processo de Gerenciamento de Clientes.   </sub>* |

&nbsp;&nbsp;&nbsp;&nbsp;No contexto do processo de locação de veículos, a abordagem adotada consistiu na implementação de uma automação abrangente dos procedimentos necessários para efetivar a locação de um veículo. O requerente, além de fornecer informações pessoais para cadastro, terá a prerrogativa de especificar o período desejado para a locação, selecionar o veículo de sua preferência e ser informado sobre os custos associados ao aluguel. Além disso, o requerente terá acesso a um contrato que poderá ser assinado digitalmente e sua forma de pagamento será sujeita a verificação e confirmação.  

<!--Figura 6-->
| ![Imagem6](https://github.com/ICEI-PUC-Minas-PMV-SI/2023-Eixo-2-Grupo-2-LocacaodeCarros/blob/main/Imagens%20do%20Doc/6.%20Processo%20TO%20BE%20Loca%C3%A7%C3%A3o%20de%20Veiculos.png "Imagem6")|
|:--:| 
| *<sub>Figura 6 - Representação TO-BE do processo de Locação de Veículos.   </sub>* |

&nbsp;&nbsp;&nbsp;&nbsp;O objetivo desta iniciativa é proporcionar ao cliente autonomia e tornar o processo desprovido de documentos físicos, assinaturas e pagamentos, viabilizando atendimentos simultâneos por meio de um website, aplicativo móvel e/ou terminal local. Consequentemente, há a perspectiva de redução da dependência de mão de obra humana, possivelmente limitando-se a um único funcionário por unidade de operação, responsável por solucionar eventuais questões relacionadas aos processos automatizados. Dessa forma, a empresa se torna mais eficaz na prestação de serviços aos clientes, diminui os gastos relacionados às operações e ao departamento de Recursos Humanos, o que contribui para o aumento da eficiência da operação. 

---

**4. Projeto da arquitetura de dados da solução proposta**

**4.1. Diagrama de Entidades e Relacionamentos (DER)**

&nbsp;&nbsp;&nbsp;&nbsp;O desenvolvimento do Diagrama de Entidades e Relacionamento (DER) da solução proposta passa pela definição da construção e armazenamento dos dados e controles associados aos processos definidos. Dessa forma, é possível criar divisões práticas e que sejam funcionais no dia a dia das locações de automóveis de uma locadora, facilitando a entrega de informações e dos serviços tanto para os clientes contratantes, quanto para os funcionários da corporação.  

&nbsp;&nbsp;&nbsp;&nbsp;A entidade denominada "Cliente" é caracterizada por uma série de atributos descritivos, cujo propósito principal é fornecer uma descrição mais detalhada e contribuir para a proteção contratual da empresa. Um exemplo é o atributo CPF, que é exclusivo e desempenha um papel crucial na identificação única do contratante. Além disso, existem atributos como telefone e e-mail, que podem ser múltiplos, e o atributo endereço, que é estruturado hierarquicamente para promover uma organização eficaz. Por outro lado, a entidade "Funcionário", embora de construção aparentemente simples, é de importância fundamental para os procedimentos em vigor, uma vez que é encarregada da administração dos Veículos, que constituem a próxima entidade a ser abordada. A entidade "Veículo" segue princípios semelhantes à "Cliente", destacando a ênfase nos atributos descritivos e na identificação individual. Como mencionado anteriormente, os Veículos estão disponíveis para seleção pelos Clientes, mas a gestão integral é da responsabilidade dos Funcionários. Finalmente, a entidade "Contrato" serve como uma reunião abrangente de informações e formaliza a prestação de serviços.  

&nbsp;&nbsp;&nbsp;&nbsp;Para uma melhor visualização, a seguir temos a representação visual do diagrama descrito: 

<!--Figura 7-->
| ![Imagem7](https://github.com/ICEI-PUC-Minas-PMV-SI/2023-Eixo-2-Grupo-2-LocacaodeCarros/blob/main/Imagens%20do%20Doc/7.%20DER.png "Imagem7")     |
|:--:| 
| *<sub>Figura 7 - Representação AS-IS do processo de Locação de Veículos.   </sub>* |

**4.2. Impactos da implementação em um banco de dados NoSQL**

&nbsp;&nbsp;&nbsp;&nbsp;Os bancos de dados SQL são comumente recomendados para sistemas centrados em transações, como ferramentas de gerenciamento de relacionamento com clientes, software de contabilidade e plataformas de comércio eletrônico. Em contraste, os bancos de dados NoSQL são mais apropriados para aplicações que lidam com dados de forma flexível, como no caso de Internet of Things (IoT), e em volumes consideráveis. 

&nbsp;&nbsp;&nbsp;&nbsp;Considerando o contexto operacional da nossa empresa de locação de veículos, podemos inferir que as interações de dados entre clientes e servidor são, predominantemente, previsíveis em termos de estrutura. Isso ocorre porque os usuários só podem interagir com itens previamente listados na loja, enquanto os fornecedores podem adicionar itens seguindo formulários fixos. Além disso, a coleta de métricas de processos de negócios, como vendas e recomendação de produtos, envolve a consulta e relacionamento de diversos tipos de dados, o que torna a utilização da linguagem SQL uma escolha mais simples e eficaz. 

&nbsp;&nbsp;&nbsp;&nbsp;Entretanto, é relevante destacar que, com o crescimento da nossa base de clientes, a escalabilidade vertical de um banco de dados SQL pode se tornar uma limitação competitiva para o negócio. Nesse cenário, a adoção de um banco de dados NoSQL pode ser vantajosa, uma vez que a expansão do cluster com a adição de mais máquinas, para cobrir porções específicas dos dados armazenados, tende a ser economicamente mais viável, devido à facilidade de amortização dos custos de hardware. 

**4.3. Modelo relacional**

&nbsp;&nbsp;&nbsp;&nbsp;O modelo relacional proposto, fundamentado no DER, foi concebido com o propósito de gerenciar informações no contexto das entidades previamente mencionadas - cliente, veículo, funcionário, contrato, entre outras. Cada classe é transposta em forma de tabela em um sistema de gerenciamento de banco de dados relacional, com atributos específicos correspondentes a cada entidade. Conforme convenção estabelecida, chaves estrangeiras são definidas com múltiplas finalidades, incluindo a facilitação de relacionamentos eficazes entre dados e tabelas. A seguir, é apresentada a representação visual do modelo relacional do projeto. 

<!--Figura 8-->
| ![Imagem8](https://github.com/ICEI-PUC-Minas-PMV-SI/2023-Eixo-2-Grupo-2-LocacaodeCarros/blob/main/Imagens%20do%20Doc/8.%20Modelo%20Relacional.png "Imagem8")    |
|:--:| 
| *<sub>Figura 8 - Representação do Modelo Relacional do projeto.  </sub>* |

**4.4. Consultas SQL em Processos TO BE**

&nbsp;&nbsp;&nbsp;&nbsp;Com o objetivo de aprimorar a eficiência, é planejado automatizar os processos por meio da implementação de scripts. 

&nbsp;&nbsp;&nbsp;&nbsp;Dessa maneira, seguem três casos abaixo usados no projeto. 

<!--Tabela de Consultas em Processos TO BE-->
| Nome do processo TO BE             | Comando SQL                                                                                       | Significado do comando para a aplicação                            |
|------------------------------------|---------------------------------------------------------------------------------------------------|------------------------------------|
| Gerenciar clientes: criar cliente  | `_object._executor = _pin._requestor;`                                                            | Esta linha define o executor como sendo o indivíduo que deu origem ao processo por meio de uma solicitação inicial, resultando, portanto, na automação do atendimento.      |
| Gerenciar clientes: modificar cliente | `if(!_object){ throw "Erro ao Modificar cadastro do cliente."; } locadoradeveiculost2g2.cliente._update({ "_id": _pin.clienteSelecionado._id, "nome": _object.nome,     "cpf": _object.cpf, "telefone": _object.telefone, "email": _object.email, "dataDeNascimento": _object.dataDeNascimento, "endereco": _object.endereco, });` | Nesta linha é conferido se o executor preencheu os requisitos para modificar o cadastro do cliente, caso contrário, não será permitida a conclusão da atividade. Caso o executor tenha preenchido os requisitos, será feito a atualização do cliente selecionado nos campos: nome, CFP, telefone, e-mail, data de nascimento e endereço.   | 
|Gerenciar clientes: excluir cadastro.  | `if(!_object){ throw "Erro ao excluir cadastro de cliente."; } if(_object.confirmarExclusaoClienteSelecionado){ locadoradeveiculost2g2.cliente._delete(_pin.clienteSelecionado); } `  | Verifica se o executor preencheu os requisitos para excluir o cadastro do cliente, caso contrário, não permite a conclusão da atividade. Caso o executor tenha preenchido os requisitos, será confirmado o cliente selecionado e posteriormente feito a exclusão.  | 

**5. Relatórios analíticos**

&nbsp;&nbsp;&nbsp;&nbsp;Considerando as necessidades de informações das diversas partes interessadas nos processos eleitos, foram desenvolvidos, com o apoio da ferramenta empregada na disciplina, relatórios úteis para o controle dos processos e a tomada de decisão. 

&nbsp;&nbsp;&nbsp;&nbsp;O Relatório Diário de Gerenciamento de Clientes tem como objetivo principal fornecer uma visão abrangente do estado atual dos clientes registrados no sistema. O modelo gráfico de barras utilizado no relatório desempenha um papel importante ao possibilitar o percebimento da distribuição da quantidade de clientes criados no sistema, categorizados de acordo com seu status, sendo concluídos ou abertos. As informações sobre clientes concluídos refletem aqueles que finalizaram com sucesso suas transações, enquanto os clientes com status aberto apresentam potenciais em andamento. Esse monitoramento diário possibilita uma gestão mais eficiente, permitindo que a locadora identifique padrões, tome decisões informatizadas e otimize seus processos para melhor atender às necessidades dos clientes. 

| ![Imagem9](https://github.com/ICEI-PUC-Minas-PMV-SI/2023-Eixo-2-Grupo-2-LocacaodeCarros/blob/main/Imagens%20do%20Doc/9.%20Analytics%20Gerenciamento%20de%20Clientes.png "Imagem9")|
|:--:| 
| *<sub>Figura 9 - Representação do Relatório Diário de Gerenciamento de Clientes.  </sub>* |

&nbsp;&nbsp;&nbsp;&nbsp;O Relatório de Veículos em Gerenciamento da locadora de veículos, exibe a quantidade de veículos criados no sistema em relação ao seu status. Seu principal objetivo é oferecer uma visão abrangente do estado da frota, categorizando os veículos como concluídos ou abertos. Ao apresentar essa informação no formato de gráfico de pizza, o relatório possibilita uma compreensão imediata do percentual de veículos que estão disponíveis para novos aluguéis e os que ainda estão em andamento. Essa representação visual é valiosa para que a locadora possa identificar padrões, aprimorar o gerenciamento de frota e tomar decisões estratégicas para a melhoria da eficiência operacional e da satisfação do cliente. 

| ![Imagem10](https://github.com/ICEI-PUC-Minas-PMV-SI/2023-Eixo-2-Grupo-2-LocacaodeCarros/blob/main/Imagens%20do%20Doc/10.%20Analytics%20Ve%C3%ADculos%20em%20Gerenciamento.png "Imagem10") |
|:--:| 
| *<sub>Figura 10 - Representação do Relatório de Veículos em Gerenciamento.  </sub>*    |

&nbsp;&nbsp;&nbsp;&nbsp;O Relatório Diário de Locações Criadas é uma ferramenta estratégica que visa fornecer uma visão detalhada e organizada da quantidade de locações registradas diariamente. Seu principal objetivo é oferecer uma estrutura que permite a fácil identificação e análise das informações, destacando aspectos como volume diário de negócios, variações ao longo do tempo e potenciais padrões sazonais. Ao disponibilizar esses dados de maneira tabular, o relatório facilita a interpretação rápida por parte dos gestores, permitindo a avaliação do desempenho diário e a tomada de decisões para otimizar a operação da locadora, ajustando as estratégias necessárias para atender às demandas do mercado de forma eficaz. 

| ![Imagem11](https://github.com/ICEI-PUC-Minas-PMV-SI/2023-Eixo-2-Grupo-2-LocacaodeCarros/blob/main/Imagens%20do%20Doc/11.%20Analytics%20Di%C3%A1rio%20de%20Loca%C3%A7%C3%B5es%20Criadas.png "Imagem11") |
|:--:| 
| *<sub>Figura 11 - Representação do Relatório Diário de Locações Criadas.  </sub>*  |

---

**5.1. Associação de comandos SQL com relatórios analíticos**

&nbsp;&nbsp;&nbsp;&nbsp;Feito o processo de engenharia reversa, informando quais seriam os possíveis comandos SQL-DML (selects) que poderiam produzir os relatórios automaticamente gerados na plataforma Sydle One. 

| Nome do Relatório Analítico | Comando SQL-DML (SELECT) |
| --- | --- |
|Relatório Diário de Gerenciamento de Clientes.  | `SELECT  status,  COUNT(*) AS quantidade_total  COUNT(CASE WHEN status = 'aberto' THEN 1 END) AS quantidade_aberto,  COUNT(CASE WHEN status = 'concluido' THEN 1 END) AS quantidade_concluido  FROM  "Gerenciar Clientes - Modelo TO-BE"  WHERE  acao = 'criar cliente'  GROUP BY  status; ` 
|Relatório de Veículos em Gerenciamento.     | `SELECT  status,  COUNT(*) AS quantidade_total  COUNT(CASE WHEN status = 'aberto' THEN 1 END) AS quantidade_aberto,  COUNT(CASE WHEN status = 'concluido' THEN 1 END) AS  quantidade_concluido  FROM  “Gerenciar Veículos - Modelo TO-BE"  WHERE  acao = 'criar veiculo'  GROUP BY  status; ` 
| Relatório Diário de Locações Criadas. | `SELECT  Data_efetivacao,  COUNT(*) as Quantidade_Locacoes  FROM  “Locação de Veículos - Modelo TO-BE”  GROUP BY  Data_criacao; ` 

---

**6. Indicadores de desempenho**

| Indicador | Objetivo | Descrição | Fórmula de Cálculo | Fontes de Dados | Perspectivas |
| --- | --- | --- | --- | --- | --- |
| Taxa de satisfação | Disponibilizar as informações necessárias para melhor escolha do cliente | Percentual de erros em relação ao total de requisições | N° total de reclamações ÷ N° total de atendimentos | Tabela Cadastro de veículos | Aprendizado e Melhorias 
| Taxa solicitação de informações adicionais | Avaliar quantidade de informações solicitadas após a conclusão do cadastro | Determina o número de informações requisitadas após a finalização do cadastro | N° de informações requisitadas ÷ N° total de cadastros finalizados | Tabela cadastro de cliente | Aprendizado e melhorias 
| Taxa Abandono | Determinar o percentual de processos não concluídos | Mede % de processos de reserva que não foram finalizados | Nº de processos de reserva abandonados ÷ Nº total de processos de reserva *100 | Tabela Locação de veículos | Análise interna  
| Taxa transações bem sucedidas | Determinar o número de transações finalizadas com sucesso | Mede % de operações bem sucedidas | N° de transações bem sucedidas ÷ Total de transações *100 | Tabela locação de veículos | Processos internos  
| Percentual de satisfação | Determinar a satisfação em relação aos métodos de pagamentos disponíveis | Apresenta o % de satisfação em relação aos métodos de pagamento disponíveis | Nº de reclamações ÷ Total de transações *100 | Tabela Locação de veículos | Análise interna  

---

**7. Conclusão**

&nbsp;&nbsp;&nbsp;&nbsp;Diante do exposto, concluímos que o presente trabalho alcançou seu objetivo principal ao identificar e propor melhorias na empresa fictícia de locação de veículos, através da aplicação efetiva do mapeamento e modelagem de processos. As melhorias delineadas, conforme explorado à luz dos indicadores de desempenho, refletem a aplicação prática da teoria tomada como referencial, confirmando a relevância dos estudos consultados. 

&nbsp;&nbsp;&nbsp;&nbsp;A criação dos modelos TO-BE, como detalhado nos tópicos 3.2 e 4, não apenas contribuiu para a resolução do objetivo do trabalho, como também promoveu avanços significativos na gestão do conhecimento dos processos internos da organização. Essa abordagem, alinhada à realidade da empresa e considerando as particularidades do setor de locação de veículos no Brasil, revelou-se determinante para apontar melhorias operacionais, identificar oportunidades estratégicas e gerar retornos tanto quantitativos quanto qualitativos a longo prazo. 

&nbsp;&nbsp;&nbsp;&nbsp;A convergência das melhorias identificadas com a literatura revisada reforça a importância da adoção do mapeamento e modelagem de processos como uma técnica eficaz para otimização operacional. Além disso, reconhecemos que, para além dos benefícios operacionais, a modelagem dos processos existentes tem o potencial de aprimorar a gestão do conhecimento na empresa, proporcionando uma compreensão mais profunda das operações e incentivando a participação ativa dos colaboradores na construção de rotinas mais eficientes. 

&nbsp;&nbsp;&nbsp;&nbsp;Em continuidade a este projeto de pesquisa, propomos a exploração de tecnologias de ponta visando a informatização aprimorada dos processos delineados. Entre as ferramentas consideradas, destacamos a aplicação de Sistemas de Informação Geográfica (SIG), que proporciona a integração de dados espaciais, viabilizando uma visualização precisa e minuciosa da geografia dos locais de operação. Tal abordagem simplifica a análise de rotas e a identificação de áreas estratégicas. Adicionalmente, propõe-se a utilização de algoritmos de aprendizado de máquina para antecipar a demanda por veículos em distintos períodos, promovendo a otimização da gestão de frota e a redução de custos operacionais. A incorporação de tecnologias de Internet das Coisas (IoT) em veículos é sugerida para possibilitar a coleta em tempo real de dados relacionados ao desempenho, manutenção e localização, contribuindo substancialmente para a tomada de decisões fundamentada em dados precisos. Além disso, a automação de processos por meio de Robotic Process Automation (RPA) figura como uma alternativa para agilizar tarefas repetitivas e burocráticas, permitindo a alocação mais eficiente de recursos humanos em atividades de cunho estratégico. 

&nbsp;&nbsp;&nbsp;&nbsp;No sentido de contribuir continuamente para a temática abordada, recomendamos a análise de novos casos de aplicação do mapeamento e modelagem de processos no mercado de locação de veículos, bem como a exploração de outras técnicas de análise e solução de problemas específicas para o setor. Essa abordagem permitirá um aprofundamento nas possíveis soluções, tanto quantitativas quanto qualitativas, e abrirá caminho para uma compreensão mais abrangente das ferramentas disponíveis para aprimorar a eficiência e a gestão no contexto do setor. 

---

### <p align="center">**REFERÊNCIAS**</p>


&nbsp;&nbsp;&nbsp;&nbsp;ASSOCIAÇÃO BRASILEIRA DAS LOCADORAS DE AUTOMÓVEIS. ABLA, 2023. Site Institucional. Disponível em: <www.abla.com.br/historias>. Acesso em: 21 ago. 2023. 

&nbsp;&nbsp;&nbsp;&nbsp;QUINTELLA, Marcus. Aumento das locações de veículos no Brasil. Fundação Getúlio Vargas, 2023. Disponível em: <https://portal.fgv.br/artigos/aumento-locacoes-veiculos-brasil>. Acesso em: 21 ago. 2023. 

&nbsp;&nbsp;&nbsp;&nbsp;VIEIRA, R. A. Locação de veículos: segmento apresenta retomada e tem tecnologia e experiência como tendências centrais para os próximos anos. Disponível em: <https://solution4fleet.com.br/editorial/locacao-de-veiculos-segmento-apresenta-retomada-e-tem-tecnologia-e-experiencia-como-tendencias-centrais-para-os-proximos-anos/>. Acesso em: 24 ago. 2023. 

---

## Professora

* Rosilane Ribeiro da Mota.
