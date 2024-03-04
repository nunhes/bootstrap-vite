# Comezando con Vite

## i. Iniciar o proxecto

```bash
$ pnpm create vite

√ Project name: ... bootstrap-vite   // indicar nome do proxecto
√ Select a framework: » Vanilla      // elixir linguaxe de script ou framework
√ Select a variant: » JavaScript     // variante da linguaxe de script

Scaffolding project in C:\laragon\www\bootstrap-vite...

Done. Now run:

  cd bootstrap-vite
  pnpm install
  pnpm run dev

$ cd bootstrap-vite
$ pnpm install
$ pnpm run dev

> bootstrap-vite@0.0.0 dev C:\laragon\www\bootstrap-vite
> vite


  VITE v5.1.4  ready in 2254 ms

  ➜  Local:   http://localhost:5173/                // xa podes ver o resultado no navegador
  ➜  Network: use --host to expose
  ➜  press h + enter to show help
```

- **Recoméndase ** usar un SCV &rarr; **Github**

  - Aínda que a instalación con Vite nos proporcione un arquivo `.gitignore`, isto non quere dicir que esteamos a facer un seguimento do proxecto. Para isto debemos iniciar o seguimento do proxecto en Git:

    ```bash
    git init
    /* se tes habilitada a visión de arquivos ocultos no teu explorador de arquivos, agora poderás ver que no teu proxecto hai un novo cartafol `.git`
    aquí é onde se gardará o seguimento do noso proxecto. NON TOCAR! */
    ```

  - No teu editor de código VSCode poderás ver que no teu proxecto aparecen novas marcas en cada un dos arquivos do teu proxecto. Se queres saber cales van a ser tido en conta polo SCV tamén podes executar na consola o seguinte comando:

    ```bash
    git status
    /* se crees que algún dos arquivos citados non debe ser incluído no repositorio citao no arquivo `.gitignore` */
    ```

  - Aínda así, a mensaxe da terminal indicará que aínda non se está a facer seguimento efectivo de ningún arquivo:

    ```bash
    On branch master
    
    No commits yet
    
    Untracked files:
      (use "git add <file>..." to include in what will be committed)
            .gitignore
    ...
    
    nothing added to commit but untracked files present (use "git add" to track)
    ```

  - Comezar co seguimento dos arquivos ten dúas fases:

    - unha primeira na que se declaran ou engaden ao *stage* os arquivos dos que queremos facer seguimento - que se resolve co comando `git add .`[^1]- e
    - unha segunda na que declaramos o seguimento activo ou *commit* dos arquivos - que se resolve co comando `git commit -m "Envío inicial"` - recomendase engadir unha mensaxe descritiva a cada envío - ex.:` -m "Mensaxe que serva para rastrear os cambios"`-.
    
  - Como subir arquivos a un repositorio remoto:
  
  - **O comando `git log` permite ver o historial de *commit*s realizados dun repositorio e elixir aquel que queremos restaurar**.
  

## ii. Preparar a escena

- Analizar o bosquexo, wireframe ou proxecto gráfico &rarr; instantanea.www.aston.martin
- Seleccionar fonte(s) tipográfica(s)
  - p.ex.: Fontes variables de GoogleFonts
- Determinar a paleta de cores
  - xerar paleta desde foto!! &rarr; [coolors.co](https://coolors.co)

## iii. Comezar co marcado de contidos

- **html**:
  - Cabeceira(menú), pasafotos, slogan, pasafotos, vídeo, contido dúas columnas, sección de novas (listado+scroll lateral), pe de páxina

## iv. Encetar co estilo





## v. Engadir interacción



---
[^1]: volve  a executar agora `git status` ou `git status -s` e comproba os cambios.





**_.ref.:_**

- https://vitejs.dev/guide/

- https://www.youtube.com/watch?v=MplFP2TnvXg&list=RDCMUCWuyqD6Pm70GwjWtENF5XJA&index=3