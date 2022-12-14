> Last updated: 11/04/22

# Request: "NYC FEC Numbers" (or, "Public FEC Numbers")

<br>

## Data requested

- **Total number of FEC clients**
>

- **Total number of sessions**
>

- **Total debt decreased**
> - This is calculated as the sum, among only the clients who increased their savings balances, of the total decrease in debt (i.e., amount in dollars) for every client, where the increase is the difference between a client's most recent and earliest recorded savings balances in FEMS.
> - Through this method, the outcome reflects the net change in debt for a client across their entire time being served by NYC FEC.

- **Total savings increased**
> - This is calculated as the sum, among only the clients who increased their savings balances, of the total increase in savings (i.e., amount in dollars) for every client, where the increase is the difference between a client's most recent and earliest recorded savings balances in FEMS.
> - Through this method, the outcome reflects the net change in savings for a client across their entire time being served by NYC FEC.

<br>

## The analysis (replication)

**Total number of FEC clients**, and   
**Total number of sessions**
  - *Final estimates* from **COGNOS** report--`data01 > Sessions report (New)`
  - <ins>same</ins> report  
  - no additional analysis required (i.e., copy + paste)

<br>  

<ins>Steps</ins>  
`Sessions report (New)`  
- `Program`:
- `Provider`:
- `Date (of Interaction)`:
- `Length`: 
- `Enrollment date`:  

<hr>

**Total debt decreased**
  - *Data* from **COGNOS** report--`data01 > All Programs Cumulative Debt Reduction Report - 2020 Corrected`
  - Extract as Excel

> *Analysis*   
  - Download data as Excel file from COGNOS  
  - Open Excel file  
  - Apply function    
    - function: retains those...; excludes those making

<br>

<ins>Steps</ins>  
`All Programs Cumulative Debt Reduction Report - 2020 Corrected`    
- `Date (of Interaction)`   

<hr>

**Total savings increased**
  - *Data* from **COGNOS** report--`data01 > All Programs Cumulative Savings Increased Report - 2020 Corrected`
  - Extract as Excel

> *Analysis*  
  - Download data as Excel file from COGNOS
  - Open Excel file
  - Apply function
    - function: retains those...; excludes those making

<hr>

<ins>Steps</ins>  
`All Programs Cumulative Savings Increased Report - 2020 Corrected`    
- `Date (of Interaction)`    


<br>

## Cognos

> [link](http://mspwvw-dcacbi01.dca.nycnet/cognos11x/bi/)


