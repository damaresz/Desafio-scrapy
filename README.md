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

# Descrição do projeto

• Criar uma automação de buscas de certidões dentro do "site específico"
• Abusca poderar ser feita pelo n° processo, n° do legado ou n° do CNPJ.
• Com as certidões devidamente verificadas, sera coletado dados específicos.
• Com os dados coletados sera gerado, planilha, tabela e gráfico.
• Caso necessário implementar projeto de falha de segurança.
• Dentro do planejamento original tem 3 opção de automação.

# automaçãoweb
# Exemplo 1

from scrapyd.import.webdrive
navegador = webdrive.chrome
navegador.get (URL........)
navegador.find_element_by_xpath

//seleciona o xpath no codigo do site, caso queira direcionar a automação para uma solicitação/janela específica.

[cola o url do xpath - do local desejado]

// buscar processo pelo 'N do processo' ou 'N do legado'


ou
/
/
/

# Exemplo 2


•lmport Pandas
•Import Bokeh
•Import Pytil
•Import Poetry
•Import Pyautogui

class ImdbSpider(scrapy.Spider):
    name = 'trf5'
    start_urls = ['http..]

    def parse(self, response):
    
    // O programa devera fazer busca de certidões em site específico, e colher informações descritas nas certidões, formando indices, listas, graficos e tabelas com os dados fornecidos.

for busca processos =
numero_processo = 
numero do cnpj =
//Os dados são fornecidos anteriormente ou já automatizados.

(caso não haja conteúdo, este campo deve ser preenchido com o numero_legado ou CNPJ) ;
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
'textoo_da_movimentação"

# Exemplo 3

import pyautogui
import time

pyautogui.alert("O código vai começar. Não utilize nada do computador até o código finalizar!")
pyautogui.PAUSE = 2

# Abrir o Google Drive no computador
pyautogui.press('winleft')
pyautogui.write('Chrome')
pyautogui.press('enter')
#time.sleep(2)
pyautogui.write('https://.....')
pyautogui.press('enter')

# Entrar na área de trabalho
pyautogui.hotkey('winleft','d')


/////////caso arquivo////////
# Clicar no arquivo e arrastar
pyautogui.moveTo(567,38)
pyautogui.mouseDown()
pyautogui.moveTo(756,635)
////////caso arquivo////////



# Enquanto estiver arrastando mudar para a página do Google Drive
pyautogui.hotkey('alt','tab')

# Soltar o arquivo dentro do Google Drive
pyautogui.mouseUp()

# Esperar alguns segundos
time.sleep(5)

pyautogui.alert("O código foi finalizado. Você já pode utilizar o computador!")

///////caso texto//////////
# Digita o numero ou texto
pyautogui.write(0000.456.999...)
//////caso texto//////////

# Fazer a busca do documentos ou arquivo
pyautogui.press('enter')

# Baixar o arquivo


# Arquivar na pasta 


# Copia os dados do n° do processo, legado, CNPJ e outros.

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
