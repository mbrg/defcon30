# Low Code High Risk: Enterprise Domination via Low Code Abuse

[View on DEFCON schedule](https://info.defcon.org/events/48565/)

## Abstract

Why focus on heavily guarded crown jewels when you can dominate an organization through its shadow IT?

Low-Code applications have become a reality in the enterprise, with surveys showing that most enterprise apps are now built outside of IT, with lacking security practices. Unsurprisingly, attackers have figured out ways to leverage these platforms for their gain.

In this talk, we demonstrate a host of attack techniques found in the wild, where enterprise No-Code platforms are leveraged and abused for every step in the cyber killchain. You will learn how attackers perform an account takeover by making the user simply click a link, move laterally and escalate privileges with zero network traffic, leave behind an untraceable backdoor, and automate data exfiltration, to name a few capabilities. All capabilities will be demonstrated with POCs, and their source code will be shared.

Finally, we will introduce an open-source recon tool that identifies opportunities for lateral movement and privilege escalation through low-code platforms.

## Recommended pre-reading materials

- [Store by Zapier vulnerability](https://www.volkis.com.au/blog/security-design-flaw-in-storage-by-zapier/)

- [Power Platform data leakage](https://www.upguard.com/breaches/power-apps)
 
- [Living-of-the-land of Office365](https://www.vectra.ai/blogpost/o365-security-powerautomate-is-the-new-powershell)

- [Gaining persistency on AWS Lambda](https://unit42.paloaltonetworks.com/gaining-persistency-vulnerable-lambdas/)

## Mentioned in the talk

### Tools and Demos

- [ZapCreds](https://github.com/mbrg/zapcreds) - scan Zapier for shared credentials ready for exploit

- [Powerful](https://github.com/mbrg/powerful) - install a backdoor on Power Platform enabling creating, triggering and deleting any arbitrary flow 

- [Power Platform account takeover demo, YouTube](https://youtu.be/vJZpNJRC_10)

### Articles

- [Low-Code / No-Code Security, Dark Reading](https://www.darkreading.com/author/michael-bargury)

- [Hackers Abuse Low-Code Platforms And Turn Them Against Their Owners, Zenity blog](https://www.zenity.io/blog/hackers-abuse-low-code-platforms-and-turn-them-against-their-owners/)

- [The Microsoft Power Apps Portal Data Leak Revisited: Are You Safe Now?, Zenity blog](https://www.zenity.io/blog/the-microsoft-power-apps-portal-data-leak-revisited-are-you-safe-now/)

- [Zapier Storage Exposes Sensitive Customer Data Due to Poor User Choices, Zenity blog](https://www.zenity.io/blog/zapier-storage-exposes-sensitive-customer-data-due-to-poor-user-choices/)

- [Connectors overview, Microsoft Docs](https://docs.microsoft.com/en-us/connectors/connectors)

- [Set-AdminPowerAppApisToBypassConsent, Microsoft Docs](https://docs.microsoft.com/en-us/powershell/module/microsoft.powerapps.administration.powershell/set-adminpowerappapistobypassconsent)

- [Power Automate Management, Microsoft Docs](https://docs.microsoft.com/en-us/connectors/flowmanagement/)

## Talk materials

- [Slides](defcon30/Low_Code_High_Risk/Michael_Bargury_Low_Code_High_Risk.pdf)
