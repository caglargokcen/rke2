<h1 align="left">
RKE2
</h1>

<h1 align="left">
🚀🚀🚀
</h1>

<br>

- [Using RKE2 and Azure File Share for Voting Management in Three-Tier Applications](#using-rke2-and-azure-file-share-for-voting-management-in-three-tier-applications)

<br>

## Using RKE2 and Azure File Share for Voting Management in Three-Tier Applications

<br>

Kullanıcıların oy verebildiği ve sonuçları görebildiği üç katmanlı uygulamaların RKE2 üzerinde deploy edilmesini amaçlamaktadır.

<br>

Vote ve Result uygulamaları HTTP/HTTPS protokolleri üzerinden dış dünyaya açılacak ve Hyper-V üzerinde bir Master node ile iki Worker node'dan oluşan bir RKE2 ortamında çalışacaktır.

<br>

Veriler RKE2 node'ları veya NFS yerine Azure File Share üzerinde saklanarak bulut ortamında güvenli bir şekilde yönetilecektir. Bu sayede uygulamalar kaldırıldığında bile veriler erişilebilir kalacak ve kullanıcıların veri güvenliği sağlanmış olacaktır.

<br>

Modern yazılım geliştirme becerilerinizi pekiştirirken bulut tabanlı uygulama dağıtımı ve veri yönetimi konularında kapsamlı bir bilgi edinmenizi hedeflemektedir.