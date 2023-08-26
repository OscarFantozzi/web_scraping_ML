# Web Scraping de Preços de Celulares - Magalu
Este projeto utiliza a biblioteca Selenium em Python para buscar informações de preços de celulares na loja online Magazine Luiza (Magalu). 
O objetivo é coletar nomes de celulares, preços originais e preços com desconto, e salvar essas informações em um arquivo Excel.

Como Funciona
O projeto usa um "robô" (um script) para navegar pela página da loja Magalu.

O robô encontra e coleta os nomes e preços dos celulares.

Os preços são organizados em preços originais e preços com desconto.

As informações são colocadas em uma lista.

Como Usar

Instale o Python (se já não tiver) e instale as bibliotecas necessárias:

Copy code

pip install selenium pandas

Certifique-se de ter o ChromeDriver instalado e disponível no seu computador.

Baixe o arquivo "web_scraping_magalu.py".

Abra o arquivo usando um editor de texto.

Mude o número de páginas (se necessário).

No terminal, vá até a pasta onde está o arquivo e digite:

Copy code

python web_scraping_magalu.py

Verifique o arquivo "celulares_magalu.xlsx" para ver os resultados.

Lembre-se de que este projeto é apenas para aprendizado e não deve ser usado de forma prejudicial ou contrária aos termos do site.

