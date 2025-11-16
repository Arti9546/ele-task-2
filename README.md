Task 2: Phishing Email Analysis and Risk Assessment

Task Objective

The objective was to analyze a sample email to identify and document characteristics that classify it as a phishing attempt, demonstrating an understanding of social engineering tactics and network security risks.

🛠 Analysis Performed

The analysis involved a manual inspection of the email's key components: Sender Domain, Subject Line, Body Content (Grammar/Urgency), and the actual hidden URL (Attack Vector).

✉️ Email Sample Reviewed

Component	Detail
Claimed Sender	Netflix Support
Fake Sender Address	billing@netfllix.com.co
Subject	URGENT: Your account has been SUSPENDED - Update Payment Immediately
Malicious URL	https://verify-billing-update.id/netflix-login-secure
Attack Vector	Credential Harvesting

🔑 Phishing Indicators Report

Category	Indicator Found	Security Implication
1. Sender Spoofing	Typosquatting used in the sender domain: netfllix.com.co (extra 'l' and foreign TLD .co).	Technical proof that the email did not originate from the legitimate company.
2. Social Engineering	Subject uses "URGENT," "SUSPENDED," and a "24 hours" deadline.	Designed to create panic and compel the user to click the link immediately without careful review.
3. Link Discrepancy	The displayed link is generic, but the hidden URL points to verify-billing-update.id (an unknown domain with an Indonesian TLD).	The user is being redirected to a fraudulent website to steal credentials and financial data.
4. Grammar/Quality	Grammatical errors in the body (e.g., "continuous of your service"). Also uses the generic salutation "Dear customer."	Indicates low effort from a non-official source, common for mass-market scams.
5. Attachment	No attachment was found. The attack relies solely on the malicious hyperlink.	

⚠️ Risk Assessment

The successful execution of this phishing attack carries a Critical impact.

Risk Summary

Factor	Rating	Justification
Likelihood	High	Strong social engineering (Urgency/Threat) and convincing brand impersonation make this attack highly probable to succeed against an untrained user.
Impact	Critical	A successful click leads to Financial Loss (stolen credit cards) and Account Takeover, potentially leading to secondary attacks via password reuse.
Overall Risk	CRITICAL	The severity of financial and identity theft consequences outweighs the relatively easy method of execution.
