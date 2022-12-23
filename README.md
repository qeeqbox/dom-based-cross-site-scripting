<p align="center"> <img src="https://raw.githubusercontent.com/qeeqbox/dom-based-cross-site-scripting/main/dom-based-cross-site-scripting.png"></p>

A threat actor may inject malicious content into HTTP requests. The content is not reflected in the HTTP response and executed in the victim's browser.

## Example #1
1. Threat actor crafts an email with a malicious request to a vulnerable target and sends the email to Bob
2. Bob clicks on the email and sends the request to the vulnerable target
3. The target sends the malicious code back to Bob
4. Bob's browser inserts the malicious code
5. When malicious code gets executed, it calls back the threat actor
 
## Impact
Vary

## Risk
- Read & modify data

## Redemption
- Client input validation
- Output encoding
- Browser built-in XSS preveiton

## ID
cb251c97-067d-4f13-8195-4f918273f41b

## References
- [wiki](https://en.wikipedia.org/wiki/cross-site_scripting)
