# nikky



curl_setopt($ch, CURLOPT_SSL_VERIFYHOST, false);
    curl_setopt($ch, CURLOPT_SSL_VERIFYPEER, false);


php_value session.cookie_httponly 1
 php_value session.cookie_secure 1


header("X-XSS-Protection: 1; mode=block");
