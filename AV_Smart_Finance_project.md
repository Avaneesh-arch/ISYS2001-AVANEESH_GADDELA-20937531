# 💰 Smart Budget Tracker Assistant – Project Planning Document

---

# 📖 Project Overview

The Smart Budget Tracker Assistant is a Python-based finance application designed to help users better understand and manage their personal spending habits.

The application allows users to upload transaction datasets, analyse spending behaviour, compare expenses against a monthly budget, and receive financial insights through an AI-powered assistant.

The project is being developed using:
- Python
- Google Colab
- Pandas
- Matplotlib
- Gradio

This project is designed for the ISYS2001 Final Programming Project and follows the six-step programming methodology taught throughout the unit.

---

# 🎯 Problem Definition

Many students and young adults struggle to manage personal finances effectively due to inconsistent expense tracking and poor visibility into spending patterns.

Small daily purchases can accumulate quickly, making it difficult for users to:
- Stay within budget
- Identify overspending habits
- Track financial goals
- Make informed financial decisions

This project aims to solve that problem by creating an interactive finance assistant that provides users with automated spending analysis and budgeting support.

---

# 👤 Intended Users

The application is primarily designed for:
- University students
- Young adults
- Beginner budget planners
- Users wanting a simple finance tracking tool

---

# 🎯 Project Goals

The main goals of the project are to:

- Help users track and analyse expenses
- Improve financial awareness
- Provide budgeting insights
- Create a simple and interactive finance assistant
- Demonstrate Python programming skills
- Demonstrate AI-assisted software development
- Apply the six-step programming methodology

---

# ⚙️ Planned Features

| Feature | Purpose | Priority |
|---|---|---|
| CSV Upload | Upload financial transactions | High |
| Spending Analysis | Analyse expenses and categories | High |
| Budget Tracking | Compare spending against budget | High |
| Savings Goal Calculator | Estimate savings targets | Medium |
| Finance Chatbot | Provide budgeting guidance | Medium |
| RAG Functionality | Retrieve answers from uploaded data | Medium |
| Gradio Interface | Interactive user interface | High |
| Data Visualisation | Charts and graphs | High |
| Testing Section | Validate functionality and edge cases | High |

---

# 📥 Inputs and Outputs

## Inputs

The application will accept:
- CSV transaction files
- Monthly budget values
- Savings goal targets
- User finance questions

Example CSV columns:
- Date
- Category
- Description
- Amount

---

## Outputs

The application will generate:
- Total spending summaries
- Category spending breakdowns
- Budget comparisons
- Savings calculations
- Financial charts and visualisations
- Chatbot responses
- Spending insights and recommendations

---

# 🧠 Six-Step Programming Methodology

## 1. Understand the Problem

Users often struggle to monitor daily spending and stay within a budget.

The application should help users:
- Upload expenses
- Analyse spending behaviour
- Track budgets
- Receive financial guidance

---

## 2. Identify Inputs and Outputs

### Inputs
- CSV transaction data
- Budget values
- Savings goals
- User prompts/questions

### Outputs
- Spending summaries
- Budget reports
- Savings estimates
- AI-generated financial advice
- Data visualisations

---

## 3. Work the Problem by Hand

### Example Transactions

| Category | Amount |
|---|---|
| Food | $45 |
| Transport | $15 |
| Entertainment | $30 |

### Manual Calculation

Total Spending:
45 + 15 + 30 = $90

Highest Spending Category:
Food

If Monthly Budget = $150:
Remaining Budget = $60

---

## 4. Write Pseudocode

```text
START

Load CSV file

IF CSV is invalid:
    Display error message

ELSE:
    Read transaction data
    Calculate total spending
    Group spending by category
    Generate spending charts

Ask user for monthly budget

IF spending exceeds budget:
    Display overspending warning

ELSE:
    Display remaining balance

Allow user to:
    - Ask chatbot questions
    - Use savings calculator
    - View spending insights

END
```

---

## 5. Convert to Python

The pseudocode will be converted into Python functions using:
- Pandas for data analysis
- Matplotlib for charts
- Gradio for interface design

Planned functions:
- CSV upload function
- Spending analysis function
- Budget calculator function
- Savings calculator function
- Chatbot response function

---

## 6. Test with a Variety of Data

Testing will include:
- Valid CSV files
- Empty CSV files
- Missing columns
- Invalid amount values
- Negative numbers
- Budget edge cases
- Chatbot response testing

The project notebook will include a dedicated Testing Section.

---

# 📊 Planned Data Visualisations

The application is planned to include:
- Pie charts for spending categories
- Bar charts for category comparisons
- Budget usage visualisations

---

# 🤖 AI Collaboration Plan

AI tools such as ChatGPT and GitHub Copilot may be used to:
- Debug code
- Improve logic
- Refine pseudocode
- Explain Python concepts
- Improve chatbot prompts
- Assist with testing strategies

All AI interactions will be documented in the Developer’s Diary.

---

# 🧪 Testing Strategy

The project will use:
- Function testing
- Input validation
- Error handling
- Edge case testing
- Debugging reflections

Testing will be performed continuously throughout development.

---

# 🚧 Development Timeline

## Phase 1
- Repository setup
- README development
- Project planning

## Phase 2
- CSV processing
- Spending analysis
- Budget calculations

## Phase 3
- Chatbot integration
- Savings tool
- RAG functionality

## Phase 4
- Gradio interface
- Testing and debugging
- Final polish and documentation

---

# ✅ Success Criteria

The project will be considered successful if:
- All required components function correctly
- The interface is user-friendly
- Users can analyse transaction data successfully
- Budget calculations work accurately
- Testing demonstrates reliability
- AI collaboration is documented clearly
- The repository is organised professionally
