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
                    <span class="problem">Problem : Fill the Boxes
                    </span>
                  </b>
                </p>
                <p class="western" align="JUSTIFY" style="line-height: 140%; margin-bottom: 0in;">
                  <b>Statement
                  </b>
                  <br>
                  <br>
                  There are N horizontally adjacent boxes on a sheet. Raju has to fill them(starting from the left) by using two colors: Red and Green. If he picks up Green color, he can fill one or more adjacent boxes while if he picks up red color, he can fill only one box and after that he has to place the color back.
                  <br>
                  <br>
                  It is pre-decided that which box will be filled with which color. You have to find the minimum no. of times Raju will have to place the picked up color back in order to match the given pattern. Raju can't re-arrange the position of the boxes.							
                  <br>
                  <br>
                </p>
                <p style="line-height: 140%;">
                  <b>Input Format:
                  </b>
                  <br>
                  <br>First line contains a Number and String delimited by whitespace where,
                </p>
                <ol>
                  <li>First Number is number of boxes
                  </li>
                  <li>Second String is the color pattern
                  </li>
                </ol>
                <br>
                <p>
                </p>
                <p style="line-height: 140%;">
                  <b>Output Format:
                  </b>
                  <br>
                  <br>
                  The minimum no. of times Raju will have to place the picked up color back in order to match the given pattern.
                  <br>
                  <br>
                </p>
                <p style="line-height: 140%;">
                  <b>Constraints:
                  </b>
                  <br>
                  <br>
                </p>
                <ol>
                  <li>If he picks up Green color, he can fill one or more adjacent boxes while if he picks up red color, he can fill only one box. 
                  </li>
                  <li>All the boxes will have to be filled sequentially.
                  </li>
                </ol>
                <br>
                <p>
                </p>
                <br> 
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
                          <br>5 RGGRR
                          <br>
                        </td>
                        <td style="width: 100px">
                          <br>3
                          <br>
                        </td>
                        <td style="width: 350px">
                          <br>First Raju picked Red color for filling and next color is Green so he placed red color back so count= 1
                          <br>
                          Raju picked Green color and filled next two boxes with Green and placed Green color back, now count =2
                          <br>
                          Again Raju picked Red color and filled the box and placed it back, now count=3
                          <br>
                          Again Raju picked Red color filled the box and as it is last box no need to place it back, so final count=3
                          <br>
                          <br>
                        </td>
                      </tr>
                      <tr>
                        <td style="width: 10px;">2
                        </td>
                        <td style="width: 100px;">
                          <br>5 RGGGG
                          <br>
                        </td>
                        <td style="width: 100px;">
                          <br>1
                          <br>
                        </td>
                        <td style="width: 350px">
                          <br>First Raju picked R color for filling and next color is G so he placed red color back so count= 1
                          <br>
                          Raju picked G color filled next 4 boxes with G color, so final count =1
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
