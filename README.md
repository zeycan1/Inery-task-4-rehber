


Inery task 4 Rehberi

Görev 4'ü çalıştırmadan önce hazırlık

• Github Hesapları

• Github Jetonları

• inery-testnet-faucet-tasks reposunu daha önce forkladıysanız silin. 

Hazırlık

1. [Github](https://github.com/) hesabı.

2. Github access token oluşturun. 

a) Github access token oluşturmak için [tıklayın](https://github.com/settings/tokens).

b) Generate new token seçin.

c) Generate new token (classic) seçin və tokenin adını yazın. Mesela: "access-inery-token". Aşağıdakı kutucukları işaretleyin. 

✓ repo

✓ workflow

✓ admin:org

d) Ardından alttaki Generate Token tıklayın. Oluşturulan tokeni kopyalayıp saklayın. 

Task 4'ü yapmak

1. Görev 4'ü otomatik olarak yapmak için aşağıdaki komutu çalıştırın.

```

wget --no-check-certificate --no-cache --no-cookies -q -O task4.sh https://raw.githubusercontent.com/node-ronin/testnet_tutorial/main/inery/task-4/task4.sh && chmod +x task4.sh

```

2. Görevi çalıştırmaya başlamak için aşağıdaki kodu çalıştırın.

```

./task4.sh

```

İstenen ayrıntıları girin.

**Masukkan nama inery account kalian:** Inery Account Name'nizi yazın.

**Masukkan IP Node kalian:** Inery Server IP adresinizi yazın

**Masukkan username github kalian:** Github kullanıcı adınızı yazın

Daha sonra sonra github'dan bir bildirim olacak:

"? What account do you want to log into?" (Hangi hesaba giriş yapmak istiyorsunuz?")

• GitHub.com seçip, enter yapın 

• HTTPS seçip, enter yapın.

• Y/N sorusu çıkacak, Y yazıp enter yapın.

• Paste an authentication token  seçip enter yapın.

• İlk adımda oluşturduğunuz Github Access Tokeni yapıştırın ve enter yapın.

4. Çıktı: Creating pull request for aslanbayramov:task4 into task4 in inery-blockchain/inery-testnet-faucet-tasks

https://github.com/inery-blockchain/inery-testnet-faucet-tasks/pull/559

TASK 4 DONE! Check URL Di atas buat memastikan pull request kalian sudah di git inery.

Böyle bir çıktı aldıysanız tamamdır. 



