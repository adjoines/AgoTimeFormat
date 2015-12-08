# AgoTimeFormat
simplemvcframework AgoTimeFormat for updates (e. g 1 day ago).

If you want your time to use the ago time format:

save the AgoTimeFormat.php to the Helper folder. 

To use it:-

Create an Alias:

````
use Helpers\AgoTimeFormat;
````

Usage:

````
$time_added = AgoTimeFormat::convert_datetime($notifies['date_time']); 
// $notifies['date_time'] holds datebase time
echo $converted_time = AgoTimeFormat::makeAgo($time_added);
````

Done!
