# sesion-02b

## Apuntes
>
> ### Music facts
>
> Música electrónica se basa en el [tempo](https://youtu.be/X83r6euJ0pk?si=Nlu_lP52Yvdogsdr&t=35), el cual se marca con un metrónomo tradicionalmente y se mide en BPM (Beats Per Minute)
>
> [TR-808 drum machine](https://youtu.be/MSKq0r5W2O0?si=nVshmN0YMwFmBIHO)
>
> [TR-303](https://youtu.be/kf2-WLK3gPA?si=5F29i2VBgnFZ-uGF)
>
> ### [YML (YAML)](https://youtu.be/BEki_rsWu4E?si=LxkK22Gq85jf582R)
>
> *"YAML Ain't Markup Languaje"* (o en sus inicios *"Yet Another Markup Languaje"*), aka YAML o YML es un archivo de configuración como lo son .json y .xml, pero diseñado para ser más facil de entender por un humano (al ser más limpio y ordenado)
>
> ### Circuito en clase
>
> <div>
>  <img align="right" src="https://github.com/FranUDP/dis8644-2025-1/blob/main/25-FranUDP/sesion-02b/circuitoClase.jpg" width=400>
>
> | Bill Of Materials (BOM) | Qty | Name | Valor |
> |:-----------------------:|:---:|:----:|:-----:|
> |       Resistencia       |  3  | R<sub>1</sub>, R<sub>2</sub>, R<sub>3</sub> | 1k ohm |
> |         LED             |  4  | D<sub>1</sub>, D<sub>2</sub>, D<sub>3</sub>, D<sub>4</sub> |
> |         Batteria        |  1  | Batt | 9V |
>
> </div>
> <br/>
> <div>
> <img align="left" src="https://github.com/FranUDP/dis8644-2025-1/blob/main/25-FranUDP/sesion-02b/circuitoClaseD.jpg" width=400>  
>
> <p align="right">
>
> | Tabla dependencia | D<sub>1</sub> | D<sub>2</sub> | D<sub>3</sub> | D<sub>4</sub> |
> |:-----------------:|---------------|---------------|---------------|---------------|
> | R<sub>1</sub>     |      0        |      1        |       1       |        1      |
> | R<sub>2</sub>     |       1       |      0        |       1       |        1      |
> | R<sub>3</sub>     |      1        |      1        |       0       |        0      |
>
> </p>
> </div>
>
><br/>
><br/>
><br/>
><br/>
------------------------------------------------------------------------------------------------------------

## Ejercicios
>
> ### 1.-
>>
>> <div>
>> <img align="left" src="https://github.com/disenoUDP/dis8644-2025-1/blob/main/00-docentes/sesion-02b/archivos/schLearn1.png" width=410>
>>
>> | Bill Of Materials (BOM) | Qty | Name | Valor |
>>  |:-----------------------:|:---:|:----:|:-----:|
>> |       Resistencia       |  4 | R<sub>1</sub>, R<sub>2</sub>, R<sub>3</sub>, R<sub>5</sub> | 220 ohm |
>> |       Resistencia       |  1 | R<sub>4</sub> | 1k ohm |
>> |         LED             |  4  | D<sub>1</sub>, D<sub>2</sub>, D<sub>3</sub>, D<sub>4</sub> |
>> |         Batteria        |  1  | Bt<sub>1</sub> | 9V |
>>
>> </div>
>>
>> | Tabla dependencia | D<sub>1</sub> | D<sub>2</sub> | D<sub>3</sub> | D<sub>4</sub> |
>>  |:-----------------:|:-------------:|:-------------:|:-------------:|:-------------:|
>> | R<sub>1</sub>     |      0        |      0        |       0       |        0      |
>> | R<sub>2</sub>     |       1       |      0        |       0       |        1      |
>> | R<sub>3</sub>     |      1        |      1        |       1       |        0      |
>> | R<sub>4</sub>     |      1        |      1        |       1       |        0      |
>> | R<sub>5</sub>     |      1        |      0        |       0       |        1      |
>>
>> <img src="https://github.com/FranUDP/dis8644-2025-1/blob/main/25-FranUDP/sesion-02b/circuito1.jpg" width=410>
>>
>><br/>
><br/>
>
> ### 2.-
>>
>> <div>
>> <img align="left" src="https://github.com/disenoUDP/dis8644-2025-1/blob/main/00-docentes/sesion-02b/archivos/schLearn2.png" width=410>
>>
>> | Bill Of Materials (BOM) | Qty | Name | Valor |
>>  |:-----------------------:|:---:|:----:|:-----:|
>> |       Resistencia       |  6 | R<sub>1</sub>, R<sub>2</sub>, R<sub>3</sub>, R<sub>4</sub>, R<sub>5</sub>, R<sub>6</sub> | 220 ohm |
>> |         LED             |  4  | D<sub>1</sub>, D<sub>2</sub>, D<sub>3</sub>, D<sub>4</sub> |
>> |         Batteria        |  1  | Bt<sub>1</sub> | 9V |
>>
>> </div>
>>
>> | Tabla dependencia | D<sub>1</sub> | D<sub>2</sub> | D<sub>3</sub> | D<sub>4</sub> |
>>  |:-----------------:|:-------------:|:-------------:|:-------------:|:-------------:|
>> | R<sub>1</sub>     |       1       |       1       |       1       |       1       |
>> | R<sub>2</sub>     |       1       |       1       |       1       |       1       |
>> | R<sub>3</sub>     |       1       |       1       |       1       |       1       |
>> | R<sub>4</sub>     |       1       |       1       |       1       |       1       |
>> | R<sub>5</sub>     |       1       |       1       |       1       |       1       |
>> | R<sub>6</sub>     |       1       |       1       |       1       |       1       |
>>
>> <img src="https://github.com/FranUDP/dis8644-2025-1/blob/main/25-FranUDP/sesion-02b/circuito2.jpg" width=410>
>>
>><br/>
><br/>
>
> ### 3
>>
>> <div>
>> <img align="left" src="https://github.com/disenoUDP/dis8644-2025-1/blob/main/00-docentes/sesion-02b/archivos/schLearn3.png" width=410>
>>
>> | Bill Of Materials (BOM) | Qty | Name | Valor |
>>  |:-----------------------:|:---:|:----:|:-----:|
>> |       Resistencia       |  5 | R<sub>1</sub>, R<sub>2</sub>, R<sub>3</sub>, R<sub>4</sub>, R<sub>8</sub> | 220 ohm |
>> |       Resistencia       |  3 | R<sub>5</sub>, R<sub>6</sub>, R<sub>7</sub> | 1k ohm |
>> |         LED             |  3 | D<sub>1</sub>, D<sub>2</sub>, D<sub>3</sub> |
>> |         Batería        |    | Bt<sub>1</sub> | 9V |
>>
>> </div>
>>
>> | Tabla dependencia | D<sub>1</sub> | D<sub>2</sub> | D<sub>3</sub> |
>>  |:-----------------:|:-------------:|:-------------:|:-------------:|
>> | R<sub>1</sub>     |       1       |       0       |       1       |
>> | R<sub>2</sub>     |       1       |       0       |       1       |
>> | R<sub>3</sub>     |       1       |       0       |       1       |
>> | R<sub>4</sub>     |       1       |       0       |       1       |
>> | R<sub>5</sub>     |       0       |       1       |       1       |
>> | R<sub>6</sub>     |       1       |       1       |       1       |
>> | R<sub>7</sub>     |       1       |       1       |       1       |
>> | R<sub>8</sub>     |       1       |       1       |       0       |
>>
>> <img src="https://github.com/FranUDP/dis8644-2025-1/blob/main/25-FranUDP/sesion-02b/circuito3.jpg" width=410>
>><br/>
>
