využili jsme chyby /usr/bin, která byla writable 

find / -writable 2>/dev/null

UID je naše id
když spustíme nějaký program, tak se spustí s naším id :D

EUID 
když spustíme program, tak to spustíme jako my jako student, ale s právy správce (vše dočastně)

Jak byste jako administrátor zajistili systém, aby tento útok nebyl možný. 

zakázat writable na /usr/bin :D
