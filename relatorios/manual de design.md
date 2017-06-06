# Manual de design do wikilab

![](https://github.com/uncreatednet/wikilab-ufabc/raw/master/render/0016.jpg)

Este manual foi/está sendo escrito no correr do desenvolvimento do projeto [Wikilab](https://github.com/uncreatednet/wikilab-ufabc) por Yorik, arquiteto do [Uncreated](http://www.uncreated.net) e um dos desenvolvedores do projeto.

O conteúdo deste manual é sob licença Creative Commons, e pode ser copiado, distribuído, usado e modificado livremente por quem quiser. Ele é construído a partir da nossa própria experiência, e a partir do [manual de design do módulo "Wren" do WikiHouse](https://github.com/wikihouseproject/Wren/wiki/Wren-Technical-Design-Guide).

#### Atenção

Não esqueça, este manual apenas reflete a nossa experiência no desenvolvimento do WikiLab, e não deve ser considerado como algo oficial, ou como uma garantia qualquer. Se você planeja construir um WikiHouse, procure sempre o conselho de algum profissional da construção (engenheiro, arquiteto ou afim). O custo disso é pequeno quando se trata apenas de aconselhar, e a construção de uma estrutura onde pessoas vão permanecer é algo sério, que pode ter consequências graves. O lugar e as condições onde você vai construir podem requerer medidas que não estão neste manual. 

Contate um engenheiro ou arquiteto, combine um preço para o conselho, e inclua este custo no orçamento desde o início, e nem vai doer ;)

## O WikiHouse

Segundo a [Wikipedia](https://en.wikipedia.org/wiki/WikiHouse): O [WikiHouse](http://www.wikihouse.cc) é um sistema [aberto](https://pt.wikipedia.org/wiki/Hardware_livre) para construir casas. Ele foi pensado para democratizar e simplificar a construção de habitações sustentáveis e que necessitem poucos recursos. O projeto foi concebido em 2011 no Reino Unido, por Alastair Parvin (Aconselho muito assistir a [palestra dele no TED](w.ted.com/talks/alastair_parvin_architecture_for_the_people_by_the_people) (tem legendas em português disponíveis clicando no botão "subtitles"), Nick Ierodiaconou, Tav of Espians, James Arthur e Steve Fisher.

![](https://github.com/uncreatednet/wikilab-ufabc/raw/master/render/0025.jpg)

O sistema permite que pessoas baixem arquivos com [licenças abertas](https://pt.wikipedia.org/wiki/Creative_Commons) da internet, modifiquem se quiser esses arquivos com programas de modelagem 3D como [SketchUp](http://www.sketchup.com) ou [FreeCAD](http://www.freecadweb.org), e a partir daí criem, como uma [máquina CNC](https://pt.wikipedia.org/wiki/Comando_num%C3%A9rico_computadorizado), peças de madeira encaixáveis como em um quebra-cabeça gigante. Essas peça são montadas sem prego nem cola, com técnicas inspiradas das construções de madeira tradicionais asiáticas. Uma WikiHouse pode ser construída em um dia só, por pessoas que nunca trabalharam com construção antes.

![](https://github.com/uncreatednet/wikilab-ufabc/raw/master/fotos/constru%C3%A7%C3%A3o%20da%20primeira%20costela/IMG_20170530_114645.jpg)

![](https://github.com/uncreatednet/wikilab-ufabc/raw/master/fotos/constru%C3%A7%C3%A3o%20da%20primeira%20costela/IMG_20170530_124422.jpg)

Essa construção de madeira ainda deve ser protegida da chuva e da umidade, e equipada com instalações elétricas e hidráulicas, para poder ser usada por pessoas.

## Planejar o projeto

Essa etapa é muito importante, um bom planejamento faz toda a diferença entre um projeto bem executado, que fica dentro do custo estabelecido, e que dá pouca ou nenhuma dor de cabeça, e um projeto caro e cheio de complicações. 

#### É para mim?

O sistema WikiHouse não fornece uma habitação mais barata que uma construção tradicional de tijolos e cimento. O preço é bem similar, em torno de R$ 1200 por m² de piso. No entanto, se trata de um sistema extremamente fácil de montar, onde você está no controle total da construção. Em vez de comprar um produto (supostamente) acabado de uma empresa, você mesmo planeja, decide, construí, e modifica depois quando quiser.

Com grandes poderes vem grandes responsabilidades, e a construção de um WikiHouse requere um trabalho consequente, e, sendo experimental (tem poucas unidades construídas no mundo ainda), um acompanhamento sério após a construção. No entanto, esse trabalho todo é muito interessante, instrutivo e em muitos momentos muito divertido.

#### Encontrar uma máquina CNC

Um ponto merce um pouco de atenção antes de começar: Uma WikiHouse é feita de painéis de madeira (geralmente [compensado](https://pt.wikipedia.org/wiki/Madeira_compensada) ou [OSB](https://pt.wikipedia.org/wiki/Oriented_Strand_Board)), cortados por uma [máquina CNC](https://pt.wikipedia.org/wiki/Comando_num%C3%A9rico_computadorizado) (também chamada "Fresadora" ou "Roteador"). A possibilidade de construir depende da disponibilidade desse tipo de máquina, razoavelmente perto da obra para não gerar custos de transporte elevados.

Cada vez mais, hoje em dia, empresas aparecem em cidades de médio ou grande porte, que possuem esse tipo de máquina. Grupos como associações de makers, [hackers](https://pt.wikipedia.org/wiki/Hackerspace), ou [fab-labs](https://pt.wikipedia.org/wiki/Fab_lab) também são cada vez mais equipados com máquinas CNC. Finalmente, existem máquinas que podem ser [compradas na internet](https://www.buildyourcnc.com/blackFoot48v40.aspx) e montadas pelo usuário, que já podem ser encontradas na faixa dos R$ 10 000, o que torna isso uma solução possível para grupos e associações. Essas máquinas não tem a mesma precisão que uma máquina profissional, e requerem bastante dedicação para ser usadas, mas já foram usadas muitas vezes pelo mundo afora para produzir peças para WikiHouses.

O que se deve procurar é: uma máquina CNC que tenha o tamanho suficiente para cortar painéis de madeira de 18mm de espessura, de 1.20m x 2.40m (tamanho padrão desses painéis no Brasil).

O custo pedido por uma empresa ou associação para cortar todas as peças de uma WikiHouse pode variar muito, é sempre bom começar essa pesquisa cedo. Veja abaixo a seção "Montar o orçamento" para mais detalhes sobre o custo do corte.

#### Apoio técnico

Como já explicado acima, é importante ter o apoio de alguém que tenha bons conhecimentos e experiência na área da construção, como um arquiteto, engenheiro ou outra pessoa que tenha bastante experiência com construção, e que possa orientar, aconselhar, e evitar problemas e consequências que podem ser graves. Se trata apenas de pagar algumas horas de trabalho para que essa pessoa possa aconselhar você e vir dar uma olhada na construção. No preço total da construção, vai ser um gasto bem pequeno para ter uma segurança boa.

#### Legislação

A legislação no Brasil, como na maior parte do mundo, não permite que você construa uma estrutura onde pessoas vão permanecer sem autorização prévia. A ideia disso é garantir que todo mundo more em condições minimamente salúbrias. Para obter essa autorização, que geralmente é concedida pela secretaria de obras da sua prefeitura, deve ser feita uma demanda de autorização de construir (o nome dessa demanda, e do documento que você recebe que dá a autorização, pode variar de uma prefeitura para outra). Essa demanda geralmente incluí o preenchimento de alguns formulários, e a entrega de desenhos (plantas, vistas das fachadas, etc) do projeto, que vão permitir aos funcionários da prefeitura julgar se o projeto atende a todas as leis necessárias. Cada prefeitura tem suas próprias regras que dizem quais desenhos ela vai exigir.

![](https://github.com/uncreatednet/wikilab-ufabc/raw/master/render/0038.jpg)

A lei mais importante que um projeto de construção deve respeitar, é o código de obras do município. Esse código geralmente define todas as caraterísticas de salubridade, solidez e respeito aos demais usuários da cidade que uma construção nova deve ter. O terreno onde você planeja construir também pode ter leis municipais ou estaduais como plano diretor ou lei de uso e ocupação do solo, que podem obrigar ou proibir certos aspectos. Mas podem existir outras leis municipais, estaduais ou até federais que se aplicam também ao seu projeto. A secretaria de obras do seu município, ou seu arquiteto ou engenheiro se você já chamou algum, poderá dizer quais leis se aplicam no seu caso. 

A partir de um certo tamanho, a prefeitura vai também exigir que os desenhos estejam assinados por um profissional (arquiteto ou engenheiro) registrado.

Cada prefeitura terá também um prazo próprio para a entrega da autorização, e pode pedir mudanças no projeto se julgar que algum aspecto no se enquadra em alguma lei. É bom planejar toda essa parte com bastante antecedência.

Não se esqueça também que o WikiHouse é um sistema experimental, com poucas unidades construídas no mundo ainda, e que pode por isso assustar os funcionários da prefeitura. É sempre uma boa ideia, quando se trata de um projeto experimental, ir conversando com os funcionários da secretaria antes de fazer o pedido, explicar o projeto, mostrar outros exemplos (como este WikiLab), e "preparar o terreno".

#### O lugar

#### O orçamento

#### O programa

#### As opçoes técnicas

## Software

## Obter os arquivos

## Adaptar os arquivos

## Montar o orçamento

## Obter os recursos

## Preparar o corte

## Planejar a obra

## A obra

## O pós-obra

## A manutenção
