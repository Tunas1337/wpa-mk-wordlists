# wpa-mk-wordlists
Macedonian language WPA2 cracking wordlists

Made using [this CSV dump of makedonski.info](https://github.com/xenicR/macedonian-dictionary) by xenicR.

# Disclaimer

These wordlists were primarily made to evaluate the password security of Wi-Fi networks throughout North Macedonia during
my pentesting, as well as to suggest better password creation techniques.
They should only be used for *informational and statistical purposes,* or on *authorized system audits / penetration tests.*

I am not responsible for any potential misuse of this resource to aid in the unauthorized access of computer systems or networks.

# File description

mk_wordlist.txt: The typical wordlist, filtered to only words with length > 8.

mk_wordlist_hob064.gz: The same wordlist with the [hob064](https://github.com/praetorian-code/Hob0Rules/blob/master/hob064.rule) ruleset applied to it, yielding ~5 million passwords after filtering. 
(Uncompressed file size: ~64MB)
