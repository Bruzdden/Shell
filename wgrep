#!/bin/bash
email = "[a-zA-Z0-9._-]+@[a-zA-Z0-9._-]+\.[a-zA-Z0-9._-]+)"
phone = "(([0-9]){3})\s([0-9]{3})\s[0-9]{3})"
url = "(https|http):\/\/([w_-]+(?:(?:\.[w_-]+)+))([\w.,@?=%&:\/~+#-]*[\w@?=%&\/>
case $3 in 
        url)
                wget -O iml.html $1
                grep -o -P $url iml.html > $2
                ;;
        phone)
                wget -O iml.html $1
                grep -o -P $phone iml.html > $2
                ;;
        email)
                wget -O iml.html $1
                grep -o -P  $email iml.html > $2
                ;;
        *)
                echo vubec
                ;; 
esac





