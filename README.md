## Uso do Reverse Shell

Fácil de usar:

1 - Identifique a linguagem de programação em execução no site.

2 - Substitua "LHOST" pelo seu endereço IP e "LPORT" pela porta que você pretende usar.

Para abrir uma porta em sua máquina, utilize o seguinte comando:
```bash
nc -nlvp (porta)
```

Normalmente, são usadas portas comuns, como:
```
80 (HTTP)
443 (HTTPS)
21 (FTP)
22 (SSH)
25 (SMTP)
3306 (MySQL)
5432 (PostgreSQL)
8080 (HTTP alternativo)
8443 (HTTPS alternativo)
```
Você pode adicionar outras portas conforme necessário.

Espero que isso ajude!
