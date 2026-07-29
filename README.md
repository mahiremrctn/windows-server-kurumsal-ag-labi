# Windows Server Kurumsal Ağ Laboratuvarı

Windows Server, Active Directory, DNS, domain istemcileri, Group Policy,
PowerShell otomasyonu ve Windows güvenliği konularını uygulamalı öğrenmek
amacıyla oluşturduğum kişisel ev laboratuvarı.

> Bu proje yalnızca izole ve yetkili bir eğitim ortamında gerçekleştirilmektedir.
> Kullanılan kullanıcılar, departmanlar, domain ve IP adresleri hayalidir.

## Laboratuvarın amacı

- Windows Server yönetimini öğrenmek
- Active Directory Domain Services kurmak
- OU, kullanıcı ve güvenlik gruplarını yönetmek
- Windows 11 istemciyi domaine katmak
- Group Policy uygulamak ve doğrulamak
- Dosya erişimini gruplar üzerinden yönetmek
- PowerShell ile tekrarlanabilir otomasyonlar hazırlamak
- Windows logları ve güvenlik olaylarını incelemek
- Sistematik sorun giderme yaklaşımı geliştirmek

## Mevcut mimari

| Sistem | İşletim sistemi | Görev | Ağ |
|---|---|---|---|
| DC01 | Windows Server 2025 Evaluation | AD DS ve DNS | 192.168.32.10 |
| PC-MUH-001 | Windows 11 Enterprise Evaluation | Muhasebe istemcisi | VMware NAT |

Domain:

```text
corp.example.com
