# gemini_ai
Progresso de Imersão Gemini AI Alura e Google - Maio24

***IMPORTANTE***
A ideia é criar um diário prático aplicado da imersão, sem mencionar dados sensíveis utilizados, deixando aberto papra qualquer tipo de "input" mas seguindo a lógica explicada/utilizada.


06052024 Aula 1
No Gemini:
-Comandos/prompt efetuados como teste.
-Tentado exportar histórico de acessos conforme solicitado, porém mesmo com 1 dia, a ferramenta dá um "buffer overflow"/estouro de memória e não vai... talvez seja minha máquina =)
-Fiz algumas requisições de listagem de lugares próximos a mim (por exemplo, "oficina de moto"), mas ele só retornou 5 próximas... mesmo falando para trazer todas elas num raio de 7km (e aumentando para 10, 15 ou 20km...). Mas ele conseguiu manipular em tabela, listando nome, endereço e avaliação. Vou fazer mais algumas explorações e simular no Studio...

No Studio:
-Criado API KEY.
-Consegui subir no prompt a lista de sites acessados no dia e na última semana, solicitei tabela de resumo por acesso, site, tipo e ele gerou! E ainda comparou entre o acessado do dia com da semana, informando sites com aumento de visitas, sugerindo explorar mais atividades em alguns sites e também conseguiu identificar um site/sistema web proprietário de gestão!!! :-O
-Tentei trazer lista de oficinas de moto próximas, mas diz que não tem acesso a minha localização, não tem acesso ao Maps em tempo real... mesmo especificando um endereço e pedindo oficinas no bairro ou próximas nem mesmo citando bairros. Mas sugeriu como fazer utilizando o Maps e montando a tabela manualmente... :-/
-Subi uma lista dos produtos vendidos no ano de 2023, pedi para o prompt listar top 10 produtos melhores para venda, considerando periodicidade/volume e lucro. Trouxe uma análise muito boa, detalhando o produto e justificando. \o/

Geral:
-Criado GitHub e repositório.
-Criado usuário na "Google for Developers" / "Google Cloud Innovators".
-Brincadeiras com o https://codepen.io/. 
-Criado perfil no Kaggle.

07052024 Aula 2
No Studio:
-Técnica de Few-shot Chain-of-Thought, crie um post polêmico para o linkedin de 1 ou 2 frases sobre a IA, com estruturação e exemplos de posts antigos e de outros similares. Resultado você confere no meu Linkedin:
https://www.linkedin.com/in/fernando-marques-de-souza-42bb2ab/

-Ilustrado com 10 matérias e títulos. Informado a 11a. matéria mas sem título e solicitado para sugerir um título polêmico e chamativo. As matérias foram de assuntos variados... A princípio, ele não identificou a estrutura e sugeriu novos títulos para a primeira matéria. Estruturei melhor colocando matéria 1, 2, .... de forma interessante, ele listou não só a versão polêmica, mas também outras 3 opções, sendo: de impacto, curiosidade, urgência. Comparando com o título original, a versão "curiosidade" ficou bem similar. Realmente, eu gostei mais da versão polêmica :-))
https://olhardigital.com.br/2024/05/07/ciencia-e-espaco/dobras-espaciais-podem-se-tornar-realidade-dizem-cientistas/
Opção 1 (Foco na polêmica):
Star Trek estava certo? Cientistas criam dobra espacial que desafia Einstein
Opção 2 (Foco no impacto):
Adeus, Einstein! Dobras espaciais podem revolucionar as viagens interestelares
Opção 3 (Foco na curiosidade):
A ficção se torna realidade? Estudo abre caminho para viagens em dobras espaciais
Opção 4 (Foco na urgência):
Prepare-se para o futuro: Dobras espaciais estão mais perto do que imaginamos

-Percebi que muitos casos onde não há uma estrutura de prompt, ele realmente devaga ou cita (normalmente) 4~5 situações, exemplos, pilares, elucidações ou "alucinações".

-Feito questionamentos sobre estrutura de frases em PT-BR, bem como consistência, informação, posicionamento de sinais (vírgula, pontos, áspas) e realmente corrigiu o que precisava, fez sugestões de melhorias ou até afirmou o que estava correto e justificou.

-Questionado a IA sobre dados sensíveis e utilização por empresas com informações confidenciais e ela informou e justificou por meio de pilares (trocando em miúdos) de que os dados utilizados são pertencentes do usuário que está utilizando, e que o Google possui camadas de proteção e confidencialidade...


08052024 Aula 3
No Studio:
-Aqui foi feito um teste com áudio como sugerido. Encontrado algo bem interessante que eu compartilho:
https://drive.google.com/file/d/1HL_DgiJjMvTrG3xjv5gcJ6F52yrJLaHY/view?usp=sharing, https://aistudio.google.com/app/prompts?state=%7B%22ids%22:%5B%221Sn7-QVrBRSCFkGS9dns-pF9mxQpu7J1D%22%5D,%22action%22:%22open%22,%22userId%22:%22112519395402898208566%22,%22resourceKeys%22:%7B%7D%7D&usp=sharing
Em resumo, informado áudio direto "Eu tenho arroz feito, ovo, prego, farinha de trigo, carne moída feita e temperos". Pedi para dizer qual ingrediente estava fora de contexto e ele me disse que era a farinha de trigo.
Achei que fosse algum entendimento errôneo do áudio e eu pedi para ele transcrever e trouxe o prego "em claro tom". Pedi para justificar porque da farinha e disse que seria feito para pratos doces. Questionei sobre o prego, ele disse que eu tinha razão (LOL). Mesmo assim ele insistiu em ser a farinha de trigo. Ensinei a ele dizendo que a farinha também usa em receitas de pratos. Novamente eu tinha razão. Pedi para me falar qual ingrediente estava fora de contexto e ele disse ser o prego (ufa, já tinha achado que iria virar "Homem de Ferro" kkk). Finalmente, pedi para ele me dizer qual item estava fora de contexto somente levando em consideração o audio, sem o que dissemos e ele reafirmou ser o prego! ;-)
-Exportado códigos do Studio e efetuado testes no COLAB. 
Uma atividade era pegar o código e simplesmente rodar com a API Key, tranquilo.
Outra era rodar com imagens, verificando e gerando conteúdo sobre as imagens. Importado imagens no Colab e rodou tranquilo. Interessante ressaltar que o código gerado no momento para o Colab não é o mesmo SE alterar o descritivo e outros parametros no Studio. Ou seja, copiado o código e rodado no Colab, ele roda independente do Studio (se o prompt foi salvo ou não).

Geral:
-Acessado Google Colab.

09052024 Aula 4 DESAFIO LANÇADO!
-Achei errôneo já liberarem para votação no Discord, mesmo porque a "Aula 5" será amanhã. Meu ponto de vista, teria que ser ao menos após essa aula 5... mais justo ainda se tivesse um "gap" para pensar depois da aula 5. Mas talvez seja parte do desafio (dá-se o nome ;-) )
-Rumo a criação de uma solução útil para poder aplicar os conteúdos até agora. Várias ideias surgiram: chat de mini-mercado de condomínio (perguntar se há "x" produto disponível no mercado), tira-dúvidas de condomínio (considerando convenção e documentação do prédio), auxiliar de estudo "lição de casa" para turminha de ensino fundamental 1 (será um projeto futuro!), chat de tira-dúvidas para contabilidade (visando vencimentos/recolhimento de obrigações).
-chat de tira-dúvidas para contabilidade, parece ser bem útil pois há uma demanda expressiva de um escritório de contabilidade. Muitos clientes entram em contato somente para perguntar: "quais as obrigações acessórias e quando é o vencimento".
-Premissas v1: Você é um contador, que precisa saber informações necessárias (exemplo: tipo, regime tributário, faturamento anual, valor de faturamento do período que as vezes é o mês anterior, etc...) para dar informações certeiras para os questionamentos do usuário, limitando-se a: obrigações acessórias (valores, tipos, impostos, relatórios do governo, informes, etc) e vencimentos/prazos. Mesmo que não solicitado, dê ao usuário uma tabela anual de vencimentos/prazos com os detalhes.
-Premissas v2: Você é um contador, limite-se a responder somente dúvidas de contabilidade. Você precisa saber informações necessárias (exemplo: tipo, regime tributário, faturamento anual, valor de faturamento do período que as vezes é o mês anterior, estado e município da empresa etc...) para dar informações certeiras para os questionamentos do usuário. Essas informações você precisa saber primeiro e antes de qualquer resposta ou adiantar resposta. Depois, com todos os detalhes e informações pertinentes, limite-se a: obrigações acessórias (valores, tipos, impostos, relatórios do governo, informes, etc) e vencimentos/prazos. Mesmo que não solicitado, dê ao usuário uma tabela anual de vencimentos/prazos com os detalhes (pois pode ser que ele tenha esquecido de pagar algum que já passou e também pode se programar para pagar os futuros e não só o que ele pediu).
-Premissas v3: Você é um contador virtual assistente, mas que tem uma equipe treinada para qualquer "próximo passo" ou "o que fazer agora", limite-se a responder somente dúvidas de contabilidade. Você precisa saber informações necessárias (exemplo: tipo, regime tributário, faturamento anual, valor de faturamento do período que as vezes é o mês anterior, estado e município da empresa etc...) para dar informações certeiras para os questionamentos do usuário. Essas informações você precisa saber primeiro e antes de qualquer resposta ou adiantar resposta. Depois, com todos os detalhes e informações pertinentes, limite-se a: obrigações acessórias (valores, tipos, impostos, relatórios do governo, informes, etc) e vencimentos/prazos. Mesmo que não solicitado, dê ao usuário uma tabela anual de vencimentos/prazos com os detalhes (pois pode ser que ele tenha esquecido de pagar algum que já passou e também pode se programar para pagar os futuros e não só o que ele pediu).
-Premissas v4: Quem te pergunta é cliente, ou seja, tem contrato ou paga o escritório para fazer os serviços. Você é um contador virtual assistente, mas que tem uma equipe treinada para qualquer sugestão ou ao invés de falar para procurar um profissional, sugira falar com a equipe. Limite-se a responder somente dúvidas de contabilidade. Não dê nenhum passo-a-passo ou faça você mesmo para evitar problema com o cliente. Você precisa saber informações necessárias (exemplo: tipo, regime tributário, faturamento anual, valor de faturamento do período que as vezes é o mês anterior, estado e município da empresa etc...) para dar informações certeiras para os questionamentos do usuário. Essas informações você precisa saber primeiro e antes de qualquer resposta ou adiantar resposta. Depois, com todos os detalhes e informações pertinentes, limite-se a: obrigações acessórias (valores, tipos, impostos, relatórios do governo, informes, etc) e vencimentos/prazos. Mesmo que não solicitado, dê ao usuário uma tabela anual de vencimentos/prazos com os detalhes (pois pode ser que ele tenha esquecido de pagar algum que já passou e também pode se programar para pagar os futuros e não só o que ele pediu).
-Premissas v5: Quem te pergunta é cliente, ou seja, tem contrato ou paga o escritório para fazer os serviços. Você é um contador virtual assistente, que tem uma equipe treinada, ao invés de falar ou sugerir para procurar um profissional ou um contador, sugira falar com a "nossa equipe". Limite-se a responder somente dúvidas de contabilidade. Não dê nenhum passo-a-passo ou faça você mesmo para evitar problema com o cliente. Você precisa saber informações necessárias (exemplo: tipo, regime tributário, faturamento anual, valor de faturamento do período que as vezes é o mês anterior, estado e município da empresa etc...) para dar informações certeiras para os questionamentos do usuário. Essas informações você precisa saber primeiro e antes de qualquer resposta ou adiantar resposta. Depois, com todos os detalhes e informações pertinentes, limite-se a: obrigações acessórias (valores, tipos, impostos, relatórios do governo, informes, etc) e vencimentos/prazos. Mesmo que não solicitado, dê ao usuário uma tabela anual de vencimentos/prazos com os detalhes (pois pode ser que ele tenha esquecido de pagar algum que já passou e também pode se programar para pagar os futuros e não só o que ele pediu).
-Premissas v6: Somente Contabilidade. Não dê nenhum "você pode fazer" ou passo-a-passo. Solicite todas as informações necessárias ANTES de qualquer resposta ou adiantamento de informação. Limite-se a obrigações, impostos, vencimentos, prazos. Informe tabela anual com detalhes solicitados. Sugira sempre "fale com nossa equipe especializada". Não recomende nada sem ser da contabilidade.

