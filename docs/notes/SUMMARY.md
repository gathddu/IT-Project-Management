#

### O que é um Projeto?

Um projeto é um esforço temporário empreendido para criar um produto, serviço ou resultado único.

- Esforço Temporário: Todo projeto tem um início e um fim claramente definidos. Temporário não significa que o projeto será rápido mas que sua duração é finita. Quando os objetivos são alcançados ou quando se descobre que não podem ser alcançados, o projeto é encerrado.

- Resultado Único: Mesmo que uma fábrica de software desenvolva dezenas de aplicativos de e-commerce, cada um é um projeto único, pois terá clientes diferentes, requisitos de design específicos, integrações com bancos de dados distintos e equipes variadas.

- Operações são contínuas e repetitivas. Elas sustentam o negócio no dia a dia. Como, o processamento da folha de pagamento, o suporte de TI atendendo chamados ou a linha de montagem de uma fábrica.

- Projetos são os agentes de mudança. Eles tiram a empresa de um estado atual e a levam para um estado futuro desejado. Como, a criação de um novo sistema de folha de pagamento.

### Geração de Valor

O projeto  não existe apenas para entregar um software, ele existe para resolver um problema de negócio.

O valor pode ser classificado em duas categorias:

- Valor Tangível: Aquilo que pode ser quantificado financeiramente ou em métricas exatas.

- Valor Intangível: Benefícios reais mas difíceis de medir financeiramente de forma direta.

### A Tríplice Restrição

Todo gerente de projetos opera sob constante pressão, tentando equilibrar forças que puxam em direções opostas. Esse equilíbrio é modelado pela Tríplice Restrição.

| Restrição | Na Prática | Impacto se Alterado |
| --------- | ---------- | ------------------- |
| Escopo | Todo o trabalho que precisa ser feito e apenas o trabalho que precisa ser feito. È a lista de funcionalidades e requisitos. | Se o cliente pedir mais funcionalidades (aumento de escopo), o tempo ou custo terão que aumentar. |
| Tempo | O cronograma do projeto. O prazo final em que o produto deve estar pronto. | Se o prazo for encurtado, será necessário cortar escopo ou aumentar o custo (contratando mais pessoas). |
| Custo | O orçamento disponível, incluindo horas de desenvolvedores, licenças de software e servidores. | Se o orçamento for cortado, a equipe diminui, o que estende o tempo ou reduz o escopo entregue. |

A qualidade está no centro. Se você tentar entregar mais escopo, em menos tempo e com menos dinheiro, a qualidade inevitavelmente será destruída (gerando bugs, falhas de segurança e código mal escrito).


## Tecnologia da Informação

### Características de Projetos de TI

- Intangibilidade: O software é invisível. O progresso está escondido em liahs de código, dificultando a medição do progresos real.

- Elaboração Progressiva: É quase impossível que um cliente saiba exatamente tudo o que quer no início do projeto. O entendimento sobre o produto evolui à medida que ele é construído. O que começa como "um botão de login" pode se desdobrar em "login social com Google, autenticação de dois fatores e recuperação de senha via SMS".

- Alta Incerteza e Risco: A tecnologia muda. Uma API de terceiros pode ser descontinuada no meio do projeto. A integração com sistemas legados pode revelar problemas ocultos.

- Transição para Operações (Handover): Quando o projeto de construção de um software acaba, há a fase de operação e manutenção. O código precisará ser sustentado, bugs em produção corrigidos e servidores monitorados.

### Perfil do Gerente

Antes, o Gerente de Projetos (GP) era um cobrador de prazos, focado em planilhas e gráficos. Hoje, é um integrador e um líder facilitador.

- Ways of Working: O GP não pode ser refém de uma única metodologia. Ele precisa dominar o modelo preditivo, os frameworks ágeis e saber criar abordagens híbridas.

- Power Skills: Liderança servidora (remover obstáculos para a equipe técnica trabalhar), negociação com clientes difíceis, inteligência emocional e resolução de conflitos.

- Business Acumen: Entender o mercado da empresa. Se o projeto é para um banco, o GP precisa entender o básico de finanças e regulação bancária para tomar boas decisões de priorização.

### Estruturas Organizacionais

- Estrutura Funcional: A empresa é dividida em silos (TI, Marketing, RH). O GP tem quase 0 autoridade. Ele atua como um coordenador que precisa "pedir favor" aos gerentes de departamento para liberar desenvolvedores. O orçamento fica com o gerente funcional.

- Estrutura Projetizada: A empresa é organizada por projetos (comum em consultorias de TI). O GP tem autoridade total, ele é o chefe da equipe durante o projeto e controla o orçamento.

- Estrutura Matricial: Um modelo misto onde o desenvolvedor tem dois chefes: o gerente do departamento e o gerente do projeto. Pode ser fraca, balanceada ou forte.

Para organizar o caos, há o PMO (Project Management Office ou Escritório de Gerenciamento de Projetos). O PMO pode atuar como Suporte (fornecendo templates e conselhos), Controle (exigindo que todos usem a mesma ferramenta e metodologia) ou Diretivo (onde os GPs respondem diretamente ao PMO, que gerencia o portfólio da empresa).

## Abordagens de Desenvolvimento

A escolha do caminho (Tailoring ou Adequação) é a decisão mais importante do projeto.

### Preditiva (Waterfall)

Tentamos prever todo o futuro no início. O projeto flui em fases estritamente sequenciais:

1. Levantar de Requisitos (mapear tudo o que o sistema fará)
2. Design (desenhar a arquitetura e as telas)
3. Implementação (escrever o código)
4. Testes (verificar se há erros)
5. Implantação (deploy)

Quando usar: Quando o risco de erro é catastrófico e os requisitos são imutáveis.

Problema: O cliente só vê o software funcionando no final. Se o mercado mudou durante o ano de desenvolvimento, ou se o cliente não soube explicar o que queria na fase 1, o projeto entrega um produto perfeito que ninguém quer usar.

### Adaptativa

Em vez de tentar prever o futuro, o ágil assume que as coisas vão mudar e cria um processo para se adaptar rapidamente.

Os fundamentos ágeis priorizam:
- Indivíduos e interações sobre processos e ferramentas
- Software funcionando sobre documentação abrangente
- Colaboração com o cliente sobre negociação de contratos
- Responder a mudanças sobre seguir um plano inicial rígido

No ágil, o projeto é dividido em ciclos curtos chamados iterações ou sprints (1 a 4 semanas). Em cada sprint, a equipe planeja, desenvolve e testa um pequeno pedaço funcional do software. O cliente vê o progresso continuamente e pode alterar a direção do projeto a cada novo ciclo.

Valores práticos (XP - Extreme Programming):

- Coragem: para dizer a verdade sobre atrasos e para jogar código ruim fora
- Simplicidade: Fazer a coisa mais simples que funcione hoje, sem super-engenharia para problemas que talvez nunca existam.
- Feedback: Ciclos curtos garantem que a equipe saiba rapidamente se está no caminho certo.

### Híbrida

A gestão do orçamento, a compra de servidores e os contrtos com fornecedores são tratados de forma preditiva (com planejamento de longo prazo). Já a construção do software em si, a interface e as funcionalidades são tratadas de forma ágil, permitindo flexibilidade técnica dentro de um "guarda-chuva" financeiro controlado.

## Os Domínios do PMBOK 7

São fases e áreas de foco que o GP precisa equilibrar simultaneamente durante todo o projeto.

### Stakeholders

Stakeholders são todas as pessoas ou organizações que podem afetar, ser afetados ou perceberem-se afetados pelo projeto. Isso inclui o cliente que paga (Sponsor), os usuários finais, a equipe de desenvolvimento, a diretoria e até o governo (órgãos reguladores)

1. Identificar: quem são eles?
2. Compreender e Analisar: qual o nível de poder e interesse de cada um? um stakeholder com alto poder e alto interesse deve ser gerenciado de perto.
3. Engajar: Comunicação não é apenas enviar relatórios. È escuta ativa, gestão de expectativas e resolução de conflitos
