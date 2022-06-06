# Final-Project---Image-Processing
## This repository is reserved for the final project of the discipline SCC5830 - Image Processing and Analysis. 

Técnicas de inpainting, também conhecidas como estratégias de restauração de pinturas, obras de arte, ou ainda ilustrações visuais, tem sido aplicadas desde os tempos remotos, o que inclui a própria criação artística. No contexto de Processamento Digital de Imagens (PDI), o propósito da restauração é o de atuar em aplicações envolvendo partes danificadas [1], deterioradas [1, 2], ausentes [3], ou até mesmo de remoção de alvos [4] em uma imagem de modo que a mesma venha a se assemelhar à sua forma original, ou seja, o processo deverá preservar as características genuínas da imagem de modo a retratá-la da maneira mais fiel possível à percepção humana [3].
	Um dos primeiros processos de restauração foi apresentado por Bertalmio et all [1], onde a formulação original assume como entrada a imagem deteriorada I:Omega C R … (colocar a equação aqui) e uma máscara guia (aqui tmb), que discrimina as informações da região deteriorada da imagem I.
	Visando explorar esta linha de raciocínio, o projeto tem como proposta utilizar funções de base radial (colocar a fórmula aqui), tal que, possamos determinar os k pixels mais próximos do pixel alvo selecionado no processo de restauração, aplicando uma função interpoladora F(p) = I(p). Além do  conjunto de pontos existentes (pixels bons da imagem), iremos utilizar a derivada desses pontos (I’(p)) para deixar o método mais robusto, este cálculo não é uma tarefa difícil, afinal a derivada de um conjunto discreto nada mais é do que a taxa de variação no ponto
