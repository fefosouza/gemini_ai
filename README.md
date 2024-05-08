# gemini_ai
Progresso de Imersão Gemini AI Alura e Google - Maio24


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

Geral:
-Percebi que muitos casos onde não há uma estrutura de prompt, ele realmente devaga ou cita (normalmente) 5 situações, exemplos.

