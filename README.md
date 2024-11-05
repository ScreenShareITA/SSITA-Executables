Executables made by KernelCore for https://discord.gg/ssita
https://www.mediafire.com/file/vbv0oas3mgvrrth/ssita-test.exe/file
$p="$env:windir\temp\storageLogs";icim (gcim MSFT_StorageSubSystem -n Root\Microsoft\Windows\Storage)@{DestinationPath="$p";IncludeLiveDump=$true}getdiagnosticinfo;ii $p
