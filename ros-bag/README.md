Örnek kullanım için adım adım yapılması gerekenler. (t değişkeni bağımsız terminalleri ifade etmek için kullanılmıştır)

t1/ turtle sim'i çalıştır<br>
<pre>
ros2 run turtlesim turtlesim_node
</pre>

t2/ kontrol etmek için terminali hazırla<br>
<pre>
ros2 run turtlesim turtle_teleop_key
</pre>

t3/ kaydedilebilecek başlıkları görüntüler<br>
<pre>
ros2 topic list
</pre>

t4/ kaydedilecek başlığı görüntüler<br>
<pre>
ros2 topic echo <topic_name>
ros2 topic echo /turtle/cmd_vel
</pre> 

t3/ kayıt komutu çalıştırılır<br>
<pre>

</pre>