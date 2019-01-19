#  Design
elementos obrigatórios
----------------------

- [ ] no mínimo 4 imagens

- [ ] texto de título (h1, h2, etc.)

- [ ] texto regular (parágrafo)

- [ ] uma logo.

HTML semântico
--------------

- Tags semânticas de HTML5 como
'''
<header>, <footer>, <article>, <section>
'''
etc. são utilizadas para adicionar significado ao código.

- Nenhuma tag <div> ou <section> deve estar sem uma classe ou id de CSS.

    Cheque a documentação da W3C em HTML Structural Elements para aprender mais!

Design customizado
------------------

Prover pelo menos as seguintes customizações:

- [ ] Customizar imagens e texto.
- [ ] Customizar o posicionamento dos elementos na página (layout de grade - grid layout) com HTML, CSS ou ambos.
- [ ] Customizar estilos CSS aplicados pelo menos em parágrafos e elementos de título (heading).

Layout baseado em grade
-----------------------

    A página utiliza um layout de grade com estilos que fazem uso de layout flexbox ou de um framework como Bootstrap, Foundation, etc.
    Se estiver utilizando Bootstrap ou HTML/CSS padrão: as linhas e colunas da grade devem estar contidas em um elemento com uma classe container.

#  Responsividade

Compatibilidade entre disposivitos
----------------------------------

Todo conteúdo é responsivo e disponível em todos os tamanhos de tela. Isto inclui:

    Desktop
    Mobile: Google Nexus 5
    Tablet: Apple iPad

Forneça todo o conteúdo
-----------------------

Todo conteúdo é renderizado em todos os três dispositivos. Nenhum conteúdo deve ser ocultado em dispositivos móveis.

Tag meta de janela de exibição
------------------------------

Tag meta de janela de exibição (viewport) está incluída no HTML (ou seja<meta name=”viewport” …).

Imagens responsivas
-------------------

Se um framework CSS é utilizado, classes fornecidas pelo framework são utilizadas para tornar as imagens responsivas. Caso contrário, um framework CSS não é utilizado, media-queries são utilizadas para garantir a responsividade das imagens.


#  Separação de conceitos

Estilos separados do HTML
-------------------------

O portfólio separa completamente a estrutura (HTML) do design/estilo (CSS). Não há atributos style presentes no corpo (body) do documento HTML. Não há elementos <style> no documento.

Observação: é aceitável incluir os atributos height e width em elementos <img>.

Estrutura dos arquivos
----------------------

Arquivos são organizados com uma estrutura de diretório que os separam com base na funcionalidade. Por exemplo:
css/ para stylesheet
img/ para imagens
js/ para arquivos JavaScript

#  Qualidade do código

Regras de formatação HTML
-------------------------


Todo código (nomes de elementos HTML, atributos, valores de atributo) está em letra minúscula (exceto text/CDATA).
Não há espaços em branco ao final (à direta) de cada linha do código (trailing whitespace) (p.ex. correto: <p>parágrafo</p>; incorreto: <p>parágrafo</p>).
Indentação é consistente (ou usando apenas tabs, ou apenas 2 espaços, ou apenas 4 espaços, etc.).
Código usa uma nova linha para cada bloco, lista ou elemento de tabela e indenta cada elemento filho (é aceitável colocar cada elemento <li> em uma linha).
[Opcional] Ao utilizar valores em atributos, o código usa aspas duplas.


Regras de estilo HTML
---------------------


    Documento HTML utiliza <!doctype html> de HTML5.
    O código passa na validação de HTML e CSS.
    [Opcional] Código não usa referencias de entidade, a menos que necessário, como caracteres com significado especial em HTML (p.ex. < e &) e caracteres de controle ou “invisíveis” (como no-break spaces).
    [Opcional] O código omite atributos type para folhas de estilo e scripts.

Regras de formatação de CSS
---------------------------


    O código não possui espaços em branco ao final (à direta) de cada linha do código (trailing whitespace) (p.ex. correto: "color: blue;"; incorreto: "color: blue; ".
    A indentação é consistente (ou usando apenas tabs, ou apenas 2 espaços, ou apenas 4 espaços, etc).
    O código indenta todo conteúdo de um bloco, que são regras dentro de regras, assim como declarações que refletem hierarquia e melhora o entendimento.
    O código usa ponto e vírgula depois de toda declaração por razões de consistência e extensibilidade.
    O código sempre utiliza um espaço após o dois pontos de um nome de propriedade, mas não há espaço entre a propriedade e o dois pontos, por razões de consistência.
    O código sempre utiliza um único espaço entre o último seletor e a chave de abertura que inicia a declaração de bloco.
    O código sempre começa com uma nova linha para cada seletor e declaração.
    O código sempre coloca uma linha em branco (duas quebra de linha) entre as regras.
    [Opcional] O código usa aspas duplas para atributos de seletores ou valores de propriedade. Não utilize aspas em valores de URI (url()).

Regras de estilo de CSS
-----------------------


    O código utiliza nomes de classe ou ID que são relevantes ou genéricos e que sejam os menores possíveis, mas tão longos quanto necessário.
    O código não utiliza nomes de elemento em conjunção com IDs ou classes.
    O código utiliza propriedades abreviadas (shorthand) assim que possível.
    [Opcional] O código omite a unidade de medida para valores 0.
    [Opcional] O código inclui 0s à esquerda em valores decimais para legibilidade.
    [Opcional] O código usa notação hexadecimal de 3 caracteres sempre que possível.
    [Opcional] O código separa palavras em nomes de classe e ID com um hífen.
    [Opcional] O código evita detecção de user agent assim como "hacks" de CSS— tente uma abordagem diferente primeiro.

Regras gerais de meta
---------------------

Templates e documentos HTML usa codificação UTF-8. (no BOM), ou seja, <meta charset="utf-8">.

    [Opcional] Marque todos* itens de ação com TODO
