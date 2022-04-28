<p align="center"> <img src="https://raw.githubusercontent.com/qeeqbox/dom-cross-site-scripting/main/dom-cross-site-scripting.png"></p>

An adversary may inject malicious content into HTTP requests. The content will be reflected in the HTTP response and executed in the victim's browser.

## Example #1
1. Adversary crafts an email with a malicious request to a vulnerable target and sends the email to Bob
2. Bob clicks on the email and sends the request to the vulnerable target
3. The target sends the malicious code back to Bob
4. Bob's browser inserts the malicious code
5. When malicious code gets executed, it calls back the Adversary
 
## Impact
Vary

## Risk
- read & modify data

## Redemption
- client input validation
- output encoding
- browser built-in XSS preveiton

## ID
cb251c97-067d-4f13-8195-4f918273f41b

## References
- [wiki](https://en.wikipedia.org/wiki/cross-site_scripting)
