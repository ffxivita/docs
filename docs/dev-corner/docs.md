# FFXIVITA Docs

 [:fontawesome-brands-github:{: .github } -  **Progetto FFXIVITA Docs -  GitHub**](https://github.com/ffxivita/docs){target=new .md-button}

## Background

FFXIVITA Docs cerca di dare tutte le informazioni necessarie per un corretto uso e sviluppo di tutti i progetti che FFXIVITA Ha da offire.

Per questo proponianmo la documentazione per i nostri pòugin e anche per contribuire al loro sviluppo.

Applichiamo i più alti standard anche nello scrivere la documentazione in modo che sia di facile lettura e comprensione. Inoltre ogni singolo step è controllato da sviluppatori certificati in modo da tenere i più alti standard.

## Come contribuire

### Contatta lo staff di FFXIVITA
In caso di domande, suggerimenti o se vuoi contribuire al progetto docs, ti preghiamo di contattarci su Discord.
[:fontawesome-brands-discord:{: .discord } - **Discord**](https://discord.gg/ffxivita){target=new}


### Tool Richiesti
Per partecipare al progetto docs, devi avere i seguenti tool installati:

- Account GitHub e Git ([Quickstart](https://docs.github.com/en/get-started/quickstart){target=new})
- Python ([Python Downloads](https://www.python.org/downloads/){target=new})
- Installa i seguenti pacchetti Python (vedi lista comandi sottostante):
  - MkDocs ([MkDocs](https://www.mkdocs.org/){target=new})
    - mkdocs-awesome-pages-plugin
    - mkdocs-git-revision-date-localized-plugin
    - mkdocs-redirects
    - mkdocs-embed-external-markdown
    - mkdocs-video
    - mike
    - pillow
    - cairosvg
- Installa tutto con un singolo comando:

    ```title="Esegui nel Terminal"
    pip install -r requirements.txt
    ```
!!! info "Pillow + Cairo"
    Come parte di un nuovo metodo di condivisione social rilasciato con `mkdocs-material 8.5.0` [Pillow](https://pillow.readthedocs.io/) e [Cairo Graphics](https://www.cairographics.org/) 
    sono stati aggiunti come dipendenze. Noi le mettiamo assieme come bundle dentro al nostro `requirements.txt` per assicurarsi di avere le dipendenze installate mentre si vuole provare localmente le [social cards](#social-cards-feature).

- Editor / IDE:
    - Raccomandato: [Microsoft Visual Studio Code](https://code.visualstudio.com/docs#vscode){target=new}
        - plugin raccomandati per lavorare col  Markdown:
            - qualsiasi plugin per il markdown - e.g. [https://github.com/yzhang-gh/vscode-markdown](https://github.com/yzhang-gh/vscode-markdown)
            - specifico per le tabelle: [https://github.com/takumisoft68/vscode-markdown-table](https://github.com/takumisoft68/vscode-markdown-table)
    - O qualunque [JetBrains](https://www.jetbrains.com/) IDE, e.g. IntelliJ IDEA o PyCharm.

#### Social Cards

!!! danger "Informazioni Importanti"
    Per l'uso generale, non c'è bisogno per te di utilizzare questa feature localmente almeno che non si voglia cambiare delle impostazioni relative a questa feature.

#### Fare cambiamenti o aggiunte alla Documentazione
- Crea un nuovo branch basato sul branch "main" e dagli un nome corto e significativo.
- Fai le tue modifiche sul tuo branch
- Apri una pull Request
- Aspetta un feedback da parte nostra e un merge