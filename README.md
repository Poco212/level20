# mobconf
blackbird netbook or laptop config


## prepare
### physical volume

### ecnrypt partition

### logical volume proc

#### proc root

#### proc opts

#### proc vars

#### proc libs

#### proc game

#### proc vlog

#### proc vaud

#### proc vtmp

#### proc vpac

#### proc ring

#### proc docs

### logical volume data

#### data home
```
```
### data pods
```
```


## configs
```
```
echo"
1. tambahkan user pengguna
2. tambahkan hostname
3. edit cmdline.d/01-boot sesuaikan dengan tipe udev / systemd
3. tambahkan UUID disk data kedalam file /etc/crypttab
4. edit file /etc/systemd/network/20-ethernet untuk mengganti ip address
5. 'nvim /etc/passwd' ganti line user game dibawah no body dan shell dari bash menjadi nologin
99. Jalankan perintah 'aide --init'
100. jalan perintah 'mv /var/lib/aide/aide.db.new.gz /var/lib/aide/aide.db.gz'
"
