# sesion-10b

16-05-2025

## Apuntes 
* En KiCad, para generar un archivo png debemos seleccionar: exportar (cuts,f. silkscreen, mask)
* Exportar archivos del BOM a excel: data > de texto a columnas > separar (desde KiCad hacia el excel)
* Tip: Soldar primero las cosas cerca del "suelo" (diodos, resistencias, socket chip, condensadores) luego las cosas que están más lejos (LEDS, terminal block, switch spdt, parlantes, batería)
* Exportar excel hacia Github: dowland > CSV > Markdown Github
* CSV: Valores separados por comas
* Convertcsv.com: Pasar CSV a Md

## encargo-22: documentación textual del proceso de ensamblado de udpudu

escribir manual con pasos a seguir, receta, de los pasos que siguieron para ensamblar la PCB.

incluir aciertos y errores, aprendizajes y consejos.

### 1. Primero realizamos el BOM para verificar si teníamos todos los componentes

## Bom Udpudu
|Referencia  |Valor   |Huella                   |Qty|OBS               |
|------------|--------|-------------------------|---|------------------|
|U1          |~       |Socket 8 pines           |1  |                  |
|R2,R3,R4    |1k      |Resistencias             |3  |                  |
|D1          |1n4007  |Diodo                    |1  |                  |
|C3          |100n    |Condensador cerámico     |1  |104               |
|C4          |1u      |Condensador electrolítico|1  |                  |
|C5          |47u     |Condensador electrolítico|1  |                  |
|D2,D3       |LED     |Led 5mm                  |2  |                  |
|J2          |TBLOCK_2|Terminal Block 2         |1  |                  |
|LS1         |SPK     |Terminal Block 2         |1  |                  |
|SW1         |SW_SPDT |Switch spdt              |1  |                  |
|U1          |NE555   |DIP-8                    |1  |Va en el socket U1|
|Clip batería|9v      |                         |1  |                  |
|Parlante    |8ohm    |                         |1  |                  |
|J1,J3       |CAIMAN  |Cables caimán            |2  |                  |

### 2. Luego nos pasaron el DIP y la PCB

![IMG_4374](https://github.com/user-attachments/assets/139df39b-3086-4417-8a99-40a18e6e7cd9)

![IMG_4373](https://github.com/user-attachments/assets/f88e44da-720e-49e3-be26-bf4503dd3630)

### 3. Realizamos el circuito en la protoboard para verificar si estaban bien el sonido y el esquemático

https://github.com/user-attachments/assets/93b0a12c-55cf-4e89-8543-497fa0d1a0f5



https://github.com/user-attachments/assets/71f48e6b-3ea5-4950-aa32-d7f91fa46741


### 4. Con el grupo dejamos los componentes en un lado para que no se nos perdieran 
* (Cabe recalcar que las fotos de procedimiento las tiene nuestro compañero Santiago)
  
### 5. Conectamos el cautín y esperamos a que se calentara, para luego limpiar la punta

### 6. Luego soldamos primero el Socket y luego los demás componentes (nos basamos en el BOM para poder soldar los compenentes, primero las resistencias, diodos y luego los condensadores)

### 7. Nos turnamos para soldar, así el trabajo fue más eficiente
* Precalentar 3 segundos el PAD
* Meter soldadura sin plomo
* Se queda 3 segundos
* Sacar cautín
* TIP: Para una buena soldadura, tiene que quedar en rampita

### 8. Cuando estén listas las soldaduras, se corta el excedente de los componentes

### 9. Al tener todo listo, Aaron trajo un set para poder tomar fotitos de la PCB.

## encargo-23: documentación visual del proceso de ensamblado de udpudu

![IMG_1386](https://github.com/user-attachments/assets/46a19571-43bd-4125-be2d-b610a28dc91a)
![IMG_4385](https://github.com/user-attachments/assets/4589aeea-1c0e-4fa6-8f57-1708233bbe88)
![IMG_4377](https://github.com/user-attachments/assets/54e58041-6f3d-4c4b-afdc-a106423ffe39)
![IMG_4380](https://github.com/user-attachments/assets/201789ff-78bf-433e-882b-682f782d0e02)
![IMG_1398](https://github.com/user-attachments/assets/4c012d51-370a-477e-9633-a5cdc647e12f)
![IMG_1394](https://github.com/user-attachments/assets/809d2671-afc3-4ae2-b9c0-e8e1b068dcc3)
![IMG_1392](https://github.com/user-attachments/assets/f2d70614-051a-4a7e-a27b-3f37ed9be7bd)
