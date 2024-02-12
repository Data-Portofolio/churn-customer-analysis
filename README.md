<h3 align='center'> ▂▃▅▇█▓▒░C𝚑𝚞𝚛𝚗 C𝚞𝚜𝚝𝚘𝚖𝚎𝚛 A𝚗𝚊𝚕𝚢𝚜𝚒𝚜░▒▓█▇▅▃▂</h3>
<br>
<details><summary>Data Analysis Flow in Tableu</summary>
  
<p align="center"><img src="https://github.com/Data-Portofolio/churn-customer-analysis/assets/133883292/afcae735-4e0a-434c-8d49-8fd9ac05601b"></p>

##### 1. Data Check: to make sure the data you received makes sense and it is ready to work with. 
Example:
  - check for duplicate values or 
  - missing values, and 
  - do a sense check with other internal data sources.
    
##### 2. Data Exploration: This is the time where you need to ask yourself different questions to explore the data. 
An example question could be:
  - Does an increase in revenue also lead to an increase in profit?
  - You'll also build your first visualization in this step.
    
##### 3. Analyze & Visualize Data: It's key to choose the right visualization to convey a message. 
  - This step also enables you to dig deeper into certain topics to make sure you don't miss any insights.
    
##### 4. Dasboarding 
  - Combine the visualizations

##### 5. Communicate the insights with stakeholders
</details>

<details><summary><b>Concept of Churn Analysis</b></summary>
> **`Churn Analysis`** merupakan proses memahami dan menganalisis tingkat pelanggan yang meninggalkan atau berhenti menggunakan produk atau layanan perusahaan dalam suatu periode waktu tertentu. Analisis churn bertujuan untuk mengidentifikasi penyebab dan faktor-faktor yang berkontribusi terhadap kehilangan pelanggan, serta mengembangkan strategi untuk mengurangi tingkat churn. Dalam konteks telekomunikasi, churn mengindikasikan pelanggan yang beralih ke penyedia layanan lain atau berhenti menggunakan layanan telekomunikasi.
<br>
  
**Churn Rate:**
   - Churn Rate adalah metrik yang mengukur persentase pelanggan yang meninggalkan layanan perusahaan dalam suatu periode waktu, biasanya dihitung per bulan atau per tahun.
   - Formula Churn Rate:
     `(Jumlah pelanggan yang meninggalkan layanan / Total pelanggan awal) x 100%`

**Faktor-faktor yang Mempengaruhi Churn:**
   - Kualitas Layanan: Pelanggan cenderung meninggalkan jika kualitas layanan tidak memenuhi harapan.
   - Harga: Penyesuaian harga yang tidak sesuai dapat menjadi penyebab pelanggan beralih.
   - Layanan Pelanggan: Pelayanan pelanggan yang buruk dapat memicu keputusan pelanggan untuk meninggalkan perusahaan.
   - Persaingan: Keberadaan penyedia layanan alternatif yang lebih menarik dapat mempengaruhi churn rate.

**Dampak Churn pada Perusahaan:**
   - Penurunan Pendapatan: Kehilangan pelanggan berarti penurunan pendapatan dari abonemen atau penggunaan layanan.
   - Biaya Akuisisi Pelanggan: Meningkatnya biaya untuk mendapatkan pelanggan baru guna menggantikan yang telah meninggalkan.
   - Reputasi Perusahaan: Churn yang tinggi dapat merusak reputasi perusahaan di pasar.

**Strategi Mengurangi Churn:**
   - Peningkatan Kualitas Layanan: Memastikan bahwa layanan yang disediakan memenuhi atau bahkan melebihi harapan pelanggan.
   - Program Loyalty: Menyusun program yang memberikan insentif kepada pelanggan setia.
   - Analisis Data: Menggunakan data untuk mengidentifikasi pola churn dan mengambil tindakan pencegahan.

**Pemantauan dan Evaluasi Churn Rate:**
   - Pemantauan Rutin: Melakukan pemantauan secara rutin terhadap Churn Rate untuk mengidentifikasi tren dan pola.
   - Evaluasi Penyebab: Menganalisis penyebab churn untuk memahami faktor-faktor yang berkontribusi.


![image](https://github.com/Data-Portofolio/churn-customer-analysis/assets/133883292/dd641b53-3da4-4afb-90d4-284bda20084f)
 
<details><summary>More Explanation...</summary>
  
### Konsep Leaky Bucket Problem

Anda dapat membandingkan `churn` dengan `Leaky Bucket Problem`. Anda dapat mengisi ember dengan lebih banyak air (atau pelanggan baru dalam hal ini), tetapi pendapatan keseluruhan Anda tidak akan meningkat jika pelanggan yang sudah ada meninggalkan perusahaan Anda. Lebih mudah untuk mempertahankan pelanggan daripada menarik pelanggan baru, jadi untuk banyak perusahaan, mengurangi churn menjadi prioritas.

>Leaky Bucket Problem merujuk pada suatu model atau analogi yang digunakan untuk menggambarkan cara mengelola data atau permintaan yang masuk ke suatu sistem dengan tingkat yang >berbeda-beda. Dalam konteks churn customer, leaky bucket dapat diartikan sebagai strategi untuk menjaga keberlanjutan dan stabilitas pelanggan. Analogi ini menggambarkan bagaimana >perusahaan berusaha mempertahankan pelanggan sambil terus menarik pelanggan baru.

1. **Bucket (Ember):**
   - Ember dalam konteks ini dapat diartikan sebagai basis pelanggan perusahaan. Ini mencakup pelanggan yang telah ada dan berkontribusi pada pendapatan perusahaan.

2. **Leaky (Bocor):**
   - Kebocoran dalam ember mewakili churn, yaitu pelanggan yang meninggalkan layanan. Kebocoran terjadi ketika pelanggan beralih ke penyedia layanan lain atau berhenti menggunakan layanan perusahaan.

3. **Pendekatan Mengatasi Kebocoran:**
   - Perusahaan harus mencoba mengurangi tingkat kebocoran dengan meningkatkan kualitas layanan, menjaga harga yang bersaing, dan meningkatkan kepuasan pelanggan.

4. **Adding Water (Menambah Air):**
   - Menambah air ke dalam ember mewakili upaya untuk mendapatkan pelanggan baru. Perusahaan dapat fokus pada strategi pemasaran yang efektif dan penawaran layanan yang menarik untuk menarik pelanggan baru ke dalam basis mereka.

**"Keeping Customer Easier to Get New Customer, Reducing Churn is Priority for Many Companies":**

1. **Prioritas Mengurangi Churn:**
   - Perusahaan menyadari bahwa mempertahankan pelanggan yang sudah ada lebih cost-effective daripada mendapatkan pelanggan baru. Oleh karena itu, mengurangi churn menjadi prioritas karena dapat membantu perusahaan mempertahankan pendapatan yang sudah ada.

2. **Mudahnya Mempertahankan Pelanggan:**
   - Memastikan kepuasan pelanggan, memberikan layanan yang berkualitas, dan menawarkan insentif atau program loyalitas membuat pelanggan cenderung tetap setia. Mempertahankan pelanggan yang sudah puas seringkali lebih mudah daripada mendapatkan pelanggan baru.

3. **Penekanan pada Akuisisi Pelanggan Baru:**
   - Meskipun mempertahankan pelanggan penting, perusahaan juga harus fokus pada akuisisi pelanggan baru untuk memperluas basis pelanggannya. Ini melibatkan strategi pemasaran yang efektif, inovasi produk, dan penawaran yang menarik.

4. **Strategi Holistik:**
   - Strategi yang efektif melibatkan pendekatan holistik, termasuk memahami penyebab churn, memperbaiki masalah yang mungkin timbul, dan secara aktif berusaha memahami dan memenuhi kebutuhan pelanggan.

Dalam keseluruhan, strategi "leaky bucket" mencakup upaya untuk mengurangi kebocoran pelanggan (churn) sambil terus menarik pelanggan baru ke dalam basis perusahaan. Pemahaman mendalam tentang kebutuhan pelanggan dan upaya yang terus-menerus untuk meningkatkan layanan dapat membantu perusahaan mencapai keseimbangan yang baik antara mempertahankan pelanggan dan mendapatkan pelanggan baru.
</details> 
</details>

## Business Understanding

### [Problem Statement](#-problem-statement)
> **Databel**, a telecom provider, has problem about customer churn. My role is a <ins>_Data Consultant_</ins> & my task is to discover why customers are churning, or in other words, leave Databel.
  
### [Goal](#-goal)
### [Objectives](#-objectives)
### [Business Metrics](#-business-metrics)

## Exploratory Data Analysis (EDA)

### [Dataset](#-dataset) 
- The Databel dataset consists of 29 different columns and has one row per customer.
### [Decriptive Statistics](#-descriptive-statistics)
### [Insights](#-insights)
- The average churn rate of Databel is 27%
- The main reasons why customers churn is related to competitors(~45%).
- The churn rate in California is abnormally high with 63.24%.

## Analyze & Visualize Data

## Business Insights & Recommendation
- The churn rate for customers who pay for an international plan, but don't call internationally is skyhigh.
  
  > Suggest: Contact customers who are an on an international plan but have not called internationally and propose them to downgrade their plan.

<p>This text needs to <del>strikethrough</del> <ins>since it is redundant</ins>!</p>
<p><tt>This text is teletype text.</tt></p>
<font color="blue">Colored text</font>
<center>This text is center-aligned.</center>
<p>This text contains <sup>superscript</sup> text.</p>
<p>This text contains <sub>subscript</sub> text.</p>
<p>The project status is <span style="color:green;font-weight:bold">GREEN</span> even though the bug count / developer may be in <span style="color:red;font-weight:bold">red.</span> - Capability of span
<p><small>Disclaimer: Wiki also supports showing small text</small></p>
<p><big>Bigger text</big></p>
