# Create multiple Files

-   `{ , }` erzeugt `File1.txt`, `File2.txt` und `File3.txt`:

        touch File{1,2,3}.txt

-   `{ .. }` erzeugt einen Bereich

        touch file{1..9}.txt
        ls file{1..9}.txt


-   Auch Verschachtelungen sind möglich:

        touch file{orginal{.bak,.txt},kopie{.bak,.txt}}

    erzeugt `fileoriginal.txt`, `fileoriginal.bak`, `filekopie.txt` und
    `filekopie.bak`
