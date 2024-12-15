# free-vpn
free vpn ( windscribe ) menggunakan openvpn

Langkah Langkah instalasi :

( pastikan anda menjalankan perintah ini dengan user root )

1. instal dulu program berbagi nya pakai git jika belum :

- apt install git


2. lalu download file vpn nya dan copy ke direktori yang di inginkan semisal saya ingin mengunduhnya ke direktori Downloads :

- cd /home/namauserkalian/Downloads


3. setelah masuk ke direktori yang di inginkan untuk menyimpan file vpn baru kita download :

- git clone https://maskhoped-private@github.com/maskhoped/free-vpn.git

note : jika dimintai password.. maka masukkan kata kunci yang ada di dalam kurung berikut ini..
👉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👈


4. jika sudah terinstall.. masuk ke file nya :

- cd free-vpn


5. setelah masuk ke filenya.. lakukan instalasi dengan perintah di bawah ini :

- apt update && apt upgrade
- apt --fix-broken install
- apt install sudo openvpn net-tools policykit-1
- apt --fix-broken install
( disini pastikan sudah masuk di direktori dimana anda menyimpan file vpn nya "windscribe-cli_2.12.7_amd64.deb" )
- sudo dpkg -i windscribe-cli_2.12.7_amd64.deb
- apt --fix-broken install

note : saya memberikan perintah "apt --fix-broken install" karena terkadang ada eror saat penginstalan, jadi kalau tidak eror saat menginstal maka tidak perlu


