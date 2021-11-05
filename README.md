# Linux_wk
Linux description 


NVME SSD + HMB Buffer on Linux/Windows
Many NVME SSDs use RAM for the Host Memory Buffer (HMB),
requiring a volume of 0.1% of its size (for example, 2048 MB for a 2TB SSD),
but WINDOWS 10+ limits HMB to 64 MB, cutting down the performance of large SSDs.
LINUX has a default limit of 128 MB and, if necessary, increases to 4 GB,
ensuring the performance of NVME HMB SSD is not worse inside the buffer.



идея tails, но их заваруха с приватностью и Тором просто отбивает им пользоваться(максимально лёгкий Дебиан) дистрибутив
Из легковесных - Slax, Porteus, MX Linux. Да любой вообще, главное чтобы
 поддерживал persistent-раздел. Но флешка от постянной записи охуеет и 
сдохнет через полгода.
