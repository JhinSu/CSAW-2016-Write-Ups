# CSAW CTF 2016 Quals: Clams_Dont_Dance

**Category:** Forensics
**Points:** 100
**Solves:** 238
**Description:**

Find the clam and open it to find the pearl. 


## Write-up

Using binwalk on the image will extract a ton of files. Most of it is useless, but you'll find something interesting in the ppt folder. 
After navigating to media, you'll see 'image0.gif' which is a MaxiCode that contains the flag. 

### Flag

`flag{TH1NK ABOUT 1T B1LL. 1F U D13D, WOULD ANY1 CARE??}`
