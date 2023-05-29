# MyIP

### This script automates the Local IP's and Private interfaces, data recolection

## Usage

> `-a check`

This will provide you all the data related with your detected active interfaces `name | IP | Broadcast | Mac Address` , and your detected Local IP `IP | Country | City | ZIP (postal code) | ISP (internet service provider)`

> `-l [IP/check]`
>
> This will only provide you all the data related with the IP you have written.

- Example
- - `myip.sh -l 8.8.8.8` This will provide `Country | City | ZIP (postal code) | ISP (internet service provider)` of **that IP**

---

- - `myip.sh -l 8.8.8.8,9.9.9.9` This will provide `Country | City | ZIP (postal code) | ISP (internet service provider)` of that **group of IP's**

---

- - `myip.sh -l check` This will provide `IP | Country | City | ZIP (postal code) | ISP (internet service provider)` of the **IP which is able to detect** (yours)

> `-s [INTERFACE/check]`
>
> This will only provide you all the data related with the IP you have written.

- Example
- - `myip.sh -s eth0` This will provide `name | IP | Broadcast | Mac Address` of **that interface**

---

- - `myip.sh -s eth0,wlo1` This will provide `name | IP | Broadcast | Mac Address` of that **group of interfaces**

---

- - `myip.sh -s check`This will provide `name | IP | Broadcast | Mac Address` of the **active interfaces which is able to detect** (yours)

![enter image description here](a)
