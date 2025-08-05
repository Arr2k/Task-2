# Task-2

Here, I have recognised the samples as phishing in two different method. In the first sample, Email: security-update@micros0ft-support.com, here instead of "Microsoft" they have used micros0ft (with a zero instead of 'o') – which defines its a spoofed domain.

Hovering over the “Click Here to Verify” link shows http://fake-microsoft-login.com, This is not a legitimate Microsoft domain – likely to lead to a phishing site.

“Urgent Action Required”
“Failure to act will result in suspension”
These phrases create panic and pressure the victim – a classic phishing tactic.

On the other hand, the second method is to anaylse the email is through using tools, such as:Google Admin Toolbox Header Analyzer, MXToolbox Analyzer

By pasting the email header to these auto generator tool, it then shows the result whether the email is legitimate or not

while analysing the sample 2 email header, the result shows that:
Return-Path	-- Looks spoofed

Received From	Unknown domain, not PayPal

SPF Result	Failed SPF check

DKIM-Signature	Missing DKIM – not signed by PayPal

Subject	Panic-inducing message "Urgent"
