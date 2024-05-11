
**projeto**
# Genealog-IA

**título do projeto**
# A história de sua família contada pela Inteligência Artificial

			Nesse dia em que comemoramos o dia das mães, você sabe dizer quem era a mãe da mãe de sua mãe ?
			Como era o nome de solteira dela?
			A genealogia pode te ajudar a resgatar essa história das mulheres de sua família!!

### DESCRIÇÃO DO PROJETO

Uma área de interesse deste projeto é a genealogia. A genealogia já utiliza hoje diversos recursos da inteligência artificial como pesquisa de registros históricos, análise de dados e comparação de testes de DNA de ancestralidade, recuperação de fotos antigas, transcrição de documentos manuscritos, etc.
Um projeto de IA para contar a história familiar tem o potencial de transformar a forma como as pessoas pesquisam, organizam e compartilham suas histórias familiares. 
A IA pode ajudar a preservar a história familiar para as gerações futuras ao oferecer ferramentas poderosas para superar os desafios da pesquisa genealógica tradicional, democratizando o acesso à história familiar e permitindo descobertas mais rápidas.
A pergunta que esse pequeno projeto quer responder é: - Será que a Inteligência Artificial pode ajudar a escrever a história de sua família? A IA pode criar uma história mais atrativa e criativa que possa despertar o interesse dos jovens para a importância de se preservar a memória familiar? 

### BASE DE DADOS UTILZADA

Esse projeto utiliza uma pequena parte de minha árvore genealógica e somente registros de pessoas que já faleceram e cujos registros já estão disponíveis para consultas na base de documentos do FamilySearch ( www.familysearch.com ). Os dados foram extraídos no formato padrão da genealogia - Gedcom (.ged). Depois foram convertidos para formato de planilha Excel. 

### ESTRUTURA DE DADOS DA PLANILHA

ID | NOME_COMPLETO	| SEXO	| DATA_DE_NASCIMENTO | LUGAR_DE_NASCIMENTO |  DATA_DE_FALECIMENTO | LUGAR_DE_FALECIMENTO | CEMITERIO | NOME_DO_CONJUGE |  DATA_DO_CASAMENTO | LOCAL_DO_CASAMENTO | NOME_DO_PAI | NOME_DA_MAE | ANOTACOES

### EXECUÇÃO

Uma entrada do usuário escolhe a pessoa ancestral da árvore genealógica. A partir dessa entrada, os dados são carregados e vão compor o prompt que vai inferir a engenharia do Google Gemini.
O resultado do prompt gera um arquivo formato txt contendo até 5 parágrafos gerados pelo Google Gemini com uma breve história da pessoa da árvore genealógica. O nome do arquivo gerado é o nome da pessoa.

### DESENVOLVIMENTOS FUTUROS

Versões futuras desse projeto deverá ler e manipular diretamente o arquivo no formato Gedcom (.ged) da árvore genealógica.
Também para geração das respostas do modelo Gemini, testes deverão ser feitos utilizando os conceitos de embeddings.
