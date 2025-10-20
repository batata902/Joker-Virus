# JokerMemz ![](https://i.ibb.co/cS18Fn7L/malware-1.png)


Um vírus troll que imita o famoso trojan MEMZ. 

Ações: Altera o papel de parede Autorun, Cria e executa um arquivo .bat

100% em Python (FUNCIONA APENAS NO WINDOWS)

São dois arquivos: DerrubaNet2 e DerrubaNet2_MEMZinsp, o segundo é uma cópia do primeiro, porém com o efeito de pop-up bomb do memz.

Print do efeito MEMZ
----

![Screenshot](https://raw.githubusercontent.com/batata902/Joker-Virus/refs/heads/main/screenshot.png)

Efeito MEMZ de spam de POP-UP na tela


Uso
----

Se você deseja empacotar o arquivo.py no seu computador você pode usar:

    pyinstaller -w -F memzinspi.py

Caso não possua o PyInstaller instalado use:

    pip install pyinstaller

Esse "malware" não danifica o computador de quem o executa. Ele possui uma função de autorun, mas esta pode ser simplesmente apagada no código fonte. Não me responsabilizo por qualquer mal uso ou modificação maliciosa que venham a fazer neste software.
