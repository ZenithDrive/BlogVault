+++
title = "Why Safety During Manual Driving Matters More Than During Autonomous Driving"
date = "2025-10-30T00:00:37+09:00"
draft = false
tags = []
+++

+++
title = "Why Safety During Manual Driving Matters More Than During Autonomous Driving"
date = "2025-10-28+09:00"
draft = false
tags = ["ADAS", "autonomous driving", "Level 3", "traffic safety", "automotive technology"]
slug = "why-l0-more-important-than-l2"
+++

## The ADAS Paradox — The "Essence" Beyond Automation

More than five years have passed since autonomous driving became a hot topic. In countries around the world, autonomous taxi demonstration experiments and advancements in highway driving assistance are progressing, and news reports increasingly proclaim that "the era of autonomous driving is near."

However, I would like to reconsider an important question here:  
**Do we really want "autonomous driving"?**

- If your car could drive itself, how much would you be willing to pay for it?
- If that autonomous driving was cautious, safety-first driving, or frequently requested operational intervention, would you still want to use it?

In fact, the value of "automation" varies depending on **what, to what extent, and for what purpose we automate**.
And at any level of automation, we cannot avoid the challenges of cost and responsibility allocation.

In this article, as an engineer who has been involved in ADAS development for eight years, I will explore from a field perspective why improving the safety of "Level 0 (manual driving)" is important for society as a whole.

---
## SAE Automation Level Classification

First, let me briefly organize the automation levels based on **SAE J3016**, the international standard for autonomous driving.

| Level | Name | Overview |
|:--|:--|:--|
| Level 0 | No Driving Automation | Driver performs all tasks. Includes warning and momentary intervention functions. |
| Level 1 | Driver Assistance | Assists with either steering or acceleration/deceleration. Example: ACC, etc. |
| Level 2 | Partial Driving Automation | Can control both, but monitoring responsibility remains with the driver. |
| Level 3 | Conditional Driving Automation | System executes all tasks under specific conditions. Human intervenes when requested. |
| Level 4 | High Driving Automation | Fully autonomous driving under specific conditions (no human intervention required). |
| Level 5 | Full Driving Automation | System drives under all conditions. Steering wheel unnecessary. |

Reference: [SAE J3016 Automated Driving Levels](https://www.sae.org/standards/content/j3016_202104/)

What's important is that **responsibility first shifts to the system side at Level 3**.  
This boundary dramatically increases the difficulty across all aspects: development, regulations, and social acceptance.
   
   
---
## Reality: Technical and Institutional Barriers Facing Level 3

### 1. ODD (Operational Design Domain) Constraints

Level 3 systems must strictly define "under what conditions they function (ODD)".  
Outside this domain, the system cannot provide guarantees.  

For example, conditions such as "limited to highways," "low-speed driving only," and "good weather" are set to clearly define the range where safety can be reliably ensured.  

However, since these conditions frequently change in real traffic environments, **ODD boundary design and operation becomes the most difficult challenge**.

### 2. Legal and Social Challenges

Autonomous driving legislation differs by country and region, and many countries have laws based on the premise that "humans drive."  

Since Level 3 places responsibility on the manufacturer during system operation, careful institutional design is required for legal liability in accidents, take-over design, risk countermeasures when drivers don't intervene, and more.

### 3. Cost and Scalability

Level 3 systems combining high-reliability sensors, redundant control ECUs, high-precision maps, and more incur **additional costs on the scale of several hundred thousand yen per vehicle**.  

As a result, deployment to mass-production vehicles is limited, and recovering development costs is not easy.  

In contrast, Level 0-2 driving assistance technologies can be widely deployed and have **high cost-effectiveness from the perspective of improving overall societal safety**.

---

## Level 0: The Area Evolving Most Today

In recent years, "Level 0" technology—namely **safety assistance functions premised on driver responsibility**—has been steadily advancing.

### AEB (Automatic Emergency Braking)

- Detection of pedestrians and cyclists and nighttime capability  
- Collision avoidance assistance during intersection turns  
- Early warning linked with DMS (Driver Monitoring System)

Through such evolution, U.S. IIHS research reports approximately **50% reduction** in frontal collision accidents.

### Lane Keep Assist / Blind Spot Detection / Cross Traffic Alert

- Prevention of lane departure, side collisions, and intersection right-angle collisions  
- Automatic intervention during drowsiness or distraction through DMS linkage  
- Detection of approaching vehicles from behind when exiting, and other safety measures rooted in daily scenarios continue to evolve

These features are already becoming standard equipment in many new vehicles.


---

## Global Regulatory Trends

- **EU GSR (General Safety Regulation) Phase 2**: Mandates AEB, LKA, DMS, and other systems from 2024  
- **China C-NCAP 2024**: Introduces pedestrian/cyclist detection AEB and DMS evaluation  
- **U.S. NHTSA Proposal**: Plans phased introduction of mandatory AEB for all vehicles by 2029  

As evident from these trends, the direction of **"safety technology for all vehicles"** has become an international consensus.

---

## What I've Felt in Nine Years on the Development Floor

In the early stages of my career, I held a strong aspiration to realize "fully autonomous driving."  
However, what I experienced on the mass production development floor was the following reality:

- "Automation doesn't necessarily mean safety": It creates new risks such as driver overconfidence and decreased attention  
- Rather than technical sophistication, "safety technology that everyone can benefit from" has greater social impact  

Ultimately, I realized the obvious fact that **what saves the most lives is the accumulation of modest and steady technology**.


---

## Safety During Manual Driving Is What Changes Society

While the term "autonomous driving" is attractive, from the perspective of accident reduction across society, what is currently most effective is **Level 0-2 safety technology**.

| Comparison Axis | Level 0~2 | Level 3 |
| :------- | :------------- | :-------------- |
| Adoption Rate | Tens of millions of vehicles/year | Thousands of vehicles/year |
| Additional Cost | Tens of thousands of yen scale | Hundreds of thousands of yen scale |
| Social Impact | ◎ Widely adopted with significant accident reduction effect | △ Expensive, operates only under limited conditions |

Looking toward "the future of autonomous driving" is important.  
However, what is saving lives around the world right now, at this very moment, is **Level 0 safety technology**.  

---

## What I Want to Convey as an Engineer

Behind the glamorous headlines, there are people who make steady improvements day after day.  
To prevent even one more accident, to save even one more life, they continue refining each sensor, each line of control logic.  

The true value of the automotive industry lies not in flashy demos or headlines, but in **"the power to make all of society safer"**.  
Improving Level 0 safety is the forefront of that mission.


## References

### Key Literature

1. SAE International, "J3016: Taxonomy and Definitions for Terms Related to Driving Automation Systems for On-Road Motor Vehicles" (2021)
2. Euro NCAP, "2024 Test Protocol – Safety Assist"
3. IIHS, "Real-world benefits of crash avoidance technologies" (2024)
4. UNECE, "UN Regulation No. 157 - Automated Lane Keeping Systems (ALKS)" (2021)
5. European Commission, "General Safety Regulation (EU) 2019/2144"
6. NHTSA, "Automatic Emergency Braking Systems" (2024)
7. AAA Foundation for Traffic Safety, "Advanced Driver Assistance Technology Names" (2023)

### Related Links

- [Euro NCAP Official Site](https://www.euroncap.com/)
- [IIHS Highway Loss Data Institute](https://www.iihs.org/)
- [SAE International Standards](https://www.sae.org/)
- [UNECE Vehicle Regulations](https://unece.org/transport/vehicle-regulations)
- [Mercedes-Benz Drive Pilot](https://www.mercedes-benz.com/en/innovation/autonomous/drive-pilot/)
- [Honda Traffic Jam Pilot](https://global.honda/newsroom/news/2021/4210311eng.html)

---