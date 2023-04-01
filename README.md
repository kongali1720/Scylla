# Scylla
Scylla for instagram
cylla is a free and open-source tool available on Github. Scylla is based upon the concept of Open Source Intelligence (OSINT). This tool is used for information gathering. Scylla is written in python language. You must have python language installed in your Kali Linux in order to use the Scylla tool. Scylla is an advanced tool that allows it’s used to perform advanced information gathering. Scylla is also called The Information Gathering Engine. Scylla is used to find all social media accounts of a person who is assigned to a particular username. Scylla is used to find account information of the account of Instagram. Twitter accounts, websites/web servers, phone numbers, and names.

Scylla has a drastic support IoT search engine Shodan. This search engine lets you know about devices all over the internet. Scylla also has in-depth geolocation capabilities which makes it more powerful. Scylla has financial modules which allow the user to check whether their credit/debit card details have been leaked or not in a pasted data breach of companies. This tool makes it easy to search for a person on social media platform by just knowing his/her number or username. You have to give your username to Scylla and this tool will give you all the social media accounts information of the target.

Features of Scylla:

    Scylla is a free tool You can download and use it free of cost.
    Scylla is open source tool. Scylla’s source code is available on GitHub you can check it and contribute to it.
    Scylla works on the concept of Open Source Intelligence (OSINT).
    Scylla is used for information gathering.
    Scylla is an advanced tool used for advance searching on the internet.
    Scylla is written in python language. You must have python language installed into your Kali Linux operating system in order to use Scylla.
    Scylla is also called an information gathering Engine.

Uses of Scylla:

    For information gathering.
    To search accounts on social media platforms associated with a number.
    To search IoT devices.
    To get account information on Instagram.
    To get account information on Twitter.
    Get the Google account details of any user.
    To see webcams that are open on the internet. You can see these webcams by using shodan search engine API key.
    To get information about specific IP addresses. Scylla will give you the exact street, city, state, country, and zip/postal along with longitude and latitude.
    To get information about credit cards and debit cards.
    To check whether the card information leaked in past or not.
    To get information on that phone number which you have provided for eg (Carrier, Location, etc.)

Step-By-Step Installation of Scylla Tool

Step 1: Open your Kali Linux operating system. Move to desktop. Here you have to create a directory called Scylla. To move to desktop use the following command.

cd Desktop
mkdir Scylla
cd Scylla
git clone https://www.github.com/DoubleThreatSecurity/Scylla
ls
cd scylla
ls
python3 -m pip install -r requirements.txt
python3 scylla.py
python3 scylla.py  --help

Working with scylla

1. Use the Scylla tool to get information about Instagram account of a user.
python3 scylla.py --instagram < username >

2. Use the Scylla tool to get information about the social media accounts of a user.
python3 scylla.py --username < username >

3. Use the Scylla tool to get information about the phone numbers.
python3 scylla.py -r +628131837xxxxxx

4. Use the Scylla tool to get information about geolocation of an IP-address.
python3 scylla.py -g <your ip address>

Good Luck.
