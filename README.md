# Mini Game — Instalação de Mini-Transponder no ROV

Jogo de estudo interativo sobre o procedimento de instalação de um mini-transponder (ou responder) em um ROV, com foco nos 11 passos do checklist e nos detalhes que costumam ser cobrados em prova.

Material de apoio para o Treinamento Profissional de Surveyor Offshore — Sistemas de Embarcações e ROV, na parte de posicionamento hidroacústico e calibração SSBL/USBL.

## Jogar agora

👉 **[Abrir o jogo](https://rafaelsantos1001.github.io/mini-game-transponder/)**

> Ajuste este link depois de ativar o GitHub Pages, caso o nome do repositório seja diferente.

Funciona no celular e no computador, direto no navegador. Não precisa instalar nada, criar conta nem fazer login.

## O que o jogo tem

São quatro modos, todos apoiados em uma animação do ROV que reage ao que você faz. Cada passo aparece na tela: a válvula de alívio girando, a borracha protetora envolvendo o equipamento, o LED acendendo, o transponder subindo para o ROV, o cabo de segurança e os dummy plugs sendo inseridos.

### 1. Aprender

Percorre os 11 passos na ordem, um de cada vez. Cada tela traz a ação do checklist e uma dica explicando o porquê daquele cuidado. Dá para pular direto para qualquer passo pelos números no rodapé. É o modo para usar na primeira vez.

### 2. Missão

Você conduz a instalação do zero. A cada etapa o jogo pergunta qual é a próxima ação e oferece quatro alternativas: a certa, passos que ainda vêm depois, passos que você já fez e erros de procedimento. Errar não trava o jogo, só conta o erro e explica o motivo. No final você recebe de 1 a 3 estrelas conforme o número de erros.

Nesta missão o equipamento é um **responder**, então a etapa do cabo específico se aplica.

### 3. Quiz

Dez perguntas de múltipla escolha sorteadas de um banco maior, em ordem aleatória e com as alternativas embaralhadas — cada partida é diferente. Cobre pontos como o raio de consulta dos canais, os equipamentos do teste de bancada, o significado de "solecado", a frequência de monitoramento da bateria e o que fazer com um transponder defeituoso. Toda resposta vem com a explicação.

### 4. Ordenar

Sem apoio da animação: você monta a sequência completa dos 11 passos do zero. Ao verificar, o jogo mostra quantos ficaram no lugar certo e, para os errados, qual seria a posição correta. É o modo mais difícil e o melhor teste antes da prova.

## Conteúdo coberto

Os 11 passos da instalação, na ordem:

1. Certificar-se de que as manutenções preventivas foram realizadas
2. Consultar as UEPs e navios de ROV na área (raio de 3 milhas náuticas) para obter os canais de seus transponders
3. Escolher um canal que não sofra interferência das embarcações próximas
4. Fechar a válvula de alívio do transponder
5. Envolvê-lo em uma borracha protetora
6. Ligar o transponder
7. Realizar teste de bancada (com TTC, DTU, Iwand etc.)
8. Conectar o transponder no ROV
9. Preparar um cabo de segurança e mantê-lo solecado, no ROV
10. Se for um responder, conectar o respectivo cabo
11. Inserir dummy/switch plugs nos penetradores que não estiverem sendo utilizados

O quiz inclui ainda dois cuidados relacionados: monitorar diariamente a bateria do transponder e, em caso de equipamento defeituoso, retornar ao convés e trocá-lo.

## Como funciona por dentro

Um único arquivo `index.html`, com o HTML, o CSS e o JavaScript juntos. Sem frameworks, sem build, sem dependências para instalar. A animação é SVG com transições em CSS.

- Abre em qualquer navegador moderno, no celular ou no desktop
- Acompanha o tema claro ou escuro do aparelho
- Respeita a preferência de redução de movimento do sistema
- Guarda seu melhor resultado de cada modo no próprio navegador, sem enviar nada para lugar nenhum
- Funciona offline depois de carregado (só as fontes vêm da internet; sem elas o jogo roda igual, com outra tipografia)

## Rodar na sua máquina

Baixe o `index.html` e abra com dois cliques. É só isso.

Para editar o conteúdo, procure no final do arquivo as listas `STEPS` (passos e dicas) e `QUIZ` (perguntas). Cada pergunta tem o enunciado, as alternativas, o índice da resposta correta e a explicação.

## Aviso

Material de estudo feito por estudante, para estudo. Não substitui a apostila, o instrutor nem o procedimento oficial. **Em operação real, siga sempre o procedimento da empresa e da embarcação.**

## Contribuindo

Achou um erro de conteúdo ou quer sugerir uma pergunta nova? Abra uma issue no repositório ou mande no grupo da turma.
