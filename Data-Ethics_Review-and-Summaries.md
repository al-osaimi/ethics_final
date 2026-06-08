

#  Data & Ethics  Final Exam Review

Quick-revision notes for the final, organized to match the **10 exam topics** from the *Topics* slides.

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

## 1. Moral, Ethics, Law & Society *(الأخلاق، المبادئ، القانون والمجتمع)*


**Morality vs Ethics**

| | **Ethics** (الأخلاق العامة) | **Morals** (المبادئ الشخصية) |
|---|---|---|
| **What** | Rules of conduct for a class of actions / a group / culture | Personal principles or habits of right & wrong |
| **Source** | **Social system  External** | **Individual  Internal** |
| **Why** | Society says it's the right thing | We believe something is right/wrong |
| **Origin** | Greek *"ethos"* = **character** | Latin *"mos"* = **custom** |
| **Acceptability** | Governed by professional/legal guidelines in a time & place | Transcends cultural norms |

**Society → Morality → Ethics → Law**
- **Society:** people in communities  universal, local, and online (Zoom, Reddit, Discord).
- **Law:** rules of conduct, enforceable by a formal body; **laws are derived from moral codes**. Two types:
  - **Natural Law (القانون الطبيعي):** unwritten but **universal**  rights of self-preservation, property, liberty, and human dignity. Civilization is based on it.
  - **Conventional Law (القانون الوضعي):** made by and for humans, **varies by society**; protects life/property/liberty and prescribes punishments (penal code).

**Is computer ethics unique?  Walter Maner**
- Some issues are so **transformed** by computers they deserve study in their **radically altered form**; computing can create **entirely new ethical issues** unique to it.
- Why study it:
  1. to **behave** like responsible professionals;
  2. to **avoid** computer abuse/catastrophes;
  3. because technology keeps creating **temporary policy gaps**.

---

## 2. Ethical Theories *(النظريات الأخلاقية)*

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

> [!TIP]
> **Worked case  judging ONE case with multiple theories** *(the "judge a case using different theories" skill)*
> *Scenario: a company suffers a minor breach and considers staying silent to avoid panic.*
> - **Deontology:** honesty is a **duty** → must inform customers, regardless of consequences.
> - **Utilitarianism (consequentialism):** weigh harms  concealment risks bigger downstream harm (fraud, lost trust) → disclose + mitigate.
> - **Virtue ethics:** an honest, responsible person (good character) discloses and takes responsibility.
> - **Judgment:** all three converge → **disclose and remediate.**

**Course example (Virtue Ethics)  Matt & Josh** *(Scenario Book 1, 2.10.2, p.91)*
- Matt's capstone code didn't meet spec; teammates rewrote it; in the final presentation he **claimed it as his own**. He asks Josh for a false good review so he can stay in school.
- **Decision (virtue ethics):** Josh must be **truthful** with the professor, won't just say "Matt was poor," and **takes responsibility for his own role** in the outcome → honesty + accountability.

**Ethical Decision-Making Framework**
- recognize the ethical conflict
- understand the problem & facts
- know the parties
- be aware of alternatives
- know ethical practices
- understand how it's implemented & who's affected
- understand the impact on affected parties

---

## 3. Code of Ethics vs Code of Conduct *(مدونة الأخلاق مقابل مدونة السلوك)*

| | **Code of Ethics** | **Code of Conduct** |
|---|---|---|
| **Governs** | **Decision-making** | **Actions / behaviour** |
| **What it is** | Broad **values & principles** | Specific **rules** |
| **Answers** | "Why"  what should guide us | "What/how"  what's allowed or not |
| **Style** | General, aspirational | Concrete, enforceable |
| **Discipline** | Usually none | Often lists **penalties** for violations |
| **Example** | ACM Code of Ethics | Workplace rules (SDAIA / NCA) |

> [!IMPORTANT]
> **One line:** a code of ethics shapes **how you decide**; a code of conduct controls **what you do**.

---

## 4. Security  CIA, Encryption, Digital Signature *(الأمن: الـ CIA، التشفير، التوقيع الرقمي)*

**Security** = a means to prevent unauthorized **access, use, alteration, theft, or physical damage**.

**The CIA triad:**
- **Confidentiality (السرية):** prevent unauthorized **disclosure**.
- **Integrity (السلامة):** prevent unauthorized **modification** (maintain status quo).
- **Availability (التوفر):** prevent unauthorized **withholding** (access when needed). *(A **DDoS** attack violates availability.)*

> [!NOTE]
> **Physical Access Controls** = physical barriers + electronic protocols.

**Physical Security:**
- **Physical barriers:** fences, walls, motion sensors, CCTV, locks/keys, infrared/ultrasonic detectors, dogs.
- **Electronic controls:** card-access systems, firewalls, passwords.

**Passwords** *(external: Microsoft 365 Admin)*  don't reuse work passwords; enforce **MFA**; enable identity-protection risk policies; pair resets with an authentication app.

**Encryption (التشفير):**
- **Symmetric / secret-key:** one shared key (fast; problem = **key distribution**).
- **Asymmetric / public-key:** **two keys**  public (known to all) + private (sender/receiver).
- **Hash function:** one-way; creates a **message digest** ("fingerprint") → provides **integrity & authenticity**.

**Authentication & Digital Signature:**
- **Authentication** verifies a user is **genuine** (identity + message integrity). *Note: authentication ≠ integrity itself  integrity is its own pillar.*
- **Digital signature:** sender signs with **private key**, receiver verifies with the sender's **public key**; valid if hashes match. Two parts: a method of **signing**, and **authentication** that the signature is truly the signer's.

---

## 5. Privacy & Information/Data Disclosure *(الخصوصية والكشف عن المعلومات/البيانات)*

**Privacy** = a human attribute of **four elements**, in two categories:
- **Control of external influences:**
  - 1 **Solitude** (be alone),
  - 2 **Anonymity** (no public identity),
  - 3 **Intimacy** (not monitored).
- **Control of personal information:**
  - 4 **Reserve** (control your info & how it spreads).

**Types of Privacy:**
- **Personal** (personal *attributes*; e.g., US 4th Amendment)
- **Informational** (protecting the *information itself*  personal/financial/medical)
- **Institutional** (an *organization's* data; e.g., Samsung's source code put into ChatGPT)

**Anonymity (إخفاء الهوية)**  good & bad sides.
- *Advantages:* whistleblowing in an organization, national security, protecting some people.
- *Disadvantages:* criminals can exploit it (online social networks).
- **Pseudonymity vs untraceable identity:**
  - **Pseudonymity (الأسماء المستعارة)** = identified by a code/pen-name (linkable with extra info); SDAIA defines **pseudonymisation** as converting identifiers into codes that make direct identification difficult without additional data.
  - **Untraceable identity (هوية لا يمكن تتبعها)** = known by no name at all (not linkable).

**Information Disclosure** = making **confidential/sensitive info public without the owner's consent**; can be intentional or unintentional → identity theft, fraud, reputational damage.
- **Enhanced 911 Services:** US providers must (by law) track active users within 100 m → *benefit:* reach people in distress; *downside:* privacy loss if location is sold/shared (e.g., a manager tracking a "sick" employee).

**Privacy Right Protection  Guidelines/Structures:**
- **Technical** (self-regulation, e.g., cookie notices)
- **Contractual** (protection vs unauthorized reproduction/distribution)
- **Legal** (laws + enforcement  e.g., **FERPA, 1974**: gives students/parents access to records, limits disclosure to third parties)

**Data Controller vs Data Processor:**
- **Controller (المتحكم):** decides the **purposes and means** of processing  bears **accountability** (e.g., must notify SDAIA of a breach within 72h). In the course's *institutional privacy*, responsibility sits with **executives, privacy officers, and IT**.
- **Processor (المعالج):** processes data **on the controller's behalf**, following the controller's instructions (e.g., a cloud/analytics vendor).

### 5.6 Acts & External Frameworks *(القوانين والأطر الخارجية)*

**SDAIA  Personal Data Disclosure Cases Guideline (the six cases)** · [official PDF](https://sdaia.gov.sa/Documents/PersonalDataDisclosureCasesGuideline.pdf)

Under the Saudi **Personal Data Protection Law (PDPL)**, the Controller shall **not disclose** personal data  **except** in the six cases below.

#### 1. Consent of the Personal Data Subject
- The data subject has explicitly consented to the disclosure of their personal data.

#### 2. Personal Data Collected from a Publicly Available Source
- The personal data was obtained from a publicly available source.
- Disclosure must comply with applicable laws and regulations.

#### 3. Request by a Public Entity
- Disclosure is required by a public authority for:
  - Public interest purposes.
  - Security purposes.
  - Implementation of another law.
  - Judicial or court requirements.

#### 4. Protection of Public Health or Safety
- Disclosure is necessary to protect:
  - Public health.
  - Public safety.
  - The life or health of one or more individuals.

#### 5. Anonymized or Non-Identifiable Processing
- Disclosure is limited to subsequent processing where the data cannot identify:
  - The personal data subject, or
  - Any specific individual.

#### 6. Legitimate Interests of the Controller
- Disclosure is necessary to achieve the legitimate interests of the controller.
- The disclosure must:
  - Not adversely affect the rights or interests of the data subject.
  - Not involve sensitive personal data unless permitted by law.
  - *(Examples: detecting fraud, network/information security.)*

**GDPR  EU General Data Protection Regulation**  comprehensive EU data-protection law (in force 2018), with **extraterritorial** reach.
- **Roles:** controller (decides purposes/means) and processor (acts on its behalf).
- **Breach notice:** authority within **72 hours** (Art. 33); individuals without undue delay if **high risk** (Art. 34).
- **Principles (Art. 5):** lawfulness/fairness/transparency, purpose limitation, **data minimization**, accuracy, storage limitation, integrity & confidentiality, accountability.

> [!NOTE]
> **SDAIA/PDPL vs GDPR:** both use **controller/processor** roles, the **72-hour** breach rule, and **data minimization**; the PDPL **bars the legitimate-interest basis for *sensitive* data** and gives ~30 days (extendable) for data-subject requests (GDPR ≈ 3 months for complex ones).

---

## 6. Bias & Fairness  Seven Sources of Harm *(التحيّز والعدالة  مصادر الضرر السبعة)*

**Data generation (توليد البيانات):**
- **Historical Bias**  e.g., word embeddings.
- **Representation Bias**  e.g., population sampling, image-dataset geographic diversity.
- **Measurement Bias**  e.g., feature selection, criminal-justice risk assessments.

**Model building (بناء النموذج):**
- **Aggregation Bias**  one-size-fits-all model.
- **Learning Bias**  accuracy, pruning.
- **Evaluation Bias**  benchmark not matching the use population (e.g., facial-analysis tools).
- **Deployment Bias**  risk-assessment tools used in practice.

> [!TIP]
> - 3 in **data generation**
> - 3 in **model building**
> - 1 in **deployment** (real-world use)

---

## 7. Intellectual Property Types *(أنواع الملكية الفكرية)*

**IP** = any **unique product of the human intellect with commercial value** (books, songs, inventions, formulas, programs). **IP ≠ its physical manifestation.**

**Four types**, each compared by **Public domain · Duration · Applications**:

| IP Type | Protects | Duration | Key facts & examples |
|---|---|---|---|
| 🔒 **Trade Secret**<br>*(السر التجاري)* | Confidential info that gives a **competitive advantage** | **Never expires** (while secret) | Reverse engineering **allowed** · lost once public · US = **state law** (no federal).<br>*Ex: Coca-Cola formula, Google's search algorithm* |
| ™️ **Trademark / Service Mark**<br>*(العلامة التجارية)* | Brand identifiers  **goods** (trademark) vs **services** (service mark) | **Does not expire** | Lost if it becomes a **common noun** · protected via advertising & pursuing misuse.<br>*Ex: brand names; American Airlines (service)* |
| 💡 **Patent**<br>*(براءة الاختراع)* | **Inventions**  a public document; exclusive right to make/use/sell | **~20 years** | Three types: **Utility · Design · Plant** |
| ©️ **Copyright**<br>*(حقوق النشر)* | **Original works** (the *expression*) | Long-term | **5 rights:** reproduction · distribution · public display · public performance · derivative works (~6% of US GDP) |

**IP for Data (data vs database):** **raw data/facts generally can't be copyrighted**, but an **original, curated database** (the selection & arrangement) **can** be protected. *(So a company's organised dataset may be protectable even when the underlying facts aren't.)*

---

## 8. Data and Ethics *(البيانات والأخلاق)*

**significant harms and benefits can data present?**

**✅ Benefits of data:**

- Human understanding — data helps us understand the world and how complex systems work, so we can act more wisely.
- Social, institutional & economic efficiency — with a clearer picture, we can improve systems (example: big data improving regional traffic).
- Predictive accuracy & personalization — better predictions and personalized services make systems run more efficiently.

**⚠️ Harms of data:**
- Harms to privacy & security — personal data can be exposed, misused, or stolen (breaches, surveillance).
- Harms to fairness & justice — biased data or decisions can discriminate against people.
- Harms to transparency & autonomy — "black box" systems reduce people's understanding and control (example: a deep-learning loan model that rejects you but can't explain why).

**Data Stewardship (الإشراف المسؤول على البيانات):** 
have an **end-to-end lifecycle plan**, a **data steward (governance)**, and standards to **delete/correct/update** data.
  - **Example:** a hospital assigns a data steward for patient records who keeps a plan for how records are stored, who may see them, and how they're corrected or deleted on request — and uses **data scrambling** (replacing real names/ID numbers with fake ones) to protect them in test systems.

**Data Hygiene  (نظافة البيانات):** 
Data hygiene is the process of keeping databases clean and error-free. Data that is *outdated, incomplete, duplicated, or simply incorrect* is known as “dirty data,” 
  - **Example:** cleaning a customer contact list delete duplicate rows, make every phone number the same format, and update addresses that have changed.



---

## 9. Ethical Issues in Data / Cybersecurity *(القضايا الأخلاقية في البيانات/الأمن السيبراني)*

**Common ethical challenges** for cybersecurity professionals:
- **Balancing security vs other values**
- **Threat / incident response**
- **Security breach / vulnerability**
- **Network monitoring vs user privacy**
- **Competing interests & obligations**
- **Data storage & encryption**
- **IoT, smart grid & product design**
- **Accountability** for cybersecurity
- Understanding the **broader impacts** of cybersecurity practice

**Important ethical issues — roles, duties & interests:**
- Cybersecurity is **inevitably costly** it consumes **time, money, and expertise**.
- **Usability / product-viability concerns can't justify weakening** security.
- **Resource allocation** is itself an ethical issue  finding the right **balance** between security and competing needs.

> [!IMPORTANT]
> **Exam example:** a hospital adds a slow but very secure logon while physicians need fast access. Staff must **weigh harms, benefits, rights, and values before deciding.**

---

## 10. Best Practices in Data / Cybersecurity *(أفضل الممارسات في البيانات/الأمن السيبراني)*

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

---

## Quick Exam Reminders

> [!TIP]
> - **Ethics vs morals:** external/social vs internal/personal.
> - **Ethics vs conduct:** governs **decisions** vs governs **actions** (+ discipline).
> - **CIA:** Confidentiality = disclosure · Integrity = modification · Availability = withholding (**DDoS = availability**).
> - **Digital signature:** sign with **private**, verify with **public**.
> - **IP:** Patent ≈ 20 yrs + public · Trade secret = secret + forever (until leaked) · Trademark ≠ the algorithm.
> - **Seven sources of harm:** Historical, Representation, Measurement (data) → Aggregation, Learning, Evaluation (model) → **Deployment**.
> - **Privacy elements:** Solitude, Anonymity, Intimacy, Reserve.
> - **SDAIA disclosure:** 6 cases + **data minimization**; legitimate interests **not** for sensitive data.
> - **Controller** decides why/how (accountable); **processor** acts on its behalf.
> - **72-hour breach notice:** SDAIA **and** GDPR (Art. 33).
