Örnek kullanım için adım adım yapılması gerekenler. (t değişkeni bağımsız terminalleri ifade etmek için kullanılmıştır)

t1/ turtle1 sim'i çalıştır<br>
<pre>
ros2 run turtle1sim turtle1sim_node
</pre>

t2/ kontrol etmek için terminali hazırla<br>
<pre>
ros2 run turtle1sim turtle1_teleop_key
</pre>

t3/ kaydedilebilecek başlıkları görüntüler<br>
<pre>
ros2 topic list
</pre>

t4/ kaydedilecek başlığı görüntüler<br>
<pre>
ros2 topic echo /turtle1/cmd_vel
</pre> 

t3/ kayıt komutu çalıştırılır. durdurmak için ctrl+c<br>
<pre>
ros2 bag record -o /home/code24/Downloads/newBag /turtle1/cmd_vel
</pre>

t3/ kayıt hakkında detayları gösterir<br>
<pre>
ros2 bag info /home/code24/Downloads/newBag 
</pre>

t3/ kaydı tekrar oynatır<br>
<pre>
ros2 bag play /home/code24/Downloads/newBag 
</pre>