![Paris Airbnb Project Cover](paris.png)
🌈 README’de Yapılacak En Çarpıcı Şeyler
🏆 Ana Mantık

README şunu göstermeli:

“Ben sadece SQL/Python/Tableau bilen biri değilim; veriden iş sonucu çıkaran, bunu stakeholder’a anlatabilen bir Data Analyst’im.”

README bir kod defteri değil, bir mini iş raporu / stakeholder sunumu gibi görünmeli.

✅ README’de Mutlaka Yapılacaklar
🟢 1. Projeyi şirket problemi gibi anlat

README’ye “bu dataset’i analiz ettim” diye değil, “bir şirketin problemini çözdüm” diye başla.

❌ Kötü:

This project uses a Kaggle dataset.

✅ İyi:

This analysis helps an e-commerce operations team understand revenue trends, product performance, refund risk, and customer behavior.

🟢 2. En üste güçlü bir Executive Summary koy

İlk 30 saniyede okuyucu şunları anlamalı:

✅ Ne analiz edildi?
✅ Neden önemli?
✅ En büyük bulgu ne?
✅ Ne öneriyorsun?
✅ İş etkisi ne?

Örnek yapı:

## Executive Summary

This project analyzes customer churn for a subscription-based service. The analysis found that early-stage customers are the highest-risk group, especially within the first month. Based on this finding, the retention team should prioritize onboarding, activation nudges, and early lifecycle engagement.
🟢 3. Başlığı teknik değil, iş odaklı yaz

README başlığı çok önemli. İlk izlenimi belirler.

❌ Zayıf Başlık	✅ Güçlü Başlık
SQL Project	Customer Retention Analysis
Tableau Dashboard	Executive Sales Performance Dashboard
Python EDA	E-commerce Revenue Trend Analysis
Churn Prediction Model	SaaS Customer Churn & Retention Analysis
HR Tableau Project	Employee Attrition & Retention Risk Analysis

Başlıkta mümkünse şu kelimeler olsun:

🔹 Revenue
🔹 Churn
🔹 Retention
🔹 ROI
🔹 Sales
🔹 Product Performance
🔹 Customer Segmentation
🔹 Refund Rate
🔹 Loyalty Program
🔹 Cost Analysis
🔹 Attrition

🟢 4. Stakeholder belirt

README’de analiz kime yapılıyor belli olsun.

Örnek:

Primary stakeholder: Head of Operations  
Business goal: Identify revenue risks and improve product performance.

Stakeholder örnekleri:

👔 Head of Operations
📈 Marketing Manager
🛒 E-commerce Growth Team
👥 People Operations Manager
💰 Finance Team
📦 Product Manager
🏥 Healthcare Strategy Team

Bu küçük detay projeyi “ödev” havasından çıkarıp “iş projesi” havasına sokar.

🟢 5. Business Questions yaz

Teknik sorular değil, şirket soruları yaz.

❌ Kötü:

- Which Python libraries were used?
- How was the data cleaned?
- Which SQL queries were written?

✅ İyi:

- Which customer segments have the highest churn risk?
- Which products drive the strongest revenue?
- Which months show seasonal sales drops?
- Does the loyalty program increase customer value?
- Which regions need targeted marketing support?
🟢 6. Insight’ları sayılarla yaz

Sadece “arttı / azaldı” deme. Sayı ver.

❌ Zayıf:

Sales decreased in 2022.

✅ Güçlü:

Sales declined sharply in Q4 2022, with January and February showing average YoY growth of -12% and -23%.

❌ Zayıf:

New users churn more.

✅ Güçlü:

Customers in their first month showed the highest churn risk, suggesting onboarding is the most important retention lever.

🟢 7. Grafik başlıklarını insight gibi yaz

Grafik başlığı “grafik ne gösteriyor?” değil, “grafikten çıkan sonuç ne?” demeli.

❌ Kötü:

Revenue by Month

✅ İyi:

Revenue peaked in 2020 before normalizing after pandemic-driven demand

❌ Kötü:

Attrition by Department

✅ İyi:

Sales and Customer Support show the highest early-tenure attrition risk

❌ Kötü:

Distribution of Listings by Year

✅ İyi:

New Airbnb listings dropped sharply after 2019 due to COVID and market pressure
🟢 8. En iyi grafik ve dashboard’ları README’ye koy

Hiring manager dosyaları tek tek gezmez. En iyi görseller doğrudan README’de görünmeli.

README’de şunlar olmalı:

📊 En iyi 2–4 grafik
🖼️ Dashboard screenshot
📌 Her grafiğin altında kısa insight
💡 Her insight’tan sonra recommendation

Grafiği koyup bırakma. Altına mutlaka yorum yaz.

🟢 9. Recommendation’ları insight’a bağla

Öneri genel olmamalı. Analizden çıkmalı.

❌ Zayıf:

Improve customer retention.

✅ Güçlü:

Because first-month customers show the highest churn risk, the retention team should prioritize onboarding emails, activation nudges, and personalized first-month engagement campaigns.

En iyi format:

Insight	Evidence	Recommendation
First-month churn is highest	New users churn more than mature users	Improve onboarding and activation
January-February sales are weak	YoY growth: -12% and -23%	Launch seasonal campaigns earlier
Refunds are concentrated in specific products	Refund rate above average	Review product descriptions and quality
🟢 10. Analizi 3–5 ana bölüme ayır

Rastgele grafik dizisi yapma. Analizi ana başlıklara böl.

E-commerce projesi için:

🟦 Sales Trends
🟩 Product Performance
🟨 Loyalty Program
🟧 Refund Rates
🟪 Regional Results

SaaS churn projesi için:

🟦 Customer Lifecycle
🟩 Churn Risk Segments
🟨 Usage Behavior
🟧 Retention Opportunities
🟪 Recommendations

HR projesi için:

🟦 Attrition Overview
🟩 Tenure Risk
🟨 Department Risk
🟧 Age / Role Segments
🟪 Retention Recommendations

🟢 11. Görselleri slide-ready yap

Grafikler sunuma konabilecek kadar temiz görünmeli.

Yap:

✅ Grid line azalt
✅ Sayıları sadeleştir: 59K, $1.3M, 25%
✅ Gereksiz axis detaylarını kaldır
✅ Başlığı insight olarak yaz
✅ Renkleri sade kullan
✅ Grafik boyutlarını küçült
✅ Bar chart dışında line chart, heatmap, cohort table gibi görseller kullan

Amaç:

Grafik ham Python çıktısı gibi değil, profesyonel analiz slaytı gibi dursun.

🟢 12. Teknik detayları sona veya ayrı dosyaya koy

README’nin üst kısmı teknik olmamalı.

Üste koy:

✅ Business problem
✅ Executive summary
✅ Key metrics
✅ Key insights
✅ Visuals
✅ Recommendations
✅ Business impact

Alta veya ayrı dosyaya koy:

⚪ SQL queries
⚪ Python notebook
⚪ Data cleaning steps
⚪ Data dictionary
⚪ Tools used
⚪ Repository structure
⚪ Methodology details

❌ README’de Yapılmaması Gerekenler
🔴 1. README’yi kod dosyası gibi kullanma

❌ Uzun SQL query koyma
❌ Python kodlarını ana bölüme yapıştırma
❌ Data cleaning adımlarını uzun uzun anlatma
❌ “I used pandas / matplotlib / SQL joins” diye anlatma

Hiring manager önce kodu değil, bulguyu ve iş etkisini görmek ister.

🔴 2. “SQL Project / Tableau Project / Python Project” deme

Bunlar projeyi teknik ödev gibi gösterir.

❌ SQL Project
❌ Tableau Project
❌ Python EDA
❌ Machine Learning Project
❌ Portfolio Project

Bunun yerine:

✅ Sales Performance Analysis
✅ Marketing ROI Analysis
✅ Customer Retention Analysis
✅ Employee Attrition Analysis
✅ Product Refund Risk Analysis

🔴 3. “Aspiring Data Analyst” yazma

Kendini zayıf konumlandırma.

❌ Aspiring Data Analyst
❌ Wannabe Data Analyst
❌ Junior portfolio project
❌ I built this project to practice

Daha güçlü:

✅ Data Analyst focused on business insights and dashboard reporting
✅ Data analyst specializing in stakeholder-ready dashboards and recommendations
✅ Data analyst focused on SQL, business metrics, and data storytelling

🔴 4. Çok fazla proje koyma

5–7 tane yarım proje yerine 2–3 tane çok güçlü proje daha iyi.

❌ Çok proje = dağınık görünür
✅ Az ama güçlü proje = odaklı görünür

En iyisi:

🏆 2 tane çok iyi proje
veya
🏆 3 tane farklı domain / skill gösteren proje

🔴 5. Role karışıklığı yaratma

Data Analyst işi istiyorsan portföyün Data Analyst gibi görünmeli.

Kaçın:

⚠️ Machine Learning model deployment
⚠️ ETL pipeline
⚠️ Airflow DAGs
⚠️ Hyperparameter tuning
⚠️ Deep learning
⚠️ Database architecture

Data Analyst için öne çıkar:

✅ Business metrics
✅ SQL analysis
✅ Dashboard
✅ KPI tracking
✅ Insight
✅ Recommendation
✅ Storytelling
✅ Stakeholder communication

🔴 6. Passion project’i hobi gibi bırakma

Kişisel ilgi alanını şirket bağlamına çevir.

❌ My Spotify Wrapped Analysis
✅ Music Streaming User Retention Analysis

❌ Dungeons & Dragons Character Analysis
✅ Video Game Customer Engagement Analysis

❌ Football Match Statistics
✅ Sports Marketing Audience Analysis

Kural:

Proje hobin gibi değil, şirketin senden isteyebileceği iş gibi görünmeli.

🔴 7. Grafik başlıklarını teknik bırakma

❌ Distribution of users
❌ Bar chart of revenue
❌ Histogram of age
❌ Univariate analysis
❌ Bivariate analysis

Bunlar yerine:

✅ Revenue declined after Q4 due to weaker demand
✅ Younger customers show higher churn risk
✅ Loyalty members spend more but order less often
✅ Early-tenure employees are most likely to leave

🔴 8. Genel recommendation yazma

❌ Improve marketing
❌ Increase sales
❌ Reduce churn
❌ Improve employee wellbeing
❌ Focus on customers

Bunlar analiz yapılmadan da söylenebilir.

Güçlü öneri şöyle olur:

✅ Hangi segment?
✅ Hangi metrik?
✅ Hangi aksiyon?
✅ Hangi beklenen etki?

Örnek:

Because January and February showed negative YoY sales growth, the marketing team should launch seasonal campaigns before these low-demand months to reduce recurring revenue dips.
🧨 En Çarpıcı README Formülü

README’yi şu sırayla yaz:

# Business-Focused Project Title

## Executive Summary
1 kısa paragraf: problem, ana bulgu, öneri.

## Business Context
Şirket / stakeholder / problem.

## Key Metrics
Revenue, churn, retention, AOV, ROI, refund rate vb.

## Key Business Questions
3–5 iş sorusu.

## Insights Deep Dive
Insight 1 + grafik + yorum  
Insight 2 + grafik + yorum  
Insight 3 + grafik + yorum  

## Recommendations
Insight’a bağlı net aksiyonlar.

## Business Impact
Bu öneriler neyi iyileştirebilir?

## Technical Appendix
Tools, SQL, Python, data cleaning, repo structure.
🏆 En Güçlü README’de Olması Gereken 10 Şey

✅ 1. İş odaklı başlık
✅ 2. Executive summary
✅ 3. Stakeholder bilgisi
✅ 4. Gerçek business metrics
✅ 5. Sayılarla desteklenen insight
✅ 6. Insight başlıklı grafikler
✅ 7. Slide-ready dashboard / görseller
✅ 8. Recommendation + evidence tablosu
✅ 9. Teknik detayların arka plana alınması
✅ 10. “So what?” sorusuna net cevap

🚫 En Büyük 10 README Hatası

❌ 1. README’yi kod deposu gibi yazmak
❌ 2. Projeye “SQL Project” demek
❌ 3. En başa tools listesi koymak
❌ 4. Data cleaning’i uzun uzun anlatmak
❌ 5. Grafik koyup insight yazmamak
❌ 6. Genel recommendation vermek
❌ 7. Çok fazla proje göstermek
❌ 8. Role karışıklığı yaratmak
❌ 9. “Aspiring” gibi zayıf ifadeler kullanmak
❌ 10. Projeyi şirket bağlamına oturtmamak

⭐ Tek Cümlelik Altın Kural

README’yi okuyan biri 1 dakika içinde hangi iş problemini çözdüğünü, ne bulduğunu, neden önemli olduğunu ve ne yapılması gerektiğini anlamalı.

🎯 En kısa özet

README’de şunu yap:

🟢 Kod değil insight göster.
🟢 Araç değil iş problemi anlat.
🟢 Grafik değil hikâye kur.
🟢 Genel yorum değil metrikli bulgu yaz.
🟢 Ödev gibi değil stakeholder sunumu gibi hazırla.
🟢 Teknik detayları alta koy.
🟢 Recommendation’ı mutlaka evidence’a bağla.
