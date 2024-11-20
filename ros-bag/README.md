Örnek kullanım için adım adım yapılması gerekenler. (t değişkeni bağımsız terminalleri ifade etmek için kullanılmıştır)

t1/ turtle sim'i çalıştır
```ros2 run turtlesim turtlesim_node```

t2/ kontrol etmek için terminali hazırla
```ros2 run turtlesim turtle_teleop_key```

t3/ kaydedilebilecek başlıkları görüntüler
```ros2 topic list```

t4/ kaydedilecek başlığı görüntüler
```ros2 topic echo /turtle/cmd_vel``` 

t3/ kayıt komutu 