# TelegramScraper
Using this tool you can easily add so many members from any group to your group. Less than 2 minutes. Super easy. Time saver. But this tool is only for educational purpose. You could be banned from Telegram. So be careful.

## • How to Setup API:
* Go to http://my.telegram.org  and log in.
* Click on API development tools and fill the required fields.
* put app name you want & select other in platform Example :
* copy "api_id" & "api_hash" after clicking create app ( will be used in setup.py )

## • How To Install and Use

`$ pkg install -y git`

`$ pkg install -y python3`

`$ pkg install -y apt install python3-pip`

`$ git clone https://github.com/darmosuke/TelegramScraper.git`

`$ cd TelegramScraper`

* Install requierments

`$ python3 setup.py -i`

* setup configration file ( apiID, apiHASH )

`$ python3 setup.py -c`

* To Genrate User Data

`$ python3 scraper.py`

* ( members.csv is default if you changed name use it )
* Send Bulk sms To Collected Data 

`$ python3 smsbot.py members.csv`

* Update Tool

`$ python3 setup.py -u`
