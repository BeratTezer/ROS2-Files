Örnek kullanım için adım adım yapılması gerekenler. (t değişkeni bağımsız terminalleri ifade etmek için kullanılmıştır)

t1/ turtle sim'i çalıştır<br>
<code>ros2 run turtlesim turtlesim_node<code>

t2/ kontrol etmek için terminali hazırla<br>
<code>ros2 run turtlesim turtle_teleop_key<code>

t3/ kaydedilebilecek başlıkları görüntüler<br>
<code>ros2 topic list<code>

t4/ kaydedilecek başlığı görüntüler<br>
<code>ros2 topic echo /turtle/cmd_vel<code> 


t3/ kayıt komutu çalıştırılır<br>