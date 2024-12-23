# Two-Factor Authentication

<br><span># Definition</span>

> **Two-factor authentication (2FA)** is a security process that requires <u>*two separate forms*</u> of verification before granting access to an account. 

<br>

### Introduction

Most users will have bounced upon this, through a Google Verification SMS (Short Message Service), giving you a 6-8 digit password, which verifies you are the owner of the account you're trying to login into. That’s all two-factor authentication (2FA) does; combines two separate factors, <u>**something you know**</u>, *your password*, with <u>**something you have**</u>, like *access to the phone number associated with the account*.

Before we move on to going through and discussing some of the ways to perform **Two-Factor Authentication**, let’s expand a little bit more on what is the purpose of it. 

The main purpose is obvious, increased **security through verification**. **Two-Factor Authentication**, simply put, aims to prevent most, if not all, unauthorized access attempts. But, there's another purpose, often **hidden from view** and based on the most-common implementation; that purpose for many providers is called **KYC (Know Your Customer)** aka <u>**identifying you**</u>. 

Let's expand on that, by taking your bank as an example; They know a whole lot about you, so, before they even ask for your phone number to perform **Two-Factor Authentication**, they don’t need to identify you, they already know who you are, they only desire to prevent unauthorized access to your funds. That’s not the case with other services though, is it? You don't have to provide your actual name or identity documents to make a Twitter or Reddit account, you just make one.

In most cases, I believe that's **NOT** purposely done in an *evil* way, it's just good business. Have multiple foolproof ways to identify your customers, base them around solid personal information, like a phone number, usually tied closely to someone's real identity, and you have one of the most shakeproof ways to close-in to your customer's identity.

Concluding, we will look at the different ways to perform **Two-Factor Authentication**, understand them, analyze them and compare them based on factors like privacy and security.



have no connections to the client computer. They typically use a built-in screen to display the generated authentication data, which is manually typed in by the user. This type of token mostly uses a OTP that can only be used for that specific session.[6] 


### Common Implementations

##### <i class="hgi-stroke hgi-command"></i> [Authentication Apps](two-factor-authentication/methods/authenticator-apps.md)
##### <i class="iconoir-mail"></i> [Email Verification](two-factor-authentication/methods/email-links.md)
##### <i class="fa-solid fa-fingerprint"></i> [Hardware Keys](two-factor-authentication/methods/hardware-keys.md)
##### <i class="mdi mdi-key-chain-variant"></i> [Password Managers](two-factor-authentication/methods/password-managers.md)
##### <i class="iconoir-app-notification"></i> [Push Notifications](two-factor-authentication/methods/push-notifications.md)
##### <i class=""></i> [Disconnected Tokens](two-factor-authentication/methods/disconnected-tokens.md)
##### <i class="iconoir-chat-lines"></i> SMS Authentication