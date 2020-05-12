# COVID-19 API
To get covid19 data from worldmeters.info 


##### if you face problem with php execution time just add those line after
~~~
<?php   
~~~
After php tag
~~~
ini_set('max_execution_time', '300'); //300 seconds = 5 minutes
ini_set('max_execution_time', '0'); // for infinite time of execution 
~~~

##### if you want special country you can use the code below : This example to get (sudan) data
~~~
foreach($data['data'] as $item){
    if($item['country'] =="sudan"){
        echo json_encode($item);
    }
}
~~~ 

### DISCLAIMER
For Educational purposes only

### Data Source
https://www.worldometers.info/coronavirus/
