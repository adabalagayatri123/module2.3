# module2.3
&lt;!DOCTYPE html&gt;
&lt;html&gt;
&lt;head&gt;
&lt;/head&gt;
&lt;body style = &quot;text-align: center; font-size: 20px;&quot;&gt;
&lt;h1&gt; Online seats reservation &lt;/h1&gt;
Enter the number of seats: &lt;input id = &quot;number&quot;&gt;
&lt;br&gt;&lt;br&gt;
&lt;button onclick = &quot;m()&quot;&gt;Pay only&lt;/button&gt;
&lt;p id = &quot;res&quot;&gt;&lt;/p&gt;
&lt;script&gt;
function ticket(num)
{
actual=num*150;
discount=(actual/10); afterdisc=actual-discount; return afterdisc
}
function m()
{
var num = document.getElementById(&quot;number&quot;).value;
var f = ticket(num);
document.getElementById(&quot;res&quot;).innerHTML=&quot;The total price is &quot; + num + &quot;
is: &quot; + f ;
}
&lt;/script&gt;
&lt;/body&gt;
&lt;/html&gt;
