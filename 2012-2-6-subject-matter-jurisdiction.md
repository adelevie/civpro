---
layout : post
category : civpro
---

## Forum Shopping

### Horizontal forum shopping
- where you bring the lawsuit

### Vertical forum shopping
- state court or federal court
- plaintiff's choice between state and federal, but if P chooses state, D can remove to Fed. court

### Differences between State and Fed. Court
- state court might be better for certain plaintiffs because they might get more sympathy from local juries
	- they are drawn from a smaller area than in federal courts
- prejudice against out of state parties by state parties
	- state judges are often elected
	- fed judges are appointed by president and have lifetime tenure
- federal judges could be richer and more elite than state judges
	- and favor big biz
	- fed courts generally favor defendants
	- perhaps better educated than state court judges
- distance_to.fed_court > distance_to.state_court
- fish out of water, lawyers can be in unfamiliar courts
- different rules and procedures
	- feds use FRCP, states could use differing rules that might favor different sides

## Diversity jurisdiction
- rooted in Article III Const. and FRCP Section 1332
- disagreement over original rationale
	- standard rationale: allows out of state parties to avoid local prejudice

### Article III

### FRCP 1332(a) 
- The district courts shall have original jurisdiction of all civil actions where the matter in controversy exceeds the sum or value of $75,000, exclusive of interest and costs, and is between—
	- (1) citizens of different States;
	- (2) citizens of a State and citizens or subjects of a foreign state;
	- (3) citizens of different States and in which citizens or subjects of a foreign state are additional parties; and
	- (4) a foreign state, defined in section 1603 (a) of this title, as plaintiff and citizens of a State or of different States.
	- Diversity of citizenship and $75k
	- state citizenship: domicile in state and us citizenship
	- state domicile: residence in fact and intent to remain indefinitely (p. 212)
		- once established, you retain it until you get a new domicile (and only in one state at a time, except for corporations)
		- you are still domiciled in the place you grow up and the place you intended to live indefinitely since you were six years old UNTIL you get a new domicile
			- ex: the couple from WWVW: domiciled in NY
				- P form NY suing D from NY
					- complete diversity => P wanted to trap the case in OK court

#### Diversity of Citizenship

#### Strawbridge v. Curtis

#### Mas V. Perry (p. 211): two-way mirror case
- P husband and wife
	- husband was a french national
	- wife was from the same state as D
- assume landlord Perry is domiciled in Louisiana, if only Mr. Mas had sued the landlord, would there have been diversity jurisdiction?
	- YES, coming from provision 1332(a)(2)
- complete jurisdiction: diversity between all Ps and all Ds
	- Would any plaintiff be diverse from any defendant?
	
		if (Jurisdiction(:plaintiffs) - Jurisdiction(:defendants)).length < (Jurisdiction(:plaintiffs) + Jurisdiction(:defendants)).length
			return :non_complete_diversity
		end

#### Corporations

##### Regular Corps
- potentially have two domiciles:
	- place where they're incorporated
	- place where they're headquartered (like a lot of Delaware corps)

##### Partnerships, LLCs, etc
- different set of rules
- org has domicile in all states of its members
- partner can't sue another partner in diversity

#### Charles Anderson Problem
<table border="1">
	<tr>
		<td></td>
		<td>Inc.</td>
		<td>HQ/Primary place</td>
	</tr>
	<tr>
		<td>Grace</td>
		<td>CT</td>
		<td>NY</td>
	</tr>
	<tr>
		<td>Beatrice</td>
		<td>Del.</td>
		<td>Ill.</td>
	</tr>
</table>
- his last place of domicile was in Mass.
- intent to stay indefinitely could be very much fact-centric
- A **stateless citizen** is never ever eligible for diversity jurisdiction
- if you move to a state with the authentic intent to stay in that state, you get the domicile in the state
- **fraudulent joinder**

#### Amount in Controversy requirement
- good faith rule
- sum claimed by P controls if it is apparently made in good faith
- must appear to appear to a legal certainty that the claim is really less to defeat it
- if P ultimately wins, but recovers less than $75k, court can deny P costs award as a punishment--not common
- value of equitable relief (like specific performance)
	- cost of benefit to the P
	- or cost for D to fix
		- different courts use different combos of tests

##### Aggregation
- when can you combine allegations to increase the amount in controversy?
- you can combine multiple claims against the same D so long as they are the same suit

### Federal Question Jurisdiction
- Reasons:
	- fed judges more competent in fed law
	- uniformity in US Const
	- fed judges more sympathetic to federal law (Reconstruction)
- most fed questions could be heard in state court (choice of P first, then maybe D)
- dispute is from something created by federal law
	- ex. Land Act claim

#### Louisville & Nashville RR v. Mottley
- Mottleys were trying to compel specific performance on a contract:
	- settlement on train accident for free passes
	- congress has law, an anti-corruption measure, against free passes
- action in Contract
- **Federal Question** has to be a part of **their cause of action** rather than an anticipated defense
- "arises under"
	- well-pleaded complaint rule
		- Hello, Alan from after learning about pleading
		- different parties are responsible for what to put in complaint and answer
		- D has to put affirmative defenses in Answer
			- "but for" defenses: even if X is true, D still isn't liable
- Supreme Court is the first court to examine Federal Question
	- *Sua Sponte* jurisdiction
- ends up in Fed court again anyway