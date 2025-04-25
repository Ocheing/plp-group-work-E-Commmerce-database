# plp-group-work-E-Commmerce-database
# 🛒 E-commerce Database Design – PLP Cohort VII (Feb 2025)

 The objective is to collaboratively design and implement a robust relational database for an e-commerce platform.

## 🎯 Objective

To master database design by:
- Creating a detailed Entity-Relationship Diagram (ERD)
- Structuring and implementing an SQL database from scratch
- Collaborating as a team through analysis, design, and version control

---

## 🛠️ Tools Used

- **ERD Design**:  draw.io
- **Version Control**: Git & GitHub
- **Database**: MySQL

---

## 🧩 Tables Included

The following tables were created to represent various aspects of an e-commerce platform:

| Table Name          | Description |
|---------------------|-------------|
| `product`           | Stores product name, brand, base price |
| `product_image`     | Stores product image URLs or file paths |
| `brand`             | Holds brand information |
| `product_item`      | Represents purchasable product variations |
| `product_variation` | Connects products to variations like size and color |
| `product_category`  | Classifies products (e.g., electronics, clothing) |
| `color`             | Manages color options |
| `size_category`     | Groups types of sizes (e.g., clothing, shoes) |
| `size_option`       | Stores specific sizes (e.g., S, M, L, 42) |
| `product_attribute` | Custom attributes like material, weight |
| `attribute_category`| Groups attributes into physical, technical, etc. |
| `attribute_type`    | Defines attribute formats (text, number, boolean) |

---

## 🧠 Data Flow and Relationships

- **One-to-many** and **many-to-many** relationships exist between product, category, brand, color, size, and attribute-related tables.
- Primary and foreign keys are defined to maintain referential integrity.
- The ERD clearly maps how data moves across tables and defines all constraints.

---

## 📂 Repository Contents

- `ecommerce.sql`: Full SQL script to create and populate the database
- `ERD.png`: The ERD diagram for the database structure
- `README.md`: Project overview and documentation

---

## 👥 Group Collaboration

This project was done collaboratively under the PLP platform:
- Regular check-ins and discussions
- Shared work using GitHub for version control
- Everyone contributed to analysis, design, and SQL scripting
  
Group Members
abdulakeem	olatubosun	       abdulakeemolatubosun@gmail.com	
patrick	mukuha	                githinjipatrick444@gmail.com	
millicent	anyango	              millicentanyango999@gmail.com	
samuel	musyoka	                samuelmmy071@gmail.com	
nontokozo	mabobe	              nontokozosweetness18@gmail.com	
babette	aketch	                akechbabette44@gmail.com	
brenda	riziki	                rizikibrenda4@gmail.com	
anyangu mukhutsi	              majimbo	majimboanyangu50@gmail.com	
kiplimo	dennis	                ruttodennis002@gmail.com	
james	ng'ang'a                  wamweajames1@gmail.com
---

## 📌 How to Use This Project

1. Clone the repository:
   ```bash
   git clone https://github.com/Ocheing/plp-group-work-E-Commmerce-database.git
   cd plp-group-work-E-Commmerce-database
Open and run ecommerce.sql using MySQL Workbench or any MySQL-compatible client to create the database schema.

Use the ERD diagram to understand the relationships and structure.

🔗 License
This project is part of the Power Learn Project peer group assignment and is intended for educational purposes only.

🙌 Special Thanks
Thanks to the PLP team, mentors, and fellow group members for the guidance and teamwork that made this project possible!
