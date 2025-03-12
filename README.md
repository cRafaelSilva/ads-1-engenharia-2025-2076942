# 📚 Diário de Engenharia de Software - {Nome do Aluno}

## 🔍 Introdução às Metodologias de Desenvolvimento de Software  
Por muito tempo a engenharia de Software careceu de metodologias para a criação de aplicações, com isso inúmeros erros ao longo dos projetos eram descobertos, ou sequer percebidos, é inegável que a utilização de metodologias já aplicadas nas outras Engenharias foi fundamental para estabelecer parâmetros de criação do projeto, implementação e testagem. Tais medidas resultaram em uma diminuição brutal nos problemas enfrentados na criação de Softwares permitindo o surgimento de projetos com maior qualidade, menor tempo e menor custo.

## 📖 Metodologias Tradicionais  
### 🛠️ Cascata  
A metodologia em Cascata foi o primeiro modelo de desenvolvimento de Software adotado. É um processo a ser executado em sequência, sem que de uma etapa posterior seja possível retornar a uma etapa anterior. A abordagem adotada é sistemática e sequencial no ciclo de vida do desenvolvimento. Suas fases podem ser identificadas como: 
Comunicação -Inicio do projeto e levantamento de requisitos; 
Planejamento - Levantamento das estimativas, cronogramas e acompanhamento;
Modelagem - Análise do projeto
Contrusção - Montagem do código e realização de testes;
Entrega- Entrega do projeto, recebimento de feedback e suporte.
O ponto forte dessa metodologia é o fácil gerenciamento pelas suas etapas bem definidas, contúdo o contraponto dessa caractrísticas é a falta de capacidade em lidar com mudanças de requisitos pois após concluída uma etapa não se retroaje para ajustes o que é agravado pela entrega do Software ser realizada somente com o projeto já concluido gerando altos custos para atender as necessidades.

### 🌐 Espiral  
Módelo advindo da mesclagem da prototipação e da Cascata, inicialmente apresenta-se um protótipo para cada etapa do ciclo de vida de desenvolvimento. O objeto é diminuir os riscos de erros no processo permitindo que seja avançado etapa por etapa após a diminuição dos riscos. O contraponto desta metodologia é seu alto custo durante o ciclo de desenvolvimento e o tempo necessário para tal, note que a cada etapa é levantado os riscos do projeto e com isso é feito um protótipo para prevenção e diminuição de tal risco, assim o desenvolvimento da aplicação só avança de etapa após efetivamente ocorrerem reduções nos riscos.

## 💪 Metodologias Ágeis  
### 📖 Manifesto Ágil  
O Manifesto Ágil surgiu da colaboração de especialistas em desenvolvimento de Software que tinham como objetivo tornar o processo menos burocrático e mais colaborativo, desta reunião extraiu-se 4 valores fundamentais:
1- indivíduos e interações mais que processos e Ferramentas;
2 - Software em funcionamento mais que documentação abrangente;
3 - Colaboração com o cliente mais que negociação de contratos;
4- Responder a mundaças mais que seguir um plano.
Podemos extrair que os valores da metodologia ágil colocam o cliente como centro do ciclo de vida do desenvolvimento do Software, as negociações e atendimento de mudanças nos requisitos são bem vistas ao longo do processo, além que nessa forma as aplicações são entregues de maneira continua e interativa permitindo feedbacks mais precisos. Em paralelo a é gerado na equipe responsável pelo Software por meio de um Espaço Colaborativo uma sensação de responsabilidade conjunta pelo Software.
Decorre desses 4 valores os 12 princípios do Manifesto Ágil, de maneira mais clara os princípios buscam sem um guia para equipes de desenvolvimento, tendo como base os 4 valores acima citados, para exemplificação, deixarei a listagem dos princípios: 
1 - Nossa maior prioridade é satisfazer o cliente através da entrega contínua e adiantada de software com valor agregado;
2 - Aceitar mudanças de requisitos, mesmo no fim do desenvolvimento. Processos ágeis se adequam a mudanças, para que o cliente possa tirar vantagens competitivas.;
3 - Entregar frequentemente software funcionando, de poucas semanas a poucos meses, com preferência à menor escala de tempo;
4 - Pessoas de negócio e desenvolvedores devem trabalhar diariamente em conjunto por todo o projeto;
5 - Construir projetos em torno de indivíduos motivados, dando a eles o ambiente e o suporte necessário e confiando neles para fazer o trabalho;
6 - O método mais eficiente e eficaz de transmitir informações para e entre uma equipe de desenvolvimento é por meio de conversa face a face;
7 - Software funcionando é a medida primária de progresso;
8 - Os processos ágeis promovem desenvolvimento sustentável. Os patrocinadores, desenvolvedores e usuários devem ser capazes de manter um ritmo constante indefinidamente;
9 - Contínua atenção a excelência técnica e bom design aumenta a agilidade;
10 - Simplicidade: a arte de maximizar a quantidade de trabalho não realizado é essencial;
11 - As melhores arquiteturas, requisitos e designs emergem de times auto-organizáveis;
12 - Em intervalos regulares, a equipe reflete sobre como se tornar mais eficaz e então refina e ajusta seu comportamento de acordo;
## 🏆 Scrum  
### 📅 Sprints  
A metodóliga Scrum é a mais popular das formas ágeis de entrega de Sotware, Consite na realização de Reuniões Diárias voltadas para atualizar de maneira sucinta a concretização de Tarefas de cada um da Equipe de Desenvolvimento e também a realização de pequenos ciclos de entrega no menor tempo possível, conhecido como Sprint, garantindo avanços constantes no ciclo de desenvolvimento. 

### 💬 Cerimônias  
Sprint Planning - Momento onde o time recebe as principais demandas que devem ser executadas até a Sprint
Daily Scrum - Reuniões que ocorrem todos os dias no mesmo horários o time de desenvolvimento deve ficar em pé para que a reunião seja rápida apenas para atualizar sobre o andamento de suas tarefas
Sprint Review - Onde o time entregue ao PO tudo aquilo que foi executado no decorrer da Sprint para que seja validado e em caso do projeto não ter atingido nível desejado pelo Project Owner retorna as demandas ao Backlog
Sprint Retrospective - Geralmente após uma Sprint o Scrum Master dará um feedback a cada membro de sua equipe e adaptar as melhores dinâmicas de trabalho a realidade do seu time
Refinamento - Por fim uma reunião semelhante ao Planning, nesta etapa o PO levanta os requisitos e expõe a equipe de desenvolvimente, esta por sua vez, faz, quando necessário, questionamentos para confirmar a viabilidade de tais requisitos 

## 🎯 Kanban  
Uma alternativa ou um complemento  para o Scrum, aqui os projetos sofrem com interrpuções frequentes, muitas vezes diárias ou a cada minuto. A imprevisibilidade de qual será a demanda torna impeditivo um planejamento semanal ou quinzenal pois podem surgir solicitações de alta urgência. O local ideal para o uso do Kanban é área voltadas ao suporte que trabalham de acordo com pedidos específicos e que não se desdobrem em grandes alterações evitando a sobrecarga do time ou desenvolvedor responsável pelo suporte

## 🚀 Extreme Programming (XP)  
1 - A metodológia XP parte da premisa que o cliente descobri suas necessidades na medida que usam o sistema, dai decorrem valores e princípios, estes que irei listar: 
2 - Feedback rápido: a comunicação entre as partes envolvidas deve ser feita de maneira rápida para sanar dúvidas e aprender o que está sendo desenvolvido;
3 - Mudança incremental: Liberdade para os programadores realizarem mudanças nos códigos e nos requisitos quando julgarem necessárias.
4 - Abraçando Mudanças: As mudanças devem sempre ser levadas em consideração independente da etapa do projeto
5 - Assumir Simplicidade: Soluções simples devem ser prioritárias
6 - Trabalho de Qualidade: O foco final é qualidade, é sempre preciso agregar o maior valor possível ao cliente

## 🔧 Ferramentas de Gestão de Desenvolvimento  
### 💪 GitHub / GitLab  
 Local para salvar as diferentes versões do código desenvolvido e compartilhar entre usuários

### 🎮 Jira / Trello  
Ferramenta para gestão on-line de métodos ágeis auxiliando na organização de tarefas, possuem versões com integração junto ao GitHub e GitLab
```

---
Fontes:
MORAIS, Izabelly S.; ZANIN, Aline. Engenharia de software. Porto Alegre: SAGAH, 2020. E-book. p.82. ISBN 9788595022539. Disponível em: https://app.minhabiblioteca.com.br/reader/books/9788595022539/. Acesso em: 11 mar. 2025.
MASCHIETTO, Luís G.; RODRIGUES, Thiago N.; BIANCO, Clicéres M D.; et al. Processos de Desenvolvimento de Software. Porto Alegre: SAGAH, 2020. E-book. p.35. ISBN 9786556900520. Disponível em: https://app.minhabiblioteca.com.br/reader/books/9786556900520/. Acesso em: 11 mar. 2025.
