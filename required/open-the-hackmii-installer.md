# 🙂 open the hackmii installer

{% tabs %}
{% tab title="wilbrand" %}
under construction
{% endtab %}

{% tab title="str2hax" %}
str2hax exploits the built-in eula channel to open the hackmii installer. you only need an internet connection to do this.

{% hint style="warning" %}
note that if your isp or networking environment prevents using custom dns servers, str2hax will not work and you should [choose another exploit to use](select-your-exploit.md)
{% endhint %}

1. go to the wii menu.
2. go to wii options.
3. go to wii settings.
4. go to page 2 -> internet settings -> connection settings
5. click "change settings"
6. set "auto-obtain dns" to no, and click "advanced settings"
7. set the primary dns to `3.143.163.250`

{% hint style="warning" %}
if there are 3 fields instead of 2, go back and make sure you are on the `Auto-Obtain DNS` page.
{% endhint %}

8. click "confirm" and "save"
9. click ok to perform a connection test.

{% hint style="danger" %}
if you are prompted to perform a wii system update, do NOT. nintendo released a faulty boot2 update that could brick your wii. so don't
{% endhint %}

{% hint style="info" %}
if it fails with error code `521xx`, please verify that you have entered the dns correctly.
{% endhint %}

10. navigate to wii settings -> page 2 -> internet -> user agreements or agreement/contact depending on your region.
11. select yes.
12. click next.
13. &#x20;this screen should pop up:

<figure><img src="https://wii.hacks.guide/images/exploits/str2hax/EULA.png" alt=""><figcaption><p>str2hax exploit splashscreen</p></figcaption></figure>

{% hint style="info" %}
if you get the normal eula, your isp blocks the use of custom dns. try another connection, or [use another exploit](select-your-exploit.md)
{% endhint %}

14. give the exploit 1-2 minutes to download (and don’t press `I ACCEPT`/`I DO NOT ACCEPT`).
15. if the exploit was successful, your device should have booted into the hackmii installer.

{% hint style="warning" %}
if the hackmii installer doesn’t load after more than 2 minutes, or you receive an error like `Hanging.` or `ERROR! if_config (ret = ...)`, please restart your wii and try again.
{% endhint %}
{% endtab %}

{% tab title="bluebomb" %}
under construction
{% endtab %}
{% endtabs %}
