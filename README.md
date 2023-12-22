***getting to know some WIN viruses***

## **WinNT. Explorador remoto**
Descoberto em 17 de dezembro de 1998, o Remote Explorer foi o primeiro vírus a se carregar como um serviço do Windows NT e o primeiro a roubar os direitos de segurança de um administrador para se espalhar . Acredita-se que tenha sido libertado por um funcionário descontente, o Remote Explorer atacou a rede global da MCI WorldCom.

## **WinNT.Infis**
WinNT.Infis é um vírus residente na memória que chegou 10 meses depois na forma de um executável infectado. Ele se carrega como umkernel mode driver chamado INF.SYS . Isso significa que ele é carregado sempre que o Windows é iniciado e tem permissões de segurança de arquivo superiores ao normal. Usando este novo método de infecção, ele pode acessar arquivos mesmo que o usuário conectado não tenha direitos para manipular o código. Outros arquivos executáveis ​​são infectados quando abertos. Usando várias APIs NT/2000 não documentadas,O Infis ignora o subsistema Win32 para funcionar exclusivamente no Windows NT 4.0 e no Windows 2000. O que é importante no Infis é que ele acessa o modo kernel do NT e, portanto, tem acesso direto a portas e hardware fora do controle do Windows NT. Felizmente, escrito como um vírus de prova de conceito, ele não possui carga útil de danos. Poderia, se quisesse, formatar o disco rígido, excluir arquivos ou interagir com o hardware do computador.
## **Win95.CIH**
criado como protesto por um estudante universitário taiwanês contra empresas de antivírus, foi o primeiro a causar danos graves a computadores, muitas vezes resultando na substituição de hardware. Afetando milhões de PCs, especialmente na Coreia do Sul, o vírus infecta arquivos PE e se aloja em áreas não utilizadas do host. Embora possa estar presente em máquinas Windows NT, recusa-se a ser executado devido ao uso de chamadas do Windows 95. Em datas específicas, o CIH implementa sua carga perigosa, tentando substituir o código do firmware do BIOS em máquinas com Windows 9x. Isso pode resultar na incapacidade de inicialização do PC. Resolver o firmware corrompido geralmente requer a reescrita do código do BIOS, mas a dificuldade em obter software do firmware pode levar à substituição de chips BIOS ou até mesmo à compra de uma nova placa-mãe. Assim, o CIH ganha destaque como o primeiro vírus a causar a substituição de hardware, apesar de não causar danos físicos.
## **Win32.Kriz**
 O vírus Kriz infecta arquivos PE e tenta implementar uma carga semelhante ao CIH em 25 de dezembro, danificando o BIOS. Por usar o subsistema Win32, e não as APIs nativas do NT, só pode ter sucesso em plataformas 9x. Quando executado pela primeira vez, ele se copia para um arquivo chamado KRIZED.TT6 e então modifica ou cria um WININIT.INI arquivo para que este arquivo seja copiado KERNEL32.DLL na próxima reinicialização. Uma vez ativo, ele infecta vários outros executáveis ​​do Windows quando determinadas chamadas de API do Windows são feitas. Independentemente de conseguir ou não corromper o BIOS, ele começará a sobrescrever arquivos em todas as unidades mapeadas, unidades de disquete e discos RAM. Somente os melhores programas antivírus podem reparar arquivos PE infectados.
## **Win95.Babilônia**
O vírus Babilônia, criado em dezembro de 1999, disfarçava-se como um arquivo de Ajuda do Windows chamado SERIALZ.HLP, prometendo ser uma lista de números de série para software pirateado. No entanto, era um vírus que se espalhava por arquivos .HLP e .EXE, modificando seu ponto de entrada. O vírus se copiava para o diretório do sistema como KERNEL32.EXE, registrando-se para iniciar com o Windows.

Enquanto conectado à internet, o Babilônia tentava atualizar-se no site do criador no Japão. O vírus baixava e executava módulos adicionais, permitindo atualizações contínuas. Modificava o AUTOEXEC.BAT, tentava enviar cópias infectadas em canais de chat IRC, enviava e-mails ao criador sobre novas infecções e alterava o arquivo WSOCK32.DLL para anexar cópias a e-mails do usuário. Essas ações ocorriam em apenas 11 KB de código.









