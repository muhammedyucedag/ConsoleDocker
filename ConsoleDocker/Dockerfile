#FROM: Kullan�lacak taban Docker imaj�n� belirtir.
#WORKDIR: �al��ma dizinini Docker i�indeki bir konuma ayarlar.
#COPY: Belirtilen kaynaktan Docker i�indeki bir konuma dosyalar� kopyalar.
#ENTRYPOINT: Docker konteyneri ba�lat�ld���nda �al��t�r�lacak komutu belirtir.

FROM mcr.microsoft.com/dotnet/runtime:8.0
WORKDIR /App
COPY \bin\Release\net8.0\publish app/
ENTRYPOINT ["dotnet","ConsoleDocker.dll"]