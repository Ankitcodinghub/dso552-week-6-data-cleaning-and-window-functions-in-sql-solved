# dso552-week-6-data-cleaning-and-window-functions-in-sql-solved
**TO GET THIS SOLUTION VISIT:** [DSO552 Week 6-Data Cleaning and Window Functions in SQL Solved](https://www.ankitcodinghub.com/product/dso552-week-6-data-cleaning-and-window-functions-in-sql-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96341&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;DSO552 Week 6-Data Cleaning and Window Functions in SQL Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Week 6: Data Cleaning and Window Functions in SQL

Parch and Posey Database

<ol>
<li>In the accounts table, there is a column holding the website for each company. The last three digits specify what type of web address they are using. Pull these extensions and provide how many of each website type exist in the accounts table.</li>
<li>There is much debate about how much the name (or even the first letter of a company name) matters. Use the accounts table to pull the first letter of each company name to see the distribution of company names that begin with each letter (or number).</li>
<li>What is the number of company names that start with a vowel and consonant letters?</li>
</ol>
POSITION

4. Use the accounts table to create first and last name columns that hold the first and last names for the primary_poc.

CONCAT

<ol start="5">
<li>Each company in the accounts table wants to create an email address for each primary_poc. The email address should be the first name of the primary_poc last name primary_poc @ company name .com. (e.g. tamara.tuma@walmart.com)</li>
<li>You may have noticed that in the previous solution some of the company names include spaces, which will certainly not work in an email address. See if you can create an email address that will work by removing all of the spaces in the account name, but otherwise your solution should be just as in the previous question.</li>
<li>We would also like to create an initial password, which they will change after their first log in. The password will be a combination of:</li>
</ol>
<ul>
<li>the first letter of the primary_poc’s first name (lowercase),</li>
<li>the last letter of their first name (lowercase),</li>
<li>the first letter of their last name (uppercase),</li>
<li>the last letter of their last name (uppercase),</li>
<li>the number of letters in their first name,</li>
<li>the number of letters in their last name, and</li>
<li>the name of the company they are working with, no spaces</li>
<li>the forth and fifth digit of their sales rep id</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Window Functions

<ol start="8">
<li>For the orders table, create a new column which shows the total number of transactions for all accounts.</li>
<li>Update the previous query to create two new column: (1) over_all_total_by_account_id, and (2) overall_count_by_account_id (without using Group By).</li>
<li>Create a running total of standard_amt_usd (in the orders table) over order time.</li>
<li>Create a running total of standard_amt_usd (in the orders table) over order time for each month.</li>
<li>YOUR TURN – Create a running total of standard_qty (in the orders table) over order time for each year.</li>
</ol>
Ranking data: RAW_NUMBER() and RANK(), DENSE_RANK()

<ol start="13">
<li>For account with id 1001, use the row_number(), rank() and dense_rank() to rank the transactions by the number of standard paper purchased.</li>
<li>For each account, use the row_number(), rank() and dense_rank() to rank the transactions by the number of standard paper purchased.</li>
<li>Your Turn Select the id, account_id, and standard_qty variable from the orders table, then create a column called dense_rank that ranks this standard_qty amount of paper for each account. In addition, create a sum_std_qty which gives you the running total for account. Repeat the last task to get the avg, min, and max.</li>
<li>Give an allias for the window function in the previous question, and call it account_window.</li>
</ol>
NTILES

<ol start="17">
<li>Use the NTILE functionality to divide the accounts into 4 levels in terms of the amount of standard_qty for their orders. Your resulting table should have the account_id, the occurred_at time for each order, the total amount of standard_qty paper purchased, and one of four levels in a standard_quartile column.</li>
<li>YOUR TURN Use the NTILE functionality to divide the accounts into two levels in terms of the amount of gloss_qty for their orders. Your resulting table should have the account_id, the occurred_at time for each order, the total amount of gloss_qty paper purchased, and one of two levels in a gloss_half column.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
