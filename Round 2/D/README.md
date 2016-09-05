<html>
  <body>
    <table>
      <tbody>
        <tr>
          <td width="auto" valign="top">
            <div class="border">
              <div class="Section1">	
                <p class="MsoNormal" align="center" style="text-align:left">
                  <b style="mso-bidi-font-weight:
                            normal">
                    <span class="problem">Problem : Matrix Match
                    </span>
                  </b>
                </p>
                <p class="western" align="JUSTIFY" style="line-height:140%;margin-bottom: 0in;">
                  <b>Statement
                  </b>
                  <br>
                  <br>
                  An m x n matrix will be given that contains only values 0 and 1. There is a pattern of 0s and 1s that you have to find and report the number of occurrences of that pattern in the matrix. 
                  <br>
                  <br>	
                </p>
                <p style="line-height:140%;">
                  <b>Input Format:
                  </b>
                  <br>
                  <br>
                </p>
                <ol>
                  <li>First line contains an integer 
                    <b>m
                    </b> that denotes number of rows of in the matrix.
                  </li>
                  <li>
                    Second line contains an integer 
                    <b>n
                    </b> that denotes the number of columns in the matrix.
                  </li>
                  <li>
                    Next, there will be m lines, each with n columns. Columns will be delimited by whitespace character.
                  </li>
                  <li>
                    Last line will consist of the string pattern which you have to search in the matrix.
                  </li>
                </ol>
                <br>
                <p>
                </p>
                <p style="line-height:140%;">
                  <b>Output Format:
                  </b>
                  <br>
                  <br>
                  Print the number of occurrences of the pattern found in the matrix.
                  <br>
                  <br>
                </p>
                <p class="western" align="JUSTIFY" style="line-height:140%;margin-bottom: 0in;">
                  <font face="Verdana, sans-serif">
                    <b>Constraints:
                    </b>
                  </font>
                  <br>
                  <br>
                  <br>The pattern has to be searched in the matrix in the following directions:
                </p>
                <ol>
                  <li>Horizontally, left to right
                  </li>
                  <li>Vertically, top to bottom
                  </li>
                  <li>Diagonally, top left to right bottom
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
                  <table width="700px" border="1" cellspacing="0" cellpadding="2">
                    <tbody>
                      <tr>
                        <th style="height:20px">SNo.
                        </th>
                        <th style="height:20px">Input
                        </th>
                        <th style="height:20px">Output
                        </th>
                        <th style="height:20px">Explaination
                        </th>
                      </tr>
                      <tr>
                        <td style="width:10px;">1
                        </td>
                        <td style="width:150px;">
                          <br>5
                          <br>
                          5
                          <br>
                          1 0 0 1 0
                          <br>
                          1 0 1 1 1
                          <br>
                          1 1 1 1 1
                          <br>
                          0 1 0 1 0
                          <br>
                          0 0 0 0 1
                          <br>
                          000
                          <br>
                          <br>
                        </td>
                        <td style="width:100px;">
                          <br>2
                          <br>
                          <br>
                        </td>
                        <td style="width:350px">
                          <br>
                          <ol>
                            <li>The pattern '000' is present 
                              <b>twice
                              </b> horizontally in row 5
                            </li>
                            <li>
                              The pattern '000' is not present  vertically in the matrix
                            </li>
                            <li>
                              The pattern '000' is not present  diagonally in the matrix
                            </li>
                          </ol>
                          <br>
                        </td>							
                      </tr>
                      <tr>
                        <td style="width:10px;">2
                        </td>
                        <td style="width:150px;">
                          <br>5
                          <br>
                          5
                          <br>
                          1 0 0 1 0
                          <br>
                          1 0 1 1 1
                          <br>
                          1 1 1 1 1
                          <br>
                          0 1 0 1 0
                          <br>
                          0 0 0 0 1
                          <br>
                          1111
                          <br>
                          <br>
                          <br>
                        </td>
                        <td style="width:100px;">
                          <br>3
                          <br>
                        </td>
                        <td style="width:350px">
                          <br>
                          <ol>
                            <li>The pattern '1111' is present 
                              <b>twice
                              </b> horizontally in row 3
                            </li>
                            <li>
                              The pattern '1111' is present  vertically in the column 4
                            </li>
                            <li>
                              The pattern '1111' is not present  diagonally in the matrix
                            </li>
                          </ol>
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
