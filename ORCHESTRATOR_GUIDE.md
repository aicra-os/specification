# 🧠 Orkestratör Rehberi

Orkestratör, AICRA standardının uygulandığı bir projede insan zekası ile yapay zeka ajanları arasındaki köprüyü kuran, projenin vizyonunu ve kalitesini koruyan en kritik roldür. Bu rol, bir proje yöneticisi, baş mimar veya tecrübeli bir geliştirici tarafından üstlenilebilir.

### Temel Sorumluluklar

**1. Bağlamı Yönetmek:**
*   Projenin başında `docs/ai-context.yaml` ve `docs/architecture.md` dosyalarını oluşturmak ve projenin hedeflerini net bir şekilde tanımlamak.
*   Proje geliştikçe bu bağlam dosyalarını güncel tutmak.

**2. Katkı Planlarını Değerlendirmek (`CONTRIBUTION_PLAN.md`):**
*   Yeni bir plan sunulduğunda, aşağıdaki kriterlere göre değerlendirmek:
    *   **Niyetin Netliği:** Görevin amacı ve beklenen çıktılar açık ve anlaşılır mı?
    *   **Mimari Uyum:** Plan, projenin genel mimarisi ve teknoloji yığını ile uyumlu mu?
    *   **Büyüklük:** Plan, tek bir Pull Request ile tamamlanabilecek makul bir büyüklükte mi?
*   Planı onaylamak veya revizyon istemek.

**3. Görevleri Atamak:**
*   Onaylanan bir planı, yeteneklerine göre bir AI ajanına (`@agent:CodeAgent`) veya bir insana atamak. Bu atama, genellikle ilgili "Issue" üzerinde bir etiketle yapılır.

**4. Pull Request'leri Gözden Geçirmek:**
*   Hem insan hem de AI tarafından gönderilen PR'ları `governance/review-policy.md` belgesindeki kriterlere göre incelemek.
*   Özellikle AI tarafından üretilen kodlarda şunlara dikkat etmek:
    *   **Niyete Uygunluk:** Kod, tam olarak planda belirtilen niyeti karşılıyor mu? Fazladan veya eksik bir işlevsellik var mı?
    *   **Mantık Hataları:** Kod, görünüşte doğru olsa bile gizli mantık hataları veya "halüsinasyonlar" içeriyor mu?
    *   **Etik Kontrol:** Kod, `governance/ai-ethics.md` politikasını ihlal ediyor mu?

**5. Nihai Kararı Vermek:**
*   Tüm kontrollerden geçen bir Pull Request'i ana branch'e birleştirmek. Deponun bütünlüğünden ve kalitesinden nihai olarak Orkestratör sorumludur.
