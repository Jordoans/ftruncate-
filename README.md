# ftruncate-
&lt;?php // Check filesize echo filesize("test.txt"); echo "&lt;br>";  $file = fopen("test.txt", "a+"); ftruncate($file,100); fclose($file);  // Clear cache and check filesize again clearstatcache(); echo filesize("test.txt"); ?>
