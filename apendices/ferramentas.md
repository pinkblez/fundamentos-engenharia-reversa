# Ferramentas

Esta seção aborda não somente ferramentas utilizadas no livro, mas também outras que vale a pena citar na esperança que o leitor se sinta atraído a baixar, usar e tirar suas próprias conclusões em relação à eficiência delas.

## Editores hexadecimais

Este tipo de ferramenta é útil para editar arquivos binários em geral, não somente executáveis, _dumpar_ \(copiar\) conteúdo de trechos de arquivos, etc. Também é possível editar uma partição ou disco com bons editores hexadecimal a fim de recuperar arquivos, por exemplo.

| Nome | Licença | Descrição |
| :--- | :--- | :--- |
| [010 Editor](https://www.sweetscape.com/010editor/) | Shareware | Multiplataforma, bastante usado. |
| [GNU poke](http://jemarch.net/poke) | Livre | Editor REPL genérico (não só para executáveis), ainda em beta, mas muito interessante. Escrevemos um [artigo](https://www.mentebinaria.com.br/artigos/editando-execut%C3%A1veis-com-o-gnu-poke-parte-1-r49/) sobre. |
| [fhex](https://github.com/echo-devim/fhex) | Livre | Editor gráfico multiplataforma capaz de exibir o binário graficamente, além de suportar expressões regulares na busca.  |
| [Hex Workshop](http://www.hexworkshop.com/) | Comercial | Pago, somente para Windows, antigo, mas muito bem feito. |
| [HexFiend](http://ridiculousfish.com/hexfiend/) | Livre | Somente para macOS, com recursos legais como diff e data inspector. |
| [Hiew \(Hacker's View\)](http://www.hiew.ru/) | Comercial | Editor (e disassembler) muito poderoso, principalmente por conta de seeus módulos HEM. É muito usado por analistas de malware, mas é pago. |
| [HT Editor](http://hte.sourceforge.net/) | Livre | Interface gráfica baseada em texto, parecido com o Hiew. Feio, mas cumpre seu trabalho. |
| [HxD](https://mh-nexus.de/en/hxd/) | Freeware | Bem bom. Possui recursos extras como geração de hashes, suporte a abrir discos. |
| [Reverse Engineer's Hex Editor](https://github.com/solemnwarning/rehex) | Livre | Nova proposta de um editor especificamente para engenharia reversa. |
| [wxHexEditor](https://sourceforge.net/projects/wxhexeditor/) | Livre | Multiplataforma, recursos interessantes. |
| [XVI32](http://www.chmaas.handshake.de/delphi/freeware/xvi32/xvi32.htm) | Freeware | Sem muitos recursos, mas quebra um galho. |

## Analisadores de executáveis

| Nome | Licença | Descrição |
| :--- | :--- | :--- |
| [DIE \(Detect It Easy\)](http://ntinfo.biz/index.html) | Freeware | Detecta compilador, linker, packer e protectors em binários. Também edita os arquivos. |
| [DUMPBIN](https://docs.microsoft.com/en-us/cpp/build/reference/dumpbin-reference) | Freeware | Analisador de PE de linha de comando disponível no SDK do Visual Studio. |
| [Exeinfo PE](http://exeinfo.xn.pl/) | Freeware | Detecta compilador, packer, protectors e edita os arquivos, além de suportar vários plugins loucos. Tem versão VIP mediante doação. |
| [Malwoverview](https://github.com/alexandreborges/malwoverview) | Livre | Mais um nacional pra uma primeira impressão de arquivos suspeitos, URLs e domínios. Checa também APK's. :) |
| [objdump](https://www.gnu.org/software/binutils/) | Livre | Parte do GNU binutils, também analisa PE, além de ELF, a.out, etc. |
| [PE-Bear](https://hshrzd.wordpress.com/pe-bear/) | Freeware | Analisador gráfico \(Qt\) multiplataforma que também detecta packers/protectors. |
| [PEdump](http://pedump.me/) | Livre | Analisador online muito legal! |
| [pestudio](https://www.winitor.com) | Freeware | Analisador de PE padrão da indústria, com foco em malware. Tem versão Pro \(paga\). |
| [pev](http://pev.sourceforge.net) | Livre | Nosso 💚 toolkit de ferramentas de linha de comando para análise de PE. Artigo introdutório [aqui](https://www.mentebinaria.com.br/artigos/estude-bin%C3%A1rios-de-windows-com-o-novo-pev-r18/). |
| [readelf](https://www.gnu.org/software/binutils/) | Livre | Também parte do binutils, analisador de ELF. |
| [Stud\_PE](http://www.cgsoftlabs.ro/studpe.html) | Freeware | Analisador e editor com suporte a plugins, assinaturas do antigo PEiD, editor de recursos e mais. |

## Bibliotecas para _parsear_ executáveis

| Nome | Licença | Descrição |
| :--- | :--- | :--- |
| [BFD](https://ftp.gnu.org/pub/old-gnu/Manuals/bfd-2.9.1/html_chapter/bfd_1.html) | Livre | **B**inary **F**ile **D**escriptor é a biblioteca usada por programas como readpe e objdump. Tem suporte a muitos tipos de arquivos, incluindo PE e ELF, claro.|
| [libpe](https://github.com/merces/libpe) | Livre | Nossa 💚 biblioteca multipltaforma para _parsing_ de arquivos PE. |
| [libPeConv](https://github.com/hasherezade/libpeconv) | Livre | Biblioteca em C++ para PE usada pelo PE-Bear. |
| [pefile](https://github.com/erocarrera/pefile) | Livre | Famosa biblioteca em Python pra fazer qualquer coisa com arquivos PE. |
| [PeNet](https://github.com/secana/PeNet) | Livre | Biblioteca em .Net para PE. |
| [PeParser](https://github.com/dorkbox/PeParser) | Livre | Biblioteca em Java para PE. |
| [pyelftools](https://github.com/eliben/pyelftools) | Livre | Biblioteca em Python para _parsear_ binários ELF. |

## Assemblers

| Nome | Licença | Descrição |
| :--- | :--- | :--- |
| [flat assembler \(FASM\)](https://flatassembler.net/) | Livre | Assembler bem recente que já vem com vários exemplos de código. Windows e Linux. |
| [GNU Assembler \(GAS\)](https://sourceware.org/binutils/docs/as/) | Livre | Também chamado simplesmente de **as**, é o assembler do projeto GNU e provavelmente já está instalado no seu Linux! ;) |
| [Microsoft Macro Assembler \(MASM\)](https://docs.microsoft.com/en-us/cpp/assembler/masm/microsoft-macro-assembler-reference) | Freeware | Atualmente já vem com o Visual Studio da Microsoft, mesmo na versão Community. Segue um [tutorial de como compilar um "Hello, world"](https://www.mentebinaria.com.br/forums/topic/146-hello-world-em-masm-no-windows/).|
| [Netwide Assembler \(NASM\)](https://www.nasm.us/) | Livre | Multiplataforma, suporte à sintaxe Intel e bem popular. Veja um [tutorial de como compilar um "Hello, world" no Linux](https://www.mentebinaria.com.br/forums/topic/51-%E2%80%9Chello-world%E2%80%9D-em-nasm-no-linux-x86/).|
| [Yasm Modular Assembler \(YASM\)](https://yasm.tortall.net/) | Livre | Multiplataforma, escrito com base no NASM pra ser um substituto mas acho que não vingou. hehe |

## Disassemblers

| Nome | Licença | Descrição |
| :--- | :--- | :--- |
| [Binary Ninja](https://binary.ninja) | Comercial | Novo disassembler que teoricamente compete com o IDA. Possui versão [online gratuita](https://cloud.binary.ninja/) mediante registro. |
| [Ghidra](https://ghidra-sre.org) | Livre | Disassembler livre lançado pela NSA. Temos um [treinamento](https://www.mentebinaria.com.br/treinamentos/curso-de-ghidra-r9/) em vídeo sobre ele. |
| [Hopper](https://www.hopperapp.com) | Comercial | Disassembler com foco em binários de Linux e macOS. |
| [IDA](https://www.hex-rays.com/products/ida/) | Comercial | Disassembler **interativo** padrão de mercado. Possui versão freeware. |

## Debuggers

| Nome | Licença | Descrição |
| :--- | :--- | :--- |
| [dnSpy](https://github.com/0xd4d/dnSpy) | Livre | Somente para .NET, descompila, debuga e (dis)assembla. |
| [edb \(Evan's Debugger\)](https://github.com/eteran/edb-debugger) | Livre | Debugger gráfico \(Qt\) com foco em binários ELF no Linux. |
| [GDB \(GNU Debugger\)](https://sourceware.org/gdb/) | Livre | Super conhecido debugger pra Linux do projeto GNU. Tem uma [versão não oficial pra Windows](http://www.equation.com/servlet/equation.cmd?fa=gdb) também. É modo texto, mas possui vários front-ends como [GDBFrontend](https://github.com/rohanrhu/gdb-frontend), dentre [outros](https://sourceware.org/gdb/wiki/GDB%20Front%20Ends). |
| [GEF](https://github.com/hugsy/gef) | Livre | O **G**DB **E**nhanced **F**eatures extende o GDB com recursos para engenharia reversa. |
| [OllyDbg](http://ollydbg.de) | Freeware | Poderoso debugger, apesar de não mais mantido. |
| [PEDA](https://github.com/longld/peda) | Livre | O **P**ython **E**xploit **D**evelopment **A**ssistance também extende o GDB, assim como o GEF. A interface é um pouco diferente, no entanto. |
| [WinDbg](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/debugger-download-tools) | Freeware | Debugger ring0/3, parte integrante do SDK do Windows. |
| [x64dbg](https://x64dbg.com/) | Livre | Debugger user-mode para Windows com suporte a 32 e 64-bits. |

## Descompiladores

| Nome | Licença | Descrição |
| :--- | :--- | :--- |
| [IDR \(Interactive Delphi Reconstructor\)](https://github.com/crypto2011/IDR) | Livre | Para binários compilados em Delphi. |
| [ILSpy](https://github.com/icsharpcode/ILSpy) | Livre | Descompilador multiplataforma para .NET. |
| [JD-GUI](https://github.com/java-decompiler/jd-gui) | Livre | Descompilador para Java com GUI. |
| [RetDec \(Retargetable Decompiler\)](https://retdec.com/) | Livre | Descompilador para C/C++ feito pelo time do Avast. Inclui detector de compilador e packer, plugins para IDA e radare2. |
| [Snowman](https://derevenets.com/) | Livre | Descompilador livre para C/C++. Pode ser usado como plugin no IDA, x64dbg, etc. |
| [VB Decompiler](https://www.vb-decompiler.org/) | Comercial | Descompilador para VB5/6 e disassembler para VB .NET. |

## Frameworks

| Nome | Licença | Descrição |
| :--- | :--- | :--- |
| [angr](https://angr.io) | Livre | Framework para análise estática e simbólica de binários. |
| [Frida](https://www.frida.re) | Livre | Framework para instrumentação dinâmica de binários. |
| [Radare](https://rada.re/r/) | Livre | Suíte completa com debugger, disassembler e outras ferramentas para quase todo tipo de binário existente! |

## Visualizadores hexadecimais

| Nome | Licença | Descrição |
| :--- | :--- | :--- |
| [hdump](https://sourceforge.net/projects/hdump/) | Livre | Clone nosso 💚, multiplataforma \(funciona no Windows!\) do hexdump que imita a saída do **hd**. |
| [heksa](https://github.com/raspi/heksa) | Livre | Multiplataforma, com saída colorida e recursos interessantes como seek negativo \(a partir do fim do arquivo\). |
| hexdump/hd | Livre | Padrão no BSD e Linux. Se chamado por "hd" exibe saída em hexa/ASCII. |
| od | Livre | Padrão no UNIX e Linux. O comando **od -tx1** produz uma saída similar à do **hd**. |
| xxd | Livre | Vem com o vim. Uma saída similar à do **hd** é obtida com **xdd -g1**. |

Abaixo um comparativo onde dumpamos os primeiros 32 bytes do binário /bin/ls utilizando os visualizadores acima:

```text
$ hdump -n 32 /bin/ls
00000000  7f 45 4c 46 01 01 01 00  00 00 00 00 00 00 00 00  |.ELF............|
00000010  03 00 28 00 01 00 00 00  21 3e 00 00 34 00 00 00  |..(.....!>..4...|

$ heksa -l 32 /bin/ls
00000┊7f 45 4c 46 01 01 01 00  00 00 00 00 00 00 00 00┊.ELF...Ø ØØØØØØØØ
00010┊03 00 28 00 01 00 00 00  21 3e 00 00 34 00 00 00┊.Ø(Ø.ØØØ !>ØØ4ØØØ

$ hd -n32 /bin/ls
00000000  7f 45 4c 46 01 01 01 00  00 00 00 00 00 00 00 00  |.ELF............|
00000010  03 00 28 00 01 00 00 00  21 3e 00 00 34 00 00 00  |..(.....!>..4...|
00000020

$ od -tx1 -N /bin/ls
0000000    7f  45  4c  46  01  01  01  00  00  00  00  00  00  00  00  00
0000020    03  00  28  00  01  00  00  00  21  3e  00  00  34  00  00  00
0000040

$ xxd -g1 -l32 /bin/ls
00000000: 7f 45 4c 46 01 01 01 00 00 00 00 00 00 00 00 00  .ELF............
00000010: 03 00 28 00 01 00 00 00 21 3e 00 00 34 00 00 00  ..(.....!>..4...
```
