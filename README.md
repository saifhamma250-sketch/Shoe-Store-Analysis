English Version

## 📊 Retail Sales Analysis & Predictive Modeling

### 📌 Project Overview
This project combines **Exploratory Data Analysis (EDA)** and **Advanced Machine Learning** to analyze retail sales data across multiple international markets. The goal is to extract actionable business insights regarding pricing strategies and inventory management, and to build a highly accurate predictive model for future sales forecasting.

---

### 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Manipulation:** `pandas`, `numpy`
* **Machine Learning:** `scikit-learn`, `XGBoost`
* **Evaluation Metrics:** Mean Absolute Error (MAE), $R^2$ Score

---

### 🚀 Key Steps & Workflow

#### 1. Data Cleaning & Preprocessing
* Handled date formats and extracted temporal features (Quarter, Month, Year) to understand seasonal trends.
* Checked for missing data and verified dataset integrity using `df.duplicated()`.

#### 2. Exploratory Data Analysis (EDA)
* Segmented and aggregated sales data (`groupby`) to measure total revenue and units sold per brand (e.g., Puma, New Balance) across different countries (e.g., France, Germany).
* Conducted **Correlation Analysis** between pricing and sales volume to assess customer price sensitivity.

#### 3. Predictive Modeling (Machine Learning)
* Developed and trained predictive models using `scikit-learn` and **XGBoost** to forecast future revenue/sales based on historical features.
* Evaluated performance using Mean Absolute Error (MAE).

---

### 📈 Results & Business Value

* **Model Performance:** 
  * Baseline Model $R^2$ Score: **99.54%**
  * XGBoost Model $R^2$ Score: **99.65%** (Best Performance)
  * Mean Absolute Error (MAE): **$52.42**
* **Business Insights:** Provided strategic recommendations for optimizing stock allocation in European branches and dynamically adjusting prices based on brand elasticity.

---

 النسخة العربية

## 📊 تحليل مبيعات التجزئة والنمذجة التنبؤية

### 📌 نبذة عن المشروع
يجمع هذا المشروع بين **التحليل الاستكشافي للبيانات (EDA)** و**التعلم الآلي المتقدم (Machine Learning)** لتحليل بيانات المبيعات في أسواق عالمية متعددة. يهدف المشروع إلى استخلاص رؤى تجارية قابلة للتطبيق لتطوير استراتيجيات التسعير وإدارة المخزون، بالإضافة إلى بناء نموذج تنبؤي عالي الدقة لتوقع المبيعات المستقبلية.

---

### 🛠️ التقنيات والمكتبات المستخدمة
* **لغة البرمجة:** Python
* **معالجة البيانات:** `pandas`, `numpy`
* **التعلم الآلي:** `scikit-learn`, `XGBoost`
* **مقاييس التقييم:** متوسط الخطأ المطلق (MAE)، معامل التحديد ($R^2$ Score)

---

### 🚀 مراحل سير العمل في المشروع

#### 1. تنظيف وتجهيز البيانات (Data Preprocessing)
* معالجة صيغ التواريخ واستخراج المتغيرات الزمنية (الربع السنوي، الشهر، السنة) لفهم الاتجاهات الموسمية.
* التحقق من جودة البيانات وضمان خلوها من التكرار باستخدام `df.duplicated()`.

#### 2. التحليل الاستكشافي للبيانات (EDA)
* تجميع وتصنيف البيانات لمعرفة إجمالي الإيرادات والوحدات المباعة لكل ماركة تجارية (مثل Puma و New Balance) في دول مختلفة (مثل فرنسا وألمانيا).
* إجراء **تحليل ارتباط (Correlation)** بين الأسعار وحجم المبيعات لقياس مدى حساسية العملاء لتغير الأسعار.

#### 3. النمذجة التنبؤية (Machine Learning)
* بناء وتدريب نماذج تعلم آلي متطورة وخوارزمية **XGBoost** للتنبؤ بالقيمة المستقبلية للمبيعات بناءً على المعطيات السابقة.
* تقييم دقة النموذج باستخدام مقياس متوسط الخطأ المطلق (MAE).

---

### 📈 النتائج والقيمة التجارية المحققة

* **أداء النموذج التنبؤي:**
  * دقة النموذج العادي ($R^2$): **99.54%**
  * دقة نموذج XGBoost ($R^2$): **99.65%** (الأداء الأفضل)
  * متوسط الخطأ المطلق (MAE): **52.42$**
* **الرؤى التجارية:** تقديم توصيات استراتيجية للإدارة حول كيفية إعادة توزيع المخزون في الفروع الأوروبية وتعديل أسعار المنتجات بناءً على مرونة الطلب لكل ماركة.
