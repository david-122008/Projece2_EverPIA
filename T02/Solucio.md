# AA3 Informe SAI

**Data:** 5/10/2025  
**Autor:** David Català  

---

## Índex
- [Càlculs realitzats](#càlculs-realitzats)
- [Determinació de l’autonomia](#determinació-de-lautonomia)
- [Elecció del SAI](#elecció-del-sai)
- [Justificació de l’elecció del SAI](#justificació-de-lelecció-del-sai)

---

## Càlculs realitzats

La primera part dels càlculs ha sigut obtenir el nombre de dispositius que es troben a l'edifici.  
Un cop sabut el nombre de dispositius i les seves especificacions, hem començat a buscar quants **VA** consumien cada dispositiu i ho hem multiplicat pel nombre total d’unitats presents a l’oficina.  

Un cop realitzats els càlculs anteriors, hem sumat tots els **Watts** dels dispositius, **menys la impressora**, que no cal connectar al SAI perquè en cas d’apagada no hi ha pèrdua d’informació ni danys importants.  

> **Resultat final:** 4463 W  
> Aquest valor ens dona una bona base per escollir el model de SAI adequat.

### Taula resum de dispositius

| Dispositiu | Model | Consum (W) | Consum (VA) | Connectat al SAI | Justificació |
|-------------|--------|-------------|--------------|------------------|---------------|
| Ordinador | HP ProDesk 400 G9 | 2340 | 2340 | Sí | Essencial per a la feina |
| Monitor | Dell P2419H | 1040 | 1040 | Sí | Necessari per veure el contingut abans de tancar-lo |
| CPU | Intel® Core™ i7-13700 | 300 | 300 | Sí | Fonamental per al funcionament del PC |
| Impressora | HP LaserJet Pro MEP M428 | - | - | No | No cal protegir-la davant d’una apagada |
| Router | TP-Link Archer AX10 | 39 | 39 | Sí | Ha de mantenir la connexió a Internet |

---

## Determinació de l’autonomia

Després de calcular la potència total, hem estimat el **temps d’autonomia mínim** que el SAI ha de proporcionar.  
Considerant el temps necessari per guardar documents i apagar correctament els equips, hem determinat que **10 minuts** és un temps òptim.  

Aquest marge permet als treballadors finalitzar tasques o tancar arxius fins i tot en situacions d’emergència.  
Casos excepcionals (com personal poc experimentat) quedarien també coberts amb aquest marge temporal.

---

## Elecció del SAI

Amb els càlculs ja fets, s’han analitzat diferents models que compleixin els requisits de potència i autonomia.  
Els candidats finals han estat dos models de la marca **Salicru**:

| Nom | Potència | Autonomia | Tipus de sortides | Preu | Marca |
|------|-----------|------------|--------------------|--------|--------|
| **SLC-5000-TWIN PRO3** | 5000 W | 9 min | AC: C13 | 2179 € | Salicru |
| **SLC-5000-TWIN RT3** | 5000 W | 8 min | AC: 2 | 2359 € | Salicru |

**Observacions:**
- Ambdós models ofereixen la mateixa potència.
- La diferència principal és el **tipus de sortides** i el **preu**.
- El model *PRO3* ofereix un minut més d’autonomia i un preu més econòmic.

---

## Justificació de l’elecció del SAI

L’equip ha triat el **Salicru SLC-5000-TWIN PRO3** per les raons següents:

- **Més autonomia** (9 minuts vs 8 minuts del model RT3).
- **Compatibilitat més gran** gràcies al tipus de sortida **AC: C13**, molt comú en equips informàtics.
- **Cost més reduït:** 2179 € davant dels 2359 € del model RT3.
- **Mateixa potència nominal (5000 W)**, suficient per cobrir la demanda de l’oficina amb un marge de seguretat adequat.

En conjunt, el **SLC-5000-TWIN PRO3** és el model més equilibrat entre **preu, prestacions i fiabilitat**, complint amb tots els requisits de TecnoGestió S.L.

---

[torna al enunciat](README.md)

