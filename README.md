# Who-Dis

DISCLAIMER: This tool should be used in the white hat way, however, I have no responsibility if someone will use for
malicious purposes.

A command line tool implemented in Python that has as main goal to give me the feel of security tools found in security
OS distributions such as Kali Linux.  This tool collects and stores Open Source Intelligence (aka OSINT) about a target
domain or individual.

I am planning to include:
1) advanced google dorks and search to target social media such as Facebook, Linkedin, Twitter.
2) Use social media information (having as target the email) to search if user has been pawned and if yes, search more
in depth for details specifically password.
3) Pipl website search searching for more accounts related to the user.
4) Construction of path of journey and statistics if twitter found.
5) Usage of the website inteltechniques to identify the interests of the target, mainly to use spear phishing against.

Current version of the program includes:
1) Help menu
2) Google, Facebook, Linkedin, Twitter and Instagram search*.
3) Search in www.pipl.com to capture the social media not covered above that the user or company has.
4) Search in www.sec.gov returning difficult to find and often confidential information about companies using the edgar
search engine.

* NOTE: for these searches you need to be careful to not overload the IP search allowance you have when it comes to
scripting because after a while google thinks that you are a web crawler and denies the service returning an error 503.
What I was doing to avoid this was to change my IP address using a VPN.  Another way of doing so is to use proxychains
in kali linux and when banned you can do 'service tor restart' to retrieve a new IP address.
