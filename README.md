### What’s DNS?

**D** - Domain  
**N** - Name  
**S** - System  

DNS is basically the internet's way of turning human-readable website names (like **google.com**) into their secret code, which are IP addresses (like **192.168...**). Think of it as a contact book where every name (website) has a unique phone number (IP address). Just like your phone connects to a friend’s number, your browser connects to a server using this IP address. But remember, your device has its own IP too, which helps establish the connection!

### How DNS Works Behind the Scenes

1. **DNS Recursor**  
   When you type a website in your browser, your request first goes to the **DNS recursor**. This is like your personal assistant that starts searching for the website. If it doesn’t know the answer, it’ll reach out to other servers to find it.

2. **Root Nameserver**  
   Next, the recursor sends your request to the **root nameserver**. Imagine this as the table of contents in a book. It doesn’t have the whole story, but it knows where to look. It tells the recursor which section to check based on the end of the website name (like **.com** or **.org**).

3. **TLD Nameserver**  
   After that, the request goes to the **TLD nameserver**. Think of it as a specific shelf in a library. It’s in charge of the last part of the web address (like **.com** or **.net**). If your website is **example.com**, this server will direct the recursor to the right authoritative nameserver that has the real details.

4. **Authoritative Nameserver**  
   Finally, we hit the **authoritative nameserver**. This is like the dictionary that has all the definitions. It holds the actual info about the website, including its IP address. If it has what you need, it sends the IP back to the recursor, which then shares it with your browser so you can finally load the site!

...in progress
