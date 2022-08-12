# Code 201 Reading Notes

## Class 01 Reading Notes
---

### Notes
- Clients are the typical web user's internet-connected devices (for example, your computer connected to your Wi-Fi, or your phone connected to your mobile network) and web-accessing software available on those devices (usually a web browser like Firefox or Chrome).
- Servers are computers that store webpages, sites, or apps. When a client device wants to access a webpage, a copy of the webpage is downloaded from the server onto the client machine to be displayed in the user's web browser.
- HTTP: Hypertext Transfer Protocol is an application protocol that defines a language for clients and servers to speak to each other. This is like the language you use to order your goods.

  1. The browser goes to the DNS server, and finds the real address of the server that the website lives on (you find the address of the shop).
  2. The browser sends an HTTP request message to the server, asking it to send a copy of the website to the client (you go to the shop and order your goods). This message, and all other data sent between the client and the server, is sent across your internet connection using TCP/IP.
  3. If the server approves the client's request, the server sends the client a "200 OK" message, which means "Of course you can look at that website! Here it is", and then starts sending the website's files to the browser as a series of small chunks called data packets (the shop gives you your goods, and you bring them back to your house).
  4. The browser assembles the small chunks into a complete web page and displays it to you (the goods arrive at your door — new shiny stuff, awesome!).

```
1. Compose a short poem describing how HTTP sends data between computers.
  - 
2. Describe how HTML, CSS, and JS files are “parsed” in the browser.
3. How can you find images to add to a Website?
4. How do you create a String vs a Number in JavaScript?
5. What is a Variable and why are they important in JavaScript?

```
---
