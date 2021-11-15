# TempEmailDomainMXRecords
A CSV of temporary email domains with their associated MX Records, in the format


| Domain  | MX Record | IP |
| ------------- | ------------- | ---- |
|tempemail.biz|mx001.tempemail.biz|78.46.205.76|
|tempemail.co.za|park-mx.above.com|103.224.212.34|
|tempmail.de|tempmail.de|85.25.13.241|
|temp-mail.de|tempmail.de|85.25.13.241|
|temp-mail.org|mx.yandex.net|77.88.21.249|
|temp-mail.ru|mx.yandex.net|77.88.21.249|
|tempmaildemo.com|mxlb.ispgateway.de|80.67.18.126|
|tempmailer.com|tempmailer.com|91.250.86.53|
|tempmailer.de|tempmailer.de|91.250.86.53|
|temporarymailaddress.com|temporarymailaddress.com|37.97.167.105|

Where Domain is a domain name associated with a temporary email address such as 
abc123@tempemail.biz the MX record is a Mail-exchange server associated with that domain, 
and the IP is the IP of the Mail-exchange server. 

Blocking user registrations if temporary email addresses are used can be risky, you can
end up blocking a legitimate user. 

If you block emails using the domain listed in the domain
column, then it is very likely the email is temporary, but fresh "disposable" domains will not
be discovered. 

If you block emails using a domain that uses the same mail exchanger as the mx-record listed
in the "MX column" then this is highly risky, since many legitimate russian users use "mx.yandex.net", 
(yandex being the russian equivalent of Google). However patterns of dispostable emails can be discovered
and blocked on a case by case basis. 

This is an open-source list and we do invite users to contribute by raising pull requests.
Please give credit to our work, if you use it.  https://www.infiniteloop.ie/
