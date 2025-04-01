# apuntes-corte-2-dinamica-de-sistemas
apuntes corte 2 dinamica de sistemas

Felipe Cruz Pineda, Angie Vargas- M6A
# Clase recuperación del parcial (Transformada de Laplace)
💡**Ejemplo 1:** 

$X”+4X=5   X(0)=5  X’(0)=0$

$S^2X(S)-SX(0)-X’(0)+4(SX(S)-X’(0))=5/S$

$S^2X(S)+4X(S)-5S=5/S$

$X(S)(S^2+4)=(5/S+5S)$

$X(S)=(5/S+5S)/(S^2+4)=(5/S)/(S^2+4)+5S/(S^2+4)$

$PARTE 1 → L⁻¹{(5/S)/(S^2+4)}$

$5/S(S^2+4) =A/S+(BS+C)/(S^2+4)$

$5=A(S^2+4)+(BS+C)S$

$5=AS^2+A4+BS^2+CS$

$S^2→B+A=0→B=-A$

$S→C=0$

$n→5=4A→A=5/4$

$B=-5/4$

$(5/4)L⁻¹{1/s}-(5/4)L⁻¹{S/(s^2+4)}$

$PARTE 1 RESPUESTA →5/4-5/4cos(2t)$

$PARTE 2 → 5 L⁻¹{(5/S)/(S^2+4)}$

$5L^(-1) {S/(S^2+4)}=5*(5/4)cos⁡(2t)=(25/4)cos⁡(2t)$

$SUMA PARTE 1 Y 2→  (25/4)cos⁡(2t)$

$SUMA PARTE 1 Y 2→5/4-(5/4)cos(2t)+(25/4)cos⁡(2t)$

$5/4+(15/4)cos(2t)$

💡**Ejemplo 2:** 

$F(S)=5(S+2)/(S^2*(S^2-4S+8)$

$F(S)=5(S+2)/(S^2*(S^2-4S+8)=A/S+B/S^2 +(CS+D)/((S-2)^2+4)$

$B=5(S+2)/(S^2*(S^2-4S+8) )→S=0$

$B=10/8=5/4$

$DERIVADA DEL COCIENTE →dx/dy=((u^' (x)*v(x)-u(x)*v^' (x)))/(v(x))^2$

$A=((5(S^2-4S+8)-5(S+2)(2S-4)))/(S^2-4S+8)^2 →S=0$

$A=(40+40)/64=10/8=5/4$

$Cuadrática para CS+D → x=(-b±√(b^2-4ac))/2a$

$x=(-4±√(4^2-4*8*1))/(2*1)=(-4±√(16-32))/2$

$x=(-4±√(-16))/2=(-4±4i)/2=-2±2i$

$CS+D=5(S+2)/S^2 →S=2+2i$

$2C+2Ci+D=5(2+2i+2)/(2+2i)^2$

$2C+2Ci+D=5(4+2i)/(2+2i)^2$

$2C+2Ci+D=(20+10i)/8i$

$2C+2Ci+D=(20+10i)/8i*((-8i)/(-8i))$

$2C+2Ci+D=(80+160i)/64$

$2C+2Ci+D=(5/4)-5/2i$

$Real → 2C+D=5/4$

$Imaginario → 2C=-5/2→C=-5/4$

$Remplazamos → 2(-5/4)+D=5/4$

$D=5/4+10/4=15/4$

$A=5/4, B=5/4, C=-5/4, D=15/4$

$5/4 L^(-1) {1/S}+(5/4) L^(-1) {1/S^2 }+ (5/4) L^(-1) {S/((S-2)^2+4)}+15/4 L^(-1) {1/((S-2)^2+4)}$

$S-2→S→e^(-at)=e^2t$

$5/4+5t/4+e^2t*((-5/4) L⁻¹{S/(S+4)}+(15/4) L^(-1) {1/(S+4)})→w=2$

$5/4+5t/4-5/4 e^2t*cos(2t)+(15/4)*(e^2t*cos(2t))/2$

$5/4+5t/4-5/4 e^2t*cos(2t)+(15/8)*e^2t*cos(2t)$


























