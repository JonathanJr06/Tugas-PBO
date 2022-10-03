# Tugas-PBO
Dokumentasi Instalasi Tools


<> Langkah pertama kita donwload wsl dan ubuntu 20.04 di Windows Powershell dengan menginputkan "wsl --install" dan "wsl --install -d Ubuntu 20.04"
![powershell](https://user-images.githubusercontent.com/114232617/193503129-0bd31a6b-6b6c-4a5a-ba53-555d8cb66e63.png)
![install ubuntu](https://user-images.githubusercontent.com/114232617/193503157-5c7717ee-4368-4651-bc5e-4515ddf17bb3.png)


<> Sembari menunggu installasi selesai kita download VsCode di web Vscode 
![vsCode](https://user-images.githubusercontent.com/114232617/193503314-b0793f35-a659-416d-9319-feb97d107d9a.png)


<>Setelah selesai terinstall kita ketikan "Ubuntu2004 config --default-user root" lalu lanjut setting terminalnya denggan mengganti Ubuntu 20.04
![setting terminal](https://user-images.githubusercontent.com/114232617/193504989-bacb75f2-9ad4-468a-b70a-27aa2136fcd7.png)


<>Lalu dilanjutkan dengan  masuk ubuntu dan ketikan "apt update"
![apt update](https://user-images.githubusercontent.com/114232617/193505090-8e4e67fe-88d5-4fbc-9ec8-43ecf8ee822e.png)


<>Jika sudah selesai kita menuju web https://github.com/ohmyzsh/ohmyzsh untuk mencari command ZSH
![copy command curl](https://user-images.githubusercontent.com/114232617/193505298-74110f94-70dd-461a-81bd-1a30017b5212.png)


<> Lalu keitkkan "install zsh" pada terminal ubuntu
![install zsh](https://user-images.githubusercontent.com/114232617/193505425-c101487c-c7ed-4fe6-94e9-efb81e5fcec7.png)


<>Ketikkan "y" setiap petanyaan dan setelah itu ketikkan "sh -c "$(curl -fsSL"
![pertanyaan](https://user-images.githubusercontent.com/114232617/193510292-1ec9dd73-b37c-4a0e-aeff-1be9eafbf086.jpg)


<>Kemudian ketikkan "nano /root/.zshrc" pada bagian ZSH_THEME="robbrissel" menjadi ZSH_THEME="agnoster"
![nano ](https://user-images.githubusercontent.com/114232617/193511242-50a6dc21-4e33-4548-86c4-be514d587456.jpg)
![pluggin](https://user-images.githubusercontent.com/114232617/193510659-1db166a9-bef0-4eed-87a0-372cb82a7f35.jpg)

<> Lalu konekkan ke github dengan menginput "ssh-keygen" di ubuntu dalam proses ini tinggal klik enter sampai muncul seperti ini
![connect to github](https://user-images.githubusercontent.com/114232617/193513637-7c9b2cdb-6284-4d89-a3be-e058b18f207c.jpg)


<>Kemudian buat ssh-keyg di https://github.com/settings/keys dengan note wsl dan paste hasil output dari CAT
![ssh key 1](https://user-images.githubusercontent.com/114232617/193514621-6cb4954a-14fd-4979-a28c-e4c591a1f169.jpg)
![ssh key](https://user-images.githubusercontent.com/114232617/193514662-95ee6fe5-8d42-4287-bb5a-15f472e35626.jpg)


<> Setelah itu masuk ke Setting->Developer Setting->Personal Access Token lalu ceklis semua pada "select scopes"
![setting github](https://user-images.githubusercontent.com/114232617/193515700-b4f05be1-98ff-45ce-b96e-ff0d7889fb9e.jpg)
![select scope](https://user-images.githubusercontent.com/114232617/193516262-7f4a5791-d6c7-4038-8c97-5f779df7ff4b.jpg)


<> Lalu buat directory melalui ubuntu 
![directory](https://user-images.githubusercontent.com/114232617/193535038-ad1f9fd8-2027-4034-bc28-c9470e6fb689.jpg)


<> Setelah itu buka VsCode yang sudah kita donwload taddi dan cari github lalu sign in 
![autirize VsCode](https://user-images.githubusercontent.com/114232617/193535839-96d1086a-49d7-4c14-be2d-7d2e489a06fd.jpg)

<> Bisa ditambahkan untuk mendowload python 3 aatau sejenisnya untuk menjalankan script.
