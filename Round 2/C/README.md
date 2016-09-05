<html>
  <body>
    <table>
      <tbody>
        <tr>
          <td width="auto" valign="top">
            <div class="border">
              <div class="Section1">
                <p class="MsoNormal" align="center" style="text-align: left">
                  <b style="mso-bidi-font-weight: normal">
                    <span class="problem">Problem : Land Buy
                    </span>
                  </b>
                </p>
                <p class="western" align="JUSTIFY" style="line-height: 140%; margin-bottom: 0in;">
                  <b>Statement
                  </b>
                  <br>
                  <br>
                  Land is divided into plots. All plots are for sale. Some plot numbers are palindromes. Our goal is to buy maximum number of palindrome plots at minimum cost. The cost in this case is measured in terms of distance between plots. Lesser the distance between plots we buy, lower the cost and vice-versa.
                  <br>
                  <br>
                  Write a program to purchase plots as per given conditions
                  <br> 
                  <br>
                </p>
                <p style="line-height: 140%;">
                  <b>Input Format:
                  </b> 
                  <br>
                  <br>
                  First line contains 3 numbers delimited by comma where,
                </p>
                <ol>
                  <li>First number is plot number of the leftmost plot
                  </li>
                  <li>Second number plot number of the rightmost plot
                  </li>
                  <li>Third number is maximum distance between plots we can buy
                  </li>
                </ol>
                <br>
                <p>
                </p>
                <p style="line-height: 140%;">
                  <b>Output Format:
                  </b> 
                  <br>
                  <br>Print the output in below format
                  <br>
                  <br>
                  Number of palindrome plots, start index of palindrome plot, end index of palindrome plot
                  <br>OR
                  <br>Print 0,0,0 if no purchase possible
                  <br>
                  <br>
                </p>
                <p style="line-height: 140%;">
                  <b>Constraints:
                  </b>
                  <br>
                  <br>
                  We have 4 conditions for buying:
                </p>
                <ol>
                  <li>If there are no palindrome number plots then no purchase should be made
                  </li>
                  <li>We need to minimize the cost
                  </li>
                  <li>Search for buying plots should start at the smallest plot number
                  </li>
                  <li>Permissible distance between two plots to be bought cannot exceed difference between left and right most plot numbers mentioned in input
                  </li>
                </ol>
                <br>
                <p>
                </p>
                <a>
                  <b>Sample Input and Output
                  </b>
                </a>
                <a>
                  <br> 
                  <br>
                  <table width="650px" border="1" cellspacing="0" cellpadding="2">
                    <tbody>
                      <tr>
                        <th style="height: 20px">SNo.
                        </th>
                        <th style="height: 20px">Input
                        </th>
                        <th style="height: 20px">Output
                        </th>
                        <th style="height: 20px">Explaination
                        </th>
                      </tr>
                      <tr>
                        <td style="width: 10px;">
                          <br>1
                          <br>
                        </td>
                        <td style="width: 100px;">
                          <br>80,120,12
                          <br>
                        </td>
                        <td style="width: 100px">
                          <br>2,99,101
                          <br>
                        </td>
                        <td style="width: 350px">
                          <br>Possible palindrome plots that satisfy constraints are
                          <br>&lt;88,99&gt;, &lt;99, 101&gt;, &lt;101, 111&gt;
                          <br>In all cases we are able to buy only two palindrome plots. However, the range 99 to 101 is the cheapest. 
                          <br>
                          Hence our answer is 2,99,101
                          <br>
                          <br>
                        </td>
                      </tr>
                      <tr>
                        <td style="width: 10px;">
                          <br>2
                          <br>
                        </td>
                        <td style="width: 100px;">
                          <br>12,20,1
                          <br>
                        </td>
                        <td style="width: 100px">
                          <br>0,0,0
                          <br>
                        </td>
                        <td style="width: 350px">
                          <br>Between 12 and 20 we do not have any palindromes for length of 1.
                          <br>
                          <br>
                        </td>
                      </tr>
                    </tbody>
                  </table> 
                  <br> 
                  <br>
                </a>
              </div>
              <a>
                <div class="note">
                  <p class="western" style="margin-top: 0.07in; margin-bottom: 0in; widows: 2; orphans: 2">
                    <font color="#950000">
                      <i>
                        <b>Note
                        </b>
                      </i>
                    </font>:
                    <br> 
                    <br>
                    <i> Please do not use package and namespace in your code.
                      For object oriented languages your code should be written in
                      one class.
                    </i>
                  </p>
                  <p class="western" style="margin-top: 0.07in; margin-bottom: 0in; widows: 2; orphans: 2">
                    <font color="#950000">
                      <i>
                        <b>Note
                        </b>
                      </i>
                    </font>:
                    <br> 
                    <br>
                    <i>Participants submitting solutions in C language should
                      not use functions from &lt;conio.h&gt; / &lt;process.h&gt; as
                      these files do not exist in gcc
                    </i>
                  </p>
                  <p class="western" style="margin-top: 0.07in; margin-bottom: 0in; widows: 2; orphans: 2">
                    <font color="#950000">
                      <i>
                        <b>Note
                        </b>
                      </i>
                    </font>:
                    <br> 
                    <br>
                    <i>For C and C++, return type of main() function should be
                      int.
                    </i>
                  </p>
                  <br> 
                  <br>
                  <p class="western" align="JUSTIFY" style="margin-bottom: 0in">
                    <br>
                  </p>
                </div>
              </a>
            </div></td>
        </tr>
      </tbody>
    </table>
  </body>
</html>
