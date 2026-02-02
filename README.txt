Bernio svět – PWA rozcestník

Co to je:
- Jedna instalovatelná PWA, ve které máš seznam všech svých aplikací.
- Klik na "Otevřít ..." otevře aplikaci uvnitř Bernio světa (iframe) + nahoře je tlačítko Menu.

Důležité omezení:
- Service Worker v této složce umí offline jen rozcestník (index.html + ikony).
- Neřídí offline ostatních aplikací, protože ty jsou v jiných složkách (mimo scope).

Nasazení:
1) V repu vytvoř složku např. /bernio-svet/
2) Nahraj do ní obsah ZIPu.
3) Otevři https://berniocal.github.io/bernio-svet/
4) Instaluj jako PWA.

Tip:
- Pokud chceš, aby se odkazy otevřely mimo viewer (jako dřív), v index.html vrať target="_blank"
  nebo přidej pod odkazy druhé tlačítko "Otevřít v nové kartě".
