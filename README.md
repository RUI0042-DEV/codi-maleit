# 🎃 El codi maleit

Benvinguts a la Casa dels Ecos, un misteri que amaga una pista dins del mateix repositori. Aquest projecte combina la narrativa d’Halloween amb la pràctica de Git i GitHub, i proposa una investigació en què les pistes es reparteixen entre diferents branques.

La web de la Casa dels Ecos ha estat sabotejada i l’única manera de reconstruir-ne el secret és explorar el repositori amb cura, respectant el treball de les altres branques i sense perdre la pista correcta.

## Descripció del projecte

`El codi maleit` és un repte de descoberta i control de versions. El seu objectiu és fer servir Git per explorar un projecte amb un misteri ocult: la pàgina principal mostra un avís de compromís i la missió consisteix a identificar pistes, analitzar la història del repositori i reconstruir el codi secret sense destruir la feina d’altres branques.

Tot i que el projecte té una ambientació de Halloween i enigmes, la part central és pràctica i educativa: treballar amb branques, lectura d’historial, organització del repositori i presa de decisions responsables en un entorn de desenvolupament real.

## Objectius

- Explorar les branques disponibles del repositori.
- Localitzar pistes sense esborrar ni sobrescriure el treball d’altres branques.
- Entendre l’estructura d’un projecte web senzill amb HTML i CSS.
- Reconstruir el codi secret a partir de la informació disponible.
- Crear una branca pròpia de solució i documentar el resultat final.
- Practicar conceptes bàsics i essencials de Git i GitHub.

## Tecnologies utilitzades

- HTML: estructura de la pàgina web.
- CSS: estil i disseny visual de la interfície.
- Git: gestió de versions i branques.
- GitHub: repositori, col·laboració i seguiment del projecte.
- Visual Studio Code: editor principal per desenvolupar i editar fitxers.
- Navegador web: per visualitzar la pàgina localment.

## Requisits

Per treballar amb aquest projecte, només cal tenir instal·lat:

- Git
- Visual Studio Code
- Un navegador web modern

## Clonar el repositori

Obre un terminal i executa la següent ordre:

```bash
git clone https://github.com/<usuari>/codi-maleit.git
cd codi-maleit
```

## Obrir el projecte a Visual Studio Code

Hi ha dues opcions principals:

### Opción 1: des de la terminal

```bash
code .
```

### Opció 2: des de l’editor

1. Obre Visual Studio Code.
2. Selecciona `File` > `Open Folder...`.
3. Tria la carpeta del repositori `codi-maleit`.
4. Obre `index.html` per visualitzar la pàgina o utilitza una extensió com Live Server si la tens instal·lada.

## Estructura de carpetes i fitxers

```text
codi-maleit/
├── README.md
├── GUIA_RAPIDA_REPO.txt
├── index.html
├── style.css
├── pistes/
│   ├── INSTRUCCIONS.txt
│   └── registre.txt
└── .git/
```

### Descripció dels elements principals

- `README.md`: documentació general del projecte.
- `index.html`: pàgina principal de la web del misteri.
- `style.css`: full d’estils que defineix la presentació visual.
- `GUIA_RAPIDA_REPO.txt`: informació útil sobre les branques disponibles.
- `pistes/`: carpeta dedicada a les pistes i la documentació del joc.
- `.git/`: carpeta de Git que guarda l’historial del repositori.

## Missió principal

1. Explora les branques disponibles.
2. Troba les pistes sense esborrar el treball d’altres branques.
3. Reconstrueix el codi secret.
4. Crea una branca pròpia `solucio-final`, escriu-hi la solució i fes un commit.

## Normes del joc

- No facis commits directament a `main`.
- No esborris cap branca.
- Llegeix les instruccions del professorat abans de començar.
- El codi secret és fictici i només forma part del joc.

## Comandes Git principals que es practiquen

Aquest projecte és una bona manera de familiaritzar-se amb les comandes bàsiques de Git:

```bash
git status
```

```bash
git branch
```

```bash
git checkout -b nom-branca
```

```bash
git switch nom-branca
```

```bash
git log --oneline
```

```bash
git add .
```

```bash
git commit -m "Descripció del canvi"
```

```bash
git pull
```

```bash
git push origin nom-branca
```

Aquestes comandes permeten practicar fluxos bàsics com:

- crear i canviar de branca,
- consultar l’estat del repositori,
- revisar l’historial de commits,
- guardar canvis de manera ordenada,
- i treballar amb un repositori compartit amb prudència.

## Aprenentatges de Git que permet practicar el projecte

Aquest exercici ajuda a comprendre i aplicar conceptes fonamentals del control de versions:

- Creació i ús de branques.
- Navegació entre versions diferents del projecte.
- Comprensió de l’historial de commits.
- Protecció del treball d’altres persones i evitació de sobrescriptura accidental.
- Pràctica de commits amb missatges clars i coherents.
- Organització del treball en un repositori de forma segura i ordenada.
- Foment de bons hàbits a l’hora de gestionar projectes col·laboratius.

## Com veure la web

Obre el fitxer `index.html` al navegador. També es pot utilitzar l’extensió Live Server de Visual Studio Code si ja la tens instal·lada, però no és necessària per a la visualització correcta del projecte.

## Resum

`El codi maleit` és un projecte educatiu que combina narrativa, misteri i pràctica real de Git. L’objectiu no és només resoldre el joc, sinó també aprendre a treballar de manera responsable amb el control de versions, protegint el repositori i mantenint una estructura clara i segura.

---

`El codi maleit` és un exercici de recerca, rigor i treball amb Git i GitHub dins d’un context de Halloween i enigmes.
