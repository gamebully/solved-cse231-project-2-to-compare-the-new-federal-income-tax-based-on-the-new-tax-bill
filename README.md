Download Link: https://assignmentchef.com/product/solved-cse231-project-2-to-compare-the-new-federal-income-tax-based-on-the-new-tax-bill
<br>
<strong> Project 02 </strong>

Assignment Overview

(learning objectives)

This assignment will give you more experience on the use of:

<ol>

 <li>integers (int)</li>

 <li>floats (float)</li>

 <li>conditionals</li>

 <li>iteration</li>

</ol>

The goal of this project isnew tax bill pa to compare the new federal income tax based on the ssed by the congress in December 2017 with the old federal income tax. You will ask the user to input their names and the taxable income. Use the income brackets given below to calculate the new and old income tax. For the sake of simplicity of the project we will only consider individuals and not married users. We will also ignore any tax deductions while calculating income tax—they can significantly alter the tax, but add too much complexity for our second programming project.




<table width="0">

 <tbody>

  <tr>

   <td width="183"><strong>Rate </strong></td>

   <td width="183"><strong>Income range </strong></td>

  </tr>

  <tr>

   <td width="183">10%</td>

   <td width="183">Up to $9,525</td>

  </tr>

  <tr>

   <td width="183">12%</td>

   <td width="183">$9,526 to $38,700</td>

  </tr>

  <tr>

   <td width="183">22%</td>

   <td width="183">38,701 to $82,500</td>

  </tr>

  <tr>

   <td width="183">24%</td>

   <td width="183">$82,501 to $157,500</td>

  </tr>

  <tr>

   <td width="183">32%</td>

   <td width="183">$157,501 to $200,000</td>

  </tr>

  <tr>

   <td width="183">35%</td>

   <td width="183">$200,001 to $500,000</td>

  </tr>

  <tr>

   <td width="183">37%</td>

   <td width="183">over $500,000</td>

  </tr>

 </tbody>

</table>

<strong>New income tax brackets (2018 and newer)  </strong>

<strong> </strong>




<table width="0">

 <tbody>

  <tr>

   <td width="183"><strong>Rate </strong></td>

   <td width="183"><strong>Income range </strong></td>

  </tr>

  <tr>

   <td width="183">10%</td>

   <td width="183">Up to $9,325</td>

  </tr>

  <tr>

   <td width="183">15%</td>

   <td width="183">$9,326 to $37,950</td>

  </tr>

  <tr>

   <td width="183">25%</td>

   <td width="183">$37,951 to $91,900</td>

  </tr>

  <tr>

   <td width="183">28%</td>

   <td width="183">$91,901 to $191,650</td>

  </tr>

  <tr>

   <td width="183">33%</td>

   <td width="183">$191,651 to $416,700</td>

  </tr>

  <tr>

   <td width="183">35%</td>

   <td width="183">$416,701 to $418,400</td>

  </tr>

  <tr>

   <td width="183">39.6%</td>

   <td width="183">over $418,401</td>

  </tr>

 </tbody>

</table>

<strong>Old income tax brackets (2017 and older)</strong>

Assignment Background

Being in the 25% tax bracket doesn’t mean you pay 25% on everything you make. The progressive tax system means that people with higher taxable incomes are subject to higher tax rates, and people with lower taxable incomes are subject to lower tax rates.

For example, let’s say you’re a filer with $32,000 in taxable income. That puts you in the 15% tax bracket in 2017. But do you pay 15% on all $32,000? No. Actually, you pay only 10% on the first $9,325; you pay 15% on the rest. (Look at the tax brackets above to see the breakout.)

If you had $50,000 of taxable income, you’d pay 10% on that first $9,325 and 15% on the chunk of income between $9,326 and $37,950. And then you’d pay 25% on the rest, because some of your $50,000 of taxable income falls into the 25% tax bracket. The total bill would be $8,238.75 — about 16% of your taxable income, even though you’re in the 25% bracket.

Project Description

Your program must meet the following specifications:

<ol>

 <li>At program start, prompt the user for their income</li>

 <li>Repeatedly prompt the user for new income until a negative income is entered.</li>

 <li>Calculate the income tax using the 2017 and 2018 tax bracket tables above.</li>

 <li>For each income entered:

  <ol>

   <li>Calculate the 2017 income tax and store it in a variable.</li>

   <li>Next calculate the 2018 income tax and store it in a variable c. Print

    <ol>

     <li>The income</li>

     <li>The 2017 tax iii. The 2018 tax</li>

     <li>The difference between the 2018 and 2017 tax rounded to cents.</li>

     <li>The difference between the 2018 and 2017 tax as a percentage of the 2017 tax rounded to cents</li>

    </ol></li>

  </ol></li>

</ol>

<h1>Assignment Deliverable</h1>

The deliverable for this assignment is the following file:

proj02.py – the source code for your Python program

Be sure to use the specified file name and to submit it for grading via the <strong>Mimir </strong>before the project deadline.

<h1>Assignment Notes</h1>




<ol>

 <li>To clarify the project specifications, sample output is appended to the end of this document.</li>

 <li>Items 1-6 of the Coding Standard will be enforced for this project.</li>

 <li>Use a while loop with a Boolean that keeps looping as long as the income is greater than or equal to zero. Prompt for income before the loop and remember to convert the input string to an int (so you are comparing an int in your Boolean expression).  Remember to prompt again at the end (aka “bottom”) of the loop.</li>

 <li>There will be no error checking in this assignment. If a float or a string is entered at the prompt, the program will crash.</li>

 <li>We provide a file “strings.txt” that has the strings used in our code so you can match the expected output in the Mimir tests.</li>

</ol>




<strong>Test Cases </strong>

<h1>Test 1</h1>

Enter income as an integer with no commas: 8000

Income: 8000

<ul>

 <li>tax: 800.0</li>

 <li>tax: 800.0</li>

</ul>

Difference: 0.0

Difference (percent): 0.0

Enter income as an integer with no commas: 15000

Income: 15000

<ul>

 <li>tax: 1783.75</li>

 <li>tax: 1609.5</li>

</ul>

Difference: -174.25

Difference (percent): 9.77




Enter income as an integer with no commas: 40000

Income: 40000

<ul>

 <li>tax: 5738.75</li>

 <li>tax: 4739.5</li>

</ul>

Difference: -999.25

Difference (percent): 17.41




Enter income as an integer with no commas: 100000

Income: 100000

<ul>

 <li>tax: 20981.75</li>

 <li>tax: 18289.5</li>

</ul>

Difference: -2692.25

Difference (percent): 12.83




Enter income as an integer with no commas: 200000

Income: 200000

<ul>

 <li>tax: 49399.25</li>

 <li>tax: 45689.5</li>

</ul>

Difference: -3709.75

Difference (percent): 7.51




Enter income as an integer with no commas: 500000

Income: 500000

<ul>

 <li>tax: 153818.85</li>

 <li>tax: 150689.5</li>

</ul>

Difference: -3129.35

Difference (percent): 2.03




Enter income as an integer with no commas: 1000000

Income: 1000000

<ul>

 <li>tax: 351818.85</li>

 <li>tax: 335689.5</li>

</ul>

Difference: -16129.35

Difference (percent): 4.58




Enter income as an integer with no commas: 10000000

Income: 10000000

<ul>

 <li>tax: 3915818.85</li>

 <li>tax: 3665689.5</li>

</ul>

Difference: -250129.35

Difference (percent): 6.39




Enter income as an integer with no commas: -1

<strong> </strong>

<strong>Test 2 </strong>

Enter income as an integer with no commas: -1

<strong> </strong>

<strong>Test 3 </strong>

This test is a blind test.  You do not get to see input or output.


