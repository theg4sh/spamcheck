# spamcheck
Automatically exported from code.google.com/p/spamcheck<br/>
<br/>
spam-check [-q] [-l] [-d dnsbl | -f filename | -i] [-s dns_server] [-t] \<br/>
           [--] [ip or domain-name ...]<br/>

   -q           - Ничего не выводить<br/>
   -l           - Показать список DNSBL-серверов<br/>
   -d           - Проверить по указанному DNSBL<br/>
   -f           - Взять список DNSBL-серверов из файла (по одному на строчку)<br/>
   -i           - Сграбить список DNSBL с сайта http://myiptest.com/<br/>
   -s           - Указать DNS-сервер, через который будет идти проверка <br/>
                  (по умолчанию OpenDNS - 208.67.222.222)<br/>
   -t           - Считать Time Out''ы ошибкой<br/>
   --           - Считается, что дальше идут только ip и/или доменные имена<br/>
   [ip or domain-name ...]      - ip и/или доменные имена, которые нужно проверить<br/>
   --vesrion, --help, --usage   - без комментариев<br/>
