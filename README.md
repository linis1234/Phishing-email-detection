# Phishing-email-detection
__Sample Email:__  
![image](https://github.com/user-attachments/assets/a78555ba-d7c9-426d-984a-422398805ccb)  
-Email Subject: Secure Your WellsFargo Online Key  
-Sender Name: Wells Fargo  
-Sender Email: inmail-hit-reply@linkedin.com  
-Date: Sat 10/22    



__Indicators of Spoofing__  

1.Email address: inmail-hit-reply@linkedin.com  

This is clearly not an official Wells Fargo domain.  

The sender uses a LinkedIn InMail address, which is inappropriate for banking alerts.  
 Indicator of spoofing: The message falsely claims to be from Wells Fargo.  


 2.Header Analysis:The visible sender domain (linkedin.com) and subject content mismatch are already a strong indication of header inconsistency.  

In a real analysis, this would be checked with tools like MXToolbox Header Analyzer.  
 Suspected spoofing or redirection via misaligned headers.  

 
3.Link in email:  
http://cabinetkignima.com/Wellsfargo_keys_account5/page2.html  

This link does not belong to Wells Fargo.  

The domain (cabinetkignima.com) is completely unrelated.  
 Deceptive URL likely leading to a credential phishing page.  
  No attachments present, which is common in link-based phishing.  

  4.Urgent or threatening language in the email body  
  The message says:  

"Your Personal Security Key... has expired, as a result, is no longer valid."  

Suggests account compromise  

Pressures user to "click the link below to reactivate"  
 Classic urgency tactic to drive users into immediate action.  

 5. Mismatched URLs (hover to see real link)  
The visible text matches the suspicious URL, so it's not masked — but it is:  

Unfamiliar  

Untrusted  

Mismatched with the claimed brand  
 URL mismatch with claimed brand (Wells Fargo).  



 6.Presence of spelling or grammar errors  
 Errors in the body:  

“Key your for your...” (redundant and incorrect)  

Awkward phrasing: “...is no longer valid” instead of “is invalid” or “has expired.”  
 Spelling/grammar mistakes — common in phishing emails from non-native speakers or automated tools.  


 __Summarize phishing traits found in the email__  
	Trait	Details  
1	Spoofed sender	Uses linkedin.com address while claiming to be Wells Fargo  
2	Mismatched domain	Malicious link points to cabinetkignima.com  
3	Urgency	Claims user’s security key is expired  
4	Grammar issues	Multiple grammatical and spelling mistakes  
5	Inconsistent branding	No Wells Fargo logo, design, or professional layout  
6	Third-party footer	References LinkedIn footer, not bank contact details  

__Recommended Action:Do not click on the link.__







 



