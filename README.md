# Dill Public Testnet (Andes Testnet) Bilgileri

| Network Name     | Dill Testnet Andes |
| ------------- | ---------------- |
Rpc URL | https://rpc-andes.dill.xyz/
Chain ID | 558329
Currency Symbol | DILL
Explorer URL | https://andes.dill.xyz/

# Hardware Requirements
| Hardware | Requirement |
| ------------- | ---------------- |
Cpu | 2 Cores
Architecture | x86-64 (x64, x86_64, AMD64, ve Intel 64)
Memory | 2 GB
Operating System | Ubuntu 22.04.2+ / MacOS
Storage | 20 GB
Network Bandwidth | 1MB/s 


Kurulum script'ini indirin ve çalıştırın:
Terminalinizi açın ve aşağıdaki komutu çalıştırarak script'i indirin ve çalıştırın:

```curl -O https://raw.githubusercontent.com/DillLabs/launch-dill-node/main/launch_dill_node.sh  && chmod +x launch_dill_node.sh && ./launch_dill_node.sh
```

Sırasıyla şu işlemleri yapın:
Dosyaların indirilmesini bekleyin.
Güçlü bir şifre oluşturun. En az 8 karakter uzunluğunda olsun ve Keystore Şifresini onaylayın:
Validator Key oluşturulduktan sonra enter tuşuna basarak onaylayın.
Tüm adımları doğru bir şekilde tamamladıysanız, şu şekilde bir çıktı alacaksınız:


```node running, congratulations 😄
validator pubkey: xxxxxx
Please backup this directory $YOUR_SCRIPT_PATH/dill/validator_keys. Required for recovery and migration. Important ！！！
```

Staking
İlk olarak, Andes kanalından cüzdanınıza token alın. Node'da oluşturduğunuz cüzdandan farklı bir cüzdan kullanın ve musluk isteğini yalnızca bir kez alabileceğinizi unutmayın ($request xxxxx)

https://staking.dill.xyz/ adresini ziyaret edin.

Burada deposit_data-xxxx.json uzantılı dosyanızı yükleyeceksiniz. Sunucunun içinde sırasıyla klasörleri takip ederek ./dill/validator_keys/deposit_data-xxxx.json isimli dosyayi bulup buraya yukleyin.

deposit_data-xxxx.json dosyasını siteye yükledikten sonra, MetaMask'a Bağlan'a tıklayın ve yeterli fonunuzun olduğundan emin olun (>2500 DILL).

MetaMask kullanarak bir depozit işlemi göndermek için send deposit deyin.

Hepsi bu kadar. Bu işlemlerden sonra, public key'inizle Explorer'daki doğrulayıcılar bölümünde kontrol edebilirsiniz https://andes.dill.xyz/validators Görünmesi 1 saat sürebilir.
