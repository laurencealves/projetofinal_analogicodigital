# projetofinal_laurencealves

Especificações gerais: 

Conectar processing e arduino
Sketches do processing em exibiçao com a projeçao mapeada
Projeçao mapeada: tamanho A2 420x594mm
Sao cinco cartazes :
	- (1) ponto linha e plano
	- (2) figura e fundo
	- (3) modularidade
	- (4) textura
	- (5) cor


# Ponto, linha e plano (1)
	Sketch inicial esta dentro desse repositorio com o nome "ponto, linha e plano" 
	(O sketch pode estar meio confuso por ter algumas coisas que eu coloquei para testar e nao estao funcionando, mas estao descomentadas)
	
	O que o cartaz faz? 
		- O cartaz será todo impresso com a tinta condutiva
		- A pessoa vai tocar no cartaz e um ponto surgirá em uma localizaçao random no plano
		- A "animaçao" aparecera em projeçao mapeada
		- Se o desenho ficar inativo por mais de 45s, ele reinicia
		
# Figura e fundo (2) e Cor (5)
	Sao dois cartazes diferentes mas a interaçao é a mesma
	link do prototipo de F/F: https://invis.io/7FEEHPK9Q
	link do prototipo de Cor: https://invis.io/E9EEHQEPB
	
	link das imagens de F/F: https://drive.google.com/open?id=13Le_Kil61Z12PpU9dVFrZK9VsiFWcC1c
	link das imagens de Cor: https://drive.google.com/open?id=1mpefgzoILd2g_nyRTxKNHSmmLQLCMVkB
	
	O que o cartaz faz?
		- Quando a pessoa tocar nas bolas (2) ou nos triangulos (5) uma projeçao aparecera
		- F/F: 18 bolas 
		- Cor: 6 triangulos
		- Cada bola ou triangula é uma entrada analoga diferente no arduino
		- A imagem anterior some e a nova aparece
		- Imagens aparecem em projecao mapeada
		- Se o desenho ficar inativo por mais de 45s, ele reinicia
		
# Modularidade (3)
	link das imagens: https://drive.google.com/open?id=1BV7dye8uKApuB-g8MOTODVgjAQec262O
	link do prototipo: https://invis.io/QSEEHQ58C
	Precisa de um sensor de distancia OU usar a propria tinta como um capacitive touch se voce conseguir uma leitura mais exata 	Acho que vai precisar ser com sensor para a pessoa poder interagir com mais espaço e com o corpo todo, sem ser mt perto do cartaz (como seria com a mao, se fosse capacitive)
		
		O que o cartaz faz? 
		- Conforme a pessoa vai se aproximando do cartaz, o desenho vai ficando mais "cheio", abrindo a imagem subsequente
		- Se a pessoa se afasta, a imagem a a anterior volta a aparecer
		- Sao 6 imagens, ou seja, quebrar a divisao de valores em 6 pedaços
		- Imagens aparecem em projecao mapeada
		- Se o desenho ficar inativo por mais de 45s, ele reinicia
		
