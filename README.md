# Zed_len
Estimar o comprimento de objetos usando a camera zed, a partir de triangulações e o Teorema de Pitágoras

Para melhor precisão, é recomendado que o objeto esteja em um local bem iluminado e que fique centralizado com distancia
de 20 a 50 centimetros em relação a câmera. 

Para estimar o tamanho do objeto, é pego a distancia entre a cemera e o objeto a ser detctado, a zed retorna a distancia em triangulação, por tanto,
temos a distancia e nos falta encontrar o comprimento do triangulo. Para facilitar o calculo, pegamos também um ponto médio entre o distancia superior e
a inferior, com isto conseguimos dois triangulos retangulos, agora basta apenas aplicar Pitagoras para conseguir estimar os valores do comprimento do objeto.



# Instalação

Primeiramente realize o tutorial de instalação da SDK da Zed, 
https://www.stereolabs.com/developers/release/

Em seguida faça o clone do repositório e instale as pendencias,
```
git clone https://github.com/plech1/Zed_len
cd Zed_len
pip install .
```
