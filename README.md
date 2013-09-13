Send-MyIP
==========================

Raspberry Pi Script that sends out it's IP at boot time, helpful for DHCP conditions.


	/usr/local/bin/send-myip --help

        sendsms - This will ONLY send an sms to whoever you've set in the variables
        email   - This will ONLY send an email to whoever you've set in the variables
        all     - Send both Email and SMS
        help    - Display this page

        Other optional formats for the above arguments can be:

                --sendsms       | sendsms       | SENDSMS
                --email         | email         | EMAIL
                --all           | all           | ALL

                This option is only for testing or local use and is not included in the --all option
                --display       | display       | DISPLAY

                --help          | help          | HELP | (nothing at all)

        ie:     $0 --sendsms
                $0 EMAIL
                $0 --help


TODO:
============


