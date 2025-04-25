# sesion-07a
## Sesión 22-04
### Primera parte (clase de Kicad)
Secuencia:

- Abrir Kicad
- Generar archivo (llamé al mío project 01)
- Seleccionar **"editor de esquema"**
- Place symbol con **"a"**
- **"r"** para rotar y **"m"** para mover
- elegir campo de valor con **"v"**
- Dibujar cables con **"w"**
- Asignar huellas en **panel de control superior**

<div align="center">
  <img height="100%" src="https://media.discordapp.net/attachments/1248658110625742862/1364254104355999806/clase_22-04.jpg?ex=68090025&is=6807aea5&hm=09b1d950a38ee900608d25b6e61908ed70edc19d4128b6128da450a70b5d8ea2&=&format=webp&width=1964&height=1104"  />
</div>

<div align="center">
  <img height="100%" src="https://media.discordapp.net/attachments/1248658110625742862/1364243893784285224/image.png?ex=6808f6a2&is=6807a522&hm=dfb5868f92714ab6609c7930cfd929f893887987934c85b92fb3ceff9a557bc6&=&format=webp&quality=lossless&width=1745&height=1109"  />
</div>

<div align="center">
  <img height="700" src="https://media.discordapp.net/attachments/1248658110625742862/1364262795817783396/image.png?ex=6809083d&is=6807b6bd&hm=529f636e4329453ef37bc8b47698b16e9e054c708f30ee53e8564e6479bfd155&=&format=webp&quality=lossless&width=825&height=440"  />
</div>

###
### Segunda parte (materiales)
Link para comprar materiales: https://www.mouser.cl/; https://www.mouser.cl/c/?q=1n4148 ; https://www.dartel.cl/ 
- do-35
- 1N4148
- rk163

**Parte de PCB del esquema en Kicad**

**IMPORTANTE: pulsar los siguientes botones ------> alt+3** -------> Visor 3D

<div align="center">
  <img height="100%" src="https://media.discordapp.net/attachments/1248658110625742862/1364264995646472373/image.png?ex=68090a49&is=6807b8c9&hm=54ccec90a083f1b0cef91ef701be2fa14d2f62336a983894917c21eb74f02a30&=&format=webp&quality=lossless&width=1314&height=1260"  />
</div>

<div align="center">
  <img height="100%" src="https://media.discordapp.net/attachments/1248658110625742862/1364265080002183310/image.png?ex=68090a5d&is=6807b8dd&hm=9ebb95da03b0b3da83979490c15815babce5e748140152c8a38acc44fdbeaa6e&=&format=webp&quality=lossless&width=1970&height=1104"  />
</div>

Por alguna razón el programa solo registro un solo componente del otro esquema, voy a tener que revisar que paso (lo mas probable que fuera de la parte "asignar huellas").

Tecnincas:

- Seleccionar capa de cobre trasera (B.CU) --> Enrutar pista única (X) ---> seleccionar el componente a unir con el que se desea.
- Generalmente editar el ancho de pista a 0.5mm
- Pulsar **alt+A** para seleccionar todos los archivos (el programa permite activar y desactivar que  elementos queremos seleccionar en la esquina inferior derecha)
