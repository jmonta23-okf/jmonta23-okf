# Hola, soc en Josep Montañà i Piqué 👋

> **Una proposta de sistema operatiu per al coneixement docent.**  
> El currículum com un graf de text pla: llegible, versionable i teu.

[![DOI](https://zenodo.org/badge/1440306517.svg)](https://doi.org/10.5281/zenodo.23823819)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/jmonta23-okf/okf-starter-kit/blob/main/LICENSE.md)
[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-blue.svg)](https://github.com/jmonta23-okf/okf-starter-kit/blob/main/LICENSE.md)

---

Soc docent de la família professional de Sanitat i biòleg de formació. Abans d'entrar a l'aula vaig treballar en control microbiològic a la indústria farmacèutica, on el que no estava validat, registrat i traçat, senzillament no existia. Aquell xip se't queda a la pell.

El 2015, barallant-me amb ontologies i classificacions mèdiques (SNOMED-CT, CIM-10), em va caure la fitxa: **el currículum funciona com una xarxa viva**, no com una llista de documents de Word. Des de llavors intento portar aquest rigor a la feina real de l'institut.

---

## 🎯 Què estic construint

**[OKF Starter Kit](https://github.com/jmonta23-okf/okf-starter-kit)**: una proposta de sistema operatiu per al coneixement docent, amb DOI persistent (`10.5281/zenodo.23823819`).

La idea és simple. En lloc de documents solts, el currículum és un **graf de nodes interconnectats** (mòduls, activitats, criteris d'avaluació) escrits en text pla, que pots validar, versionar i compartir. Quan el coneixement està ordenat així, hi pots connectar eines d'IA mitjançant els **Paquets LLM**: receptes obertes, transparents i en text pla, que el docent pot llegir i modificar.

El kit és volgudament mínim: l'esquelet que queda quan treus la sobreenginyeria de tres projectes germans desenvolupats a l'aula.

- **TCAI-OKF** (2025-2026): el graf del cicle de Cures Auxiliars d'Infermeria. On va néixer el Paquet LLM i el «factor Montse».
- **SAD-GRAF** (2026-2027): el graf del cicle de Documentació Sanitària. On es van conceptualitzar els Cores, les FitxaAEA i els Protocols.
- **PTE-OKF** (2026-2027): el graf de Pedagogia Terapèutica a primària. On es va reforçar la privacitat de les dades de menors.

Són proves artesanals fetes a l'aula i amb companys, no un estudi d'impacte.

---

## 🧭 Principis del projecte

1. **El coneixement professional és teu.** El vault viu a la teva màquina, no en un núvol propietari: el pots copiar, versionar i emportar quan canviïs de centre.
2. **Portabilitat.** Text pla (Markdown + YAML), el format que millor resisteix el pas del temps i que s'obre amb qualsevol editor.
3. **Transparència on es pot, verificació on no.** Les receptes (Paquets LLM), el graf i el validador són llegibles. El model d'IA no ho és, i per això validem i supervisem. El validador comprova la forma, no la veritat: l'última paraula és d'una persona que coneix la matèria.
4. **Ètica de taller.** El marc [MIAE](https://jjdeharo.github.io/miae/ca/) per graduar i declarar l'ús de la IA, amb la supervisió humana al centre, i el [VCER](https://vibe-coding-educativo.github.io/vibe-responsable/ca/) (*Vibe Coding Educatiu Responsable*): materials d'aula 100% offline, privats i lliures.
5. **Codi obert.** Dues llicències, cadascuna per a una part: MIT per al codi i CC BY-SA 4.0 per al contingut.

---

## 🚀 Per on començar

Entra al [repositori del kit](https://github.com/jmonta23-okf/okf-starter-kit). Si vols entendre el per què, llegeix primer `02-filosofia.md`; si prefereixes anar al gra, tens `04-inici-rapid.md`.

---

## 📝 Com citar el projecte

Si fas servir el kit en un treball acadèmic o una publicació:

> Montañà Piqué, J. (2026). *OKF Starter Kit: una proposta de sistema operatiu per al coneixement curricular* (V1.1) [Programari]. Zenodo. https://doi.org/10.5281/zenodo.23823819

---

## 🙏 Amb qui he après

Aquest projecte no s'ha fet sol. S'ha forjat a la sala de professors, amb companys que han posat el seu temps, la seva paciència i el seu criteri:

- **Montse G.** (co-docent de TCAI): la seva sinceritat a l'aula va fer néixer el concepte del Paquet LLM.
- **Benet M.** (Química, MP1257): va confiar en el mètode per al seu debut docent i em va servir per comprovar que l'estructura aguanta fora de la meva especialitat.
- **Anna** (Pedagogia Terapèutica): la millor aliada en l'exploració de grafs per a Plans Individuals (PI) i adaptacions DUA (Disseny Universal per a l'Aprenentatge).
- **César** (Sanitat, MP1523): la complicitat en la creació del seu propi graf docent autònom, de 59 nodes que passen el validador sense errors.

I a **Juan José de Haro**, pels marcs MIAE i VCER que guien el nostre taller digital.

---

## 🛠️ Eines i context

Treballo amb Markdown, YAML i Python. El projecte neix de la meva experiència docent i vol adaptar-se a diferents marcs curriculars (LOGSE, LOE, LOMLOE) i famílies professionals; de moment l'he provat amb els casos de dalt.

---

## 📫 Contacte

- **GitHub:** [@jmonta23-okf](https://github.com/jmonta23-okf)
- **Correu:** [jmonta23@gmail.com](mailto:jmonta23@gmail.com)
- **Repositori principal:** [okf-starter-kit](https://github.com/jmonta23-okf/okf-starter-kit)
- **DOI:** [10.5281/zenodo.23823819](https://doi.org/10.5281/zenodo.23823819)

---

*Si fas servir el kit a la teva aula, si crees el graf d'un cicle nou o si tens idees per simplificar-lo, obre un issue al [repositori](https://github.com/jmonta23-okf/okf-starter-kit/issues) o escriu-me. El taller és obert. Porteu el cafè.* ☕
