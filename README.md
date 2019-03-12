# Curl


CURL is a library that allows you  to make a http request in php

1. Create a curl Resource
  Syntax: $curl = curl_init();
  
2. Set curl OPTIONS
  curl_setopt($curl, CURLOPT_URL, 'https://www.youtube.com/');
  
3. Run curl (execute http request)
  curl_exec($curl)
  
4. Close curl resource
  curl_close($curl);
