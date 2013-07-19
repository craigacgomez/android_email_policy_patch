Email Policy Patch
========================

Email Security Policy Patch (Based on CM 10.1)

This is a set of code changes which bypasses the Exchange security restrictions and policies for the AOSP Email application. This is based on the latest CyanogenMod 10.1 code. It will be frequently updated with the latest CyanogenMod 10.1 changes.

It bypasses:
    1. The need to set up the account as a "Device Administrator" and does not require that you set up a lockscreen policy
    2. The security restrictions like requiring "Remote Wipe", "Encryption" and "Manual Sync When Roaming"
    3. The security restrictions like disabling "Attachments", "HTML Email" & the "Camera"

SUPPORTED ANDROID VERSIONS:
Stock & AOSP-based ROMS (including CM10.1, AOKP, ParanoidAndroid, Evervolv, etc.) based on Android 4.2.x (4.2_r1, 4.2_r2, 4.2.1_r1, 4.2.1_r1.1, 4.2.1_r1.2, 4.2.2_r1.1, 4.2.2_r1.2)

IMPORTANT:
1. You would need to remove all existing Exchange accounts and re-add them.
2. You would need to replace the Email & Exchange apks from your custom ROM before re-flashing or flashing an update
3. Using themed versions of Email & Exchange after setting up accounts with the patched version will cause issues
4. You may lose additional features, if any, which you custom ROM devs have added which are not part of AOSP or CyanogenMod 10.1
5. Make sure you have only on instance of the Email and Exchange apks in your /system/app folder. The possible known names for the Email apk are Email.apk, Email2.apk, EmailGoogle.apk & Email2Google.apk. The possible known names for the Exchange apk are Exchange.apk, Exchange2.apk, ExchangeGoogle.apk & Exchange2Google.apk

DISCLAIMER:
Since this bypasses most, if not all, the security requirements set up for an Exchange account, it will most probably not be condoned by your organisation (work, school, etc.).
Please note that if you do choose to use this, you are complete responsible for all legal or any other issues which you may be subject to should anyone find out.
This requires that you have a rooted device which read/write access to the /system partition, and is, hence, potentially dangerous. Though I have tested these changes, I will not
be responsible for any issues you may face including, but not limited to data loss, bricked phones & void warranties.

XDA Thread: http://forum.xda-developers.com/showthread.php?t=1749921
RootzWiki Thread: http://rootzwiki.com/topic/29015-app-mod-exchange-security-bypass-no-pin-android-42x41x/

CREDITS:
Google
CyanogenMod
Some other awesome people from XDA and RootzWiki (I don't remember who, I just remember the changes I collected from various sources)

 - Craig Gomez <https://github.com/craigacgomez/>
