# DSA 2050 Week 2: SQL, Data Acquisition and Join Validation

Name: shawn kamuyu
Student ID: 675405

# Objective
using SQLite and pandasto combine customer, order and region data, detect key problems (duplicate and unmatched keys), validate joins by reconciling row counts and totals, and calculate sales KPIs by category, segment and region.

# Key Findings
1. The duplicate CustomerID C004 inflated the join from 15 to 16 rows and sales from KSh 113,500 to 122,600 (an overstatement of KSh 9,100).
2. Order O015 has CustomerID C999, which does not exist in the customers table, so KSh 9,900 cannot be assigned to a segment or region.
3. Corporate generated the most sales (KSh 46,800) and Nairobi was the top region (KSh 39,800).