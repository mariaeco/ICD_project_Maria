**Título: "Enem na Paraíba de 1998 a 2019"**

Autora: Maria Marcolina Lima Cardoso



**Introdução**

  **Objetivo geral:**

        Analisar o desempenho dos estudantes da Paraíba entre os anos de 1998 a 2019, relacionar com o perfil sócio-econômico e desenvolver um arquivo de acesso fácil    para gestores com o consolidado das notas e do perfil do alunado por Município e Escola.


    **Objetivos Específicos:**
      - Descrever o perfil dos inscritos no Enem (Sexo, Raça, Tipo de Escola, e aspectos socioecômicos, como renda, número de pessoas na casa, bens tecnológicos).
      - Descrever o perfil dos faltantes
      - Descrever as médias gerais e por componentes curriculares (Linguagens, Ciências Humanas, Ciências da Natureza, Matemática e Redação).
      - Relacionar as Médias as variaveis de perfil sócio-econômico.
      - Tentar predizer os aspectos mais importantes para a melhoria das notas.


**Seleção dos Dados**

Os micro dados do ENEM pode ser baixado no site do [INEP](https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados). O banco de dados 'Microdados do Enem' é muito grande, preciso selecionar previamente com quais variáveis desejo trabalhar, ou não consigo abri-lo.

Para selecionar as variáveis previamente, consultei os nomes das colunas, importando o banco de dados e usando o argumento nrows=0, e consultando a pasta Dicionário, no arquivo Dicionário_Microdados_Enem_2019.xlsx no meu github para entender melhor o significado de cada variável.

O Banco de Dados selecionado, os dicionários e demais arquivos necessários são encontrados no meu git hub.

Abaixo seleciono as variáveis que vou trabalhar e importo o banco de dados do meu Drive. Ao selecionar, fiz o download apenas do banco de dados e salvei no meu GitHub para outros terem acesso.

*Variáveis Selecionadas:*

Ano no Enem:'NU_ANO'

Número de Inscrição:'NU_INSCRICAO'

Código do Município de Residência: 'CO_MUNICIPIO_RESIDENCIA'

Nome do Município de Residência:'NO_MUNICIPIO_RESIDENCIA'

UF de Residência: 'SG_UF_RESIDENCIA'

Tipo de Escola: 'TP_ESCOLA'

Codigo do Municipio da Escola: 'CO_MUNICIPIO_ESC'

Código da Escola: 'CO_ESCOLA'

Tipo de Dependência Escolar:'TP_DEPENDENCIA_ADM_ESC'

Tipo de Localização Escolar: 'TP_LOCALIZACAO_ESC'

Raça: 'TP_COR_RACA'

Notas no Enem:'NU_NOTA_CN', 'NU_NOTA_CH', 'NU_NOTA_MT', 'NU_NOTA_REDACAO', 'NU_NOTA_LC', 'TP_LINGUA'

Nível de Formação dos pais: 'Q001', 'Q002'

Tipo de Ocupação dos pais; 'Q003', 'Q004'

Renda Familiar: 'Q005'

Número de pessoas na casa:'Q006'

Acesso a tecnologias (Celular, Computador, Internet):'Q023', 'Q024', 'Q025'
