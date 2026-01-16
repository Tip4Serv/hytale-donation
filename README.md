## Donation plugin for Hytale (Tip4Serv)

This plugin connects your [Tip4Serv.com](https://tip4serv.com/?ads=github) store to your **Hytale** server.  
It automatically checks if a player has made a purchase on your Tip4Serv store and delivers the order in-game (ranks, items, permissions, commands…) within a minute by executing server-side commands.

This solution is designed to be simple, secure, and fully automated.

---

## Secure communication (HMAC authentication)

Tip4Serv uses **HMAC authentication** to secure communications between your Hytale server and the Tip4Serv API.  
This is a strong and proven authentication method, also used in banking systems.

More information:  
[HMAC on Wikipedia](https://en.wikipedia.org/wiki/HMAC)

---

## Features for starter plan (only 5% fee)

- Unlimited game servers & commands  
- Create subscription products  
- Commands execution tracking  
- Stock management  
- Discord roles & messages delivery  
- Discount coupons  
- Store managers access  
- Purchase emails & invoices  
- Sales statistics  
- Private flow for subscribers  
- Custom sub-domain  
- Resend failed commands  
- Permanent commands  
- No advertisements  

---

## Features for PRO members (subscription required)

- Dynamic Dark / Light theme  
- Account linking with avatars  
- Product pages with gallery & video  
- Advanced color editor & custom CSS  
- Top customers & related products  

---

## Store available in 15 languages

English, Danish, Dutch, French, German, Hungarian, Italian, Norwegian, Polish, Portuguese, Romanian, Russian, Spanish, Swedish and Turkish.

---

## Multiple payment methods

You can offer your players the following payment methods:

Card, PayPal, Google Pay, iDEAL, Giropay, Bancontact, Sofort, SEPA, EPS, BACS, Multibanco, BECS, Przelewy24, BOLETO, OXXO, Afterpay.

---

## Installation (Hytale)

Before starting, you **must** create a Tip4Serv account and add your Hytale server.

1) Create an account on [Tip4Serv.com](https://tip4serv.com/?ads=github)  
2) Go to your servers dashboard:  
   👉 https://tip4serv.com/dashboard/my-servers  
3) Add a new **Hytale** server and follow the on-screen instructions  
4) Download and install the plugin on your Hytale server  
5) Configure your API key as indicated in the plugin configuration file  
6) Start or restart your Hytale server  

> Once connected, your server will automatically receive and execute commands after a purchase.

---

## Official Hytale documentation

The full and up-to-date documentation for the Hytale integration is available here:

👉 https://docs.tip4serv.com/games/hytale

This documentation covers:
- Plugin installation
- API configuration
- Command setup
- Product linking
- Subscriptions
- Troubleshooting

---

## Setting up products & commands on Tip4Serv

***Important:***  
All commands configured on Tip4Serv are executed **server-side**, not by players or admins in-game.

Make sure:
- Your Hytale server is online
- The plugin is correctly connected
- Commands used are valid Hytale server commands or plugin commands

You can manage your products here:  
https://tip4serv.com/dashboard/my-products

---

## Dynamic variables

Tip4Serv allows you to use dynamic variables in your commands, such as:
- Player identifiers
- Product quantity
- Total amount paid
- Currency

These variables are automatically replaced when a purchase is processed.

---

## Quantity multiplier

You can multiply the quantity chosen by the customer directly in your commands.

Example:
`give {hytale_username} Food_Pie_Apple --quantity {quantity*5}`


⚠️ You must enable **Allow quantity choice** in your product settings for this to work.

---

## Subscriptions & permanent rewards

Tip4Serv supports **subscriptions**, perfect for:
- Monthly VIP ranks
- Premium access
- Temporary permissions

When a subscription expires, associated commands are automatically disabled.

---

## Need help?

[Documentation](https://docs.tip4serv.com)

[Contact us](https://tip4serv.com/contact)
