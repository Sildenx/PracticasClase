# PracticasClase
estaturas <-c(1.2, 1.23, 1.19, 1.32, 1.28, 1.22, 1.17, 1.29, 1.33, 1.15)
# Nivel socioeconómico 110, 130, 108, 130, 108, 167, 156, 115, 104, 138, 170, 107
# QUEREMOS COMPROBAR LA HIPOTESIS QUE ENTRE MAYOR INGRESO DE LA FAMILIA HAY UNA MAYOY ESTATURA EN LOS NIÑOS 
neco <-c(110, 130, 108, 167, 156, 115, 104, 138, 170, 107)
plot(neco, estaturas, pch=11, xlab = "estatura", ylab = "ingreso economico ", main ="grafica de dispersion", col=18)

#a) obtener la grafica de  dispersion 
#b) Observara las  correlaciones 
#c)Para calcular el coeficiente de correlacion se utiliza 
cor()
# La forma general de cor() es...; Sus argumentos son : Variable dependiente, variable independiente 

#cor(x, y, use ="Todos los datos" puede ser el caso de datos perdidos, método )
 cor(estaturas, neco, method = "pearson")
 # una vez de que comprobamos que hay una buena relacion 
 #variables hay que confirmarla 
 # La prueba de hipotesis para esta funcion es Ho= r=0
 #es decir no hay relacion entre las variables, h!=0  si hay relacion 
 #misma logica de cor()
 cor.test(estaturas, neco, method = "pearson")
 
 #si el p-value es menor a .05 rechazamos Ho
 #por lo que existe relacion 
 
 
 #Ya que confirmamos la correlacion aplicamos el modelo 
 #Para aplicar el modelo se utiliza  la fucnion lm()
 mod1 <- lm(estaturas ~neco)
 summary(mod1)
 #los asteriscos indican que tan significativos son los datos del modelo 
 #Los residuales  nos generan las dieferencias en los valores ajustados y los reales 
 #en los resultados tenemos los coeficientes quen contienen 
 
 plot(neco,estaturas , pch=11, xlab = "estatura", ylab = "neco", main="grafica de dispersion")
 
 abline(mod1) #graficar la recta del mod1 en grafica de dispersion de las variables 
 
 
#con esto podriamos decir que tenemos una ecuacion 
 estaturas=.9323+.0023 eco 

 
