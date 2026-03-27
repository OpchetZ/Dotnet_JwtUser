SetUp

1.Create Database in SSMS and name whatever

2.Change Catalog and Data Source in file name appsettings.json

Pattern example "Data Source={PCNAME};Initial Catalog={databasename} ;Integrated Security=True;Connect Timeout=30;Encrypt=False;TrustServerCertificate=False;ApplicationIntent=ReadWrite;MultiSubnetFailover=False"

3.change IP localhost in same file with IP that donnet run give

4.optional change SigninKey as long as you can

5.run in terminal:dotnet ef migrations add {nametoadd}

6.run in terminal:dotnet ef database update
