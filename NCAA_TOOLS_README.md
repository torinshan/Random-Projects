# NCAA D1 Total Compensation Tools - Usage Guide

## Overview

This repository contains a comprehensive suite of NCAA Division 1 salary comparison and analysis tools designed to help coaches, administrators, and professionals compare compensation packages across all 364 NCAA Division 1 schools.

## 🚀 Quick Start

Visit the live GitHub Pages site: **https://torinshan.github.io/Random-Projects/**

The main page features an iframe-based tool selector with a dropdown menu that allows you to seamlessly switch between different analysis tools.

## 📊 Available Tools

### 1. Side-by-Side Comparison Tool (`2_school_side_by_side_compare_total_value.html`)

**Purpose**: Advanced side-by-side comparison of two schools with comprehensive tax, benefits, and cost-of-living analysis.

**Key Features**:
- Compare two schools simultaneously with separate inputs
- All 364 NCAA Division 1 schools included
- Independent salary inputs for each school
- Comprehensive compensation breakdown including:
  - Federal, state, and local tax calculations
  - FICA (Social Security + Medicare) calculations
  - School-specific retirement contributions (employer & employee percentages)
  - Health insurance benefits (varies by institution and coverage type)
  - Social Security savings for eligible institutions
  - Benefits package value with vesting considerations
  - Take-home salary after all deductions
  - Cost of living adjusted values (most accurate real-value comparison)
- Interactive school search with filtering by name, city, state, or conference
- Retirement contribution customization
- Benefits election options (filing status, health coverage)
- Years of service tracking for vesting calculations
- Real-time comparison summary showing:
  - Best real value (COL adjusted)
  - Take-home pay differences
  - Benefits value differences
  - Tax burden comparison
  - Cost of living index comparison

**When to Use**:
- Comparing specific job offers between two schools
- Evaluating the real value of salaries in different locations
- Understanding how taxes and benefits impact net compensation
- Making informed career decisions based on total compensation

### 2. Single School Analysis (`NCAA_D1_Total_Compensation_V4B_Single_School.html`)

**Purpose**: Deep dive into total compensation at a single institution.

**Key Features**:
- Detailed analysis of one school at a time
- Comprehensive breakdown of all benefits components
- Retirement plan details and vesting information
- Full tax analysis (federal, state, local, FICA)
- Customizable benefit elections
- Cost of living adjusted calculations

**When to Use**:
- Evaluating a single offer in detail
- Understanding the full benefits package at a specific school
- Planning for retirement contributions
- Analyzing take-home pay scenarios

### 3. Tax & COL Comparison Tool (`2_School_Taxes_COL_Comparssion_Tool.html`)

**Purpose**: Focus on tax implications and cost of living differences between schools.

**Key Features**:
- Streamlined comparison focusing on taxes and COL
- Quick comparison between two locations
- Tax burden visualization
- Cost of living impact analysis

**When to Use**:
- Quick comparison of tax implications
- Understanding location-based cost differences
- Comparing net pay without detailed benefits analysis

### 4. Benefits & Total Compensation Dashboard (`2_School_Benefits_Total_Comp_Compare_Tool.html`)

**Purpose**: Comprehensive benefits comparison with visual dashboard.

**Key Features**:
- Full benefits package comparison
- Visual representation of compensation components
- Interactive dashboard interface
- Detailed benefits breakdown

**When to Use**:
- Visual comparison of benefits packages
- Presentation-ready analysis
- Comprehensive benefits evaluation

## 💡 How to Use the Tools

### Accessing the Tools

1. Visit the GitHub Pages site
2. Use the dropdown menu in the header to select your desired tool
3. The tool will load in the iframe below

### Using the Side-by-Side Comparison Tool

1. **Select Schools**:
   - Type in the search box to find schools by name, city, state, or conference
   - Click on a school from the dropdown to select it
   - Repeat for both School 1 and School 2

2. **Enter Salary Information**:
   - Input the annual salary offered at each school
   - Enter your expected years of service (affects vesting)
   - Select your filing status (Single, Married Filing Jointly, Head of Household)
   - Choose health coverage type (Self Only or Family)
   - Optionally override the retirement contribution percentage

3. **Review Results**:
   - Scroll down to see detailed breakdowns for each school
   - Compare compensation overview, retirement, health benefits, taxes, and real value
   - Check the comparison summary at the bottom for quick insights

4. **Key Metrics to Consider**:
   - **COL Adjusted Value**: The most accurate representation of real purchasing power
   - **Take-Home Pay**: Actual cash you receive after all deductions
   - **Total Compensation**: Salary plus all benefits
   - **Effective Tax Rate**: Your actual tax burden as a percentage
   - **Benefits Value**: The dollar value of employer-provided benefits

### Understanding the Data

#### School Information
- All 364 NCAA Division 1 schools are included
- Data includes actual retirement rates, health benefits, and cost of living indices
- Information is institution-specific and reflects real benefit structures

#### Tax Calculations
- **Federal Tax**: Based on 2024 tax brackets with standard deductions
- **State Tax**: State-specific tax rates and deductions
- **Local Tax**: City-specific taxes for applicable locations
- **FICA**: Social Security (6.2% up to wage base) and Medicare (1.45% + 0.9% additional on high earners)

#### Retirement Benefits
- **Employee Contribution**: Your required contribution percentage
- **Employer Contribution**: School's contribution percentage
- **Vesting**: Years required before employer contributions fully belong to you
- **SS Exempt**: Some schools are exempt from Social Security, saving you 6.2%

#### Health Insurance
- **Self Only**: Premium for individual coverage
- **Family**: Premium for family coverage
- **Employer Contribution**: Annual value the school pays toward your premiums
- **Your Cost**: What you pay annually for coverage

#### Cost of Living Index
- Index where 100 = national average
- Higher numbers = more expensive
- Lower numbers = more affordable
- COL Adjusted Value = (Take-Home / COL Index) × 100

## 📋 Data Sources

- **School Data**: Institutional benefit handbooks and HR documentation
- **Tax Rates**: IRS 2024 tax tables and state revenue departments
- **Cost of Living**: Regional price indices and housing data
- **Retirement Plans**: State pension systems and institutional 403(b)/401(a) plans
- **Health Insurance**: Institutional benefit summaries

## 🔧 Technical Details

### Implementation
- Self-contained HTML files with embedded CSS and JavaScript
- No external dependencies or API calls
- Client-side processing only (your data stays in your browser)
- Works offline after initial load

### Browser Compatibility
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Responsive design for mobile and tablet
- JavaScript required for functionality

### GitHub Pages Integration
- Iframe-based tool selector with dark theme
- LocalStorage for remembering last selected tool
- Seamless navigation between tools
- Loading indicators for smooth user experience

## 🎯 Use Cases

### Job Offer Comparison
Compare two offers to determine which provides better total value:
1. Select both schools
2. Enter offered salaries
3. Review COL adjusted value to see real purchasing power
4. Consider benefits differences and tax implications

### Career Planning
Understand long-term financial implications:
1. Analyze retirement benefits and vesting schedules
2. Calculate total compensation over time
3. Factor in cost of living for quality of life assessment

### Negotiation Support
Use data to inform salary negotiations:
1. Understand the full value of the benefits package
2. Calculate the salary equivalent of benefits
3. Compare to other institutions for market context

### Relocation Decisions
Evaluate the financial impact of moving:
1. Compare cost of living between locations
2. Understand state and local tax differences
3. Calculate net change in purchasing power

## 🔐 Privacy & Security

- All calculations are performed locally in your browser
- No data is transmitted to any server
- No personal information is collected or stored
- Safe to use with confidential salary information

## 📝 Notes & Limitations

- Data is as accurate as institutional sources allow
- Tax calculations use standard deductions; itemizing may yield different results
- Cost of living indices are regional approximations
- Benefits values may vary based on individual circumstances
- Retirement calculations assume standard vesting schedules
- Local tax rates may not cover all municipalities

## 🆘 Support

For issues, questions, or data corrections:
- Open an issue on the GitHub repository
- Provide specific school names and data points for corrections
- Include browser information for technical issues

## 📄 License

This project is provided as-is for informational purposes. Users should verify data with official institutional sources before making career decisions.

## 🔄 Updates

Data is periodically updated to reflect:
- Changes in tax laws
- Updated institutional benefit structures
- Cost of living adjustments
- New schools or conference realignments

---

**Last Updated**: December 2024

**School Count**: 364 NCAA Division 1 Institutions

**Version**: 4B - Advanced Side-by-Side Comparison
