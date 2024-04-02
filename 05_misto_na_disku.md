## Místo na disku

## V Shellu (Z grafického rozhraní)

1. Stiskněte klávesu `Windows (⊞)` + `T`.
2. Napište:
```bash
df -h
```
3. Stiskněte klávesu `ENTER`

Výstup příkazu `df -h` ukazuje informace o využití disku, přičemž `/dev/sda1` má velikost 19 GB, s 7.4 GB použitého a 11 GB volného místa.

```
pavel@debian:~$ df -h
Filesystem      Size  Used Avail Use% Mounted on
udev            479M     0  479M   0% /dev
tmpfs            99M   11M   88M  11% /run
/dev/sda1        19G  7.4G   11G  42% /
tmpfs           494M     0  494M   0% /dev/shm
tmpfs           5.0M     0  5.0M   0% /run/lock
tmpfs           494M     0  494M   0% /sys/fs/cgroup
tmpfs            99M     0   99M   0% /run/user/1000
```

## V Linuxu
Funknční návod pro čistou instalaci s MATE.
1. Klikněte na "Menu".
2. Do vyhledávacího pole zadejte "MATE Disk Usage Analyzer".
3. Stiskněte klávesu `ENTER`.
4. Vidíte souhrn disku, jejich kapacit a jejich využití.


## Ve Windows
Tento návod je pro Windows v čestině.
1. Stiskněte klávesu `Windows (⊞)` + `E`.
2. V levém panelu zvolte položku "Tento počítač".
3. V sekci "Zařízení a jednotky" vidíte jednotlivé disky s jejich kapacitou a volným místem.



