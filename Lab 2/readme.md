
## Lab 2 - Secret-Key Encryption
This [lab](https://seedsecuritylabs.org/Labs_20.04/Files/Crypto_Encryption/Crypto_Encryption.pdf) will apply your knowledge of block cipher modes of operation to find out some interesting results. You have to complete five tasks in this lab and submit a report describing your works and observations. The lab is one of the exercises in [SEED Project](https://seedsecuritylabs.org/Labs_20.04/Crypto/). Load the VM image with your Virtualbox or VMware, and read the User Manual carefully before you start working on the tasks.

## Environment Setup

- Please refer to the VM/environment instructions from Lab 1.

***Note*** Starting from this lab, you can use Mac + VMware Fusion Player. The kernel version issue affecting Lab 1 does not impact this experiment.


## Lab Notices
* You can skip **Tasks 1, 6.2, 6.3 and 7**– frequency analysis against monoalphabetic substitution cipher and programming using the crypto library.
* Container setup is not required. You may ignore section *2 Lab Environment* of the lab manual.
* The original image, [pic_original.bmp](https://raw.githubusercontent.com/xyliatgithub/IntroCrypto2024/main/Lab%202/pic_original.bmp), is available in this GitHub repository. It is the image mentioned for Task 3.
* You can use any **bmp file** you found for Task 3 as long as you can see the differences when it is encrypted using ECB and CBC. Though [lena](https://github.com/Yu-Tsern/EN.650.658/blob/master/lab/lena_color.gif) is the standard testing image, it is not a good choice in this lab due to its complexity. Use some simple image that has large areas of same colors instead, such as [legoshi.bmp](https://raw.githubusercontent.com/xyliatgithub/IntroCrypto2024/main/Lab%202/legoshi.bmp). The header of pictures encrypted by ECB and CBC should be the same.
* For Task 5, you should consider the decryption processes for ECB, CBC, CFB and OFB.
* Include screenshots, original pictures, codes, IVs, keys you use in your report.
* Take screenshots periodically and include it in your report. They not only serve as evidences of completion but also help the grader understand what you're trying to achieve.

## Points Breakdown
This lab has 40 points in total. The five tasks (2, 3, 4, 5, 6.1) are worth 5, 10, 10, 10, 5 points respectively.

Note that **Task Number** is not the same as **Section Number**, for example: 
> 3 Task 1

Task 1 is in Section 3. Please use the **Task Number** in your report.

## Grading
* Completeness (25 pts): All the steps as instructed in the lab manual must be included in the report with adequate evidence.
* Presentation (15 pts): The report must be clear and correct in organization and writing with adequate explanation.
