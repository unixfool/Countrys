### FILE FORMAT
#### All lines beginning with either "" or whitespace are comments

IP FROM      IP TO        REGISTRY  ASSIGNED   CTRY CNTRY COUNTRY<br/>
"1346797568","1346801663","ripencc","20010601","IL","ISR","ISRAEL"

```
<?php
$two_letter_country_code=iptocountry("IP-HERE");

function iptocountry($ip) {   
    $numbers = preg_split( "/\./", $ip);   
    include("files/ip_files/".$numbers[0].".php");
    $code=($numbers[0] * 16777216) + ($numbers[1] * 65536) + ($numbers[2] * 256) + ($numbers[3]);   
    foreach($ranges as $key => $value){
        if($key<=$code){
            if($ranges[$key][0]>=$code){$country=$ranges[$key][1];break;}
            }
    }
    if ($country==""){$country="unkown";}
    return $country;
}
?>
```
