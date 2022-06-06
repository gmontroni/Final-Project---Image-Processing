# Final-Project---Image-Processing
## This repository is reserved for the final project of the discipline SCC5830 - Image Processing and Analysis.
### Hermite RBF Interpolation Digital Inpainting
\
	Inpainting techniques, also known as restoration strategies for paintings, artworks or visual illustrations, have been applied since ancient times, including artistic creation itself. In the context of Digital Image Processing (DIP), the purpose of restoration is to work on applications involving damaged, deteriorated, missing, or even removal of targets in an image so that it resembles its original form, i.e., the process must preserve the genuine characteristics of the image in order to portray it as accurately as possible to human perception.\
\
	One of the first restoration processes was presented by Bertalmio et al, where the original formulation in order to recover an image (a) assumes as input the (b) deteriorated image $I:Ω → ℝ, Ω ⊂ ℝ²$, (c) a guide mask $𝐃 ⊂ Ω$, that discriminates the information from the deteriorated region of the image $I$.\
  \
	To explore this line of reasoning, the project proposes to use Radial Basis Functions $\phi_i(p)$, such that, we can determine the $\it{k}$ pixels closest to the selected target pixel in the restoration process by applying an interpolating function that satisfies $F(p) = I(p)$. Furthermore, given a set of existing points (good pixels of the image), we will use the derivative of these points $I’(p)$ n the interpolation process, called  $\textbf{Hermite Interpolation}$, obtaining a more robust method. This calculation is not a difficult task, after all the derivative of a discrete set is nothing more than the rate of change at the point.

<p align="center">
	<img align="center" width="700" height="250" src="https://user-images.githubusercontent.com/96217617/172216241-21a8ba08-3453-4e95-97ac-2b882565967a.png">
</p>
