# KDMapper without allocating memory in BigPoolTable

Original creator https://github.com/z175

Improved by https://github.com/TheCruZ

run kdmapper.exe in admin CMD to see it's arguments, in order to not be in BigPoolsTable the arguments are --mdl --free!

Please note I've taken the code from TheCruz and updated it so that it doesn't allocate any memory in the BigPoolTable, if there is some code I could've written better please let me know since I'm always willing to improve. Please note that your mdl address is passed to the first argument of your driver entry so you can clean the pfn easily. Also credits to the original creator of kdmapper z175

please note TheCruz had merged my repo and improved the code, I then took this code and added a few more things to it.

Tested from **Windows 10 1607** to current **Windows 11 22000** :heavy_check_mark:


Credits: z175, TheCruz
