# Salesforce Reports

## Objective

Create Salesforce reports to provide visibility into sales pipeline, opportunity outcomes, sales-agent performance, and product revenue.

## Reports Created

### 1. Opportunities by Stage

**Purpose:** Monitor the number of opportunities at each stage of the sales pipeline.

**Grouping:**
- Opportunity Stage

**Measure:**
- Record Count

**Business Use:**
Helps identify how opportunities are distributed across the sales process.

---

### 2. Won vs Lost

**Purpose:** Compare closed opportunities based on their final outcome.

**Grouping:**
- Opportunity Stage

**Filter:**
- Closed Won
- Closed Lost

**Measure:**
- Record Count

**Business Use:**
Provides a quick view of the balance between won and lost opportunities.

---

### 3. Opportunities by Sales Agent

**Purpose:** Analyse opportunity performance by sales representative.

**Grouping:**
- Opportunity Owner / Sales Agent

**Measure:**
- Sum of Opportunity Amount

**Business Use:**
Helps compare the sales pipeline and opportunity value associated with different sales agents.

---

### 4. Revenue by Product

**Purpose:** Analyse sales revenue associated with individual products.

**Grouping:**
- Product Name

**Measure:**
- Sum of Total Price

**Business Use:**
Helps identify products generating higher revenue and supports product-performance analysis.

## Reporting Approach

The reports were designed around key sales-performance questions:

| Business Question | Report |
|---|---|
| Where are opportunities in the sales process? | Opportunities by Stage |
| How many opportunities were won or lost? | Won vs Lost |
| Which sales agents have higher opportunity value? | Opportunities by Sales Agent |
| Which products generate more revenue? | Revenue by Product |

## Outcome

The reports provide structured sales insights that can be combined into a Salesforce dashboard for management-level performance monitoring.

## Project Type

Self-Directed / Portfolio Project
