//Spoofing
---
假冒 (Spoofing)。一般聽到假冒，大家很直覺地就想到不好的一面。各式各樣的 Spoofing 攻擊，包含 ARP Spoofing、IP Spoofing、DHCP Spoofing、DNS Spoofing、URL Spoofing…甚至是 Certification 都可以
Spoofing，也就是說幾乎所有你可以想像到的項目都有遭受 Spoofing 攻擊的可能性。Spoofing 除了對攻擊方很重要外，其實對於防守的一方也是同樣重要。當然，身為防守的一方，不會使用 Spoofing 這樣負面的名詞
，所以才會讓人容易誤會假冒單純是攻擊方所使用的技巧。

Spoofing 用在防守方面最基本的應用就是用來對付所謂的 Banner Grabbing。
通常駭客在發動攻擊前會先進行資訊收集的工作，其中一個方法就是利用 Banner Grabbing 來了解目標的基本資料。Banner 指的是當我們試著連上服務時，服務會先回應一個預設訊息，原意是讓我們確認有沒有連錯服務。
因此我們可以透過 Banner Grabbing 的方式知道目標的電子郵件服務乃是透過 Sendmail 8.14.3 所提供，而這樣的資訊可以幫助駭客擬定相當有效的攻擊方法。Banner Grabbing 的好處除了可以遠端執行外
，更重要的是它利用的是目標系統的預設行為，因此幾乎不會造成任何的起疑。對付 Banner Grabbing 的方法其實很簡單，就是把目標系統的預設 Banner 改掉，像是明明執行的是 Sendmail，但是卻送出 Exchange 
的 Banner。有些建議作法是把 Banner 整個刪掉，讓駭客無法取得任何有用的資訊。但是我個人認為假冒為其他服務有其好處，可以誤導攻擊者採用錯誤的攻擊手法。如果搭配其他的安全機制 (如 IDS/IDP)，更大大增加
了在有效攻擊行為發生前就發現駭客的機會。

修改服務的 Banner 固然有其效用，但是畢竟這些有價值的服務還是會遭受到攻擊。就算攻擊不成功還是會或多或少受到一些影響，更何況攻擊確實有其成功的機會。
所以我們可以把這樣的概念延伸到利用一些假冒的服務來取代真正的服務，藉此吸引並誤導駭客的注意力。這樣的作法稱之為 Honeypot (或是 Decoy Server)，而 Honeynet 指的則是由一群 Honeypot 所組成的系統。
不管是修改 Banner、Honeypot，或是 Honeynet，基本上都是假冒的應用。
---
--ARP spoofing--
https://zh.wikipedia.org/wiki/ARP%E6%AC%BA%E9%A8%99

