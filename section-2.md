# Types of Hackers

## Classic Bad Guy: Black Hat
* Very skilled cyber criminals
* Hack primarily for financial interests

## Gray Hat
* Not necessarily bad guys
* Employ black hat tactics for white hat objectives
* Hack companies to discover vulnerabilities and inform them
* Companies' reactions vary

## Script Kiddie
* Annoying individuals in cybersecurity space
* Lack skills and knowledge
* Engage in hacking for fun and kicks
* Deface websites and show off to friends

## Hacktivists
* Not inherently evil or bad
* Hack for religious or social causes
* May target companies they perceive as acting illegally
* Examples: Anonymous, WikiLeaks

## Disgruntled Employee or Ex-Employee
* Dangerous within a company
* Unhappy with their situation, may seek revenge
* Knowledge of security policies and internal systems
* Can use this knowledge against the company

## Insider Threat
* Most dangerous adversary in cybersecurity
* Employee working within the company
* Acts as a spy or saboteur
* May be part of a black hat gang or have ulterior motives
* Especially dangerous if working in the IT or cybersecurity department

# The Hacking Methodology

* No official playbook or guide on hacking
* Hacking process is flexible but follows common steps

1. Reconnaissance Phase
2. Exploitation Phase
3. Privilege Escalation
4. Establishing Persistence
5. Actual Attack Phase
6. Cover Up

## Step 1: Reconnaissance or Footprinting
* Cyber criminals gather information about the target
* Two types: Passive Recon and Active Recon

## Step 2: Exploitation
* Hackers take advantage of identified vulnerabilities
* Methods include phishing emails, social engineering, weak passwords, unpatched software, and malware injection

## Step 3: Privilege Escalation
* Hackers gain control over the exploited target
* Increase control by creating accounts, hijacking the network, and targeting admin accounts

## Step 4: Establish Persistence
* Ensuring continued access after discovery
* Create backdoors, establish remote access control, etc.

## Step 5: Actual Attack Phase
* Data extraction, data corruption, malware injection, etc.

## Step 6: Cover Up
* Implement coverup to hide the attack
* Use techniques like ICMP tunnels, clearing event logs, erasing command history

# The WhoIS Query

* ICANN WHOIS website is used to look up admin contacts for websites.
* Individuals, businesses, organizations, governments register domain names and provide identifying information.
* This information is referred to as WHOIS data.

## Using the ICANN WHOIS website

let's look up "facebook.com" as an example:
* The website displays three different contacts: registrants, admin, and tech contact.
* Information includes mailing address, phone number, fax number, and email address (domain@fb.com).

For Facebook, it's challenging to cause malice using this information due to their security measures.
However, for small-sized websites or unaware individuals, cyber attackers can exploit this information.

* Attackers might call the phone number posing as a cybersecurity organization or send emails with malicious links.
* The link in the email could lead to viruses or malware.

ICANN WHOIS also provides the registration expiration date:
* For "facebook.com," it expires on March 29, 2025.
* If not renewed, someone could purchase the domain.

Additionally, name servers are listed, which experienced hackers can use to plan the next stage of an attack.

Let's look up another website, "wpbeginner.com," which is a resource for learning WordPress:
* Similar information is displayed, including the person's name (Syed Balkhi), organization (Boy Genius Inventions, LLC), mailing address, phone number, and email address (syedbalkhi@gmail.com).
* An attacker could send an email with malware or a virus attached, targeting this individual.

# Social Engineering Tactics - Part 1

## The Danger of Social Engineering
* Reliance on human error, which is less predictable than software or hardware vulnerabilities.
* Social engineering is a dangerous form of attack due to the unpredictability of human behavior.
* Employees are often vulnerable to social engineering attacks despite training.

## Five Main Tactics of Social Engineering

### Baiting
* Luring targets with unfavorable actions, such as malicious links or infected USB drives.
* Deliberately dropping infected USB drives in strategic locations.
* Exploiting curiosity by enticing individuals to pick up and connect an unknown USB drive.

### Pretexting
* Looking, acting, or sounding the part to gain trust and legitimacy.
* Impersonating a representative from a trusted organization or authority figure.
* Establishing a convincing backstory to manipulate individuals into sharing sensitive information.

### Quid pro quo
* Offering a service in exchange for valuable information.
* Posing as an IT support technician offering assistance in exchange for login credentials.
* Promising rewards or benefits in return for personal or confidential data.

### Phishing
* Creating a sense of excitement or panic through deceptive emails.
* Sending fraudulent emails that mimic reputable organizations to trick recipients.
* Urging recipients to click on malicious links or provide sensitive information.

### Vishing
* Manipulating individuals through phone calls.
* Impersonating bank representatives and requesting account details over the phone.
* Using social engineering techniques to extract personal information from unsuspecting victims.

## Kevin Mitnick - The Master Social Engineer
* Kevin Mitnick's expertise in social engineering and reputation as one of the greatest hackers.
* Mitnick's success in accessing important data through social engineering skills.

## Examples in Media
* The movie "Catch Me If You Can" tells the true story of Frank Abagnale Jr., a master social engineer who successfully impersonated a doctor, lawyer, and airline pilot at a young age.
* A popular YouTube video called "Hack Attack Vision" demonstrates how social engineers can lock someone out of their mobile account using vishing tactics.

# Social Engineering Tactics - Part 2

## Lunch Time Attack
  * Employee not logging off before leaving workstation
  * Risk of insider accessing important work
  * Importance of logging out during lunch
## Tailgating
  * Unauthorized person following an authorized person
  * Example from movie "Sneakers"
  * Planting seeds of conviction to gain access
## Piggybacking
  * Attacker enters secure building with permission of employee
  * Example from movie "Diamonds Are Forever"
  * James Bond's clever tactics to gain access

## Similarities and differences between piggybacking and tailgating

* Similarities:
  * Exploiting Authorized Access
  * Leveraging Human Trust
* Differences:
  * Method of Entry
  * Intent and Level of Deception
  * Opportunity for Attack
  * Detection and Suspicion
    
## Other techniques
 * Shoulder surfing
 * Dumpster diving

## Prevention measures
 * Training and awareness
 * Observant behavior and questioning
 * Properly shredding sensitive files

