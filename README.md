# Password-Security-Analysis-Project

## Project Overview
This project demonstrates practical password security analysis using CUPP (Common User   Password Profiler) and Bitwarden to understand password vulnerabilities and strength assessment in real-world scenarios.

## Objective
Generate targeted password lists using personal profiling with CUPP

Evaluate password strength using Bitwarden's strength assessment

Understand common password vulnerabilities and best practices

Demonstrate practical security testing methodology

## Tools Used
1. CUPP (Common User Password Profiler)
  Purpose: Generate targeted wordlists based on personal information
  
  Usage: Interactive mode (cupp -i)
  
  Output: Personalized password lists for security testing

2. Bitwarden Password Strength Assessment
  Purpose: Evaluate password strength in real-world conditions
  
  Method: Testing CUPP-generated passwords against Bitwarden's strength meter
  
  Focus: Understanding commercial password manager evaluation criteria

## Methodology
**Phase 1: Password Generation with CUPP**
bash
# Interactive profiling
      cupp -i

# Input parameters used:
 - Name: Test profiles (non-sensitive data)
 - Birth years: Random test data
 - Keywords: Common password patterns
 - Special characters: Enabled for complexity
   
**Phase 2: Strength Assessment with Bitwarden**
  Tool: Bitwarden Password Strength Meter
  
  Method: Manual testing of CUPP-generated passwords
  
  Evaluation: Strength ratings and pattern analysis
  
  Safety: Used test passwords only, no real credentials

**Phase 3: Analysis & Reporting**
  Pattern identification in weak passwords
  
  Strength correlation analysis
  
  Security recommendations
  
  Best practices documentation

