**TÍTULO: "ENEM NA PARAÍBA DE 1998 A 2019"**


Autora: Maria Marcolina Lima Cardoso

Versão 1.0 de 07/07/2021
\
\
**INTRODUÇÃO**
 
 
 
 

**OBJETIVO GERAL:**


   Analisar o desempenho dos estudantes da Paraíba entre os anos de 1998 a 2019, relacionar com o perfil sócio-econômico e desenvolver um arquivo de acesso fácil para gestores com o consolidado das notas e do perfil do alunado por Município e Escola.
   

**Objetivos Específicos:**
  
  \
   - Descrever o perfil dos inscritos no Enem (Sexo, Raça, Tipo de Escola, e aspectos socioecômicos, como renda, número de pessoas na casa, bens tecnológicos).
   - Descrever o perfil dos faltantes
   - Descrever as médias gerais e por componentes curriculares (Linguagens, Ciências Humanas, Ciências da Natureza, Matemática e Redação).
   - Relacionar as Médias as variaveis de perfil sócio-econômico.
   - Tentar predizer os aspectos mais importantes para a melhoria das notas.
 
 

**SELEÇÃO E CRIAÇÃO DOS BANCOS DE DADOS UTILIZADOS**


  Para este projeto, nós baixamos os microdados do Enem fornecidos pelo site do [INEP](https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados).
Os dados são referentes as edições de 1998 à 2019. O microdado de cada ano contém a planilha em .csv com os dados e uma planilha com os dicionários das variáveis.
					
  Após baixarmos, nós seguimos os seguintes passos:
					
  *1) Separação dos dados referentes a Paraíba, contido no notebook abaixo:*
     [ProjetoICD_Separacao_dados_PB.ipynb](https://github.com/mariaeco/Projeto_ICD_UFPB_EnemPB/blob/main/ProjetoICD_Separacao_dados_PB.ipynb)
										
  *2) Seleção e renomeação e organização de variáveis, limpeza e definição dos tipos das variáveis, e junção dos dados em um único arquivo:*
     [ProjetoICD_Limpeza_e_Organizacao_Dados.ipynb](https://github.com/mariaeco/Projeto_ICD_UFPB_EnemPB/blob/main/ProjetoICD_Limpeza_e_Organizacao_Dados.ipynb)
	
   Algumas organizações e limpezas relazidas: Os dados das esdições do Enem estão com nomes, tipos e níveis de variáveis despadronizados, valores digitados errado, como nomes de Escola e Município, notas também despadronizadas (alguns anos a nota vai de 0 a 100, em outros de 0 a 1000). Muitos anos constam nota 0 para alunos faltantes, portanto, mudamos para NaN, uma vez que a presença de zeros baixa a média geral das notas.
	
   Dois produtos finais são gerados a partir deste notebook:
   
   i) o banco de dados geral da Paraíba de 1998 a 2019 (Banco de dados grande, e não possível de carregar no github pela conta Free):
     	[ENEM_PB_1998_2019.csv](https://drive.google.com/file/d/1ZV0He8T_cFMidQScQvrVtRBT_70uPnFa/view?usp=sharing)
	
   ii) o banco de dados com a média dos fatores por escola de 1998 a 2019 (Mais leve e utilizado para nossas análises nos demais notebooks):
        [ENEM_POR_ESCOLA_PB_1998-2019.zip](https://github.com/mariaeco/Projeto_ICD_UFPB_EnemPB/blob/main/DADOS/ENEM_POR_ESCOLA_PB_1998-2019.zip)
		
   iii) Utilizamos também o banco de dados da média geral por escola, fornecido pelo INEP, para acessar os Nomes e Códigos corretos das Escolas e Municípios, pois muitos dos  dados estão erroneamente digitados pelos participantes.
       [ENEM_2019_POR_ESCOLA_PB.csv](https://raw.githubusercontent.com/mariaeco/Projeto_ICD_UFPB_EnemPB/main/DADOS/ENEM_2019_POR_ESCOLA_PB.csv)
    
    
**EXPLORAÇÕES DOS DADOS**




