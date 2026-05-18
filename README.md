# podkop-lists

Списки для podkop.

## Файлы

- lists/vpn-domains.txt — домены, которые надо отправлять через VPN.
- lists/vpn-subnets.txt — IP/подсети, которые надо отправлять через VPN.
- lists/exclude-domains.txt — домены, которые надо исключить из VPN.
- lists/exclude-subnets.txt — IP/подсети, которые надо исключить из VPN.

## Raw URL для podkop

MAIN / External domain lists:
https://raw.githubusercontent.com/hell-llex/podkop-lists/main/lists/vpn-domains.txt

MAIN / External subnet lists:
https://raw.githubusercontent.com/hell-llex/podkop-lists/main/lists/vpn-subnets.txt

EXCLUSION / External domain lists:
https://raw.githubusercontent.com/hell-llex/podkop-lists/main/lists/exclude-domains.txt

EXCLUSION / External subnet lists:
https://raw.githubusercontent.com/hell-llex/podkop-lists/main/lists/exclude-subnets.txt

## Команды

.\podkop-lists.ps1
.\podkop-lists.ps1 init
.\podkop-lists.ps1 add -Target vpn-domain -Values chatgpt.com,openai.com
.\podkop-lists.ps1 remove -Target exclude-domain -Values youtube.com
.\podkop-lists.ps1 list
.\podkop-lists.ps1 urls
.\podkop-lists.ps1 sync
