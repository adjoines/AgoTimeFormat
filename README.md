# AgoTimeFormat
simplemvcframework AgoTimeFormat for updates (e. g 1 day ago).

If you want your time to use the ago time format:

save the AgoTimeFormat.php to the Helper folder. 

To use it:-

<?php $time_added = \Helpers\AgoTimeFormat::convert_datetime( $notifies['date_time']); ?>
// $notifies['date_time'] some sql datebase time
<?php  echo $converted_time = \Helpers\AgoTimeFormat::makeAgo($time_added); ?>

Done!
