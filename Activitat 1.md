# Compartició d'impressores per parelles
### El professor ens ha demanat el següent: 
La vostra oficina disposa d'una impressora centralitzada que està connectada a un equip amb Linux. La resta d'ordinadors de l'oficina fan servir Windows 10. Has de fer que tots els usuaris puguin utilitzar la impressora. La xarxa de l'oficina fa servir aquestes adreces IP. On X és el número assignat al teu grup.

També hem de fer un tutorial a Github i una demostració a clase de com fer-ho.

Les maquines virtuals han de fer ping entre elles, per poder fer això li hem de posar la IP 192.168.15.100 a la maquina Linux i la IP 192.168.15.10 a la maquina Windows.

## Instal·lem el CUPS i impressora PDF virtual

sudo apt update

![image](https://github.com/user-attachments/assets/5c468399-7780-4532-a362-1e6b5756e94f)
```bash
sudo apt instal cups

![image](https://github.com/user-attachments/assets/2ac7d778-8657-4ba3-8605-5d713d451e19)

sudo apt install printer-driver-cups-pdf

![image](https://github.com/user-attachments/assets/7472e0f3-f0f7-4208-8891-2ef154013940)

## Compartim la impressora amb el CUPS

Hem d'anar al navegador i posar http://localhost:631 per entrar al CUPS

![image](https://github.com/user-attachments/assets/fa85bf48-f887-46e7-88ad-716f47fc6bc0)

Ara anem a administració i afegim la impressora

![image](https://github.com/user-attachments/assets/61b46e27-fcb7-4ea1-8934-6c69275c1152)

![image](https://github.com/user-attachments/assets/0805fe42-9d63-4fd1-9577-aed3512673a8)

Entre les opcions de Local Printers escollim la de CUPS-PDF

![image](https://github.com/user-attachments/assets/f3a00c9e-020f-41fa-84cf-e5ef8e304cb6)

Li canviem el nom i habilitem l'opció de sharing

![image](https://github.com/user-attachments/assets/54d8feff-e062-46d3-92ce-8917b20649f1)


![image](https://github.com/user-attachments/assets/e5d45785-0e1b-42fd-a5c3-8502bf80ccfc)

Ara hem d'afegir els controladors anomenats Generic i el model Generic CUPS-PDF Printer (w/options) (en)

![image](https://github.com/user-attachments/assets/cad064a3-9bf5-43a3-ab79-b68011555578)

![image](https://github.com/user-attachments/assets/72b3bfdb-8823-439a-b52a-ca761ff55198)



