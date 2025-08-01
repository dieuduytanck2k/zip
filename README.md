# zip

curl.exe -fo teleport.cer https://teleport-onpre.dieuduytan.online/webapi/auth/export?type=windows

curl.exe -fo teleport-windows-auth-setup.exe https://cdn.teleport.dev/teleport-windows-auth-setup-v18.1.1-amd64.exe

teleport-windows-auth-setup.exe install --cert=teleport.cer -r
