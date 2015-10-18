# pregramacion_numeral-p5.1
los nimerales p 5.1 hasta 5.16 de la pagina 42 del documento 
%
%ejercicio p5.1 
%graficacion en mathlab
%usare subplot para hacer las graficaciones
L=-3:8;
subplot(2,2,1);
plot(L,'*')
title('PUNTO UNO')
hold on
subplot(2,2,2);
K=-9:2;
plot(K,'-K*')
axis('auto')
title('punto dos')
subplot(2,2,3);
O=linspace(-4.2,-10,6);
plot(O,'+r')
title('punto 3')
subplot(2,2,4)
U=linspace(3,3.33,100);
plot(U,'>y');
title('punto cuatro')
axis('tight')
