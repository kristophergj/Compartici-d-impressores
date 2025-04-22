# Activitat 2
### El professor ens ha demanat el següent: 
La vostra oficina disposa d'una impressora centralitzada que està connectada a un equip amb Windows 10. La resta d'ordinadors de l'oficina fan servir Linux. Has de fer que tots els usuaris puguin utilitzar la impressora. La xarxa de l'oficina fa servir aquestes adreces IP. On X és el número assignat al teu grup.

També hem de fer un tutorial a Github i una demostració a clase de com fer-ho.

Les maquines virtuals han de fer ping entre elles, per poder fer això li hem de posar la IP 192.168.15.100 a la maquina Linux i la IP 192.168.15.10 a la maquina Windows.

## Instal·lem el PDFCreator 

![image](https://github.com/user-attachments/assets/c9860407-a1c8-42ec-9b72-0fc9421f8600)

## Anem al Panell de control a la màquina de Windows

![image](https://github.com/user-attachments/assets/416b9a5a-cc84-4916-8f10-3cff6bf9e14b)

##  Després a dispositius i impressores, fem clic a PDFCreator i seleccionem Propietats de la impressora

![image](https://github.com/user-attachments/assets/96f7e5b5-75b0-4613-a150-c2c6cafd3d11)

## Hem d'instal·lar el client de Samba

```
sudo apt install smbclient
```

![image](https://github.com/user-attachments/assets/472317d1-2d2a-4d6c-a061-68f11e8d2303)

## Ara anem al cups al navegador i afegim la impressora "Windows printer via SAMBA"

![image](https://github.com/user-attachments/assets/3281c4d2-8bdb-4533-a273-740f65a705d5)

## Fiquem la IP, l'usuari i la contrasenya i després el nom de la impressora

![image](https://github.com/user-attachments/assets/107cfe8d-127d-49c1-b6cb-343488ec39f2)

## Li posem un nom i li afegim els controladors i pre ultim la connectem

![image](https://github.com/user-attachments/assets/7a8938bd-bef6-49e0-9e72-0c90f9568495)

![image](https://github.com/user-attachments/assets/5a1cec16-a8d0-42b8-860b-38ad5d366b30)

## Imprimim una pàgina de prova i ho comprovem al CUPS

![image](https://github.com/user-attachments/assets/ffbe1aea-d0ee-408e-a807-607bc30d1648)

![image](https://github.com/user-attachments/assets/2455d04d-eac2-4c71-877d-51472aa3d8e9)
