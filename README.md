# Hola, sóc en Josep Montañà 👋

> **Una proposta de sistema operatiu per al coneixement curricular docent.**  
> El currículum com un graf de text pla: llegible, versionable i teu.  
> I una invitació oberta a construir, entre tots, un estàndard per al currículum.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23823818.svg)](https://doi.org/10.5281/zenodo.23823818)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/jmonta23-okf/okf-starter-kit/blob/main/LICENSE.md)
[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-blue.svg)](https://github.com/jmonta23-okf/okf-starter-kit/blob/main/LICENSE.md)

---

Soc del 74, biòleg de formació i professor de FP a l'escola pública catalana des del 2008. Abans d'entrar a l'aula treballava en control microbiològic a la indústria farmacèutica, on el que no estava validat, registrat i traçat, senzillament no existia. Aquell xip se't queda a la pell.

L'any 2015, barallant-me amb ontologies i classificacions mèdiques (SNOMED-CT, CIM-10), em va caure la fitxa: **el currículum educatiu és una xarxa biològica viva**, no una llista de documents de Word. Des de llavors, treballo per portar aquest rigor científic i estructural a la feina real de l'institut.

---

## 🎯 Què estic construint

**[OKF Starter Kit](https://github.com/jmonta23-okf/okf-starter-kit)** — una proposta de sistema operatiu per al coneixement curricular docent, amb DOI permanent ([10.5281/zenodo.23823818](https://doi.org/10.5281/zenodo.23823818)).

La idea és simple: en lloc de tenir documents solts, el teu currículum es converteix en un **graf de nodes interconnectats** (mòduls, activitats, criteris d'avaluació) que pots validar, versionar i compartir. I, quan el coneixement està ordenat i validat, pots connectar-hi eines d'IA mitjançant els **Paquets LLM**: receptes obertes, transparents i en text pla que converteixen el que saps en el que la teva aula necessita cada dia.

**Versió actual: V1.3** (amb 38 codis d'error, 75 tests, 41 nodes OKF validats amb 0 errors).

### Tres portes d'entrada (i una de sortida)

El kit té **tres Paquets LLM** que cobreixen tot el cicle:

| Paquet | Enfocament | Punt de partida | Punt d'arribada |
|:---|:---|:---|:---|
| **Paquet 00** | Deductiu | Currículum oficial | Vault construït |
| **Paquet 01** | Inductiu | Programació existent | Vault construït |
| **Paquet 02** | Sortida | Vault construït | Document oficial (Word) |

El kit és la **síntesi de dos projectes reals** (TCAI-OKF i SAD-GRAF) i forma part d'un ecosistema més ampli, **OKF-CATALA**, que comparteix eines i filosofia:

- **TCAI-OKF** (2025-2026): el graf del cicle de Cures Auxiliars d'Infermeria. On va néixer el Paquet LLM i el "factor Montse".
- **SAD-GRAF** (2026-2027): el graf del cicle de Documentació Sanitària. On es van conceptualitzar els Cores, les FitxaAEA i els Protocols.
- **OKF-CURS-FP** (2026-2027): el curs formatiu de 9 mòduls (M0-M8) que ensenya el sistema.
- **PTE-OKF** (2026-2027): el vault de Pedagogia Terapèutica (adaptació d'OKF-CURS-FP per a l'Ariadna C.).
- **OKF-CURS-MP1523** (2026-2027): el vault per al mòdul MP1523 (adaptació d'OKF-CURS-FP per a en César G.).

---

## 📰 Publicacions recents

- **[Del laboratori a la sala de mestres: un currículum que és una xarxa viva](https://comunitat.edigital.cat/t/del-laboratori-a-la-sala-de-mestres-un-curriculum-que-es-una-xarxa-viva/47039)** (article de difusió, novembre de 2026). Reflexions sobre OKF, els Paquets LLM i el gust de fer les coses amb les mans. Publicat a la comunitat eDigital.

---

## 🧭 Principis del projecte

1. **El coneixement és teu.** El vault viu a la teva màquina, no en un núvol propietari. El pots copiar, versionar i emportar quan canviïs de centre.
2. **Portabilitat.** Text pla (Markdown + YAML). D'aquí a vint anys podràs obrir-lo sense dependre de cap llicència, empresa o connexió.
3. **Transparència on es pot, verificació on no.** Les receptes (Paquets LLM), el graf i el validador són llegibles. El model d'IA no ho és, i per això validem i supervisem.
4. **Ètica innegociable.** Marc **MIAE** (supervisió humana al centre) i **VCER** ([Vibe Coding Educatiu Responsable](https://vibe-coding-educativo.github.io/vibe-responsable/ca/)): materials 100% offline, privats i lliures.
5. **Codi obert.** Doble llicència: MIT (codi) + CC BY-SA 4.0 (contingut).

---

## 📝 Com citar el projecte

Si fas servir el kit en un treball acadèmic o una publicació:

> Montañà Piqué, J. (2026). *OKF Starter Kit: una proposta de sistema operatiu per al coneixement curricular docent* (V1.3) [Programari]. Zenodo. https://doi.org/10.5281/zenodo.23964880

*(Per citar el concepte global del projecte de manera independent de la versió: [https://doi.org/10.5281/zenodo.23823818](https://doi.org/10.5281/zenodo.23823818)).*

---

## 🙏 Amb qui he après

Aquest projecte no s'ha fet sol. S'ha forjat al meu despatx, en caps de setmana i vacances, però amb companys que han posat el seu temps, la seva paciència i el seu criteri:

- **Montse G.** (co-docent de TCAI): la seva sinceritat a l'aula va fer néixer el concepte del Paquet LLM.
- **Benet M.** (Química, MP1257): va confiar en el mètode per al seu debut docent i va demostrar que l'estructura funciona en qualsevol família professional.
- **Ariadna C.** (Pedagogia Terapèutica): la millor aliada en l'exploració de grafs per a Plans Individuals (PI) i adaptacions DUA.
- **César G.** (Sanitat, MP1523): la complicitat en la creació del seu propi graf docent autònom (59 nodes, 0 errors).

I a **Juan José de Haro**, pels marcs MIAE i VCER que guien el nostre taller digital.

---

## 🛠️ Eines i context

Treballo amb Markdown, YAML i Python. El projecte neix de la meva experiència docent i de la necessitat d'un sistema que s'adapti a qualsevol marc curricular (LOGSE, LOE, LOMLOE) i a qualsevol família professional.

---

## 🤖 Declaració d'ús d'IA

Aquest projecte s'ha desenvolupat en **cocreació amb models de llenguatge** (Claude, DeepSeek, Gemini). **Nivell MIAE declarat: 4 (cocreació).** L'autor ha aportat la visió, la filosofia, el domini curricular, els casos reals i les decisions ètiques; la IA ha generat esborranys, ha proposat estructures i ha comès errors que l'autor ha detectat i corregit. Els detalls complets són a la [filosofia del kit](https://github.com/jmonta23-okf/okf-starter-kit/blob/main/00-documentacio/02-filosofia.md#declaració-dús-dia-en-aquest-kit).

---

## 📫 Contacte

- **GitHub:** [@jmonta23-okf](https://github.com/jmonta23-okf)
- **Correu:** [jmonta23@gmail.com](mailto:jmonta23@gmail.com)
- **Repositori principal:** [okf-starter-kit](https://github.com/jmonta23-okf/okf-starter-kit)
- **Concept DOI:** [10.5281/zenodo.23823818](https://doi.org/10.5281/zenodo.23823818)
- **DOI V1.3:** [10.5281/zenodo.23964880](https://doi.org/10.5281/zenodo.23964880)

---

*Si fas servir el kit a la teva aula, si crees el graf d'un cicle nou o si tens idees per simplificar-lo, obre un issue o envia'm un correu. El taller és obert. Porteu el cafè.* ☕
