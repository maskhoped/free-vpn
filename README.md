# free-vpn
free vpn ( windscribe ) menggunakan openvpn

Langkah Langkah instalasi :

( pastikan anda menjalankan perintah ini dengan user root )

1. instal dulu program pengunduhan link jika belum :

- apt install wget


2. lalu download file vpn nya dan copy ke direktori yang di inginkan semisal saya ingin mengunduhnya ke direktori Downloads :

- cd /home/namauserkalian/Downloads


3. setelah masuk ke direktori yang di inginkan untuk menyimpan file vpn baru kita download :

- wget https://windscribe.com/install/desktop/linux_deb_x64
( prosesnya cukup lama jadi tunggu saja )


4. jika sudah didownload.. masuk ke file nya :

- cd free-vpn


5. setelah masuk ke filenya.. lakukan instalasi dengan perintah di bawah ini :

- apt update && apt upgrade
- apt --fix-broken install

( jangan lupa untuk menginstall dependensi yang dibutuhkan [penting!] )
- apt install iptables sudo openvpn net-tools policykit-1 psmisc
- apt --fix-broken install
- apt install iptables sudo openvpn net-tools policykit-1 psmisc

( disini pastikan sudah masuk di direktori dimana anda menyimpan file vpn nya "windscribe-cli_2.12.7_amd64.deb" )
- sudo dpkg -i https://windscribe.com/install/desktop/linux_deb_x64
- apt --fix-broken install
- sudo dpkg -i https://windscribe.com/install/desktop/linux_deb_x64
- apt-get update && apt-get upgrade

note : saya memberikan perintah "apt --fix-broken install" karena terkadang ada eror pada saat penginstalan, jadi kalau tidak eror saat menginstal maka tidak perlu


untuk menjalankan, buka programnya dari gui yang ada di menu pojok kiri bawah


