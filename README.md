## Projeto Final module_StoryTelling

Projeto de estudo, avaliativo do modulo de StoryTelling.

Fiz o uso dos dados do censo escolar de 2021 para trazer insights utilizando graficos plotly e Power BI.

Aproveitando ao máximo o modulo, produzi conteudo para um jornal local, e uma tela PowerBI


## Referência

 - Dados utilizados no projeto >--  https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/censo-escolar
 
 - Dados modelo desenvolvido em PowerBi >-- https://drive.google.com/file/d/1BG1eVOER7MyxLJytmwBHRJOfpVvUzzKR/view?usp=sharing
 
 
## Documentação


1. Gerar os gráficos utilizando Python + Plotly (Google Colab).

2. Baixar a base de dados do Censo escolar 2021, necessária para a realização da
prática (esse material compactado já contém a base de dados em um arquivo
CSV e um dicionário de dados em um arquivo XLSX).
https://download.inep.gov.br/dados_abertos/microdados_censo_escolar_2021.zip

3. Os gráficos devem respeitar o template padrão “ggplot2”

4. O título do gráfico deve ser: “Censo Escolar 2021: Análise de Localização
Diferenciada (RS)”, centralizado, todo em negrito com tamanho de fonte 14.

5. O gráfico deve ser gerado com 600 pixels de altura e 1200 pixels de largura.

6. A legenda deve ser utilizada na orientação horizontal, centralizado e na parte
inferior do gráfico. Também deve apresentar o significado de cada dado,
conforme o dicionário de dados.

7. O título da legenda de ser alterado para: “Localização Diferenciada”, com
tamanho de fonte igual a 12.

8. Para escolas em área de assentamento, deve ser utilizada a cor “brown”.

9. Para escola em terra indígena, deve ser utilizada a cor “orange”.

10. Para escolas em áreas remanescentes de quilombo, deve ser utilizada a cor
“turquoise”.

11. Os títulos individuais dos subgráficos devem apresentar o significado de cada
tipo de localização, conforme o dicionário de dados.

12. O eixo com a quantidade de matrículas deve ser fixado entre 0 e 500. Deve
também receber o título: “Quantidade de Matrículas”, com fonte tamanho 11.

13. O eixo com a quantidade de docentes deve ser fixado entre 0 e 200. Deve
também receber o título: “Quantidade de Matrículas”, com fonte tamanho 11.

14. Os marcadores devem ter borda da cor preta e opacidade de 75%.

15. Marcadores devem ter seu tamanho máximo igual a 30.

16. No canto superior direito da imagem, deve ser inserida uma anotação com o
texto “Fonte: INEP”, com a cor “dark_gray” e fonte tamanho 12.

17. O visual deve ser exportado no formato HMTL com o nome:
“localizacao_diferenciada_rs.html”

Adicionalmente, incluo o material de outra atividade, na qual utilizei PowerBi e mais 3 gráficos que produzi para uso em um jornal local.

## Lendo os gráficos:

- Nos gráficos do jornal:

    O tamanho dos circulos é representado pela quantidade de alunos por professor;
    Cada circulo é uma escola, e o insight representa a comparação entre quantidade de alunos/ Docentes.
    São 3 cidades, cada uma possui um documento e um documento geral comparando as 3.

- No gráfico final de modulo:

    O tamanho dos circulos é representado pela quantidade de turmas por escola;
    Cada circulo é uma escola, e o insight representa a comparação entre quantidade de alunos/ Docentes,
    apresentando a diferença em locais de localização diferenciada em regiões rurais e urbanas

- No PowerBI:

    Cada circulo é uma escola do Rio Grande do Sul com quantidade de matriculas menor que 215;
    Demonstra a quantidade de matriculas masculinas e femininas,
    Sendo possivel filtrar por dependência administrativa(1 - Federal, 2 - Estadual, 3 - Municipal, 4 - Privada)
