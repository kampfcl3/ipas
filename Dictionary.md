#資訊管理
```
   #1.CIA
   
   #機密性(confidentiality)
     ```
     「機密資訊不可揭露於未經授權的主體之下」
     而其主要目的就是要維持資訊的機密性。這裡所提到的主體，可以是一個人、一個團體或一套系統。一般而言，稍有危機意識的企業組織都會建立若干套防護措施，以避免機密或敏感性的資產遭到未經授權的主體所
     讀取或使用。
     
     攻擊行為有：竊取 password 檔案、交際套密 (social engineering)、肩隙偷覽 (shoulder surfing)、刻意偷聽 (eavesdropping) 等等。
     此外，非攻擊性行為，例如人為的錯誤 (human error)、未能留意某威脅或徵兆而所造成的疏失 (oversight)、以及做事缺乏適當的技能 (ineptitude) 等等，也可能會導致機密或敏感性的資產遭到未經授權
     的主體所讀取或使用。
     ```
   #完整性(Integrity)
     ```
     「對任何機密資訊所施行的修改運作，都必須是經過授權且無竄改情事的」，而其主要目的就是要維持資訊的真實度 (veracity)、一致性 (consistency) 與完整性 (completeness)。常見的違反 integrity 之
      行為有：竄改機密資訊的內容與刪除機密檔案等等。
     ```
   #可用性(Availability)
     ```
      「已經取得授權的主體可以『及時地』與『不受中斷地』讀取或使用資訊」，而其主要目的就是要維持作業活動的順暢性。常見的違反 availability 之攻擊行為有：denial of service attack 
      與 communication interruptions。此外，天災與人禍也可能導致資訊無法及時地與不受中斷地被讀取或使用，例如電廠跳電、電力中斷 (維修人員不小心切斷電源、怪手不小心挖斷電線)、地震、颱風、硬體因
      年久而自然損壞等等。
     ```
```
   ![image](https://github.com/kampfcl3/ipas/blob/main/PIC/cia-triad.png)
```
   
   #鑑別性(Authenticity)
     ```
     可證明一主體或資源之識別就是其所聲明者的特性。鑑別性適用於如使用者、程序、系統與資訊等實體。
     ```
   #可歸責性(Accountability)
     ```
     確保實體之行為可唯一追溯到該實體的性質。
     ```
   #可靠性(Reliability)
     ```
     始終如一預期之行為與結果的性質。
     ```
   #不可否認性(Non-repudiation)
     ```
     對一已發生之行動或事件的證明，使該行動或事件往後不能被否認的能力。
     ```
```
   ![image](https://github.com/kampfcl3/ipas/blob/main/PIC/cia-as-security-objectives-v2.jpg)
```
========================================================================================
   #風險管理(risk management)
     ```
     
     ```

     
   
   
   
   
   
   
   
   
   對於組織來說還要做到法規的遵循(compliance)
   
   參考資料:
     1. http://blog.udn.com/chungchia/3428077
 ```
 
 ## RAID 0
 ```
RAID 0亦稱為帶區集。它將兩個以上的磁碟並聯起來，成為一個大容量的磁碟。在存放資料時，分段後分散儲存在這些磁碟中，因為讀寫時都可以並列處理，所以在所有的級別中，RAID 0的速度是最快的。但是RAID 0既沒有冗餘功能，也不具備容錯能力，如果一個磁碟（物理）損壞，所有資料都會遺失，危險程度與JBOD相當。

https://zh.wikipedia.org/wiki/RAID
 ```
 ![image](https://github.com/kampfcl3/ipas/blob/main/PIC/800px-RAID_0.svg.png)
 
   
