#**Título: "Efeito das diferenças socioeconômicas sobre as notas do Enem na Paraíba"**
##**Objetivo geral:**
Avaliar o perfil socioeconômico dos Estudantes na Paraíba e seus efeitos sobre o desempenho no Exame Nacional de Ensino Médio

###**Objetivos Específicos:**
Avaliar a relação dos fatores abaixo com o desempenho no Enem:

tipo de escola (privada, particular)
tipo de dependência admnistrativa (Federal, Estadual, Municipal, Privada)
cor/raça
tipo de localização (Rural, Urbana)
escolaridade dos pais
tipo de ocupação dos pais
renda familiar
numero de pessoas na casa
acesso a celular, computador e internet

**Seleção dos Dados**
Os micro dados do ENEM pode ser baixaidos no site do INEP. O banco de dados 'Microdados do Enem' é muito grande, preciso selecionar previamente com quais variáveis desejo trabalhar, ou não consigo abri-lo.

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
