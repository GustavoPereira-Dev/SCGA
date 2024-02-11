# SCGA

| :placard: Atributos | Descrição   |
| -------------  | --- |
| :sparkles: Nome        | **SCGA - Sistema de Comunicação e Gerenciamento de Ambiente**
| :label: Tecnologias | php, css, js, Bootstrap, Laravel, Firebase (tecnologias utilizadas)
| :rocket: URL         | https://scga.onrender.com/
<h3>Bem vindo ao repositório do Sistema de Comunicação e Gerenciamento de Ambiente (SCGA/ECMS)! </h3>
<p>Esse projeto foi feito com a itenção de ser o Trabalho de Conclusão de Curso (TCC) da Etec Zona Leste de São Paulo em 2023, com os integrantes
<a href="https://github.com/GustavoPereira-Dev">Gustavo Pereira</a>, <a href="https://github.com/ThiagoMartins11">Thiago Martins</a>, <a href="https://github.com/caitanoandre">André Caitano </a> e <a href="https://github.com/ReblerHugoh">Hugo Reblerson</a></p>
<p>Será descrito brevemente cada tela da aplicação desse sistema e seus objetivos no geral</p>

## Tela de início
<p>Nessa tela temos resumidamente a introdução do sistemas, seus objetivos, clientes (público-alvo), propósitos, sobre nós, opinião dos instrutores e entre outros,
além de a imagem nos mostrar que o site tem modo claro ou escuro pelo ícone da lua</p>
<img src="https://github.com/Gustavo-Henrique-da-Silva/SCGA/assets/108029506/689d6649-aabb-4fb4-ae5d-b3dc2cb36fe7"/>

## Telas de autenticação
<p>Clicando em um dos botões da imagem anterior de registrar-se ou login, entramos em uma das telas de autenticação, as quais cada uma tem seu objetivo descrito no
nome e o estilo visto na próxima imagem, sendo que todo esse sistema foi feito utilizando o aglomerado da funcionalidades do Firebase (FireStore, Authenticator, Realtime, Storage)</p>
<p>Além disso, podemos ver na imagem a possibilidade do esqueci a senha</p>
<img src="https://github.com/Gustavo-Henrique-da-Silva/SCGA/assets/108029506/ae3fccbf-e86e-4132-82f9-6487883fa388"/>

## Dashboard dos usuários
<p>Fazendo login na conta do usuário, dependendo de que topologia o mesmo tem (aluno, professor ou técnico) temos algumas diferenças em cada tela, entretanto, só para
amostra a tela escolhida para mostrar agora foi a do professor</p>
<p>Na imagem assim vemos a apresentação do dashboard ao usuário, cards com funcionalidades principais do tipo de usuário em específico, uma sidebar no canto esquerdo
mostrando mais funcionalidade, cada uma com seu ícone e no canto superior direito temos um ícone de calendário com o fundo azul, que tem o cronograma de hoje do usuário,
seja ele aluno, professor ou técnico e abaixo o ícone de robô que serve como o chatbot (pequeno suporte) para o sistema que foi feito utilizando o DialogFlow</p>
<img src="https://github.com/Gustavo-Henrique-da-Silva/SCGA/assets/108029506/1ac13067-5b21-45cf-915a-f4bc44dc840b"/>

## Perfil do usuário
<p>Seguindo a sequência das funcionades descritas no dashboard de cima para baixo, temos a tela de Perfil, com a opção do usuário alterar a imagem, email, nome e senha</p>
<img src="https://github.com/Gustavo-Henrique-da-Silva/SCGA/assets/108029506/04a12df9-2186-4838-be68-22432f5460c9"/>

## Calendário
<p>No ícone de calendário, temos um próprio para cada topologia/usuário, utilizando a API Fullcalendar do JS, em que o mesmo pode ir passando os e meses vendo os
agendamentos envolvendo sua topologia (Visualização pessoal) e também ver a geral de todos os outros usuários (Visualização Geral), com ambas as opções estando
no select abaixo do título da funcionalidade</p>
<img src="https://github.com/Gustavo-Henrique-da-Silva/SCGA/assets/108029506/f363cc00-4f43-4241-94a1-5d1589223868"/>

##  Agendamento e Cronograma 
<p>Aqui e na próxima funcionalidade após dessa temos uma pequena limitação para cada topologia de usuário, sendo que irei explicar as que englobam o agendamento: </p>
<p>O Agendamento é por onde apenas os Professores e Técnicos o acessam, por sua necessitade seja de agendar um horário para utilizar a sala para aula ou para
manuntenção dos dispositivos respectivamente, assim alguns dos dados pedidos para o agendamento do técnico não se relaciona totalmente com o do professor, como é o caso
Classe e Disciplina. Mais abaixo podemos ver os agendamentos que o usuário fez, que por sua está em anteriores para demonstra o estilo de cada lista da tabela, mas que
por padrão se inicia-se com os próximos agendamentos, podendo-o mudar pelo select acima da tabela e do subtitúlo</p>
<img src="https://github.com/Gustavo-Henrique-da-Silva/SCGA/assets/108029506/ffb0eee9-4775-444a-ba20-a37075ede2f9"/>

<p>No cronograma, local onde pode ser acessado pelo professor e técnico pelo link abaixo do título do agendamento, temos algo mais englobado, como no caso do calendário,
entretanto com o filtro visto (atual e anterior) no agendamento e com a adição de uma tabela para aulas (professor) e manuntenções (técnico)</p>
<img src="https://github.com/Gustavo-Henrique-da-Silva/SCGA/assets/108029506/b63b6bdb-8a6a-4154-986f-eeff35b751a6"/>

## Reporte de Problemas
<p> Como um auxiliar para o planejamento de agendamento e também para o Ambiente Organizacional da Unidade (enfoque principal do projeto), junto com o âmbito de agendamento também temos um pequeno sistema de reportar problemas nos ambientes de estudo (laboratórios e salas), com o objetivo principal de melhorar a comunicação geral do usuários
da ETEC caso ocorra alguma ocorrência de problemas nos computadores dos labs, mitigando possíveis dores de cabeça tanto para o professor quanto ao aluno</p>
<p>Ao meio, vemos uma lista dos reportes feitos por um usuário, que pode editá-las ou também acrescentar uma nova no canto inferior direito (símbolo +), ou caso queira
averiguar se o seu problema já foi reportado, filtrá-los pelo ícone de filtro no canto superior direito (lembrando que o técnico poderá ver esse reporte, e se caso for
resolvido, marcar a mesma como resolvido</p>
<img src="https://github.com/Gustavo-Henrique-da-Silva/SCGA/assets/108029506/20eb0a21-c140-438c-8c8b-109e12acef63"/>

## Mapeamento
<p>Em mapeamento, primeiro é possível ver o jogo de cores do tema escuro e segundo temos uma imagem do mapa da unidade, sendo uma outra alternativa para o usuário visualizá-lo sem precisar ficar descendo a barra na tela inicial do site. Logo após, temos a principal funcionalidade dela, que foi implementada por mim após o fim do TCC devido a falta de tempo: A Viabilização dos Ambientes (tornar mais palpável a visualização de cada ambiente de estudo e seus recursos no geral). </p>
<img src="https://github.com/Gustavo-Henrique-da-Silva/SCGA/assets/108029506/41418caa-5b48-4371-9b20-e8fcb6969d58"/>

<p>Nela os usuários podem visualizar os recursos de cada anexo, laboratório de informática ou sala (cadeiras, PCs, Apps, SO, etc) com a ajuda geral da comunidade de professores e técnicos para atualizar esses recursos assim que necessário</p>
<p>Além disso, a próxima possível atualização no sistema será envolvendo essa funcionalidade com o objetivo de inteligar a imagem da unidade com os ambientes na 
viabilização de recursos</p>
<img src="https://github.com/Gustavo-Henrique-da-Silva/SCGA/assets/108029506/f35ae5bb-574d-4f7f-8653-606784c2f1ba"/>

## Suporte (ChatBot)
<p> Por último mas não menos importante, temos a funcionalidade avulso de nosso ChatBot chamado IRIS, como um auxílio para o usuário iniciante no sistema para saber
o local de tal funcionalidade e derivados.</p>

<img src="https://github.com/Gustavo-Henrique-da-Silva/SCGA/assets/108029506/922314c0-858e-4622-947f-bc731833628d"/>

## Conclusão
<p>Finalizando, espero que tenham gostado desse pequeno tour do SCGA pelo README e também das funcionalidades, vejo vocês no próximo README!</p>

