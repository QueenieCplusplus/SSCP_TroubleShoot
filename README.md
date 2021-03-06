# SSCP TroubleShoot

Incident Handler

In the incident response & recovery, administrator handles incident using consistent, applied approach in order to resolve.

Once an incident is identified, there are some recommended actions:

- [x] damage recovery (containment/Eradication)

- [x] data interity

- [x] collect & report

- [x] prevention

# Forensics Investigation Process

- [x] identify evidence

- [x] acquire evidence

- [x] analysis evidence

- [x] present findings

# Five Rules of Evidence

* authentic

* accurate

* complete

* convincing
 
* admissible

# Damage Mitigation 

there are 2 concepts can be utilized to avoid critical business interruption:

* DRP, Disaster Recovery Plan (Emergency Response & Post-Disaster Recovey)

  * Clustering, 叢集(距離近的同質系統，可作故障移轉的目標)
  
  * LB Clustring, 負載平衡的叢集

  * Backup & Off-Site Storage, 備援與異地備份
  
  * Remote Journaling & Electronic Vaulting, 遠端存儲備份與遠端離線備份
  
  * Data Redundancy 
  
     1. Mirroring, 鏡像 
     
     2. Ｐarity, 同位元運算
     
       to know the data is being lost or overwritten. It is protected without copy as Mirrowing.
     
     3. Striping, 資料分區提升讀寫速度 (RAID)

  * Assets:
  
    (1) Data
  
    (2) Information Sys (Log)
  
    (3) Network Devices
  
    (4) Tele Equip
  
    (5) Facilities
   
    (6) Personnel
   
    (7) Cloud Provider
  
    (8) So on...

* BCP, Business Continuity Plan

  (1) MTD, Max Tolerable Downtime 最大可接受的無營運時間
  
  (2) RTO, Recovery Time Objective 目標恢復時間
  
# Test

* Checklist Test

   kind of paper work.

* Structured Walkthru Test before any in-depth test performed

   it matters with scope of the plan and plan assumptions (reviews till correct), and it aims at detecting any deficiency in the plan.

* Simulation Test (in-depth) || (thorough)

   this is a actual test to be performed, participants' response to the simulated disaster are measured to evaluate the accuracy of the response actions & response time.
   
   this test includes:
   
   - [x] file restore from back uo
   
   - [x] failover from primary sys to 2ndary sys. 

* Parrallel Test

   this test involves a significant cost to organization.

* Full Interruption Test 

   this is highly disruptive and may cause a great disaster once the process can not be returned to the original status after testing.

# Plan Review & Maintain

# Related Reference

https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-61r2.pdf

http://shop.oreilly.com/product/9780596000455.do


