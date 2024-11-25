# Comparing Hashes
## Objective
Investigate and compare two files to verify if they are identical.
## Tasks
* Check the contents of each file.
* Generate a hash for each file and compare the hashes.
* Determine whether the files are identical or not.
## Steps Taken
* Used ```ls``` command to list and identify the two files I will be investigating.
* Read the contexts of ```file1.txt``` and ```file2.txt``` using the ```cat``` command.
* Upon first look, the contents of these files seem identical. To further verify, we will generate a hash for each file using ```sha256sum```.

![1.png](https://github.com/iduredia97/Comparing-Hashes/blob/main/1%20(1).png)
* Generated a hash for ```file1.txt``` and ```file2.txt``` using ```sha256sum```.
* Created two new files to contain corresponding hashes for ```file1.txt``` and ```file2.txt``` using ```sha256sum```.

With the two hashes generated, we can be determine that although the contains looked identical, there are differences between the two files.

![2.png](https://github.com/iduredia97/Comparing-Hashes/blob/main/2%20(1).png)
* Compared the two files created ```file1hash``` and ```file2hash``` using the ```cmp``` command.

The output shows us what and where the differences are found between the two file hashes.

![3.png](https://github.com/iduredia97/Comparing-Hashes/blob/main/3%20(1).png)
## Conclusion
```file1.txt``` and ```file2.txt``` are not identical files.
