# asm-example
<strong>Esempi in Assembler (NASM e MinGW)</strong>
<br>
<br>
(c) 09/2016 - Raffaele Ficcadenti (raffaele.ficcadenti@gmail.com) <br>
Ho cercato di raccogliere in questo repository, piccoli esempi di programmazione assempler (win/linux)
Per ogni correzione o suggerimento, non esitate a scrivermi.<br>
Se volete provare ogni singolo esempio andate sul mio sito <a href="http://www.raffaeleficcadenti.it/">www.raffaeleficcadenti.it</a> nella sezione: <a href="https://www.raffaeleficcadenti.it">i miei sviluppi/Corso Assembler</a>.<br>
Buon 'coding'.
Raffaele.
<p>
  <b>Prima di partire</b><br><br>
  Per gli esempi riportati di seguito, potete usare il compilateore NASM per il codice assemble, che trovate al <a href="http://www.nasm.us/">www.nasm.us</a><br><br>
  E il compilatore gcc per passare dal'obj all'eseguibile. Potete usare <a href="http://www.mingw.org/">MinGW</a>.
  <br><br>
  Dovete aggiungere alla variabile ambientale PATH le directory [path_installazione]\NASM;[path_installazione]\MinGW\bin
</p>
<ul>
  <li>
    <b>CiaoMondo</b>: 
    <p>
      Come suggerisce il nome, il primo 'ciao mondo' in asm.<br>
       - nasm -fwin32 ciaomondo.asm<br>
       - gcc ciaomondo.obj -o ciaomondo<br>
       - ./ciaomondo<br>
    </p>
  </li>
  <br>
</ul>

