# How to Encrypt Email?

[![how to encrypt email](redd.png)](https://github.com/namewebie/how.to.encrypt.email)


If you're a Gmail user, we have good news for you: Google automatically encrypts all emails in transit using Transport Layer Security (TLS), the standard means of performing this type of encryption.

TLS, a set of cryptographic protocols designed to provide communications security over a computer network, makes it impossible for unauthorized third parties to snoop on your email communication when sharing the same network, such as the WiFi at your favorite coffee shop.

You can imagine TLS as a magical envelope for messages. Even if someone steals this envelope, the person won't be able to read your email unless they know how to unlock it.

Besides TLS, Gmail also supports S/MIME, which is an advanced encryption standard that encrypts the actual message, instead of simply providing an encrypted envelope for it. S/MIME is only available with G Suite Enterprise, G Suite for Education, and G Suite Enterprise for Education, and each sender and recipient must have it enabled for it to work.

**To enable S/MIME:**

* Log in to your Google Admin console.
* Go to Apps → G Suite → Gmail → User settings.
* Select the domain or organization you want to configure.
* Check the Enable S/MIME encryption for sending and receiving emails box.
* Click Save
