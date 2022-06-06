# Final-Project---Image-Processing
## This repository is reserved for the final project of the discipline SCC5830 - Image Processing and Analysis.
\
	Técnicas de inpainting, também conhecidas como estratégias de restauração de pinturas, obras de arte, ou ainda ilustrações visuais, tem sido aplicadas desde os tempos remotos, o que inclui a própria criação artística. No contexto de Processamento Digital de Imagens (PDI), o propósito da restauração é o de atuar em aplicações envolvendo partes danificadas, deterioradas, ausentes, ou até mesmo de remoção de alvos em uma imagem de modo que a mesma venha a se assemelhar à sua forma original, ou seja, o processo deverá preservar as características genuínas da imagem de modo a retratá-la da maneira mais fiel possível à percepção humana.\
\
	Um dos primeiros processos de restauração foi apresentado por Bertalmio et all, onde a formulação original assume como entrada a imagem deteriorada $I:Ω → ℝ, Ω ⊂ ℝ²$ e, uma máscara guia $𝐃 ⊂ Ω$, que discrimina as informações da região deteriorada da imagem $I$.\
  \
	Visando explorar esta linha de raciocínio, o projeto tem como proposta utilizar funções de base radial $\phi_i(p)$, tal que, possamos determinar os $\it{k}$ pixels mais próximos do pixel alvo selecionado no processo de restauração, aplicando uma função interpoladora que satisfaça $F(p) = I(p)$. Além disso, dado o conjunto de pontos existentes (pixels bons da imagem), utilizaremos a derivada desses pontos $I’(p)$ no processo de interpolação, denominada $\textbf{Interpolação de Hermite}$, obtendo um método mais robusto. Este cálculo não é uma tarefa difícil, afinal a derivada de um conjunto discreto nada mais é do que a taxa de variação no ponto.

	
