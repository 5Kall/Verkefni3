
1.	Setjið upp Domain Controller.

Við bættum Active Directory Domain Services hlutverkinu og keyrum Configuration Wizard til að tilgreina valkosti og ljúka uppsetningu. Eftir að þjónninn hefur verið endurræstur stiltum við tölvunar, hópum og stefnum með Active Directory verkfærum.
    
2.	Lénsnafnið á að vera TSK-<nafnið ykkar>.local. 


<img width="513" alt="Mynd1" src="https://github.com/5Kall/Verkefni3/assets/89195445/b3823007-3e42-49e0-8329-d74125d056fc">


3.	Setjið upp DHCP server.
   
settum fyrst upp DHCP Server hlutverkið á Windows Server vélinni. .


<img width="513" alt="Mynd-3" src="https://github.com/5Kall/Verkefni3/assets/89195445/5861b5b9-ab6b-4775-acf9-1c380a5e04be">

4.	Notið netið 192.168.1.64/26, LAN ip-talan á servernum ykkar á að vera síðasta nothæfa talan af netinu.

    stilltum svið ip-talanna, sjá mynd virkni og kóða
   


<img width="512" alt="Mynd-45" src="https://github.com/5Kall/Verkefni3/assets/89195445/a9a6d832-e83d-4a2c-96c2-2252b35351d4">

   
5.	Úthlutið fyrstu 30 tölum af netinu með DHCP.

    úthlutuðum 30 tölum, þar sem við byrjuðum á 10 gefur hann frá sér bara upp að 40
   
   <img width="512" alt="image" src="https://github.com/5Kall/Verkefni3/assets/89195445/9274c083-2ad8-4230-8f62-049ba45b8c73">




   
6.	Setjið upp NAT.

    stilltum á static iptölu,  uppsetning á NAT búnaði
   
   
<img width="513" alt="Mynd-3" src="https://github.com/5Kall/Verkefni3/assets/89195445/4ed5f53d-417d-4bca-9771-f95002fc75e0">



7.	Hver starfsmaður þarf að fá sína eigin möppu á servernum sem aðeins hann hefur aðgang að, mappast sem H:

   
   bjóum til folder fyrir hvern einasta notanda
   
   <img width="515" alt="7" src="https://github.com/5Kall/Verkefni3/assets/89195445/40003aeb-3c6b-45fc-a9ab-846e3a22e112">




8.	Vísið Documents og Desktop möppum starfsmannsins á möppuna á servernum.


9.	Setjið upp möppu og prentara fyrir hverja deild.

    Við bjóum til prentara inná device manager fyrir hverja deild ásamt möppu

<img width="520" alt="9_prentarar" src="https://github.com/5Kall/Verkefni3/assets/89195445/b4be4d67-1e7b-48a9-8ec9-832bd1803dee">




<img width="533" alt="9" src="https://github.com/5Kall/Verkefni3/assets/89195445/35830038-91bd-4078-b1a3-4c1f1a4b55b3">


10.	Setjið upp eina möppu og einn prentara sem allir hafa aðgang að.

    bjóum til möppu og prentara sem allir hafa aðgang að

    
<img width="529" alt="10-mappa" src="https://github.com/5Kall/Verkefni3/assets/89195445/dc08469d-9ae8-4564-aef6-199bdc6a6edb">




<img width="526" alt="10-prentari" src="https://github.com/5Kall/Verkefni3/assets/89195445/7523fc79-f8e0-4530-afab-023edc9ff2ba">


11.	Starfsmenn í Framleiðsludeild eiga að vera með http://www.forritun.is og https://kodun.is í Favorites í Internet Explorer. Tryggið einnig að þeir geti ekki eytt history í Internet Explorer.

    stilla upp group policy fyrir notendur þar sem þeir eru með forritun.is og kodun.is sem upphafsforrit. réttindi notendana var tekin í burtu með því að þeir geta        ekki eytt gögnum af internet explorer

<img width="378" alt="11-A" src="https://github.com/5Kall/Verkefni3/assets/89195445/2428efa1-39ac-4a95-8110-ae95556dc579">



15.	Starfsmenn Tölvudeild hafa full admin réttindi á allar Win10 tölvur.




16.	Allar tölvur eiga vera með Firefox vafrann upp settan.




17.	Starfsmenn í Framleiðsludeild eiga ekki að geta ræst Firefox.



18.	Allir notendur eiga að vera með Chrome vafrann upp settan.



19.	Allir notendur eiga að vera með Bubbles screen-saver (bubbles.scr) sem fer sjálfkrafa á hjá þeim eftir fimm mínútur.

með því að fara í stillingar, "personalization", "screen saver settings". stillum við á Bubbles og að tölvan slekkur eftir 1 mínutu

![Bubbles](https://github.com/5Kall/Verkefni3/assets/89195445/eb09f7b2-6d31-40f3-b2fc-c1126cc655ff)



20.	Starfsmenn í Framleiðsludeild geta ekki opnað taskmanager eða control panel.



    
22.	Starfsmenn í Tölvudeild eiga að fá Start Screen en ekki Desktop þegar þeir logga sig inn.
 
