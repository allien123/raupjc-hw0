# raupjc-hw0
C# 0.domaća zadaća

# Pitanje 1:
Pojavile su se .dll i .pdb datoteka class library projekta. Nakon micanja .dll
datoteke i pokretanja .exe datoteke aplikacija se ruši u startu sa System.IO.FileNotFoundException iznimkom. To se dogodi zato jer je konzolnoj aplikaciji za izvođenje metode PrintHelloWorld potrebna .dll datoteka u kojoj se nalazi njen izvršivi kod. Ako biste me tražili da vam pošaljem aplikaciju poslao bih .exe i .dll datoteku (odnosno sve .dll datoteke kad bi ih bilo više).

# Pitanje 2:
Konzolna aplikacija je koristila staru verziju class librarya zato jer je u direktoriju ostala stara .dll datoteka (nova .dll datoteka bi se pojavila tek prevođenjem class library projekta).

# Pitanje 3:
Pri buildanju se automatski ponovno instalirao NodaTime, a packages direktorij opet sadrži mapu NodaTime.
