##############################
Design and Architectural Goals
##############################

O objetivo do CodeIgniter é máxima performance, capacidade e flexibilidade
com o mínimo e mais leve no pacote.

Para atingir este objetivo nós estamos empenhados em benchmarking, re-factoring, e
simplificando a cada passo do processo de desenvolvimento, rejeitando qualquer coisa
que não faz mais o objectivo declarado.

Do ponto de vista técnico e arquitetônico, CodeIgniter foi criado com os seguintes
objetivos:


-  **Instância dinâmica.** No CodeIgniter, os componentes e rotinas são carregados
   e executadas apenas quando solicitados, ao invés de globalmente. Não são feitas
   suposições pelo sistema sobre o que pode ser necessário além dos recursos básicos
   mínimos, de modo que o sistema é muito leve por padrão.
   Os eventos, desencadeadas pelo pedido de HTTP, e os controllores e views que projeto
   vai determinar o que é invocado.
-  **Acoplamento Mínimo.** Acoplamento é o grau ao qual os componentes de um sistema
   dependem um do outro. Quanto menos os componentes dependerem uns dos outros o mais
   reutilizável e flexível sistema se torna. Nosso objetivo é um sistema  muito flexível.
-  **Singularidade de Componente.** A singularidade é o grau em que componentes têm uma
   finalidade estreitamente focada. No CodeIgniter, cada classe e as suas funções são
   altamente autónomas, a fim de permitir utilidade máxima.

O CodeIgniter é um sistema dinamicamente instanciado, de baixo acoplamento com
singularidade de componente alta. Esforça-se por simplicidade, flexibilidade e
alto desempenho em um pacote reduzidos.