# Vypařování vody

<p>Program řeší výpočet vypařování vody dle následujícího zadání:

<i>Určete množství tepla, které se musí dodat vodě, aby vznikla přehřátá pára. Pohybujte se pod kritickým bodem vody.</i> </p>

<p>Tento projekt byl realizován jako desktopová aplikace v Pythonu a je strukturován do dvou souborů: gui.py a main.py. Soubor gui.py tvoří grafické uživatelské rozhraní, které bylo vytvořeno pomocí nástroje Qt Designer (na bázi "drag-and-drop"). Soubor main.py zase zahrnuje celý výpočetní proces, přičemž využívá hodnot pro vodu a vodní páru z knihovny IAPWS, specificky z regionů 1 a 4 podle standardu IAPWS-97. Navíc aplikace nabízí funkci pro export výsledků do souboru ve formátu Excel.</p>

<p>Při zpětném pohledu je zřejmé, že primárním cílem při vývoji programu bylo zajistit jeho funkčnost, přičemž se věnovala malá pozornost jeho čitelnosti, rozšiřitelnosti a opakování kódu. Pro budoucí vylepšení by bylo vhodné aplikovat principy objektově orientovaného programování (OOP), což by přineslo lepší organizaci kódu, usnadnilo jeho škálování a zlepšilo testovatelnost. </p>

<p>Program vznikl jako součást mé bakalářské práce (odkaz <a href="https://www.vut.cz/studenti/zav-prace/detail/116680">zde</a>) jež měl ukázat využití Pythonu pro technické výpočty konkrétně z pohledu procesního inženýrství.
Další programy z této práce:</p>

<ul>
    <li><a href="https://github.com/JanKomis/vyparovani">Částečné vypařování</a></li>
    <li><a href="https://github.com/JanKomis/vypousteniNadrze">Tepelné ztráty</a></li>
    <li><a href="https://github.com/JanKomis/spalovaniJupyter">Spalování zemního plynu</a></li>
    <li><a href="https://github.com/JanKomis/vypousteniNadrze">Vypouštění nádrže</a></li>
</ul>

# Vytvořeno pomocí

<p align="left">
<a href="https://www.python.org" target="_blank" rel="noreferrer"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/800px-Python-logo-notext.svg.png" width="36" height="36" alt="Python" /></a>
<a href="https://jupyter.org" target="_blank" rel="noreferrer"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/38/Jupyter_logo.svg/640px-Jupyter_logo.svg.png" width="36" height="36" alt="Jupyter" /></a>
<a href="https://1url.cz/xuOL4" target="_blank" rel="noreferrer"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/73/Microsoft_Excel_2013-2019_logo.svg/2170px-Microsoft_Excel_2013-2019_logo.svg.png" width="36" height="36" alt="Excel" /></a>
</p>
