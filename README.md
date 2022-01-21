# Desafio-scrapy
O webscraping nada mais é do que fornecer informações da web de forma automática, neste caso usando Python.
#Passos do projeto
Em


Abrir uma pasta do projeto desejado
Criar um ambiente Virtual no Python
Instalaros módulos e bibliotecas
Abrir um projeto no Pycharm, ou ambiente de sua preferência
Buscar as informações no URL 
criar o códico com especificações desejada

#automação web

from scrapyd.import.webdrive
navegador = webdrive.chrome
navegador.get (URL)
navegador.find_element_by_xpath

//seleciona o xpath no codigo do site, caso queira direcionar a automação para uma solicitação/janela específica.

[cola o url do xpath - do local desejado]

// buscar processo pelo 'N do processo' ou 'N do legado'


ou



class ImdbSpider(scrapy.Spider):
    name = 'trf5'
    start_urls = ['http..]

    def parse(self, response):

for busca processos =
numero_processo =['']
(caso não haja conteúdo, este campo deve ser preenchido com o numero_legado) ;
numero_legado= 
numero_cnpj=
{
'numero_processo'
'numero_legado'
'numero_cnpj'
'data_atuação'
'assunto_do_processo'
'list_nome_envolvidos]
'papel_do_envolvido'
'nome_do_envolvido'
'nome_relator'
'movimentações'
'data_da_movimentação'
'testo_da_movimentação"

Em vermelho, o numero_processo [string] (caso não haja conteúdo, este campo deve ser preenchido com o numero_legado) ;
Em verde, o numero_legado [string];
Em azul, a data_autuacao [datetime.datetime];
Em ciano, os envolvidos [list of dict]:
À esquerda, o papel [string] do envolvido;
À direita, o nome [string] do envolvido;
Em rosa, o relator [string] (apenas o nome é necessário)
Em cinza, as movimentacoes [list of dict]:
Em cima, a data [datetime.datetime] da movimentação;
Embaixo, o texto [string] da movimentação.



            }

Em
