# Orange_Summer_Challenge
Orange_Summer_Challenge
1. NAME: OWAN AYUK Daisy Ajijia

2. Libraries Used
The following Python libraries were used in the analysis:

- pandas
- numpy
- matplotlib.pyplot
- seaborn
- sklearn
- warnings



3. Summary of Analysis and Observations
The analysis focused on exploring and clustering customer data from a telecommunications dataset. Key steps included:

Data Loading and Initial Exploration:

The dataset contains 1,000 entries with columns such as client_id, age, region, forfait_type (subscription type), appels_min (call minutes), data_mo (data usage), sms_envoyes (SMS sent), and montant_facture (billing amount).

No missing values or duplicates were found.

Descriptive Statistics:

Most customers (70.4%) prefer prepaid subscriptions (prépayé), while 29.6% use postpaid (postpayé).

The highest number of customers are from the Adamaoua region (212), followed closely by Sud-Ouest (208) and Nord-Ouest (206).

Visualizations:

A count plot showed the distribution of subscription types by region, revealing that Nord-Ouest has the highest proportion of prepaid users (73.3%), while Adamaoua has the lowest (66%).

Clustering (Potential Next Step):

This notebook sets up for clustering using KMeans but does not fully implement it due to time constraints.

4. Business Recommendations
- Targeted Marketing:

Focus on converting prepaid users to postpaid in regions like Nord-Ouest and Littoral, where prepaid dominance is highest.

Offer incentives (e.g., discounted data bundles) to postpaid users in Adamaoua to retain them.

- Regional Strategies:

Investigate why Adamaoua has fewer prepaid users—local preferences or network issues? Tailor campaigns accordingly.

For the different segments;
1. For High-Value Segments:
- Develop retention programs with premium services

- Offer bundled packages with enhanced data/calling features

- Personalize loyalty rewards

2. For Young Prepaid Segments:

- Targeted youth-oriented packages

- Social media-focused marketing

- Upsell opportunities to postpaid as they mature

3. For Data-Heavy Users:

- Promote unlimited/high-cap data plans

- Offer device bundles or streaming partnerships

- Network optimization in regions with many data-heavy users

4. For Low-Usage Customers:

- Reactivation campaigns

- Low-cost entry plans to maintain market presence

- Investigate reasons for low engagement


What Could Be Added with More Time?
Clustering Implementation: Apply KMeans/PCA to segment customers based on usage (appels_min, data_mo, montant_facture).

Churn Analysis: Predict prepaid users at risk of leaving using machine learning.

Geospatial Visualization: Map regional trends to identify coverage gaps or promotional hotspots.

Time-Based Analysis: Track usage trends over time to spot seasonal patterns.
- Upselling Opportunities:

Analyze high-usage prepaid customers (data_mo, appels_min) and target them for postpaid upgrades with better value plans.

Customer Segmentation:

Complete the clustering analysis to group customers by usage patterns (e.g., high-data users, frequent callers) for personalized offers.
