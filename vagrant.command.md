尋找你要的vagrant box os
https://app.vagrantup.com/boxes/search




創一個資料夾
```
mkdir debian11
cd debian11
```

init 一個debian11 Vagrantfile
```
vagrant init debian/bullseye64
```
啟動
```
vagrant up
```



進入此vm
```
vagrant ssh
vagrant rdp
```


停止虛機
```
vagrant halt
```

暫停虛機
```
vagrant suspend
```

恢復虛機
```
vagrant resume
```

過載虛機
```
vagrant reload
```

刪除虛機
```
vagrant destroy
```

秀本地vagrant box list
```
vagrant box list
```
刪除box
```
vagrant box remove laravel/homestead --box-version=0.1.7 
```





編輯Vagrantfile
可設定預先執行shell安裝什麼東西
memory GB