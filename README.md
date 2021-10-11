# TCC I Engenharia de Software

Software incliudo em https://matrizgamer.com/ em JavaScript VueJS e PHP Laravel.
https://github.com/pwviptbl/Matriz-Gamer


<p>&nbsp;</p>

<p><strong>Marcio Antonio Silva Alves Junior </strong></p>

<p>&nbsp;</p>

<p><strong>Software Desktop para campeonatos e-sports de categoria battle boyale. </strong></p>

<p>&nbsp;</p>

<p>Rio de Janeiro - RJ 08/2021</p>

<p>&nbsp;</p>

<p><strong>1. INTRODU&Ccedil;&Atilde;O</strong></p>

<p>O n&uacute;mero de est&uacute;dios de desenvolvimento de games vem crescendo muito no Brasil e deve crescer em torno de 5,3% at&eacute; 2022, conforme resultado apresentado pela 19&ordf; Pesquisa Global de Entretenimento e M&iacute;dia (PricewaterhouseCoopers, 2018), nos dois &uacute;ltimos anos foram criados quase dois mil jogos eletr&ocirc;nicos, o crescimento impulsiona uma cadeia de produ&ccedil;&atilde;o e necessidades no setor .</p>

<p>Seguindo a linha de racioc&iacute;nio o numero de streaming de games, especificamente dos torneios de e-sports desse segmento n&atilde;o para de crescer. Mais que isso, com a pandemia de covid-19 que trouxe mudan&ccedil;as na rotina de todos ocorreu um salto gigantesco nesse mercado, portanto a necessidade de ferramentas para auxiliar o setor de games tamb&eacute;m foi crescendo, uma dessas necessidades s&atilde;o ferramentas automatizadas para torneios de e-sports.</p>

<p>A falta de ferramentas automatizadas para torneios tem sido um problema para seus organizadores de torneios sejam eles de grande ou m&eacute;dio mas em especial os de pequeno porte.</p>

<p>Tendo como a melhor solu&ccedil;&atilde;o adotada atualmente o uso de planilhas eletr&ocirc;nica como do excel ou outros softwares para registrar e calcular os resultados dos torneios, dessa forma surge outro problema, a necessidade em programar as planilhas, p&ocirc;s &eacute; necess&aacute;rio o conhecimento especifico para criar f&oacute;rmulas que fa&ccedil;am men&ccedil;&atilde;o ao conte&uacute;do de c&eacute;lulas que contem as informa&ccedil;&otilde;es de entrada, como por exemplo a formula =(SOMA(A1:A4)) onde o resultado deve ser a soma das c&eacute;lulas de A1 a A4, com o sistema o usu&aacute;rio somente fornecera as entradas ligada as equipes e o sistema fara os caculos.</p>

<p>&nbsp;</p>

<p><strong>1.1 Objetivos </strong></p>

<p><strong>1.1.1 Objetivos Gerais</strong></p>

<p>Desenvolver uma Aplica&ccedil;&atilde;o Desktop onde os organizadores poder&atilde;o cadastrar seus torneios, equipes e partidas para que o software calcule e exiba os resultados.</p>

<p><em><strong>1.1.2 Objetivos Espec&iacute;ficos</strong></em></p>

<ul>
	<li>
	<p><em>An&aacute;lise da documenta&ccedil;&atilde;o de requisitos, identificar as caracter&iacute;sticas essenciais para desenvolver a estrutura do software;</em></p>
	</li>
	<li>
	<p>Definir escopo do sistema;</p>
	</li>
	<li>
	<p>Modelar o sistema usando <em>UML(Unified Modeling Language)</em>;</p>
	</li>
	<li>
	<p><em>Aplicar as t&eacute;cnicas e linguagens de programa&ccedil;&atilde;o Java;</em></p>
	</li>
	<li>
	<p><em>Aplicar Testes, verifica&ccedil;&atilde;o do comportamento e funcionalidades;</em></p>
	</li>
</ul>

<p><strong>1.2 Justificativa</strong></p>

<p>Diante disso, o software proporcionara a facilidade, otimiza&ccedil;&atilde;o do tempo, e um designer interativo para os usu&aacute;rios criarem seus torneios com suas configura&ccedil;&otilde;es especificas, cadastrar todas as partidas e com base nesses dados o software fara os c&aacute;lculos e apresentara o resultado final podendo ser exportado.</p>

<p>&nbsp;</p>

<p><strong>2. ESPECIFICA&Ccedil;&Otilde;ES INICIAIS DO SOFTWARE</strong></p>

<p>Este Cap&iacute;tulo apresenta os conceitos necess&aacute;rios para o bom entendimento e desenvolvimento deste trabalho.</p>

<p>&nbsp;</p>

<p><strong>2.1 Escopo do Produto</strong></p>

<p>O documento descreve as principais funcionalidades do Software, que tem o objetivo de arquivar e calcular competi&ccedil;&otilde;es de e-sports da categoria battle boyale. Sendo Compilada em Java com compatibilidade com sistemas operacionais Windows, Linux ou Mac.</p>

<p>,</p>

<p><strong>2.2 P&uacute;blico-Alvo</strong></p>

<p>Este Software te como publico alvo Organizadores de Competi&ccedil;&otilde;es e <em>influencers</em> digitais.</p>

<p>&nbsp;</p>

<p><strong>2.3 Defini&ccedil;&otilde;es, Acr&ocirc;nimos e Abrevia&ccedil;&otilde;es</strong></p>

<p><br />
&nbsp;</p>

<table cellspacing="0" style="border-collapse:collapse; width:604px">
	<tbody>
		<tr>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:293px">
			<p><strong>Termo </strong></p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:293px">
			<p><strong>Descri&ccedil;&atilde;o</strong></p>
			</td>
		</tr>
		<tr>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:293px">
			<p>Battle Royale</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:293px">
			<p>&Eacute; um g&ecirc;nero de jogo eletr&ocirc;nico que mistura elementos de explora&ccedil;&atilde;o, sobreviv&ecirc;ncia, e procura de equipamentos e de armas, encontrados em um jogo de sobreviv&ecirc;ncia com a jogabilidade encontrada em um jogo de &uacute;ltimo sobrevivente.</p>
			</td>
		</tr>
		<tr>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:293px">
			<p>C&eacute;lula</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:293px">
			<p>Uma c&eacute;lula &eacute; o cruzamento de uma coluna com uma linha. A fun&ccedil;&atilde;o de uma c&eacute;lula &eacute; armazenar informa&ccedil;&otilde;es que podem ser um texto, um n&uacute;mero ou uma f&oacute;rmula que fa&ccedil;a men&ccedil;&atilde;o ao conte&uacute;do de outras c&eacute;lulas. Cada c&eacute;lula &eacute; identificada por um endere&ccedil;o que &eacute; composto pela letra da coluna e pelo n&uacute;mero da linha.</p>
			</td>
		</tr>
		<tr>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:293px">
			<p>Requisitos funcionais</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:293px">
			<p>Requisitos de software que comp&otilde;e o sistema, descrevendo a&ccedil;&otilde;es que o sistema dever&aacute; executar quando solicitado.</p>
			</td>
		</tr>
		<tr>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:293px">
			<p>Requisitos n&atilde;o funcionais</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:293px">
			<p>Requisitos de software que comp&otilde;em o sistema, descrevendo atributos de qualidade que o sistema deve possuir, ou restri&ccedil;&otilde;es que ele deve satisfazer.</p>
			</td>
		</tr>
		<tr>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:293px">
			<p>UML(<em>Unified Modeling Language</em>)</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:293px">
			<p>Linguagem de Modelagem Unificada &eacute; uma linguagem-padr&atilde;o para a elabora&ccedil;&atilde;o da estrutura de projetos de software.</p>
			</td>
		</tr>
		<tr>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:293px">
			<p>Bytecodes</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:293px">
			<p>Bytecode e o c&oacute;digo escrito na linguagem Java compilado para ser interpretado pelas M&aacute;quinas Virtuais Java (JVMs).</p>
			</td>
		</tr>
	</tbody>
</table>

<p><br />
&nbsp;</p>

<p><strong>2.4 Conven&ccedil;&otilde;es </strong></p>

<p>&nbsp;</p>

<p>Por conven&ccedil;&atilde;o, os requisitos aqui especificados estar&atilde;o associados &agrave; um identificador &uacute;nico. O identificador &eacute; composto de uma sigla a respeito da classifica&ccedil;&atilde;o do requisito (RF = Requisito Funcional e RNF = Requisito N&atilde;o-Funcional) .</p>

<p>&nbsp;</p>

<p><strong>2.5 Perspectiva do Produto </strong></p>

<p>A internet tem exigido cada vez mais o apoio de ferramentas para c&aacute;lculos matem&aacute;ticos de diversos tipos e finalidades, em especial as ferramentas para calcular competi&ccedil;&otilde;es de e-sports na categoria battle boyale. Os usu&aacute;rios t&ecirc;m desenvolvido suas pr&oacute;prias solu&ccedil;&otilde;es usando planilhas eletr&ocirc;nicas. No entanto, as necessidades do conhecimento para programar as planilhas acabam dificultando, assim se mostrando pouco ineficientes e trabalhosas.</p>

<p>A proposta &eacute; trazer um software intuitivo onde o Usu&aacute;rio n&atilde;o precise se preocupar em programar c&eacute;lulas para efetuar c&aacute;lculos facilitando e agilizando seu trabalho.</p>

<p>&nbsp;</p>

<p><strong>2.6 Funcionalidade do Produto</strong></p>

<p>A lista abaixo apresenta os RF:</p>

<ul>
	<li>
	<p>Cria&ccedil;&atilde;o de torneios;</p>
	</li>
	<li>
	<p>Altera&ccedil;&atilde;o da pontua&ccedil;&atilde;o;</p>
	</li>
	<li>
	<p>Listar de torneios;</p>
	</li>
	<li>
	<p>Alterar torneios;</p>
	</li>
	<li>
	<p>Excluir torneios;</p>
	</li>
	<li>
	<p>Adicionar equipes do torneio;</p>
	</li>
	<li>
	<p>Listar de equipes do torneio;</p>
	</li>
	<li>
	<p>Alterar equipes do torneio;</p>
	</li>
	<li>
	<p>Excluir equipes do torneio;</p>
	</li>
	<li>
	<p>Criar grupos;</p>
	</li>
	<li>
	<p>Listar de grupos;</p>
	</li>
	<li>
	<p>Alterar grupo;</p>
	</li>
	<li>
	<p>Excluir grupo;</p>
	</li>
	<li>
	<p>Adicionar as equipes do torneio no grupo;</p>
	</li>
	<li>
	<p>Listar de equipes do grupo;</p>
	</li>
	<li>
	<p>Excluir equipes do grupo;</p>
	</li>
	<li>
	<p>Adicione partidas;</p>
	</li>
	<li>
	<p>Listar de partidas;</p>
	</li>
	<li>
	<p>Excluir partidas;</p>
	</li>
	<li>
	<p>Efetuar calculo das partidas;</p>
	</li>
	<li>
	<p>Exibir Resultados;</p>
	</li>
	<li>
	<p>Exportar Resultado em PDF;</p>
	</li>
</ul>

<p>A lista abaixo apresenta os RNF:</p>

<ul>
	<li>
	<p>Usar Banco de dados SQLite</p>
	</li>
	<li>
	<p>O sistema deve permitir facilidades de uso, tendo uma interface gr&aacute;fica clara, intuitiva e responsiva;</p>
	</li>
	<li>
	<p>As consultas realizadas ao sistema n&atilde;o podem ultrapassar o limite m&aacute;ximo de tempo de 10 segundos;</p>
	</li>
	<li>
	<p>As mensagens de erro do sistema dever&atilde;o ser claras e objetivas;</p>
	</li>
	<li>
	<p>Confirma&ccedil;&atilde;o de Opera&ccedil;&atilde;o;</p>
	</li>
	<li>
	<p>Verificar entrada de dados;</p>
	</li>
</ul>

<p>&nbsp;</p>

<p>&nbsp;</p>

<p><strong>2.7 Modelagem de Requisitos Funcionais (Caso de Uso)</strong></p>

<p>&nbsp;</p>

<p>&nbsp;</p>

<p>&nbsp;</p>

<p><strong>2.8 Usu&aacute;rios </strong></p>

<p>O Software tem como p&uacute;blico-alvo, Organizadores de Competi&ccedil;&otilde;es e influencers digitais.</p>

<p>&nbsp;</p>

<p><strong>2.9 Ambiente Operacional</strong></p>

<p>O Software &eacute; um software <em>Desktop </em>desenvolvido para a plataforma <em>Java Standard Edition </em>(JSE), dispon&iacute;vel para qualquer Sistema Operacional desde que possua a <em>Java Virtual Machine </em>(JVM) instalada, sendo o Java vers&atilde;o 8 ou superior.</p>

<p>&nbsp;</p>

<p><strong>2.10 Restri&ccedil;&otilde;es de Projeto e Implementa&ccedil;&atilde;o</strong></p>

<p>O Software sera desenvolvido utilizando a linguagem de programa&ccedil;&atilde;o Java, sendo portanto multiplataforma. Os requisitos m&iacute;nimos s&atilde;o: Mem&oacute;ria RAM de 1GB e espa&ccedil;o livre de 30MB no disco r&iacute;gido.</p>

<p>&nbsp;</p>

<p><strong>2.11 Suposi&ccedil;&otilde;es e Depend&ecirc;ncias </strong></p>

<p>O ambiente necessita da <em>Java Virtual Machine </em>(JVM) para execu&ccedil;&atilde;o.</p>

<p>&nbsp;</p>

<p><strong>3. METODOLOGIA</strong></p>

<p>Este cap&iacute;tulo apresenta as metodologias utilizadas para atingir o resultado final.</p>

<p><strong>3.1 M&eacute;todos</strong></p>

<p><strong>3.1.1 Metodologia de desenvolvimento XP</strong></p>

<p>Para o desenvolvimento do sistema ser&aacute; adotada &agrave; metodologia XP (Extreme Programming &ndash; Programa&ccedil;&atilde;o Extrema) Programa&ccedil;&atilde;o extrema &eacute; uma metodologia &aacute;gil, para desenvolvimento de software, voltada para pequenas e m&eacute;dias equipes onde os requisitos s&atilde;o vagos e mudam frequentemente, tem como principais tarefas a codifica&ccedil;&atilde;o e testes com &ecirc;nfase menor nos processos formais de desenvolvimento (WILDT, LACERDA, 2014).</p>

<p>A estrat&eacute;gia se base&aacute; no constante acompanhamento, executando testes, e a implementa&ccedil;&atilde;o de pequenos ajustes no decorrer do desenvolvimento.</p>

<p>A metodologia XP pode ser dividida em quatro atividades:</p>

<table cellspacing="0" style="border-collapse:collapse; width:605px">
	<tbody>
		<tr>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:287px">
			<p><strong>Atividade</strong></p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:287px">
			<p><strong>Artefatos resultantes</strong></p>
			</td>
		</tr>
		<tr>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:287px">
			<p>Planejamento</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:287px">
			<p>Levantamento de requisitos funcionais e n&atilde;o-funcionais, planejamento de teste de aceita&ccedil;&atilde;o, escolha de Stakeholders, planejando assim uma solu&ccedil;&atilde;o que facilite os documentos tanto pelas pessoas que os criam (Analistas) como para as que os l&ecirc;em (Programadores, Testadores).</p>
			</td>
		</tr>
		<tr>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:287px">
			<p>Projeto</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:287px">
			<p>Elabora&ccedil;&atilde;o e confec&ccedil;&atilde;o dos diagrama de caso de uso, diagrama de classes e diagrama de atividades, utilizando a linguagem UML<em>(</em><em>Unified Modeling Language</em><em>)</em><em> </em>para modelagem .</p>
			</td>
		</tr>
		<tr>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:287px">
			<p>Codifica&ccedil;&atilde;o</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:287px">
			<p>Para esta atividade usaremos a ferramenta Eclipse, ferramenta interface de desenvolvimento dispon&iacute;vel no pr&oacute;prio site da Eclipse. (ECLIPSE_DOWNLOAD, 2021) e o JDK 8 para Compila&ccedil;&atilde;o para <em>Bytecodes</em>.</p>
			</td>
		</tr>
		<tr>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:287px">
			<p>Testes</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:287px">
			<p>Para esta atividade utilizamos o framework open-source Junit &nbsp;para a constru&ccedil;&atilde;o de testes automatizados em<strong>&nbsp; </strong><strong>Java.</strong></p>
			</td>
		</tr>
	</tbody>
</table>

<p><br />
&nbsp;</p>

<p><strong>3.2 CRONOGRAMA</strong></p>

<table cellspacing="0" style="border-collapse:collapse; width:605px">
	<tbody>
		<tr>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:291px">
			<p><strong>ATIVIDADES</strong></p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:12px">
			<p><strong>Jan</strong></p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:11px">
			<p><strong>Fev</strong></p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:9px">
			<p><strong>Mar</strong></p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:9px">
			<p><strong>Abr</strong></p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:11px">
			<p><strong>Mai</strong></p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:15px">
			<p><strong>Jun</strong></p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:10px">
			<p><strong>Jul</strong></p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:12px">
			<p><strong>Ago</strong></p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:12px">
			<p><strong>Set</strong></p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:11px">
			<p><strong>Out</strong></p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:11px">
			<p><strong>Nov</strong></p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:7px">
			<p><strong>Dez</strong></p>
			</td>
		</tr>
		<tr>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:291px">
			<p><em>An&aacute;lise de requisitos</em></p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:12px">
			<p>X</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:11px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:9px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:9px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:11px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:15px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:10px">
			<p>X</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:12px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:12px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:11px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:11px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:7px">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:291px">
			<p>Definir escopo do sistema</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:12px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:11px">
			<p>X</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:9px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:9px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:11px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:15px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:10px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:12px">
			<p>X</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:12px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:11px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:11px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:7px">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:291px">
			<p>Modelar o sistema usando UML</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:12px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:11px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:9px">
			<p>X</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:9px">
			<p>X</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:11px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:15px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:10px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:12px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:12px">
			<p>X</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:11px">
			<p>X</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:11px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:7px">
			<p>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:291px">
			<p><em>Aplicar linguagens de programa&ccedil;&atilde;o Java</em></p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:12px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:11px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:9px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:9px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:11px">
			<p>X</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:15px">
			<p>X</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:10px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:12px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:12px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:11px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:11px">
			<p>X</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:7px">
			<p>X</p>
			</td>
		</tr>
		<tr>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:291px">
			<p><em>Aplicar os Testes</em></p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:12px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:11px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:9px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:9px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:11px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:15px">
			<p>X</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:10px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:12px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:12px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:11px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:11px">
			<p>&nbsp;</p>
			</td>
			<td style="border-bottom:1px solid #000000; border-left:1px solid #000000; border-right:1px solid #000000; border-top:1px solid #000000; width:7px">
			<p>X</p>
			</td>
		</tr>
	</tbody>
</table>
<p><strong>REFER&Ecirc;NCIAS</strong></p>

<p>19&ordf; Pesquisa Global de Entretenimento e M&iacute;dia, da <strong>PricewaterhouseCoopers (PwC)</strong>. Dispon&iacute;vel em: &lt;<a href="https://www.pwc.com.br/pt/outlook-18.html">https://www.pwc.com.br/pt/outlook-18.html</a>&gt;.</p>

<p>&nbsp;</p>

<p>WILDT, Daniel de Freitas; LACERDA, Guilherme Silva de. <strong>Conhecendo o eXtreme Programming (XP)</strong>.Dispon&iacute;vel em: &lt;<a href="https://pt.slideshare.net/dwildt/conhecendo-o-extreme-programming">https://pt.slideshare.net/dwildt/conhecendo-o-extreme-programming</a>&gt; Acesso em: 01 Ago. 2014.</p>

<p>&nbsp;</p>

