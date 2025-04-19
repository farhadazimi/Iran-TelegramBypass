# Iran-Telegram API Bypass


**Bypassing Telegram API Filtering on Iranian Servers**

With the help of a Cloudflare Worker, instead of sending requests directly to the Telegram server, we route them through our Worker first. The Worker then forwards the request to Telegram and sends the response back to us. It's the easiest and cost-free way to bypass this filtering.

New Update The source code has been rewritten! Now, if there’s another web service that’s filtered, all you need to do is replace the Telegram endpoint with that service’s address. Then, just send your requests to your Worker and you're good to go!

I'm Farhad and I'm passionate about SYSOPS and Server Administrator, and I'm always excited to share my experiences with you.

**Requirements**

• Cloudflare

**Activation**

Go to the Cloudflare website and create an account.

In the left menu, select Workers.
In the middle of the page, click the blue Create Application button.

Select the blue Create Worker button.
Give your Worker a name and hit Deploy.

On the next page, simply copy the contents of the index.js file and paste it in. That's it, your Worker is now ready!
Choose your URL and replace the Telegram API endpoint with your own. Now, you’re all set to use it!

If you don’t feel like setting it up yourself, don’t worry! I’ve set one up for you and you can use it directly:

```
https://develogerapitelegram.develogerapi.workers.dev
```
