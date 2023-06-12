## Selección de materiales para minimizar la distorsión térmica en dispositivos de presición[^1]

La precisión de un dispositivo de medición, como un medidor de desplazamiento submicrométrico, está limitada por su rigidez y por el cambio dimensional provocado por los gradientes de temperatura. Es posible compensar la desviación elástica y realizar correcciones para hacer frente a la dilatación térmica, siempre que el dispositivo esté a una temperatura uniforme. Los gradientes térmicos son el verdadero problema: provocan un cambio de forma, es decir, una deformación del dispositivo, que no se puede compensar. La sensibilidad a las vibraciones también es un problema: la excitación natural introduce ruido y, por tanto, imprecisión en la medición. Por tanto es permisible que se produzca una expansión al realizar diseño de instrumentos de precisión, siempre que no se produzca distorsión (Chetwynd, 1987). Se permite la deflexión elástica siempre que las frecuencias naturales de vibración sean altas.

Entonces, ¿cuáles son los materiales adecuados para los dispositivos de precisión? La tabla 6.29 enumera los requisitos.

<div align="center">
  <sup>
      Tabla 6.29: Requisitos de diseño de los dispositivos de precisión
  </sup>
</div>

| Criterios | Descripción |
| ------------- | ------------- |
| Función  | Bucle de fuerza (marco) para dispositivo de precisión  |
| Restricciones  | Debe tolerar el flujo de calor - Debe tolerar las vibraciones  |
| Objetivo  | Maximizar la precisión posicional (minimizar la distorsión)  |
| Variables libres  | *Selección del material* |

<div align="center">
  <br><img src=https://github.com/darckoala/Demo-repo/blob/main/CasosEstudio/DistorsionTermica/Imagenes/Figura%20629.JPG width=40%"></br>
</div>

<div align="center">
  <sub>
      Figura 6.29: Esquema de un dispositivo de medición de precisión. Entre los dispositivos superprecisos son el microscopio de fuerza atómica y el microscopio de barrido en túnel.
  </sub>
</div>

### El modelo

La figura 6.29 muestra, esquemáticamente, un dispositivo de este tipo: consta de un bucle de fuerza, un actuador y un sensor. Nuestro objetivo es elegir un material para el bucle de fuerza. En general, soportará fuentes de calor: los dedos del operario del dispositivo de la figura o, más habitualmente, componentes eléctricos que generan calor. El índice de material pertinente se obtiene considerando el caso simple de un flujo de calor unidimensional a través de una varilla aislada excepto en sus extremos, uno de los cuales está a temperatura ambiente y el otro conectado a la fuente de calor. En el estado estacionario la ley de Fourier es

  $\ q=-\lambda \frac{dT}{dx} $
    
donde q es el aporte de calor por unidad de superficie, λ es la conductividad térmica y dT/dx es el gradiente de temperatura resultante. La deformación se relaciona con la temperatura mediante
    
  $\ \epsilon = \alpha (T_{0}-T) $
    
donde α es la conductividad térmica y T<sub>0</sub> es la temperatura ambiente. La distorsión es proporcional al gradiente de la deformación:

  $\ \frac{d\epsilon }{dx} = \frac{\alpha dT}{dx} = \frac{\alpha }{\lambda }q $
    
Así, para una geometría y un flujo de calor dados, la distorsión dε/dx se minimiza mediante seleccionando materiales con valores elevados del índice

  $\ M_{1} = \frac{\lambda }{\alpha } $  
    
El otro problema son las vibraciones. La sensibilidad a la excitación externa minimiza haciendo que las frecuencias naturales del dispositivo sean lo más altas posible. Las vibraciones de flexión tienen las frecuencias más bajas; son proporcionales a    
    
  $\ M_{2} = \frac{E^{2}}{\rho } $
    
Un valor alto de este índice minimizará el problema. Por último, el dispositivo no debe costar demasiado.    

### La selección
    
La figura 6.30 muestra el coeficiente de dilatación, α, representado gráficamente frente a la conductividad térmica, λ. Los contornos muestran valores constantes de la cantidad λ/α. Una región de búsqueda está aislada por la línea λ/α = 10<sup>7</sup>W/m, dando la pequeña lista de la tabla 6.30. Los valores de M<sub>2</sub> = E<sup>1/2</sup>/ρ leídos en el gráfico E-ρ de la figura 4.3 se incluyen en la tabla. Entre los metales, el cobre, el tungsteno y la aleación especial de níquel Invar presentan los mejores valores de M<sub>1</sub>, pero tienen la desventaja de tener densidades elevadas y, por tanto, valores pobres de M<sub>2</sub>. La mejor elección es el silicio, disponible en grandes secciones y de gran pureza. El carburo de silicio es una alternativa.
    
<div align="center">
  <br><img src=https://github.com/darckoala/Demo-repo/blob/main/CasosEstudio/DistorsionTermica/Imagenes/CartaDistorsionTermica.JPG width=75%"></br>
</div>

<div align="center">
  <sub>
      Figura 6.30: Materiales para aparatos de medición de precisión. Los metales son menos buenos que la cerámica porque tienen frecuencias de vibración más bajas. El silicio puede ser la mejor opción.
  </sub>
</div>

<div align="center">
  <sup>
      Tabla 6.30: Materiales para minimizar la distorsión térmica
  </sup>
</div>

| Material | M<sub> 1 </sub> = λ/α (W/m) | M<sub> 2 </sub> = E<sup>1/2</sup>/ρ (GPa<sup>1/2</sup>/(Mg/m<sup>3</sup>)) | Comentario |
| ------------- | ------------- | ------------- | ------------- |
| Silicio  | 6 x 10<sup>7</sup>  | 5.2 | Excelente M<sub> 1 </sub> y M<sub> 2 </sub> |
| Carburo de silicio  | 3 x 10<sup>7</sup>  | 6.4 | Excelente M<sub> 1 </sub> y M<sub> 2 </sub> pero más difícil de moldear que el silicio |
| Cobre  | 2 x 10<sup>7</sup>  | 1.3 | La alta densidad da un valor pobre de M<sub> 2 </sub> |
| Tungsteno  | 3 x 10<sup>7</sup> | 1.1 | Mejor que el cobre, la plata o el oro, pero menos bueno que el silicio o el SiC. |
| Aleaciones de aluminio  | 10<sup>7</sup> | 3.3 | La opción más barata y fácil de elección de forma |

### Posdata

Los sistemas de medición e imagen a escala nanométrica presentan el problema analizado aquí. El microscopio de fuerza atómica y el microscopio de túnel de barrido se basan en una sonda apoyada en un bucle de fuerza, normalmente con un actuador piezoeléctrico y un sistema electrónico que detecta la proximidad de la sonda a la superficie. Más cerca de casa, el mecanismo de una grabadora de vídeo y el de una unidad de disco duro son instrumentos de precisión; ambos tienen un sensor (el cabezal de lectura) unido , con su electrónica asociada, a un bucle de fuerza. Los materiales identificados en este estudio son la mejor elección para el bucle de fuerza.
    
    

[^1]: M. F. Ashby, Materials selection in mechanical design, 3a ed. Amsterdam: Elsevier Butterworth-Heinemann, 2005.

##
  <div align="center"><a href="http://www.escuelaing.edu.co" target="_blank"><img src=https://github.com/darckoala/Demo-repo/blob/main/Imagenes/Logo_Escuela.png alt="Support by" width="25%" border="0" /></a><sub><br>Este curso guía ha sido desarrollado con el apoyo de la Escuela Colombiana de Ingeniería - Julio Garavito. Encuentra más contenidos en https://github.com/uescuelaing</sub><br><br></div>
