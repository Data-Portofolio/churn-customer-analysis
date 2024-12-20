<h3 align='center'> ▂▃▅▇█▓▒░C𝚞𝚜𝚝𝚘𝚖𝚎𝚛 C𝚑𝚞𝚛𝚗 A𝚗𝚊𝚕𝚢𝚜𝚒𝚜░▒▓█▇▅▃▂</h3>

<p align="center">
  <img src="https://github.com/user-attachments/assets/6a07e3a9-8df6-4d1f-8b1d-6c5823bb32ac" width="200" height="150" />
</p>

<p align='center'>
    <a href='https://github.com/astutir'><img alt='Follow Me on GitHub' title='Follow Me on GitHub' src='https://custom-icon-badges.herokuapp.com/github/followers/astutir?style=for-the-badge&&label=GitHub&logo=Github&color=green'/>
    </a>
     <a href='https://www.linkedin.com/in/a-rahmawati' target='_blank'><img alt='Follow Me on LinkedIn' title='Follow Me on LinkedIn' src='https://img.shields.io/badge/linkedin%20-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white' alt='LinkedIn Profile'/>
    </a>
    <a href='https://public.tableau.com/app/profile/astuti.rahma/viz/CustomerChurnDASHBOARD/Dashboard8' target='_blank'>
    <img src='https://img.shields.io/badge/Tableau-Visit%20Dashboard-grey?style=for-the-badge&logo=tableau&logoColor=white&labelColor=red' alt='Tableau Public Profile'/>
</a>

</p>


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
   - Churn Rate : Metrik yang mengukur persentase pelanggan yang meninggalkan layanan perusahaan dalam suatu periode waktu, biasanya dihitung per bulan atau per tahun.
   - Formula Churn Rate:
     
    `(Jumlah pelanggan yang meninggalkan layanan / Total pelanggan awal) x 100%`

**Faktor-faktor yang Mempengaruhi Churn:**
   - **Kualitas Layanan**: Pelanggan cenderung meninggalkan jika kualitas layanan tidak memenuhi harapan.
   - **Harga**: Penyesuaian harga yang tidak sesuai dapat menjadi penyebab pelanggan beralih.
   - **Layanan Pelanggan**: Pelayanan pelanggan yang buruk dapat memicu keputusan pelanggan untuk meninggalkan perusahaan.
   - **Persaingan**: Keberadaan penyedia layanan alternatif yang lebih menarik dapat mempengaruhi churn rate.

**Dampak Churn pada Perusahaan:**
   - **Penurunan Pendapatan**: Kehilangan pelanggan berarti penurunan pendapatan dari abonemen atau penggunaan layanan.
   - **Biaya Akuisisi Pelanggan**: Meningkatnya biaya untuk mendapatkan pelanggan baru guna menggantikan yang telah meninggalkan.
   - **Reputasi Perusahaan**: Churn yang tinggi dapat merusak reputasi perusahaan di pasar.

**Strategi Mengurangi Churn:**
   - **Peningkatan Kualitas Layanan**: Memastikan bahwa layanan yang disediakan memenuhi atau bahkan melebihi harapan pelanggan.
   - **Program Loyalty**: Menyusun program yang memberikan insentif kepada pelanggan setia.
   - **Analisis Data**: Menggunakan data untuk mengidentifikasi pola churn dan mengambil tindakan pencegahan.

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
 **Databel**, a telecom provider, is experiencing customer churn where users terminate their services and switch to competitors. As **a Data Consultant**, my task is to investigate the root causes behind customer churn and provide actionable insights. This analysis will help Databel reduce churn rates, enhance customer satisfaction, and strengthen its market position.
  
### [Goal](#-goal)
- **Reduce Churn Rates**: Implement data-driven strategies to decrease the number of customers leaving Databel. Success in this goal will contribute to increased customer retention, improved revenue stability, and a stronger competitive position in the telecom market.
  
### [Objectives](#-objectives)
- **Identify Key Drivers Behind Customer Churn**: Analyze customer data to pinpoint the primary factors contributing to churn.
- **Segment Customer Profiles**: Classify customers according to their churn risk to understand which segments are most likely to leave the service.
- **Provide Data-Driven Recommendations**: Develop actionable insights and strategies to help Databel reduce customer churn and improve customer retention rates.
### [Business Metrics](#-business-metrics)
-  **Churn Rate** 

## Exploratory Data Analysis (EDA)

### [Dataset](#-dataset) 
- The Databel dataset consists of 29 columns and 6687 records.

[Metadata - Case study_ Analyzing customer churn in Tableau](https://assets.datacamp.com/production/repositories/5952/datasets/e117ea26cf73db68bbf18cba29d0c84d4961ee9e/Metadata%20-%20Case%20study_%20Analyzing%20customer%20churn%20in%20Tableau.pdf)

### [Decriptive Statistics](#-descriptive-statistics)

### [Insights](#-insights)
#### 1. The churn rate of Databel is `26.86%`

#### 2. Churn Category Reason
Almost half of all customer churning are related to **`the competitor category (44.82%)`**.
<p align="center"><img src="https://github.com/Data-Portofolio/churn-customer-analysis/assets/133883292/9aafa6a3-f4b2-40d0-b713-1f98147bd76c)"></p>

#### 3. Churn Reason
**Top 5 reasons** of churn customer in Databel :
- Competitor made better offer (29.25%)
- Competitor had better devices
- Attitude of support person
- Don't know
- Competitor offered more data

<p align="center"><img src="https://github.com/Data-Portofolio/churn-customer-analysis/assets/133883292/a39fd10e-d0a3-4905-8a70-7b610e77bee8"></p>


#### 4. Geomap
The churn rate in **California (CA)** is the highest (`63.24%`).
<p align="center"><img src="https://github.com/Data-Portofolio/churn-customer-analysis/assets/133883292/7c95a24b-89ec-44ec-a7c8-c8e22a1845a5"></p>


## Analyze & Visualize Data
#### 1. Demographics
- Churn rate for `Senior group` is 10% higher than average `(38.22%)`.
  
<p align="center"><img src="https://github.com/Data-Portofolio/churn-customer-analysis/assets/133883292/8f7eddcc-6620-465e-8336-bcb7e27f87ac"></p>

#### 2. Age Group
- The age group of 80-85 year old have the highest churn rates `(52%)` but they contain the least of people `(only 25 customers)`. 
<p align="center"><img src="https://github.com/Data-Portofolio/churn-customer-analysis/assets/133883292/26ce648f-a589-4f24-b407-c603bcc368c4"></p>

#### 3. Churn Rate by Group of Customer
- The lowest churn rate **(`5.6%`)** is a customer group consisting of 6 people and conversely, the highest churn rate (`32.85%`) is for customers who are **`Not in a Group`**.
  
<p align="center"><img src="https://github.com/Data-Portofolio/churn-customer-analysis/assets/133883292/d2b77c32-121e-4f63-b86e-5c29e81d6b8d"></p>

#### 4. Churn Rate vs Dynamic Metric
- The average monthly charge in the group is relatively low compared to customers `Not in a group`.  This is what causes the churn rate in `Not in a Group` to be the highest.
  <p align="center"><img src="https://github.com/Data-Portofolio/churn-customer-analysis/assets/133883292/e5c0f8fe-307a-4f9d-a7d2-0969cd5aca6a"></p>
  
- Based on analysis of the graph below, it can be seen that there are 5166 customers or 77.25% of all customers, who are `Not in a Group`.
  <p align="center"><img src="https://github.com/Data-Portofolio/churn-customer-analysis/assets/133883292/6c85d740-d3e1-42e4-953e-2cc8088ca990"></p>

#### 5. Unlimited Plan 
- Customers who have an unlimited plan but do not consume more than 5GB per month tends to churn more.
  <p align="center"><img src="https://github.com/Data-Portofolio/churn-customer-analysis/assets/133883292/f8ef0aae-16ca-4807-96cd-cf93a031be9f"></p>
  
#### 6. International Plan
- Customers who an `International Plan` but do not actively make international calls have the highest churn rate (`71.19` but fortunately, the number of customers in this group is the lowest (`177 customers`). In this group, there appears to be the highest average monthly charge (`$33.12`).
<p align="center"><img src="https://github.com/Data-Portofolio/churn-customer-analysis/assets/133883292/10995b29-fa77-428d-9177-ee65498fb6d1"></p>

#### 7. Contract Type & Payment method
- Out of 1796 churned customers, 1141 of them have an average monthly charge of `$18.75`, with a contract type of `Month to Month` and a payment method of `Direct Debit`. This is a significant number, so DataBel needs to focus on this customer group.
<p align="center"><img src="https://github.com/Data-Portofolio/churn-customer-analysis/assets/133883292/067da8c9-7a6d-4749-ba70-82cb94ce951d"></p>

## Business Insights & Recommendation
#### 1. The highest reason for customer churn in Databel is that competitors made better offers, accounting for 29.25% of the churn.
   > Suggest: Databel should develop more attractive and tailored offerings that meet customer needs, making them more appealing than those of competitors in terms of pricing and packages. Additionally, Databel's devices should be more advanced than those of its competitors. Furthermore, the support staff should receive training to ensure they provide high levels of customer satisfaction, particularly for the senior group.
#### 2. The churn rate for customers who pay for an international plan, but don't call internationally is skyhigh.
  
  > Suggest: Contact customers who are an on an international plan but have not called internationally and propose them to downgrade their plan.
  
#### 3. Senior customers have a churn rate 10% higher than average.
  > Suggest: Databel should implement simplified billing, dedicated support channels, special pricing, and loyalty rewards for senior customers. Personalized assistance and educational initiatives can help seniors feel more confident and satisfied with the service. Specifically, for the 80-85 age group, Databel should provide enhanced customer service, including priority service, in-home assistance, and health-related
#### 4. The overall churn rate for customers in a group is lower than for those who are not in a group. This is partly because the average monthly charge for customers in a group is relatively low compared to those not in a group.
  > Suggest: Databel should contact customers to promote group plans, highlighting the lower average monthly charges. Additionally, offer special discounts or incentives for customers to switch from individual plans to group plans. This approach can help reduce churn by making the service more affordable and appealing.

#### 5. Customers who have an unlimited plan but do not consume more than 5GB per month tends to churn more.
  > Suggest: Databel should contact customers to offer attractive pricing and other benefits that are more appealing compared to competitors.

#### 6. Customers who an `International Plan` but do not actively make international calls have the highest churn rate.
  > Suggest: Contact customers with an International Plan who have not actively made international calls for a certain period to offer them a switch to a normal package or provide a monthly discount below $30 or below any competitors. This can help lower their average monthly charge, making it more competitive and reducing the churn rate.

#### 7. That 63% customer churned  were on a Month to Month contract with Direct Debit payment.
  > Suggest: Databel should contact customers through direct calls or campaigns via email/messages to offer a more attractive monthly charge for the Month to Month plan, such as below $18 or lower than any competitors, and propose payment options via credit card. Databel can also offer a more affordable annual package for customer that switch from Month to Month to an annual plan.

#### 8. California is a state in the western United States that has the highest churn rate.
  > Suggest: Databel should contact customers in California through campaigns to offer more attractive options, such as a lower average monthly charge and devices that are more advanced than those of competitors



<p align="right">(<a href="#top">back to top</a>)</p>

<p align="center">
    :copyright: 2024 | A-Rahmawati </p>
</h3>
