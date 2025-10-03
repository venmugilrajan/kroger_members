# kroger_members
🛒 Kroger Members Data Analysis

This project analyzes 100 Kroger customers to understand membership status, spending behavior, and discount eligibility. The goal is to explore patterns between members and non-members and derive insights that can help with customer engagement.

📂 Dataset

kroger_id → Unique customer ID

has_member_card → Y (Member) or NaN/N (Non-member)

Additional features created:

membership_numeric / Is_Member → Encoded membership (1 = Member, 0 = Non-member)

Monthly_Spend → Simulated spend values between 50–500

Discount_Eligible → Members with spend > 200

Spend_Quartile → Spending groups (Q1–Q4)

⚙️ Workflow

Data Cleaning

Handled 37 missing values in has_member_card.

Converted IDs to integer, verified uniqueness.

Exploration & Visualization

Found 63 members (63%) and 37 non-members (37%).

Plotted pie and bar charts of membership distribution.

Statistics

Probability of being a member: 63%

Members spend more (265.5) vs non-members (247.6).

Spending gap between top (Q4) and bottom (Q1) quartile members: 374.28

Numpy Operations

Performed vector addition, dot product, and matrix multiplication with spend and membership arrays.

Advanced Analysis

Identified top 10 members by spend.

Found high-spending non-members (potential membership targets).

Discount eligibility: 33 eligible, 67 not eligible.

📊 Key Insights

Members form the majority (63%) and spend slightly more than non-members.

High-spending non-members exist, which represents an opportunity for conversion.

About 1/3rd of customers are discount-eligible.

Clear spending differences between quartiles show strong segmentation.

🚀 Tools Used

Python

Pandas – Data analysis

NumPy – Computations

Matplotlib & Seaborn – Visualizations
