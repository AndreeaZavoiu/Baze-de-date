# Baze-de-date

:heavy_check_mark: BD: Anul 1, Sem 2

:heavy_check_mark: SGBD: Anul 2, Sem 1




Proiect - FMI, Unibuc, SGBD, Anul 2, Semestrul 1 :

Am creat conexiunea la baza de date cu ajutorul platformei Oracle Cloud (https://idcs-ac99522eb5dc48668d1054ab9b09cafc.identity.oraclecloud.com/ui/v1/signin), unde mi-am creat cont folosind adresa institutionala. Am conceput baza de date autonoma:

Create administrator credentials -> Username: admin, parola care va fi folosita la realizarea conexiunii;
Secure access from everywhere;
License Included; si am descarcat wallet-ul pentru a-l folosi la conexiunea din mediul de dezvoltare SQL Developer, cu care lucram la curs si laborator. In SQL Developer -> New Connection => am setat Numele conexiunii, Database Type Oracle, la User Info: Username admin, Parola, la Connection Type: Cloud Wallet, la Configuration File am incarcat zip-ul cu wallet-ul.
La reluarea lucrului in conexiune, daca apare eroarea "Listener refused the connextion with the following error: ORA-12514, TNS: listener does not currently know of service requested in connect descriptor", atunci baza de date autonoma trebuie repornita din Oracle Cloud, adica modificat state-ul din 'stopped' in 'start' -> https://docs.oracle.com/en/cloud/paas/autonomous-database/adbsa/autonomous-start.html#GUID-01A11B85-D5F7-49FB-95E6-BA77ACC33009 .
