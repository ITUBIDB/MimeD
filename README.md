# MimeD
MimeD is a decoder for mime encoded mail headers


# Build MimeD
g++ mime_decoder.cpp -o MimeD

# Pre-Requests for MimeD
There is no pre-request for building MimeD except standart C++ Libs which comes with gcc version 4.8.5

# Usage
[MAIL_FILE] Mail file location
[MAIL_FILE] For getting output mail file must put to standard input

[HEADER] is the header that you want to decode
[HEADER] have to type as one letter PASCAL CASE (Subject, To, Cc, From etc.)

Example:
[root@test mail] cat /var/spool/mail/a_user/mail_file | MimeD -h Subject
[root@test mail] "This is a test mail subject";




