#FROM: Kullanýlacak taban Docker imajýný belirtir.
#WORKDIR: Çalýþma dizinini Docker içindeki bir konuma ayarlar.
#COPY: Belirtilen kaynaktan Docker içindeki bir konuma dosyalarý kopyalar.
#ENTRYPOINT: Docker konteyneri baþlatýldýðýnda çalýþtýrýlacak komutu belirtir.

FROM mcr.microsoft.com/dotnet/runtime:8.0
WORKDIR /App
COPY \bin\Release\net8.0\publish app/
ENTRYPOINT ["dotnet","ConsoleDocker.dll"]