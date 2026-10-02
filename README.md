Esse é o link da página do GIF, não o arquivo .gif direto. Para o README, pode deixar o link como destino, mas o src precisa ser a mídia.

Se você quer simplesmente colocar o GIF do Tenor no lugar do coelho, use o embed oficial assim:

<div class="tenor-gif-embed"
     data-postid="9280350723013648355"
     data-share-method="host"
     data-aspect-ratio="1"
     data-width="180%">
  <a href="https://tenor.com/view/i-drive-gif-9280350723013648355">
    I Drive GIF
  </a>
</div>
<script type="text/javascript" async src="https://tenor.com/embed.js"></script>

Mas: o GitHub README provavelmente não executará esse <script>, então o embed pode aparecer quebrado. Para GitHub, o ideal é pegar o link direto do GIF ou baixar o GIF e colocar no próprio repositório.

https://media1.tenor.com/m/gMpt0CxEn-MAAAAd/i-drive.gif

Aí sim. Esse é o link direto do GIF. Cola essa parte:

<div align="center">

<table>
<tr>
<td valign="middle">

<a href="https://tenor.com/view/i-drive-gif-9280350723013648355">
<img src="https://media1.tenor.com/m/gMpt0CxEn-MAAAAd/i-drive.gif" width="180">
</a>

</td>
<td valign="middle">

<pre>
cancel@only
---------------------------
self:     fullstack / guitarrist
os:       cachyOS
wm:       kde plasma + nyx shell
editor:   vscodium
</pre>

</td>
</tr>
</table>

</div>
<div align="center">


▄█▄  ▄    ▄▄▄        █▄ ▄        ▄█▄  ▄   ▓ ▄▄██   ██▓    
▓ █▀ ▀█   ▒▄▀ █▄      ██ ▀█   █  ▓ █▀ ▀█   ▓█   ▀  ▓██▒    
▒▓█    ▄  ▒██  ▀█▄   ▓██  ▀█ ██▒ ▒▓█    ▄  ▒█ █    ▒██░    
▒▒▒▄ ▄  ▒ ░▄█▄▄▄▄██  ▓██▒  ▐ ██▒ ▒▒▒▄ ▄  ▒ ▒▓█  ▄  ▒█ ░    
▒ ▒   ▀ ░  ▓█   ▓██▒ ▒██░   ▓██░ ▒ ▒   ▀ ░ ░▒████▒ ░▄█████▒
░ ░▒ ▓  ░  ▒▒   ▓▒█░ ░ ▒░   ▒ ▓  ░ ░▒ ▓  ░ ░░ ▒░ ░ ░ ▒░▓  ░
  ░  ▒      ▒   ▒▒ ░ ░ ░░   ░ ▒░   ░  ▒     ░ ░  ░ ░ ░ ▒  ░
░           ░   ▒       ░   ░ ░  ░            ░      ░ ░   
░ ░             ░  ░          ░  ░ ░          ░  ░     ░  ░
░                                ░


[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=14&pause=1000&color=F7F7F7&center=true&vCenter=true&width=520&lines=linux+enjoyer;see+you+space+cowboy)](https://git.io/typing-svg)
</div>

---

<div align="center">

<table>
<tr>
<td valign="middle">

<a href="https://tenor.com/view/i-drive-gif-9280350723013648355">
<img src="https://media1.tenor.com/m/gMpt0CxEn-MAAAAd/i-drive.gif" width="180">
</a>

</td>
<td valign="middle">

<pre>
cancel@only
---------------------------
self:     fullstack / guitarrist
os:       cachyOS
wm:       kde plasma + nyx shell
editor:   vscodium
</pre>

</td>
</tr>
</table>

</div>
---

**Languages**

![JavaScript](https://ziadoua.github.io/m3-Markdown-Badges/badges/Javascript/javascript2.svg)
![Shell](https://ziadoua.github.io/m3-Markdown-Badges/badges/Shell/shell2.svg)
![Python](https://ziadoua.github.io/m3-Markdown-Badges/badges/Python/python3.svg)

---

**Tools**

![After Effects](https://ziadoua.github.io/m3-Markdown-Badges/badges/AfterEffects/aftereffects1.svg)
![Git](https://ziadoua.github.io/m3-Markdown-Badges/badges/Git/git1.svg)
![Raspberry Pi](https://ziadoua.github.io/m3-Markdown-Badges/badges/RaspberryPI/raspberrypi1.svg)

---

**OS**

![Kali Linux](https://ziadoua.github.io/m3-Markdown-Badges/badges/KaliLinux/kalilinux1.svg)
![Arch Linux](https://ziadoua.github.io/m3-Markdown-Badges/badges/Arch/arch1.svg)

---

### "In this day and age, ignorance is a choice, and people are still choosing ignorance.
Now retardation comes in all shapes and sizes on the internet..." - Francis of the Filth
    

</div>


Ficou bem mais coerente. Só tem um detalhe de HTML/Markdown: você fechou o <div> do GIF antes do ---, então aquele </div> final lá embaixo fica sobrando e pode causar comportamento estranho no GitHub.

Se a intenção é manter exatamente esse layout, eu deixaria assim:

GitHub Profile README

<div align="center">

 ▄█▄  ▄    ▄▄▄        █▄ ▄        ▄█▄  ▄   ▓ ▄▄██   ██▓    
▓ █▀ ▀█   ▒▄▀ █▄      ██ ▀█   █  ▓ █▀ ▀█   ▓█   ▀  ▓██▒    
▒▓█    ▄  ▒██  ▀█▄   ▓██  ▀█ ██▒ ▒▓█    ▄  ▒█ █    ▒██░    
▒▒▒▄ ▄  ▒ ░▄█▄▄▄▄██  ▓██▒  ▐ ██▒ ▒▒▒▄ ▄  ▒ ▒▓█  ▄  ▒█ ░    
▒ ▒   ▀ ░  ▓█   ▓██▒ ▒██░   ▓██░ ▒ ▒   ▀ ░ ░▒████▒ ░▄█████▒
░ ░▒ ▓  ░  ▒▒   ▓▒█░ ░ ▒░   ▒ ▓  ░ ░▒ ▓  ░ ░░ ▒░ ░ ░ ▒░▓  ░
  ░  ▒      ▒   ▒▒ ░ ░ ░░   ░ ▒░   ░  ▒     ░ ░  ░ ░ ░ ▒  ░
░           ░   ▒       ░   ░ ░  ░            ░      ░ ░   
░ ░             ░  ░          ░  ░ ░          ░  ░     ░  ░
░                                ░                         




</div>

<div align="center">

<table> <tr> <td valign="middle">

<a href="https://tenor.com/view/i-drive-gif-9280350723013648355"> <img src="https://media1.tenor.com/m/gMpt0CxEn-MAAAAd/i-drive.gif" width="180"> </a>

</td> <td valign="middle">

<pre> cancel@only --------------------------- self: fullstack / guitarrist os: cachyOS wm: kde plasma + nyx shell editor: vscodium </pre>

</td> </tr> </table>

</div>

Languages






Tools






OS





"In this day and age, ignorance is a choice, and people are still choosing ignorance.

Now retardation comes in all shapes and sizes on the internet..." - Francis of the Filth

Assim fica um </div> para cada <div> aberto, sem alterar o visual que você montou.
