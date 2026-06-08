
# Data & Ethics  Final Exam Review


---

## Table of Contents
1. [Moral, Ethics, Law & Society](#1-moral-ethics-law--society)
2. [Ethical Theories (+ judging a case)](#2-ethical-theories)
3. [Code of Ethics vs Code of Conduct](#3-code-of-ethics-vs-code-of-conduct)
4. [Security  CIA, Encryption, Digital Signature](#4-security--cia-encryption-digital-signature)
5. [Privacy & Information/Data Disclosure](#5-privacy--informationdata-disclosure)  ·  incl. [Acts & External Frameworks (SDAIA, GDPR)](#56-acts--external-frameworks)
6. [Bias & Fairness  Seven Sources of Harm](#6-bias--fairness--seven-sources-of-harm)
7. [Intellectual Property Types](#7-intellectual-property-types)
8. [Data and Ethics](#8-data-and-ethics)
9. [Ethical Issues in Data / Cybersecurity](#9-ethical-issues-in-data--cybersecurity)
10. [Best Practices in Data / Cybersecurity](#10-best-practices-in-data--cybersecurity)
- [Quick Exam Reminders](#-quick-exam-reminders)

---

## 1. Moral, Ethics, Law & Society
*(الأخلاق، المبادئ، القانون والمجتمع)*

**Morality vs Ethics** 

| | **Ethics** (الأخلاق العامة) | **Morals** (المبادئ الشخصية) |
|---|---|---|
| What | Rules of conduct for a class of actions / a group / culture | Personal principles or habits of right & wrong |
| Source | **Social system  External** | **Individual  Internal** |
| Why | Society says it's the right thing | We believe something is right/wrong |
| Origin | Greek *"ethos"* = **character** | Latin *"mos"* = **custom** |
| Acceptability | Governed by professional/legal guidelines in a time & place | Transcends cultural norms |

**Society → Morality → Ethics → Law**  *(filled gap)*
- **Society:** people in communities  universal, local, and online (Zoom, Reddit, Discord).
- **Law:** rules of conduct, enforceable by a formal body; **laws are derived from moral codes**. Two types:
  - **Natural Law (القانون الطبيعي):** unwritten but **universal**  rights of self-preservation, property, liberty, and human dignity. Civilization is based on it.
  - **Conventional Law (القانون الوضعي):** made by and for humans, **varies by society**; protects life/property/liberty and prescribes punishments (penal code).

**Is computer ethics unique?  Walter Maner** 
- Some issues are so **transformed** by computers they deserve study in their **radically altered form**; computing can create **entirely new ethical issues** unique to it.
- Why study it:
  - (1) to **behave** like responsible professionals;
  - (2) to **avoid** computer abuse/catastrophes;
  - (3) because technology keeps creating **temporary policy gaps**.

---

## 2. Ethical Theories
*(النظريات الأخلاقية)*  

**Summary table  what each decision is based on:**

| Theory (النظرية) | Decision is based on… |
|---|---|
| 1. Consequentialism (العواقبية) | the **outcome / results** |
| 2. Deontology (الواجب) | whether it's done as a **duty** |
| 3. Human Nature (الطبيعة البشرية) | the **capabilities** of the actor |
| 4. Relativism (النسبية) | what's **relative to society** (no universal norms) |
| 5. Hedonism (اللذة) | seeking **maximum pleasure** for all |
| 6. Emotivism (العاطفية) | **feelings**  statements are neither true nor false, depend on the person |
| 7. Virtue (الفضيلة) | the actor's **character** (the "mean") |

**Each theory + 2 examples:**

- **Consequentialism (العواقبية)**  judged by results. Types:
  - **Egoism (الأنانية)** = self first;
  - **Utilitarianism (النفعية)** = the group first;
  - **Altruism (الإيثار)** = favours everyone *except* the actor.
  - **Examples:**
    - Releasing an AI model is "good" because overall it helps more than it harms.
    - Collecting data without consent is "right" only if benefits outweigh harms.
- **Deontology (الواجب)**  good if done as a duty.
  - Killing vs killing to save lives.
  - Hacking vs **ethical hacking** (a tester with permission acts from duty).
- **Human Nature (الطبيعة البشرية)**  judged by the actor's capabilities.
  - "Guilty by reason of insanity"  the actor lacked capability.
  - Letting people with no technical skills make data decisions → bad choices.
- **Relativism (النسبية)**  right/wrong depend on society and **change over time**.
  - Accessing a child's phone/data: normal in KSA, viewed differently in the US.
  - Marrying within the (royal) family  accepted in some societies, not others.
- **Hedonism (اللذة)**  pleasure is the **only** good; people *ought* to seek it.
  - Choosing the most enjoyable option is the "right" one.
  - Sharing personal data for fun/convenient apps because the pleasure is treated as good.
- **Emotivism (العاطفية)**  statements just express **how someone feels**.
  - "Gun restrictions are bad" = they make me feel unsafe.
  - Using a machine (not a human) for elderly patients/bank transactions is "wrong" because it makes them nervous.

**Virtue Ethics (أخلاق الفضيلة)** 
- Treats **virtue and character** as the **primary subjects** of ethics (vs consequences, rules, or divine authority).
- Right action = **what a virtuous person, acting in character, would do** in the same situation.
- The virtue ethicist **rejects** simply (a) following rules or (b) chasing certain consequences.
- **Virtue = the mean**; both **deficiency** and **excess** become vices: e.g., **Courage** between cowardice (deficiency) and foolhardiness/suicide-bomber (excess); **Anger** = protesting injustice (good) vs controlling innocents with power (bad).
- **Case against:** people differ on "human flourishing"; it can't guide **government policy**; it can **undermine holding people responsible**.

**Worked case  judging ONE case with multiple theories**  *(filled gap; this is the "judge a case using different theories" skill)*
*Scenario: a company suffers a minor breach and considers staying silent to avoid panic.*
- **Deontology:** honesty is a **duty** → must inform customers, regardless of consequences.
- **Utilitarianism (consequentialism):** weigh harms  concealment risks bigger downstream harm (fraud, lost trust) → disclose + mitigate.
- **Virtue ethics:** an honest, responsible person (good character) discloses and takes responsibility.
- **Judgment:** all three converge → **disclose and remediate.**

**Course example (Virtue Ethics)  Matt & Josh**  *(Scenario Book 1, 2.10.2, p.91)*
- Matt's capstone code didn't meet spec; teammates rewrote it; in the final presentation he **claimed it as his own**. He asks Josh for a false good review so he can stay in school.
- **Decision (virtue ethics):** Josh must be **truthful** with the professor, won't just say "Matt was poor," and **takes responsibility for his own role** in the outcome → honesty + accountability.

**Ethical Decision-Making Framework**   
  - recognize the ethical conflict
  - understand the problem & facts
  - know the parties
  - be aware of alternatives
  - know ethical practices
  - understand how it's implemented & who's affected
  - understand the impact on affected parties.

---

## 3. Code of Ethics vs Code of Conduct
*(مدونة الأخلاق مقابل مدونة السلوك)*  

| | **Code of Ethics** | **Code of Conduct** |
|---|---|---|
| Governs | **Decision-making** | **Actions / behaviour** |
| What it is | Broad **values & principles** | Specific **rules** |
| Answers | "Why"  what should guide us | "What/how"  what's allowed or not |
| Style | General, aspirational | Concrete, enforceable |
| Discipline | Usually none | Often lists **penalties** for violations |
| Example | ACM Code of Ethics | Workplace rules (SDAIA / NCA) |

**One line:** *A code of ethics shapes how you decide; a code of conduct controls what you do.*

---

## 4. Security  CIA, Encryption, Digital Signature
*(الأمن:  الـ CIA، التشفير، التوقيع الرقمي)*  

**Security** = a means to prevent unauthorized **access, use, alteration, theft, or physical damage**.

**The CIA triad:**
- **Confidentiality (السرية):** prevent unauthorized **disclosure**.
- **Integrity (السلامة):** prevent unauthorized **modification** (maintain status quo).
- **Availability (التوفر):** prevent unauthorized **withholding** (access when needed). *(A **DDoS** attack violates availability.)*

**Physical Security:** 
- **Physical barriers:** fences, walls, motion sensors, CCTV, locks/keys, infrared/ultrasonic detectors, dogs.
- **Electronic controls:** card-access systems, firewalls, passwords.
> **Physical Access Controls** = physical barriers + electronic protocols.

**Passwords** *(external: Microsoft 365 Admin)*  don't reuse work passwords; enforce **MFA**; enable identity-protection risk policies; pair resets with an authentication app.

**Encryption (التشفير):**
- **Symmetric / secret-key:** one shared key (fast; problem = **key distribution**).
- **Asymmetric / public-key:** **two keys**  public (known to all) + private (sender/receiver).
- **Hash function:** one-way; creates a **message digest** ("fingerprint") → provides **integrity & authenticity**.

**Authentication & Digital Signature:**
- **Authentication** verifies a user is **genuine** (identity + message integrity). *Note: authentication ≠ integrity itself  integrity is its own pillar.*
- **Digital signature:** sender signs with **private key**, receiver verifies with the sender's **public key**; valid if hashes match. Two parts: a method of **signing**, and **authentication** that the signature is truly the signer's.

---

## 5. Privacy & Information/Data Disclosure
*(الخصوصية والكشف عن المعلومات/البيانات)*

**Privacy** = a human attribute of **four elements**, in two categories :
- **Control of external influences:**
  - 1. **Solitude** (be alone),
  - 2. **Anonymity** (no public identity),
  - 3. **Intimacy** (not monitored).
- **Control of personal information:**
  - 4. **Reserve** (control your info & how it spreads).

**Types of Privacy** : 
  - **Personal** (personal *attributes*; e.g., US 4th Amendment) ·
  - **Informational** (protecting the *information itself*  personal/financial/medical) ·
  - **Institutional** (an *organization's* data; e.g., Samsung's source code put into ChatGPT).

**Anonymity (إخفاء الهوية)**   good & bad sides.
- *Advantages:* whistleblowing in an organization, national security, protecting some people.
- *Disadvantages:* criminals can exploit it (online social networks).
- **Pseudonymity vs untraceable identity** / *(filled gap)*: **Pseudonymity** = identified by a code/pen-name (linkable with extra info); SDAIA defines **pseudonymisation** as converting identifiers into codes that make direct identification difficult without additional data. **Untraceable identity** = known by no name at all (not linkable).

**Information Disclosure**  = making **confidential/sensitive info public without the owner's consent**; can be intentional or unintentional → identity theft, fraud, reputational damage.
- **Enhanced 911 Services:** US providers must (by law) track active users within 100 m → *benefit:* reach people in distress; *downside:* privacy loss if location is sold/shared (e.g., a manager tracking a "sick" employee).

**Privacy Right Protection  Guidelines/Structures** : **Technical** (self-regulation, e.g., cookie notices), **Contractual** (protection vs unauthorized reproduction/distribution), **Legal** (laws + enforcement  e.g., **FERPA, 1974**: gives students/parents access to records, limits disclosure to third parties).

**Data Controller vs Data Processor**  *(filled gap)*:
- **Controller (المتحكم):** decides the **purposes and means** of processing  bears **accountability** (e.g., must notify SDAIA of a breach within 72h). In the course's *institutional privacy*, responsibility sits with **executives, privacy officers, and IT**.
- **Processor (المعالج):** processes data **on the controller's behalf**, following the controller's instructions (e.g., a cloud/analytics vendor).

### 5.6 Acts & External Frameworks
*(القوانين والأطر الخارجية)*


**SDAIA  Personal Data Disclosure Cases Guideline (the six cases)** 
*Interprets the Saudi **PDPL**; the Guideline is **non-binding**  the Law & Implementing Regulations are the reference. Across all cases the controller must tie disclosure to a **defined purpose**, exercise **due diligence**, and apply **data minimization** (only the minimum data necessary).*
1. **Consent** of the personal data subject.
2. **Publicly available source**  data lawfully obtained from a source already public.
3. **Public-entity request**  for **public interest, security, implementing another law, or judicial requirements** (minimum data only).
4. **Public health/safety**  to safeguard public health, public safety, or the **life/health of specific individuals** (e.g., emergencies).
5. **De-identified subsequent processing**  disclosure limited to processing that **does not identify** the data subject or any other individual.
6. **Controller's legitimate interests**  allowed **only if**: it doesn't unduly prejudice the data subject's rights, it's within the data subject's **reasonable expectations**, it does **NOT** involve **sensitive data**, and the controller has done a documented **Legitimate-Interest Assessment**. (Examples: detecting fraud, network/information security.)

**SDAIA  Personal Data Breach (Procedural Guide, Oct 2024)**   the **Controller** must notify **SDAIA within 72 hours** of a breach likely to harm data subjects, and notify affected **data subjects** without undue delay. Three stages: **SDAIA Notice → Containment → Documentation.** Roles: Controller, Data Subject, **DPO**. (PDPL: Royal Decree M/19, amended M/148.)

**GDPR  EU General Data Protection Regulation**  *(filled gap)*  comprehensive EU data-protection law (in force 2018), with **extraterritorial** reach.
- **Roles:** controller (decides purposes/means) and processor (acts on its behalf).
- **Breach notice:** authority within **72 hours** (Art. 33); individuals without undue delay if **high risk** (Art. 34).
- **Principles (Art. 5):** lawfulness/fairness/transparency, purpose limitation, **data minimization**, accuracy, storage limitation, integrity & confidentiality, accountability.
- **SDAIA/PDPL vs GDPR:** both use controller/processor roles, the **72-hour** rule, and **data minimization**; PDPL bars the **legitimate-interest** basis for **sensitive** data and gives ~30 days (extendable) for data-subject requests (GDPR ≈ 3 months for complex ones).

---

## 6. Bias & Fairness  Seven Sources of Harm
*(التحيّز والعدالة  مصادر الضرر السبعة)*  

**Data generation (توليد البيانات):**
- **Historical Bias**  e.g., word embeddings.
- **Representation Bias**  e.g., population sampling, image-dataset geographic diversity.
- **Measurement Bias**  e.g., feature selection, criminal-justice risk assessments.

**Model building (بناء النموذج):**
- **Aggregation Bias**  one-size-fits-all model.
- **Learning Bias**  accuracy, pruning.
- **Evaluation Bias**  benchmark not matching the use population (e.g., facial-analysis tools).
- **Deployment Bias**  risk-assessment tools used in practice.

*Memory tip:* 3 in data generation, 3 in model building, + **Deployment** (real-world use). Detecting bias **after deployment** → **continuous monitoring & auditing**. Imbalanced data → the model **favors the over-represented group** (never "auto-unbiased").

---

## 7. Intellectual Property Types
*(أنواع الملكية الفكرية)*  

**IP** = any **unique product of the human intellect with commercial value** (books, songs, inventions, formulas, programs). **IP ≠ its physical manifestation.**

**Four types**, each compared by **Public domain · Duration · Applications**:

| Type | Key facts |
|---|---|
| **Trade Secret (السر التجاري)** | Confidential, gives competitive advantage; **never expires**; **reverse engineering allowed**; lost if leaked/public; in US = **state law** (no federal). *Ex: Coca-Cola formula, Google search algorithm.* |
| **Trademark / Service Mark (العلامة التجارية)** | Trademark = identifies **goods**; service mark = **services**; a "brand name"; **does not expire**; **lost if it becomes a common noun**; protected via advertising & contacting misusers. |
| **Patent (براءة الاختراع)** | Public document; **exclusive right ~20 years**; types **Utility / Design / Plant**. |
| **Copyright (حقوق النشر)** | 5 rights: reproduction, distribution, public display, public performance, derivative works; ~6% of US GDP. |

**IP for Data (data vs database)**  *(filled gap)*: **raw data/facts generally can't be copyrighted**, but an **original, curated database** (the selection & arrangement) **can** be protected. *(So a company's organised dataset may be protectable even when the underlying facts aren't.)*

---

## 8. Data and Ethics
*(البيانات والأخلاق)*  

**Big Data Ethics Principles** (datacamp): **Transparency**, **Accountability**, **Individual Agency** (access/correct/delete your data), **Data Privacy**.

**What does ethics have to do with data?** (Markkula Center)  no single rule set fits all contexts; a **"perfect storm of ethical risks"** (powerful/misused analytics, poorly-regulated market, missing standards) makes a **broader understanding of data ethics** essential.

**Data Stewardship:** have an **end-to-end lifecycle plan**, a **data steward (governance)**, and standards to **delete/correct/update** data; technique example = **data scrambling** (replace real values with fake ones).

**Data Hygiene & Relevance:** validate/audit data, ensure **consistent field labels** and **integrity during transfer**, **scrub dirty data**, and **refresh out-of-date datasets**.

---

## 9. Ethical Issues in Data / Cybersecurity
*(القضايا الأخلاقية في البيانات/الأمن السيبراني)*  

**Common ethical challenges:** balancing **security vs other values**; **threat/incident response**; **breach/vulnerability**; **network monitoring vs privacy**; **competing interests & obligations**; **data storage & encryption**; **IoT / smart grid / product design**; **accountability**; broader impacts.

**Important ethical issues  roles, duties & interests:** cybersecurity is **costly** (time, money, expertise); **usability can't justify weakening** security; **resource allocation** is itself ethical  find the right **balance** (e.g., a slow secure logon vs physicians needing fast access). Staff should **weigh harms, benefits, rights, and values before deciding.**

---

## 10. Best Practices in Data / Cybersecurity
*(أفضل الممارسات في البيانات/الأمن السيبراني)*  

**Shared best practices (data & cybersecurity):**
- Keep ethics **in the spotlight  out of the compliance box**.
- Consider the **human lives & interests** behind data/systems.
- Focus on **downstream risks & uses**.
- Establish **chains of responsibility & accountability**.
- **Design for privacy & security**.
- **Invite diverse stakeholder input**.
- *(Cybersecurity adds:* disaster planning/crisis response; promote transparency, autonomy, trustworthiness.*)*
- *(Data adds:* mind the expectation–reality gap; treat data as a **conditional good**.*)*

**Best practices for living well:** look for **moral exemplars**, exercise **moral imagination**, practice **self-reflection**, acknowledge your **moral strength**, seek the **company of other moral persons**.

