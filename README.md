# Contexto e Objetivos
O assunto de interesse deste NotebookLM é o Path of Exile (PoE) 3.28, especificamente a expansão "Mirage" lançada em março de 2026. O material compõe um guia abrangente que cobre as mudanças sistêmicas, mecânicas de jogo, progressão de personagens e otimização econômica dentro deste novo meta.
# Curadoria de Fonte
1. https://poedb.tw/us/
1. https://poe.ninja/
1. https://www.craftofexile.com/
1. https://www.youtube.com/watch?v=x818XzRLMkg
1. https://www.youtube.com/watch?v=yv1amTJQvGA
1. https://www.youtube.com/watch?v=4NiqdH9QE2Y
1. https://www.youtube.com/watch?v=4jM7qbpwPyU
1. https://www.youtube.com/watch?v=6wKmmcMym2s
1. https://www.youtube.com/watch?v=ov_NCCkSjOg
1. https://www.youtube.com/watch?v=7BYFpZ1UbS0
1. https://www.youtube.com/watch?v=je2RCwbAt4I
1. https://www.youtube.com/watch?v=w2ijHbTWrxs
1. https://www.youtube.com/watch?v=PW1wH-u4-Ks
1. https://www.youtube.com/watch?v=TabbqG-OKig

Além disso utilizei as fontes vindas do prompt "Path of exile crafting and currency making guides" para chegar até o limite(50).

# Engenharia de Prompts e "Cicatrizes"
1. Esse NotebookLm foi feito somente para a liga "Mirage" de Path of Exile 1.
1. É necessário situar a IA quanto ao tempo que já estamos dentro da liga.
1. A IA não consegue ler sites para crafting ou checagem de preços, então ela fica "parada no tempo" dependendo das outras fontes.
1. Máximo de 50 fontes é pequeno.

# Miniguia

## Resumo estruturado de Crafting:
### Reestruturação da Hierarquia de Moedas

1. O Renascimento do Orbe Exaltado (Exalted Orb): Em 3.28, o Orbe Exaltado voltou a ser a principal moeda de meta-crafting.
    1. Custos de Bancada: Opções que antes custavam de 1 a 3 Exalts agora custam um flat de 4 Exalted Orbs.
        Receita de Vendedor: Vender um set completo de itens influenciados (como Shaper/Elder) não identificados agora recompensa o jogador com 2 Exalted Orbs, criando um "piso" de valor para esses itens.
1. Filtro de Itens: Com a abundância de Exalts, o caos (Chaos Orb) perdeu valor relativo, sendo usado principalmente para rolar modificadores de mapas e spam de itens básicos.

### Os Pilares do Crafting em 3.28

1. Monopólio de Fósseis no Delve: Uma das mudanças mais impactantes foi a remoção de fósseis de fontes externas (Heist, Ritual, Legion, Delirium). Agora, eles caem exclusivamente no Delve.
    1. Isso tornou o Delve profundo (500+) extremamente lucrativo, pois todos os crafters dependem dessa fonte.
1. O Motor de Recombinação (Recombinators): Retornaram como a ferramenta suprema para criar armas de elite.
    1. A estratégia envolve fundir bases de alta qualidade do Rog ou itens com modificadores Fractured Tier 1 para criar itens com múltiplos Tier 1 isolados.
1. Rog Crafting (Expedition): Como a nova Genesis Tree foca em armaduras e joias, mas não em armas, o Rog tornou-se o principal "impressor de armas" pDPS de alto nível no início da liga.

### Sistemas Determinísticos e Novas Tecnologias

1. Árvore de Gênese (Genesis Tree): Utiliza consumíveis de Breach (Wombgifts) para produzir equipamentos. O nó "Solid Cysts" é fundamental, pois permite criar bases com modificadores Fractured Tier 1 de forma determinística.
1. Imbuing de Gemas (Coins): Coletadas no Reino Astral (Mirage), as moedas de Conhecimento, Poder e Habilidade permitem imbuir gemas nível 20 com um suporte aleatório, corrompendo a gema no processo.
    1. Hitar suportes de elite como Multistrike pode valorizar uma gema em dezenas de Divines.
1. Refracting Fog (Cluster Jewels): Esta nova moeda permite trocar o encantamento de uma Cluster Jewel (ex: trocar Dano de Raio por Dano de Gelo) sem alterar os modificadores explícitos já existentes no item.

### Exemplos de Receitas Meta (High-End)

1. Wand de Kinetic Fusillade (KF):
    1. Obter base ilvl 83+ com Fracture T1 Lightning Damage.
    1. Spam de Essence of Woe (Spell Damage) até acertar T1/T2 de dano de Fogo ou Gelo.
    1. Limpar sufixos e usar Harvest "Add Critical" para T1 Crit Multi ou Chance.
    1. Finalizar com Multimod e Veiled Chaos Orb para penetração elemental.
1. Joias de RF: Foco em fraturar +2% de Resistência Máxima a Fogo e usar Harvest Reforge Fire para buscar multiplicador de dano e vida.

### Ferramentas Indispensáveis
Para navegar nesses sistemas complexos, os especialistas utilizam:

1. Craft of Exile: Para simular probabilidades e emular o uso de recombinadores/fósseis antes de gastar moedas reais.
1. PoEDB: Para verificar pesos de modificadores e níveis de itens (ilvl) necessários.
1. WealthyExile: Para monitorar o valor líquido de materiais de crafting acumulados.

## Resumo estruturado de *Currency Farming*
Na liga Path of Exile 3.28 Mirage, o sistema de *farming* foi profundamente alterado pela introdução da mecânica Mirage, pela reformulação do Atlas e pelo novo paradigma econômico que favorece orbes clássicos e especialização mecânica.

Abaixo está o resumo estruturado das melhores estratégias de geração de riqueza (*currency farming*):

### Estratégias de Elite (S-Tier)
Estas estratégias oferecem os maiores retornos por hora e definem o topo da economia atual:

1. Unstable Breach (Alto Investimento): Considerada o ápice do lucro bruto em mapas. Utiliza o Horned Scarab of Bloodlines para transformar monstros de Breach em milhares de monstros mágicos altamente lucrativos. É a melhor forma de buscar "jackpots" como Hinekora's Lock ou o Mirror of Kalandra.
1. Monopólio de Fósseis no Delve: Em 3.28, os fósseis caem exclusivamente na mina (Delve). Isso gerou um choque de oferta e preços recordes. Especialistas recomendam atingir profundidades de 500 ou mais para encontrar nós especiais como *Molten Cavity* (Faceted Fossils) e *Humid Fissure* (Fractured Fossils).
1. Cornucopia Harvest: Aproveita a mecânica Mirage para duplicar os jardins de Harvest, efetivamente dobrando o rendimento de *lifeforce* por mapa. O lucro é impulsionado pela demanda estável de *lifeforce* amarela e azul para o novo "Astrolabe flip" (transformar Astrolabes comuns em Breach Astrolabes).
1. Legion (Início da Liga): Permanece dominante no começo da liga devido à alta demanda por itens 6-link e joias atemporais (*Timeless Jewels*).
1. Inscribed Ultimatum: Oferece retornos consistentes em Divine Orbs e a chance de duplicar recompensas através da Mirage.

### Estratégias Consistentes e de Nicho (A-Tier)
1. Boss Rushing (Destructive Play): Foca em matar rapidamente o chefe do mapa para obter Gemas de Suporte Excepcionais (que substituíram as Awakened) e Maven Chisels.
1. Heist: Uma das fontes mais seguras de lucro, focando em contratos de Deception para revelações baratas de plantas, onde se buscam bases experimentais e moedas brutas.
1. Beast Farming: Estratégia rápida em mapas lineares como *Strand*, focada em capturar e duplicar (via scarabs) feras vermelhas valiosas como a Vivid Vulture e a Black Morrigan.
1. Stacked Deck Farming: Utiliza scarabs de *Cloister* e a mecânica de Ritual para gerar centenas de *Stacked Decks* por hora, que possuem alta liquidez no mercado.

### O Papel da Mecânica Mirage no Farming
A mecânica Mirage atua como um multiplicador de força (2x a 3x) sobre o investimento em mapas.
1. Desejos (Wishes): O "Wish for Abundance" concede 100% mais moedas dentro da Mirage, sendo a escolha padrão para estratégias de alto investimento.
1. Duplicação: Encontros de Harvest, Expedition e Legion dentro da Mirage herdam todos os scarabs e modificadores do mapa original.
1. Ouro: O desejo por ouro (*Golden Volatiles*) é essencial para sustentar os custos do mercado de trocas de Faustus e a manutenção de Kingsmarch.

### Mudanças Estruturais e Econômicas
1. Renascimento do Exalted Orb: O orbe exaltado voltou a ser a moeda principal para meta-crafting, com custos de bancada fixados em 4 Exalts. Itens influenciados agora são valiosos devido à receita de vendedor que recompensa com 1 ou 2 Exalted Orbs.
1. Astrolabes e Blobs: Substituíram os Sextantes, permitindo que regiões inteiras do Atlas sejam "moldadas" com bônus progressivos de recompensa.
1. Currency Exchange (Faustus): Reduziu a fricção na venda de moedas menores (*bubblegum currency*), permitindo liquidação instantânea de lucros acumulados.

### Cronograma de Farming Recomendado
1. Dias 1-3: Legion, Expedition (Rog Crafting) e Delve para fósseis básicos.
1. Semanas 1-2: Transição para Harvest, Ultimatum ou Boss Rushing.
1. Mês 1.5+: Alva Temple (Double Corrupt) atinge o pico de lucratividade.

## Glossário 

### Principais Estratégias de Currency (Farming)
A economia de 3.28 é definida pelo impacto da mecânica Mirage, que atua como um multiplicador de força ao duplicar encontros lucrativos dentro do Reino Astral.

1. Unstable Breach (S-Tier): Atualmente considerada o ápice do lucro bruto em mapas. Utiliza o Horned Scarab of Bloodlines para transformar monstros de Breach em pacotes mágicos massivos, gerando retornos altíssimos em moedas brutas, além de itens raros como Hinekora's Lock e Mirror of Kalandra.
1. O Monopólio de Fósseis no Delve (S-Tier): Em 3.28, os fósseis caem exclusivamente no Delve. Isso criou um choque de oferta, tornando o Delve profundo (profundidade 500+) extremamente lucrativo, com lucros projetados de 15 a 25 Divines por hora.
1. Cornucopia Harvest (S-Tier): Aproveita a capacidade da Mirage de duplicar os jardins de Harvest, dobrando o rendimento de Lifeforce por mapa. O preço da Lifeforce permanece estável devido à alta demanda por crafts de meta-resiliência e pelo novo "Astrolabe flip".
1. Boss Rushing e Gemas Excepcionais: Com a introdução da Originator Voidstone, chefes do Atlas podem dropar as novas Gemas de Suporte Excepcionais, que substituíram as gemas Despertas (Awakened), criando um mercado de alto valor para "boss-rushers".
1. Flipping e Arbitragem no Currency Exchange: O novo sistema de Faustus permite liquidez instantânea. Crafters lucram comprando Astrolabes comuns (como Templar ou Lightless) e usando Harvest para transformá-los em Breach Astrolabes (Grasping), que são essenciais para a estratégia de Unstable Breach.

### Conceitos Fundamentais de Crafting
O crafting em Mirage retornou às bases determinísticas, com foco em salvar itens falhos e criar equipamentos de elite para builds populares como Kinetic Fusillade.

1. Renascimento do Orbe Exaltado: O Exalted Orb voltou a ser a moeda principal de meta-crafting. Custos na bancada foram aumentados para 4 Exalts, e uma nova receita de vendedor de itens influenciados não identificados agora recompensa o jogador com 2 Exalted Orbs.
1. Recombinadores: Retornaram como a ferramenta suprema para armas de elite. A estratégia envolve fundir bases de alta qualidade do Rog ou itens com modificadores Tier 1 isolados para criar itens "triple T1".
1. Rog Crafting (Expedition): Como a nova Árvore de Gênese (Genesis Tree) foca em armaduras e joias, o Rog tornou-se a fonte essencial para produzir armas físicas (pDPS) de alto nível no início e meio da liga.
1. Árvore de Gênese (Genesis Tree): Permite a produção determinística de equipamentos através do consumo de Wombgifts. O nó "Solid Cysts" é obrigatório para crafters profissionais, pois permite criar bases com modificadores Fractured Tier 1, servindo de base para projetos complexos.
1. Imbuing de Gemas (Coins): Utiliza as novas Coins (Conhecimento, Poder, Habilidade) em gemas nível 20 para adicionar um suporte aleatório. Hitar um suporte de alto nível como Multistrike pode valorizar uma gema em dezenas de Divines, embora o processo corrompa a gema.
1. Otimização de Implícitos Eldritch: O uso de Orbs of Conflict para subir o tier de modificadores implícitos em itens não influenciados continua sendo o padrão ouro para maximizar o poder de luvas, botas, capacetes e peitorais.

### Infraestrutura e Ferramentas Necessárias
Para navegar nestes sistemas, o uso de ferramentas externas é mandatório:

1. Path of Building (PoB): Para planejar o escalonamento de dano real.
1. Craft of Exile: Essencial para simular probabilidades antes de gastar recursos caros como Orbes de Fratura ou Exalts.
1. WealthyExile: Para rastrear o valor líquido do baú e identificar itens de "bubblegum currency" que podem ser liquidados via Faustus.

## Prompts Reutilizáveis
Um conjunto de prompts reutilizáveis que possam apoiar futuras revisões sobre o tema.

1. Melhor currency farming para quem está entrando um mês dentro da liga.
1. Ranking de currency farms para harvest.
1. Como flipar Astrolabes?
1. Melhores currency farms para quem acabou de sair da campanha.
1. Qual a melhor build para Sanctum?
