# Sobre o Projeto

Aplicação web que terá como finalidade o gerenciamento de dados, 
video chat, monitoramento online em tempo real, histórico de atividades, emissão de boletos e projetos realizados ao longo do ano da escola de educação infantil Recanto do Jardim. 
Este projeto terá código opensource e o objetivo será construir uma ferramenta completa e melhor que todas disponíveis no mercado e que todos os módulos da aplicação serão gratuitos apenas para escolas pública e que 50% da rentabilidade será destinado para abrir novas creches pelo Brasil com modelo de franquia.

As tecnologia aplicadas no projeto irão rodar na plataforma Node.js e o banco de dados com NoSQL MongoDB, ou seja, todo o código de back end será inscrito em javascript e no front end html/css/javascript. 

Para as operações de CRUD usarei o mongoose. O banco de dados será Model, tabela serão collections e linhas da tabelas serão documentos.
Em NoSQL documentos são objetos representados entre chaves:
 {  
	nome:”vagner” 
	, documentos: { 
		cpf:”999.99999.99”
		, rg:”8888,9888888” 
    } 
 }.

Como padrão de arquitetura vou seguir modelo MVC com framework express. Para o monitoramento online usarei a tecnologia de webrtc para vídeo chat. Para a camada de front end usarei o gulp como automatizador de tarefa executando e organizando o código scss e gerar um arquivo css compilado e minificado,
além de usar outras bibliotecas para auxiliar na construção do html, tais como jeet.js, compass etc.. o uso dessas bibliotecas é para organizar o código e criar componentes html além de melhorar performace do código de carregamento no browser e aumentar SEO do site.

***

 
# Problemas
 
- Atualmente todos os dados referente aos alunos estão salvos em planilhas salvas no computador, 
em agendas dos próprios alunos e folhas de oficio. A idéia inicial é melhorar essa gestão desses dados.

- Não queremos excluir o uso das agendas, mas as mesmas informaçõe das agendas devem estar
disponivel online de forma fácil e rápida em tempo real.

- Dados coletados devem ser atividades recreativas, o que o aluno se alimentou, e outras opçoes..(vou complementar),
podem haver vária anotações. Não sei se seperadas ou todas em um unico aviso. 

- Atualmente o comprovante dos pagamentos referente as mensalidade são através de promissórias,
precisamos automatizar isso e liberar um recurso que emita um boleto online, o mesmo pode ser gerado
pelos pais ou pelo gestor do site. 

- Os pais podem monitorar seus filhos em tempo real.

# Solução


 