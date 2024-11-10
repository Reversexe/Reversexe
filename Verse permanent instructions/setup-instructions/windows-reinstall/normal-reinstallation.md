---
icon: circle-small
description: Normal reinstallation instructions.
---

# Normal reinstallation

{% hint style="warning" %}
<mark style="background-color:orange;">**Reinstalling Windows with a USB is HIGHLY recommended. This is to ensure the disk bans are gone.**</mark>\
\
🌟 **Easiness**: <mark style="color:green;">**8/10 VERY EASY**</mark>** |** 🕒 **15 Minutes Average Time.**\
\
<mark style="color:yellow;">**Am I Disk Banned? Here’s How to Tell:**</mark> If numerous spoofers have failed and u've been banned multiple times on the same PC, it might be a disk ban. In such cases, we suggest reinstalling Windows with a USB like the instructions below. [**If u don't have a USB, read this.**](normal-reinstallation.md#i-dont-have-a-usb-or-it-looks-too-hard-for-me)
{% endhint %}

<details>

<summary><mark style="color:red;"><strong>I DONT HAVE A USB</strong></mark><strong> | IT LOOKS TOO HARD FOR ME!</strong></summary>

Believe in the process. It may seem challenging at first with all the images and information, but trust us, it's much simpler than it looks! We encourage you to give it a try. If you need assistance, don't hesitate to contact us in the Discord.\
\
<mark style="color:red;background-color:red;">**Don't have a USB to reinstall with?**</mark> Most cost **$5**, and it's recommended to get one.\
\
**Otherwise;** **Reinstall Windows by settings** > remove everything > Cloud download > <mark style="color:blue;">**Change settings**</mark> > Clean data <mark style="color:green;">\[YES]</mark> / Delete files from all drives <mark style="color:green;">\[YES]</mark> / Download Windows <mark style="color:green;">\[YES]</mark> > Confirm & next and wait. This could take 4 to 5 hours.

</details>

### <mark style="color:blue;">REINSTALL WINDOWS WITH A USB</mark> (AND BYPASS DISK BAN)

{% embed url="https://www.microsoft.com/en-us/software-download/windows10" %}

1. Download the Media Creation Tool above, click **"Download Now"**
2. Open the **Media Creation Tool as an administrator**
3. Select **Create Installation media (USB Flash drive)**
4. Use all the recommended options & continue & wait for it to finish.

<div align="left" data-full-width="false">

<figure><img src="../../.gitbook/assets/flashdrive.png" alt="" width="563"><figcaption></figcaption></figure>

</div>

### <mark style="color:blue;background-color:blue;">**YOUR USB CONTENTS LOOK LIKE THIS NOW:**</mark>

<figure><img src="../../.gitbook/assets/USB insides.png" alt=""><figcaption></figcaption></figure>

{% hint style="danger" %}
**NOTE:** When reinstalling Windows, most modern systems will automatically detect and install basic Ethernet drivers, so ur connection will work fine right after the installation. \
\
<mark style="color:red;background-color:red;">**However, in certain cases it might be needed to manually download and install network drivers:**</mark>\
\
Make sure to download your network drivers (LAN) from your corresponding motherboard model. So for example "Asus B550 Network drivers" on Google, and put them in the USB drive. You can skip this step since this is just a precaution, but there is a small risk of no connection after reinstallation.
{% endhint %}

***

5. Restart the computer, and **hold shift** at the same time.

<div align="left">

<figure><img src="../../.gitbook/assets/+ HOLD SHIFT (1).png" alt=""><figcaption></figcaption></figure>

</div>

5. Select **Use a device** and select the USB <mark style="background-color:blue;">**(Known as "Flash Drive")**</mark>

<div align="left">

<figure><img src="../../.gitbook/assets/Untitled design (14).png" alt="" width="563"><figcaption></figcaption></figure>

</div>

5. Select **Windows 10 Pro** <mark style="color:red;background-color:red;">**(IMPORTANT!)**</mark>

<div align="left">

<figure><img src="../../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

</div>

8. Select **"I don't have a product key"** (No worries about this)

<div align="left">

<figure><img src="../../.gitbook/assets/image.avif" alt="" width="525"><figcaption></figcaption></figure>

</div>

9. **Select Custom:** Install Windows Only (advanced)

<div align="left">

<figure><img src="../../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

</div>

10. Press **SHIFT + F10** (A CMD will pop up)
11. Now write **`diskpart`** into the CMD
12. Then write **`list disk`** into the CMD to see all ur drives
13. Write **`select disk 'X'`** (X = Disk number) then write `clean` for ALL disks, besides ur USB.

{% hint style="danger" %}
**For example,** most people have one disk. Then write '**select disk 1**' and then '**clean**'. In case u have two drives, ur gonna 'select disk 2' as well, and write 'clean' and so forth for all disks. ✅\
\
Flash drives (USB) usually have a smaller size compared to internal hard drives or SSDs, and are likely the last drive listed! **DO NOT CLEAN YOUR FLASH DRIVE (USB)!** <mark style="color:red;background-color:red;">**Still Unsure? Please contact us.**</mark>
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

<div align="left">

<figure><img src="../../.gitbook/assets/Offline acc.webp" alt="" width="563"><figcaption></figcaption></figure>

</div>

17. Turn **OFF** All privacy questions/settings

<div align="left">

<figure><img src="../../.gitbook/assets/Turnoff.png" alt="" width="563"><figcaption></figcaption></figure>

</div>

***

{% hint style="danger" %}
**Make sure to follow these steps while and after reinstallation:**\
\
1\. Make an offline account or a new Microsoft account. Don't log in to the old ones.\
\
2\. Do not log in to <mark style="color:blue;">OneDrive, Logitech G Hub,</mark> or <mark style="color:green;">Geforce Experience.</mark>\
\
3\. Install: [https://aka.ms/vs/17/release/vc\_redist.x64.exe ](https://aka.ms/vs/17/release/vc\_redist.x64.exe)to prevent errors.
{% endhint %}

***
