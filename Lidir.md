
1.	Setjið upp Domain Controller.

Við bættum Active Directory Domain Services hlutverkinu og keyrum Configuration Wizard til að tilgreina valkosti og ljúka uppsetningu. Eftir að þjónninn hefur verið endurræstur stiltum við tölvunar, hópum og stefnum með Active Directory verkfærum.
sjá mynd 1. fyrir virkni
    
2.	Lénsnafnið á að vera TSK-<nafnið ykkar>.local. 



Mynd 1)
<img width="513" alt="Mynd1" src="https://github.com/5Kall/Verkefni3/assets/89195445/b3823007-3e42-49e0-8329-d74125d056fc">


3.	Setjið upp DHCP server.
   
settum fyrst upp DHCP Server hlutverkið á Windows Server vélinni. .

sjá mynd 2. fyrir virkni

Mynd 2)
<img width="513" alt="Mynd-3" src="https://github.com/5Kall/Verkefni3/assets/89195445/5861b5b9-ab6b-4775-acf9-1c380a5e04be">

4.	Notið netið 192.168.1.64/26, LAN ip-talan á servernum ykkar á að vera síðasta nothæfa talan af netinu.


<img width="512" alt="Mynd-45" src="https://github.com/5Kall/Verkefni3/assets/89195445/a9a6d832-e83d-4a2c-96c2-2252b35351d4">

   
5.	Úthlutið fyrstu 30 tölum af netinu með DHCP.
   <img width="512" alt="image" src="https://github.com/5Kall/Verkefni3/assets/89195445/9274c083-2ad8-4230-8f62-049ba45b8c73">




   
6.	Setjið upp NAT.
   
<img width="513" alt="Mynd-3" src="https://github.com/5Kall/Verkefni3/assets/89195445/4ed5f53d-417d-4bca-9771-f95002fc75e0">



7.	Hver starfsmaður þarf að fá sína eigin möppu á servernum sem aðeins hann hefur aðgang að, mappast sem H:

   
   bjóum til folder fyrir hvern einasta notanda
   
   <img width="515" alt="7" src="https://github.com/5Kall/Verkefni3/assets/89195445/40003aeb-3c6b-45fc-a9ab-846e3a22e112">





10.	Vísið Documents og Desktop möppum starfsmannsins á möppuna á servernum.
11.	Setjið upp möppu og prentara fyrir hverja deild.
12.	Setjið upp eina möppu og einn prentara sem allir hafa aðgang að. 
13.	Starfsmenn í Framleiðsludeild eiga að vera með http://www.forritun.is og https://kodun.is í Favorites í Internet Explorer. Tryggið einnig að þeir geti ekki eytt history í Internet Explorer.
14.	Starfsmenn Tölvudeild hafa full admin réttindi á allar Win8 tölvur.
15.	Allar tölvur eiga vera með Firefox vafrann upp settan. 
16.	Starfsmenn í Framleiðsludeild eiga ekki að geta ræst Firefox.
17.	Allir notendur eiga að vera með Chrome vafrann upp settan.
18.	Allir notendur eiga að vera með Bubbles screen-saver (bubbles.scr) sem fer sjálfkrafa á hjá þeim eftir fimm mínútur.
19.	Starfsmenn í Framleiðsludeild geta ekki opnað taskmanager eða control panel.
20.	Starfsmenn í Tölvudeild eiga að fá Start Screen en ekki Desktop þegar þeir logga sig inn.
 
