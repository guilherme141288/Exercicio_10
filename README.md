# Exercicio_10

#currency corversion, values need updates


real = float (input ('quantos reais voce tem?:  '))
dollar = float (real * 0.18)
libra = float (real * 0.13)
euro = float (real * 0.15)
print ('com R${:.2f} reais voce pode comprar U${:.2f} dollars, {:.2f} libras e EU{:.2f} euros ' .format (real , dollar , libra , euro))
