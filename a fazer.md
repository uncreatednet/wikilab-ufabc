# wikilab

Um laboratório experimental baseado no [wikihouse](http://wikihouse.cc/)

![](ideia%20b%C3%A1sica.jpg)

### Contatos

Ver da experiência desses caras e se/como pode rolar uma parceria

* Contatar Alastair Parvin - o fundador do wikihouse - http://wikihouse.cc/ - contatado 18.10.2016
* Contatar WikiHouseRio - http://wikihouserio.cc/ - contatado 18.10.2016
* Contatar Anderson França - trabalhou com o wikihouse Rio - http://www.andersonfranca.com/
* Ver contato do Alex Garcia na UFRJ que trabalhou no wikihouse
* Outros contatos na wikihouse foundation?
* Contatos com fab-labs?

### Construção

* Ver empresas ou lugares que podem cortar os painéis de madeira
* Ver possível pareceria com FabLabs? 
* Os [fab-labs livres de SP](http://fablablivresp.art.br/) que são indicados como "grande porte" tem uma máquina de tamanho suficiente para cortar os painéis de 1.20x2.40m do wikihouse
* Quem vai construir? Estudantes, empreiteiro, PPP? 
* Pode ser feito em compensado tanto quanto em OSB. OSB é melhor: mais sustentável, um pouco mais barato, e mais fácil de proteger contra fogo
* Diferentes estratégias de proteção contra fogo possíveis: impregnação com produto, revestimento com placas, etc
* A aprovação (universidade, prefeitura, bombeiros) vai ser difícil: O conceito é muito novo, vai ter alta desconfiança

### Projeto

* ~~Levantar um projeto básico do que precisa~~ feito - ver o que dá
* Conversar BEM com o pessoal sobre o aspecto experimental
* Definir estratégia de manutenção / plano "Marte"
* Ver esquema de segurança
* Accessibilidade
* Ventilação / aspecto sustentabilidade
* Ver estratégia de aprovação (instalação temporária?)
* Ver estratégia de fabricação
* Opções de material de revestimento
* Pesquisar proteção contra fogo
* Ver técnicas para portas e janelas
* Estimar cronograma / tempo de montagem / pessoal necessário

### Custos

* Estratégia de financiamento?
* 38.7m² no padrão popular (CUB = R$ 1300/m²) = R$ 50000
* 38.7m² = 35.3m² (wikihouse) + 3.4m² (caixa de alvenaria)
* Casa de 9 módulos = 225 painéis -> Casa de 7 módulos = 225 * 7/9 = 175 painéis
* 1 painel = +/- R$ 115 -> 175 painéis = R$ 20000
* Alternativa: 1 painel de OSB = */- R$ 100 - > 175 painéis = R$ 17500
* Precisa do custo de corte
* Custo da impregnação / proteção contra fogo
* Custo de fundação
* Custo do bloco de alvenaria completo (com instalações sanitárias)
* Custo do revestimento exterior = +/- 84m² (placas de polipropileno = R$ 41/m² x 84 = R$ 3500
* Custo conexões esgoto/água fria/eletricidade
* Pintura
* Custo portas e janelas -ver cálculo padrão abaixo
* Custo instalações elétricas
* Mobiliário?
* Custo maquete
* Custo transporte
* Custo projeto? Contribuição wikihouse
* Esquadrias: 28m² *x R$ 300/m² = R$ 8500

### FreeCAD & arquivos digitais

Ajustes a fazer no FreeCAD para poder trabalhar com wikihouse. Tudo feito já.
* ~~Ver melhor formato de transferência~~ Precisa de um processo complexo para passar do formato original (sketchup) para FreeCAD. 1) No sketchup, isolar um módulo 2) exportar para collada 3) importar no Blender 4) separar as diferentes camadas de elementes em layers 5) identificar e linkar os idênticos 6) deixar somente uma face por peça 7) limpar a triangulação 8) exportar para obj 8) importar para FreeCAD 9) usar macro em anexo para extrair wires 10) criar clones para as peças duplicadas
* ~~Tornar cada peça do modelo sketchup em um painel~~
* ~~Identificar painéis idênticos~~ Isto tem que ser feito na hora de importar o arquivo para o Blender. Deixar os dois (blender e sketchup) abertos ao lado, e ir identificando cada peça. Esta etapa é também importante para ter um bom entendimento da estrutura.
* ~~Extrair "marca"?~~
* ~~Gerar perfis no plano XY. Cada perfil é "filho" do painel? Ou contrário?~~
* ~~Perfil podia ser Path (verificar se interessante)~~
### Links

#### Wikihouse

* http://buildandrenovate.co.nz/wikihouse/
* http://www.wikihouserio.cc/
* http://www.archdaily.com.br/br/773676/casa-revista-a-primeira-casa-fabricada-digitalmente-no-brasil
* https://www.newcivilengineer.com/technical-excellence/structures-home-delivery/8670782.article
* http://buildandrenovate.co.nz/wikihouse/
* http://www.plataformaarquitectura.cl/cl/800684/wikihouse-presenta-la-primera-casa-de-codigo-abierto-de-dos-pisos-en-el-london-design-festival

#### Materiais

* http://www.smartply.com/products/fr-build-osb3

### Próximos passos

* ~~Ver terreno com Reitor~~
* Achar terreno
* Montar um projeto básico (3D, planta, corte)
* Verificar preços de corte
* Verificar preços da impregnação contra fogo
* Montar orçamento básico do resto (alvenaria, etc)

### Mobiliário necessário

**makerspace

* 1 mesa de montagem (para trabalho) 8 lugares
* 1 mesa ou bancada para 2 impressoras lasers (+/- 3 metros)
* 2 armários fechados
* 2 mesas para computadores (3 em cada 1)
* 1 espaço para almofadas e conversas
* se possível colocar estantes em uma das paredes

**Lablivre

* Uma mesa para 8 computadores
* 2 armários
* 2 hacks de servidores
* 1 mesa de reuniões 
* 1 espaço para projeção
* 1 mesa/bancada para impressoras
* estantes de livros (quto couber)
