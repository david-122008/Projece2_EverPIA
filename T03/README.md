# Enunciat de la pràctica

Després de la primera feina exitosa, us arriba un encàrrec urgent que obliga a que us hi poseu per donar-li solució.  
Com a fase prèvia rebreu una formació sobre la **seguretat lògica** que us permetrà tenir els coneixements necessaris per afrontar la tasca.  
Han arribat a la consultora un equip provinent d’un client que demana que els hi solucionem el problema.

Tenen un portàtil amb **Zorin OS** (un Linux amb entorn gràfic) que usava habitualment un directiu. El problema és que ha oblidat la contrasenya i és necessari poder recuperar l’accés perquè hi ha documentació molt important que cal recuperar. Per evitar que una acció catastròfica pugui danyar l’equip original, ens han clonat el disc en un disc virtual perquè hi treballeu.

Per tant, el primer pas serà crear una màquina virtual a la qual connectareu aquest disc. A continuació, cal que entreu a la màquina virtual, trobeu el nom de l’usuari existent i li assigneu una contrasenya nova.

Quan el client és informat del senzill que és accedir a l’equip, demana si n’hi ha alguna manera de fortificar el sistema, ja que té por que si algú roba el portàtil hi pugui accedir a la informació que hi conté. Per tant, ara ens demanen que cerquem solucions per tal d’evitar que es pugui reiniciar la contrasenya amb el procediment anterior. Investigueu el procediment per tal que l’accés al **GRUB** quedi protegit per contrasenya per evitar canvis de configuració.

---

## Procediment individual (tasques a realitzar)

1. **Vulneració controlada de l’accés al GRUB** del Linux (sobre la còpia/clon del disc, no sobre l’equip original).  
2. **Identificació de l’usuari** del sistema.  
3. **Modificació de la contrasenya** de l’usuari i verificació que ara té accés.  
4. **Investigació de mesures per fortificar l’accés al GRUB** (cal indicar les fonts d’informació utilitzades).  
5. **Configuració de la màquina virtual** per tal de fortificar l’accés al GRUB.  
6. **Documentació del procediment** en un document final (cal incloure imatges) per posteriorment pujar-lo al vostre repositori.

---

## Requisits i notes importants

- És una pràctica de classe: qualsevol acció ha de fer-se sobre la **còpia/clon del disc** proporcionada, **mai** sobre l’equip original del client.  
- Documenteu **tots** els passos amb captures i explicacions (comandes, fitxers editats, sortides rellevants).  
- Citeu **les fonts** d’informació usades per la investigació (guies de GRUB, manpages, documentació oficial, tutorials fiables).  
- Assegureu-vos que les mesures proposades no trenquin la possibilitat de recuperació legítima si el client ho necessita (descriure avantatges i inconvenients de cada mesura).  
- El format de lliurament ha de ser un document amb text i imatges (Markdown o PDF), i pujat al vostre repositori.

---

## Resultats esperats (resum)

- Accés recuperat a l’usuari del sistema a la màquina virtual clonada.  
- Concepte i aplicació d’una mesura per protegir el menú del GRUB amb usuari/contrassenya (per exemple: `set superusers=...` i `password_pbkdf2 ...` a `/etc/grub.d/40_custom` + regenerar `grub.cfg`).  
- Documentació completa amb imatges, comandes i fonts.

- 
a l'arxiu [solució.md](Solucio.md)
