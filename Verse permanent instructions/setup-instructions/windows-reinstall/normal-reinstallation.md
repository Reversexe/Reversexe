---
description: Reinstall Windows without RAID.
---

# Normal reinstallation

{% hint style="warning" %}
Reinstalling Windows with a USB is <mark style="color:red;">**HIGHLY**</mark> recommended. This is to ensure the disk bans are gone.\
\
🌟 **Easiness**: <mark style="color:green;">**8/10 VERY EASY**</mark>** | Takes max 15 Minutes.**\
\
<mark style="color:yellow;">**Am I disk banned? This is how to know:**</mark> A lot of spoofers didn't work for you and you've been banned multiple times on your same PC. Then we'd recommend reinstalling with a USB like this guide.&#x20;
{% endhint %}

<details>

<summary><mark style="color:red;"><strong>I DONT HAVE A USB / IT LOOKS DIFFICULT!</strong></mark><strong> HELP ME</strong></summary>

Believe in the process. It 'looks' difficult because you might've been overwhelmed by all the pictures and information. Believe us<mark style="color:green;">**, IT'S FUCKING EASY.**</mark> We would recommend you to at least attempt it. If you need support, please reach out to us, and we will help you.\
\
<mark style="color:red;">**You don't have a USB to Reinstall with?**</mark> Most cost **$5**, and it's recommended to get one.\
\
**In case u don't want to do so:** [https://youtu.be/23GvVWXt6KU](https://youtu.be/23GvVWXt6KU) follow this tutorial video. This reinstallation method works fine for 90% of people as well.

</details>

### REINSTALL WINDOWS WITH USB (AND BYPASS DISK BAN)

{% embed url="https://www.microsoft.com/en-us/software-download/windows10" %}

1. Download Media Creation Tool above, click **"Download Now"**
2. Open the **Media Creation Tool as an administrator**
3. Select **Create Installation media (USB Flash drive)**

<figure><img src="../../.gitbook/assets/flashdrive.png" alt=""><figcaption></figcaption></figure>

4. Use all the recommended options & continue & wait for it to finish.

### <mark style="color:blue;background-color:blue;">**YOUR USB CONTENTS LOOK LIKE THIS NOW**</mark>

<figure><img src="../../.gitbook/assets/USB insides.png" alt=""><figcaption></figcaption></figure>

5. Hold **SHIFT,** and click **Restart and keep holding SHIFT!**

<div align="left">

<figure><img src="../../.gitbook/assets/image.webp" alt=""><figcaption></figcaption></figure>

</div>

6. Select **Use a device** and select the USB _<mark style="background-color:blue;">(Known as "Flash Drive")</mark>_

<figure><img src="../../.gitbook/assets/select.webp" alt=""><figcaption></figcaption></figure>

7. Select **Windows 10 Pro** <mark style="color:red;">**(IMPORTANT!)**</mark>

<div align="left">

<figure><img src="../../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

</div>

8. Select **"I don't have a product key"** (No worries about this)

<div align="left">

<figure><img src="../../.gitbook/assets/image.avif" alt=""><figcaption></figcaption></figure>

</div>

9. **Select Custom:** Install Windows Only (advanced)

<div align="left">

<figure><img src="../../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

</div>

10. Press **SHIFT + F10** (A CMD will pop up)
11. Now write `diskpart` into the CMD
12. Then write `list disk` into the CMD to see all ur drives
13. Write `select disk 'X'` (X = Disk number) then write `clean` for ALL disks, besides ur USB.

{% hint style="danger" %}
**For example,** most people have one disk. Then write '**select disk 1**' and then '**clean**'. Incase u have two drives, ur gonna 'select disk 2' as well, and write 'clean' and so forth for all disks.\
\
Flash drives (USB) usually have a smaller size compared to internal hard drives or SSDs, and likely the last drive listed! **DO NOT CLEAN YOUR FLASH DRIVE (USB)!** <mark style="color:red;">**Unsure?**</mark> <mark style="color:red;">**Please open a ticket so we can help**</mark>**.**
{% endhint %}

Now it should output: <mark style="color:green;">**'Succeeded in cleaning the disk'**</mark> or something related to <mark style="color:green;">**'success'**</mark>

<div align="left">

<figure><img src="../../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

</div>

14. Close the CMD and click **Refresh**

<div align="left">

<figure><img src="../../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

</div>

15. Select your **main drive** (Unallocated Space) and click **Next**
16. The installation process should start, <mark style="color:red;background-color:red;">**AND MAKE AN OFFLINE ACCOUNT!**</mark>

<figure><img src="../../.gitbook/assets/Offline acc.webp" alt=""><figcaption></figcaption></figure>

17. Turn **OFF** All privacy questions/settings

<figure><img src="../../.gitbook/assets/Turnoff.png" alt=""><figcaption></figcaption></figure>

***

{% hint style="danger" %}
**Make sure to follow these steps while and after reinstallation:**\
\
1\. Make an offline account or a new Microsoft account. Don't login to ur old one.\
\
2\. Do not login to <mark style="color:blue;">OneDrive</mark>. <mark style="color:green;">Geforce Experience</mark>, or <mark style="color:blue;">Logitech G Hub</mark>.\
\
3\. Install: [https://aka.ms/vs/17/release/vc\_redist.x64.exe ](https://aka.ms/vs/17/release/vc\_redist.x64.exe)to prevent errors.
{% endhint %}