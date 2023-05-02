Download Link: https://assignmentchef.com/product/solved-comp2710-homework-2-paying-off-the-loan-of-a-stereo-system
<br>
<strong><em><u>Description:</u></em></strong>

You have just purchased a stereo system that cost $1000 on the following credit plan: no down payment, an interest rate of 18% per year (and hence 1.5% per month), and monthly payments of $50. The monthly payment of $50 is used to pay the interest, and whatever is left is used to pay part of the remaining debt. Hence, the first month you pay 1.5% of $1000 in interest. That is $15 in interest. The remaining $35 is deducted from your debt, which leaves you with a debt of $965.00. The next month you pay interest of 1.5% of $965.00, which is $14.48. Hence, you can deduct $35.52 (which is $50–$14.48) from the amount you owe.




Write a program that will tell you how many months it will take you to pay off this loan in particular and any loan in general. Your program also needs to calculate the total amount of interest paid over the life of any loan. Use a loop to calculate the amount of interest and the size of the debt after each month. Your program must output the monthly amount of interest paid and remaining debt. Use a variable to count the number of loop iterations and hence the number of months until the debt is zero. You may want to use other variables as well. The last payment may be less than $50 if the debt is small, but do not forget the interest. If you owe $50, then your monthly payment of $50 will not pay off your debt, although it will come close. One month’s interest on $50 is only 75 cents.

Here is a sample dialog (where the user input is depicted as <strong>Bold</strong>, but you do not need to display user input in bold.):




<sup> </sup> Loan Amount: <strong>1000</strong>

Interest Rate (% per year): <strong>18</strong>

Monthly Payments: <strong>50 </strong>




<sub> </sub>













<table width="576">

 <tbody>

  <tr>

   <td width="576"><strong> </strong>******************************************************       Amortization Table<strong><sup> </sup></strong>******************************************************<strong> </strong>Month Balance Payment Rate Interest Principal<strong> </strong>0         $1000.00 N/A N/A      N/A     N/A<strong> </strong>21  $929.48 $50.00 $965.00 $50.00 1.51.5        $14.48 $15.00 $35.53 $35.00<strong> </strong>3     $893.42 $50.00 1.5      $13.94 $36.06 <strong> </strong>4 $856.82 $50.00 1.5      $13.40 $36.605        $819.67 $50.006        $781.97 $50.00 1.51.5  $12.30 $12.85 $37.70 $37.157        $743.70 $50.00 1.5      $11.73 $38.27 <strong> </strong>8   $704.85 $50.00 1.5       $11.16 $38.84 <strong> </strong>9   $665.42 $50.00 1.5      $10.57 $39.43<strong><sub> </sub></strong>1110  $584.79 $50.00 $625.40 $50.00 1.51.5      $9.38 $9.98 $40.62 $40.02<strong> </strong>12    $543.56 $50.00 1.5      $8.77 $41.23 <strong> </strong>13 $501.71 $50.00 1.5      $8.15 $41.85 <strong> </strong>1514  $416.13 $50.00 $459.24 $50.00 1.51.5      $6.89 $7.53 $43.11 $42.47<strong><sup> </sup></strong>16    $372.37 $50.00 1.5      $6.24 $43.76 <strong> </strong>17 $327.95 $50.00 1.5      $5.59 $44.41<strong>18           </strong>$282.87 $50.00 1.5      $4.92 $45.08<strong>19           </strong>$237.11 $50.00 1.5      $4.24 $45.76 <strong><sup> </sup></strong>20   $190.67 $50.00 1.5 $3.56 $46.44 <strong> </strong>21   $143.53 $50.00 1.5      $2.86 $47.14<strong>22           </strong>$95.68 $50.00 1.5       $2.15 $47.85<strong>23           </strong>$47.12 $50.00 1.5       $1.44 $48.56 <strong><sup> </sup></strong>24   $0.00 $47.83 1.5 $0.71 $47.12<strong> </strong>******************************************************<strong> </strong><strong><sub> </sub></strong>It takes Total interest paid is: <strong>24</strong> months to pay off the loan.  <strong>$197.83 </strong><strong> </strong></td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<strong>Your program’s output should match the style of the sample output. </strong>







In what follows, you find a second case used to test the correctness of your program.







<sup> </sup><sup> </sup>Loan Amount: <strong>2000</strong>

Interest Rate (% per year): <strong>12</strong>

Monthly Payments: <strong>80 </strong><sub> </sub>****************************************************** <sub>      </sub>Amortization Table

<strong><em> </em></strong>******************************************************




<strong><em><sup> </sup></em></strong>0Month  $2,000.00 Balance     N/A Payment Rate N/A     N/A Interest Principal N/A

<strong><em><sup> </sup></em></strong>21  <sub>         </sub> $1,879.40 $1,940.00     $80.00 $80.00 11  <sub>     </sub>      $19.40 $20.00 $60.60 $60.00

<ul>

 <li>$1,818.19 $80.00 1    $18.79 $61.21</li>

 <li>$1,756.38 $80.00 1    $18.18 $61.82</li>

 <li>$1,693.94 $80.00 1    $17.56 $62.44</li>

 <li>$1,630.88 $80.00 1    $16.94 $63.06</li>

 <li>$1,567.19 $80.00 1    $16.31 $63.69</li>

 <li>$1,502.86 $80.00 1    $15.67 $64.33 <strong><em> </em></strong>9   $1,437.89   $80.00 1    $15.03 $64.97</li>

</ul>

<strong><em><sup> </sup></em></strong>1110  $1,305.99 $1,372.27 $80.00 $80.00 11  $13.72 $14.38 $66.28 $65.62

<strong><em><sup> </sup></em></strong>1312 <sub>        </sub> $1,171.44 $1,239.05     $80.00 $80.00 11  <sub>     </sub>      $12.39 $13.06 $67.61 $66.94




<ul>

 <li>$1,103.15 $80.00 1    $11.71 $68.29</li>

 <li>$1,034.19 $80.00 1    $11.03 $68.97 <strong><em> </em></strong>16 $964.53     $80.00 1    $10.34 $69.66 17      $894.17     $80.00 1    $9.65 $70.35 <strong><em><sup> </sup></em></strong>18   $823.12     $80.00 1    $8.94 $71.06</li>

</ul>

<strong><em><sup> </sup></em></strong>2019        $678.86  $751.35          $80.00 $80.00 11             $7.51 $8.23 $72.49 $71.77

<strong><em> </em></strong>2221  <sub>      </sub> $531.70  $605.65  <sub>   </sub>     $80.00 $80.00 11  <sub>     </sub>      $6.06 $6.79 $73.94 $73.21

<ul>

 <li>$457.02    $80.00 1    $5.32 $74.68</li>

 <li>$381.59    $80.00 1    $4.57 $75.43</li>

 <li>$305.41    $80.00 1    $3.82 $76.18</li>

 <li>$228.46    $80.00 1    $3.05 $76.95</li>

 <li>$150.75    $80.00 1    $2.28 $77.72 28   $72.25      $80.00 1    $1.51 $78.49 <strong><em><sup> </sup></em></strong>29    $0.00       $72.98 1    $0.72 $72.25</li>

</ul>




<strong><em> </em></strong>******************************************************

<strong><em> </em></strong>Total interest paid is: It takes <strong>29</strong> months to pay off the loan.  <strong>$312.98 </strong>

<strong><em> </em></strong>

<strong><em><u>Special Cases:</u></em></strong>

<ol>

 <li>Please think about how to deal with the last payment, which is smaller than regular payment. For example, in the above table, the regular payments are $80.00 whereas the last payment is only 72.98.</li>

 <li>Your program needs to ensure that regular payments are larger than any monthly interest. For example, in the above amortization table, your program must test if the regular monthly payment (i.e., $80.00) is larger than the monthly interest (e.g., $20.00 in the first month).</li>

 <li>If you do not address the above issue, your program may not terminate in some special cases. See the example below:</li>

</ol>

<strong><em> </em></strong>

<strong><em> </em></strong>Loan Amount: Interest Rate (% per year): <strong>2000</strong>   <strong>49.2</strong>

<strong><em> </em></strong>Monthly Payments: <strong>80 </strong>




<strong><em> </em></strong>******************************************************    Amortization Table

<strong><em> </em></strong>******************************************************

<strong><em><sup> </sup></em></strong>0Month  $2,000.00 Balance       N/A Payment Rate N/A N/A Interest Principal

<strong><em> </em></strong>21  $2,004.08 $2,002.00 <sub>      </sub> $80.00 $80.00 4.14.1        $82.08 $82.00 –$2.08 $2.00

<ul>

 <li>$2,006.25 $80.00 4.1 $82.17 -$2.17</li>

 <li>$2,008.51 $80.00 4.1 $82.26 -$2.26</li>

 <li>$2,010.85 $80.00 4.1 $82.35 -$2.35</li>

 <li>$2,013.30 $80.00 4.1 $82.45 -$2.45</li>

 <li>$2,015.84 $80.00 4.1 $82.55 -$2.55</li>

 <li>$2,018.49 $80.00 4.1 $82.65 -$2.65 <strong><em><sup> </sup></em></strong>9   $2,021.25   $80.00 4.1   $82.76 -$2.76</li>

</ul>

<strong><em><sup> </sup></em></strong>1110  $2,027.11 $2,024.12      $80.00 $80.00 4.14.1        $82.99 $82.87 –$2.99 $2.87

<strong><em><sup> </sup></em></strong>1312  $2,033.46 $2,030.22 <sub>     </sub> $80.00 $80.00 4.14.1        $83.24 $83.11 –$3.24 $3.11

<ul>

 <li>$2,036.84 $80.00 4.1 $83.37 -$3.37</li>

 <li>$2,040.35 $80.00 4.1 $83.51 -$3.51</li>

 <li>$2,044.00 $80.00 4.1 $83.65 -$3.65</li>

 <li>$2,047.80 $80.00 4.1 $83.80 -$3.80</li>

 <li>$2,051.76 $80.00 4.1 $83.96 -$3.96</li>

 <li>$2,055.89 $80.00 4.1 $84.12 -$4.12</li>

</ul>

<strong><em> </em></strong>…   … <sub>        </sub> <sub>       </sub>… <sub>    </sub> <sub>       </sub>… <sub>    </sub>… <sub>    </sub>

<strong> </strong>

<strong><em><sub> </sub></em></strong>

<strong><em> </em></strong>

<strong><em> </em></strong>

<strong><em><u>Programming Environment:</u></em></strong>

Write a short program in C++.




<strong><em><u>Requirements:</u></em></strong>

<ol>

 <li><strong>Use comments to provide a heading at the top of your code</strong> containing your name, Auburn Userid, filename. And pair partner’s info, if applicable. Also describe any help or sources that you used (as per the syllabus).</li>

</ol>

<strong>// name: Sally Ride, szr0001 </strong>

<strong>// partner: Lizz Jones, lzj0001                   </strong><strong>(“NONE” if work alone)</strong>

<strong>// filename: hw01.cpp</strong>

<h1>// due date: 08/31/2018 // problem: determine how much diet soda it is possible to drink  //    without dying as a result</h1>

<strong>// collaboration: I got help with data types from the TA.</strong>

<strong>    </strong><strong>(OR “I did not use any external sources for this assignment.”)</strong>




<ol start="2">

 <li> Your source code file should be named as “hw2.cpp”. 3. (10 points) No compilation error and no warning messages</li>

</ol>

<ol start="4">

 <li>Use modifier const for the fraction.</li>

 <li>Usability of your program (e.g., input and output)</li>

 <li>Quality of your source code.</li>

</ol>




You will <strong>lose points</strong> if you: do not use the specific program file name, or do not have a comment block on <strong>EVERY</strong> program you hand in. You will lose <strong>at least 40 points</strong> if there are compilation errors or warning messages when we compile your source code.




<ul>

 <li></li>

</ul>


