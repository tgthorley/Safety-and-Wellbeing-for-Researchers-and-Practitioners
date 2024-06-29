In this field, maintaining safety and security as you conduct your research is paramount. As we navigate the online eco-system data leaks our about our identities and creates risks that can threaten our physical and mental health. These risks are dynamic in nature shifting as fast as the online eco-system and as fast as the violence that we seek to prevent. To protect ourselves we must have a framework on which base your security practices allows you "to understand security and risk, and as a result, facilitates the development of a sustained, adaptable security posture and risk balance."[(Loadenthal, 2021)](https://www.researchgate.net/publication/354506971_Risks_Dangers_and_Threat_Models_Evaluating_Security_Analysis_for_Conflict_Practitioners)

> 1. Rather than teach practitioners special means of protecting themselves (e.g., device hardening, defensive driving), organizations should aim to teach reasoned, analytical thinking, focused on threat mapping and risk mitigation so that individuals can be active agents in establishing their personal and organizational security postures.
> 2. Security should be planned for prior to a practitioner’s deployment, at the ‘design’ stage, and not understood as a burdensome feature to be added in at the end.
> 3. Practitioners should engage routinely with the formal practice of threat modeling and risk analysis, guided by leaders in the field, and following the example of communities engaged in digital security.
> 4. Security management plans should aim to mitigate risks while also acknowledging their ever-presence and unavoidable nature (i.e., harm reduction approach).
> 5. Planning for security must take into account situational contexts, local realities, the individual positionalities and identities of practitioners, and the inherently intersectional nature of threat environments and attack vectors.
> 6. Any analysis, prediction, and planning should be understood as temporary—a snapshot in time—and as such, security planning should prioritize those approaches that are agile, adaptable, and suited to persistent refinement and adaptation.
> 7. Digital operational security (e.g., secure communications, anti/counter-surveillance) must feature as a central comment of any skills-based training, with the acknowledgment that any specific mitigations and technological solutions are temporary fixes in an ever-present, ongoing, electronic arms race.
> 8. A standardized set of tools can help form the basis of a first-stage analysis to be used in identifying risks, dangers, and insecurities. Such a toolkit should include standard approaches (e.g., mind maps, SWOT analyses, risk matrices), as well as more closely-tailored tools, such as those driven by user archetype, motive, and capability assessment.

## Prepare

Before researching or engaging, lay the foundations for your security strategy. 

* Map out your existing security practices
* Consider how personal beliefs and values inform our perception of security
* [What is Security?](https://holistic-security.tacticaltech.org/chapters/prepare/chapter-1-1-what-is-holistic-security.html)

## Explore the Threats

It's important to consider the operational environment and understand the threats you are facing

* Map out our vision and the actors around us in this context
* Create an inventory of our information as a resource for our work, and understand the threats to it
* Identify and analyse the most relevant threats to our security.
* [Threat Context Analysis](https://holistic-security.tacticaltech.org/chapters/explore/2-1-overall-framework-for-context-analysis.html)

## Strategize

Next we need to identify how we match the capabilities we have to the risks we face and identify any key gaps. 

* Map out how your existing strategies meet the threats
* Identify new capacities or practices you want to build
* [Responding to Threats](https://holistic-security.tacticaltech.org/chapters/strategise/3-1-responding-to-threats.html)

## Act
Go and do your research safely and securely. Be mindful - threats and risks are constantly changing. Preparing, exploring and strategizing a constant flow and cycle that we should be continually evaluating. 

Below are resources to help you identify capabilities and gaps that you should consider.

## Digital Security Resources
### VPNs

Use a VPN (Virtual Private Network): A VPN encrypts your internet connection, making it harder for third parties to track your online activities. It also masks your IP address, enhancing anonymity. [NordVPN and ExpressVPN](https://www.comparitech.com/blog/vpn-privacy/expressvpn-vs-nordvpn/) are popular choices though the market is constantly changing. Your VPN can also be useful in creating an appropriate persona as you can alter the exit node to appear to be connecting from a different region (be sure to update timezones and language packs on your device or VM to match if an illusion is important!).

#### TOR

[TOR, short for The Onion Router](https://www.torproject.org/), is a free and open-source software that enables anonymous communication over the internet. It directs internet traffic through a worldwide volunteer network of servers to conceal a user's location and usage from anyone conducting network surveillance or traffic analysis. TOR is often used to access websites on the dark web or to bypass censorship.

### Encryption

Encrypt sensitive data and communications using tools like [Signal](https://signal.org/) for messaging and [VeraCrypt](https://www.veracrypt.fr/) for file encryption. 

### Device separation

Use separate devices for personal and research purposes to minimize the risk of cross-contamination of data and potential security breaches.

#### Virtual Machines

Using Virtual Machines (VMs) is a one strategy strategy for device separation. VMs create isolated environments on your computer where you can conduct research activities without risking your primary operating system's integrity. They allow you to experiment with potentially malicious software or visit risky websites while minimizing the risk of compromising your personal data or system. Tools like [VMware](https://www.vmware.com/) and [VirtualBox](https://www.virtualbox.org/) offer robust VM solutions that can be configured with different operating systems and security settings. Organizations like Trace Labs provide resources and challenges that can help hone your skills in using VMs effectively. They also have an initiative to build an [OSINT VM](https://www.tracelabs.org/initiatives/osint-vm) which is a quick way to get started and have access to the most popular OSINT tools and scripts all neatly packaged under one roof.

### Identity separation

Create separate identities, personas, or [sock puppets](https://ztrkouzhan.medium.com/the-mega-sock-puppets-tutorial-for-osint-af3bd29dd5fc) for research activities. This can involve using different email addresses, usernames, and pseudonyms to protect your real identity. Think about how and where you create these accounts. If you use your personal phone number it may not be enough separation, if you create it from your university office, it may not be enough separation. Consider the list of personas and their characteristics (age, DoB, ethnicity, religion, ideologies, etc.) and the accounts they own. The use of a VPN can enhance a persona as it can give the illusion of coming from a particular region - or perhaps just coming from a VPN is important for a more technical persona.

### Best practices: Cloud storage

Utilize encrypted cloud storage services like [Google Drive](https://www.google.com/drive/) with two-factor authentication enabled, or secure alternatives like [Tresorit](https://tresorit.com/) or [SpiderOak](https://spideroak.com/)

### Browsers

Use privacy-focused browsers like [Mozilla Firefox](https://www.mozilla.org/firefox/) with extensions such as [uBlock Origin](https://ublockorigin.com/) for ad-blocking and [HTTPS Everywhere](https://www.eff.org/https-everywhere) for secure browsing. How your browser appears online can be highly unique but you can alter this fingerprint using add-ons such as [User-Agent Switcher](https://addons.mozilla.org/en-US/firefox/addon/user-agent-switcher-revived/).

### Pubic data removal & social media lockdown

Regularly audit and remove public data from online platforms especially social media profiles to limit personal information visibility. Tools like [DeleteMe](https://www.abine.com/deleteme/) or [Optery](optery.com)can assist in removing personal data from public databases.

### Doxxing, Abuse and Harassment

Unfortunately, there is a constant threat to researchers of doxxing, abuse, and coordinated harassment. Doxxing involves the malicious act of publicly revealing personal information about an individual, such as their home address, phone number, family members' details, or other identifying information. For researchers, this exposure can lead to harassment, threats, or even physical harm from extremist groups or individuals opposed to their work. It can also result in professional repercussions, such as damage to reputation or career disruption. Researchers may become targets of doxxing campaigns as a means to intimidate, discredit, or silence their work, making it crucial for them to adopt stringent security measures to protect their personal information and maintain their safety online.

There is lots of information about how to protect yourself from Doxxing and other coordinated harassment as well as how to respond if and when this happens:

* [DHS - Resources for Individuals on the Threat Of Doxing](https://www.dhs.gov/sites/default/files/2024-01/24_0117_ope_resources-for-individuals-on-the-threat-of-doxing-508.pdf)
* [Pen America - Explaining what is online abuse and the forms it can take](https://onlineharassmentfieldmanual.pen.org/what-is-online-abuse/)
* [Crash Override  Network - tools for dealing with online abuse](http://www.crashoverridenetwork.com/resources.html)
* [Digital First Aid - Step-by-step process for what to do in a wide variety of circumstances](https://digitalfirstaid.org/en/)

### Additional Digital Resources

* [VoxPol - Researcher Welfare 1: Privacy and Security](https://voxpol.eu/researcher-welfare-1-privacy/)
* [Advice on how to stay secure online from the UK's National Cyber Security Centre](https://www.ncsc.gov.uk/cyberaware/home)
* [NCSC - Cybersecurity for Individuals](https://www.ncsc.gov.uk/section/infographics/individuals))
* [Security in a Box](https://securityinabox.org/en/)

## Physical Safety Resources for Practitioners 
[Risks, Dangers, and Threat Models: Evaluating Security Analysis for Conflict Practitioners](https://www.researchgate.net/publication/354506971_Risks_Dangers_and_Threat_Models_Evaluating_Security_Analysis_for_Conflict_Practitioners)
_TODO: EXPAND THIS SECTION_

