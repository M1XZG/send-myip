Send-MyIP
==========================

Raspberry Pi Script that sends out it's IP at boot time, helpful for DHCP conditions.


	/usr/local/bin/send-myip --help

	You must provide 1 argment on the command line.

        sendsms - This will ONLY send an sms to whoever you've set in the variables
        email   - This will ONLY send an email to whoever you've set in the variables
        all     - Send both Email and SMS
        help    - Display this page

        Other optional formats for the above arguments can be:

                --sendsms       | sendsms       | SENDSMS
                --email         | email         | EMAIL
                --all           | all           | ALL
                --help          | help          | HELP | (nothing at all)

        ie:     /usr/local/bin/send-myip --sendsms
                /usr/local/bin/send-myip EMAIL
                /usr/local/bin/send-myip --help




TODO:
============

- Add External IP detection

