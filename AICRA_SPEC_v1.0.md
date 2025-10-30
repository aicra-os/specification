# 📜 AICRA Spesifikasyonu v1.0

## Evrensel Yapay Zeka-Bağlamsal Depo Mimarisi

---

### **Özet**

AICRA (AI-Contextual Repository Architecture), yapay zeka-odaklı (AI-native) yazılım depoları oluşturmak için bir spesifikasyondur. Amacı, insan geliştiriciler ve yapay zeka ajanları arasında sorunsuz, denetlenebilir ve yönetişime uygun bir işbirliği sağlamak üzere evrensel, bağlam-odaklı ve kendini tanımlayan bir standart oluşturmaktır.

---

### **1. Temel Prensipler**

AICRA standardı dört temel prensip üzerine kurulmuştur:

*   **1.1. Bağlam Odaklılık:** Depo, yapay zeka ajanlarının projenin hedeflerini, mimarisini ve kurallarını anlamasını sağlayan zengin, makine tarafından okunabilir bir bağlam sunmalıdır.
*   **1.2. Niyet Odaklı Katkı:** Tüm önemli değişiklikler öncesinde, değişikliğin "neden"ini açıklayan net bir niyet beyanı (`CONTRIBUTION_PLAN.md`) bulunmalıdır.
*   **1.3. Açık Yönetişim:** İşbirliği kuralları, kod incelemesi ve etik değerlendirmeler örtük değildir; `governance/` dizininde açıkça tanımlanır.
*   **1.4. Evrensel Uygulanabilirlik:** Yapı, dil ve alan bağımsız olacak şekilde tasarlanmıştır.

---

### **2. Standart Yapısı**

AICRA uyumlu bir depo, aşağıdaki **İngilizce** dosya ve klasör yapısını temel almalıdır:

*   `/src`: Ana kaynak kodunu barındırır.
*   `/tests`: Otomatik testleri içerir.
*   `/docs`: `architecture.md` gibi insan tarafından okunabilir belgeleri tutar.
*   `/governance`: `review-policy.md` gibi yönetişim kurallarını tanımlar.
*   `/.aicra`: `repo-spec.yaml` gibi makine tarafından okunabilir meta verileri içerir.
*   `/workflows`: CI/CD otomasyonlarını barındırır.
