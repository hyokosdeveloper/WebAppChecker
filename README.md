# WebAppChecker
***
batch script that check the status of a list of urls

---

# TO Check a Single URL
-- From a Terminal Prompt on a Unix/Linux based OS --
--
> ./check http://theurltocheck.com

---

# To Check a List of URLS
-- Create a text file with each url listed on a seperate line - ie:

http://urlone.com

http://urltwo.com

http://urlthree.com


-- Save file as "urlsToCheck.txt"

-- From Terminal Prompt on Unix/Linux based OS 

./check < urlsToCheck.txt
