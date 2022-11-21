---
başlık: Robonomics Portalı'nda hesabınıza para ekleme

katkı veren: [Houman]
çeviri: true
araçlar:   
  - Robonomics 2.4.0
    https://github.com/airalab/robonomics
---

**Hesaplarınızı Robonomics portalında başarıyla oluşturduktan sonra, işlemleri başlatabilmeniz için hesaplarınıza para ekleme zamanı geldi.**

<robo-wiki-note type="warning" title="Geliştirici Düğümü">

  Lütfen bu ve sonraki eğitimlerin Robonomics Node'un yerel bir örneğinde gösterildiğine dikkat edin. Sizinkini [bu talimatlarla kurun].(/docs/run-dev-node).

</robo-wiki-note>

## 1. Robonomics portalındaki Hesaplar bölümüne gidin

![Hesaplar](../images/creating-an-account/portal-top-left.jpg "Accounts")

## 2. Para transferi yapmak istediğiniz hesabı seçin

Geliştirme modunda, geliştirme ağında oluşturulan diğer hesaplara para aktarmak için kullanılabilecek, her biri 10000 Birim değerinde fon içeren birkaç hesap vardır. Bu hesaplar, yanlarında İngiliz anahtarı işaretleri <img alt="wrench sign" src="../images/adding-funds/wrench.png" width="20" /> ile gösterilir.

 
![Accounts-for-sending](../images/adding-funds/accounts-for-sending.svg "Accounts-for-sending")

- Para transferi yapmak istediğiniz hesabın "gönder" düğmesine tıklayın, örneğin BOB

## 3.Para aktarmak istediğiniz hesabı seçin
"Gönder" düğmesine tıkladıktan sonra, sizden "para gönder penceresi" istenir. İstenen pencerede:

- Mevcut hesaplar listesinden para göndermek istediğiniz hesabı seçin.
- Göndermek istediğiniz Birim sayısını girin.
- "Transfer yap"a basın

![Transfer-Funds](../images/adding-funds/send-funds.png "Transfer-Funds")

## 4. İşlemi yetkilendirin

Bir önceki aşamada "transfer yap"a bastıktan sonra "işlem yetkilendirme penceresi" ile karşılaşacaksınız.<br/>
İşlemin ayrıntılarını inceleyin ve son olarak "imzala ve gönder" düğmesine tıklayın.

![sign-transaction](../images/adding-funds/sign-transaction.png "sign-transaction")
Bu örnekte, "BOB"dan "İŞVEREN"e 500 birim fon aktardık. İŞVEREN'in başlangıçta hiç parası olmayan hesabında şu anda 500 Birim fon olduğunu görebilirsiniz.

![funds-added](../images/adding-funds/funds-added.svg "funds-added")

**Oyun alanında kullanmak istediğiniz hesaplarda yeterli para olduğundan emin olun.**
