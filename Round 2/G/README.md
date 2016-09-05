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
                    <span class="problem">Problem : Saving Private Ryan 
                    </span>
                  </b>
                </p>
                <p class="western" align="JUSTIFY" style="line-height:140%;margin-bottom: 0in;">
                  <b>Statement
                  </b>
                  <br>
                  <br>
                  It's the D-Day. Normandy has been invaded. German forces are all over, while American infantry is badly wounded. Captain John Miller with few other survivors is in search of a missing paratrooper, Private James Ryan.
                  <br>
                  <br>
                  Now Ryan is stranded at a remote location heavily surrounded by enemy troops, so he can't come out of the hiding. Both Miller and Ryan have a radio for communication. Now Ryan needs to communicate with Miller and tell him his co-ordinates so that he can get rescued. But the German's are listening to all radio frequencies, so the message needs to be encrypted, otherwise they will reach his co-ordinates first. But to encrypt the message they need a key, which unfortunately they haven't agreed upon beforehand.
                  <br>
                  <br>
                  Now they try to come up with a shared key over the radio which the enemy can't decipher. They try to use the following standard method to arrive at it:
                </p>
                <ol>
                  <li>Both Miller and Ryan agree on a prime number P and a base number N over the radio. The Germans are listening.
                  </li>
                  <li>Then Miller independently chooses a key X and computes A = N^X (mod P) and Ryan independently chooses a key Y and computes B = N^Y (mod P). Both X and Y are relatively prime to N.
                  </li>
                  <li>They share A and B with each other over the radio.
                  </li>
                  <li>Now Miller computes (B^X (mod P)) and Ryan computes (A^Y (mod P)) and eventually they turn out to be the same (mystery?). Thus they now have a shared key without the Germans knowing it. So now they can encrypt their messages.
                  </li>					
                </ol>
                <br>
                Now you, being a squad member of Miller, need to help Miller arrive at the final shared key and save Private Ryan.
                <br>
                <br>
                <p>
                </p>
                <p style="line-height:140%;">
                  <b>Input Format:
                  </b>
                  <br>
                  <br>
                  First line of input contains a file path where file contents are as follows:
                </p>
                <ol>
                  <li>The first line will contain a positive integer T determining the number of test cases.
                  </li>
                  <li>Next T lines will contain the three space separated integers B, X, P 
                    <br>
                    Where,
                    <ul>
                      <li>B is the response from Ryan
                      </li>
                      <li>X is Miller's private key and
                      </li>
                      <li>P is the prime number shared between Miller and Ryan.
                      </li>
                    </ul>
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
                  For each test case, output the following.
                  <br>
                  <br>
                  Print -1, if P is not a prime number 
                  <br>
                  Otherwise, compute the shared key value. For brevity, print it modulo 10
                  <br>
                  <br>
                  Each test case output should be printed on a separate line.
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
                </p>
                <ol>
                  <li>1&lt;=T&lt;=100,000
                  </li>
                  <li>
                    1&lt; B &lt; 10,000,000
                  </li>
                  <li>
                    1&lt; X &lt; 4,000,000,000
                  </li>
                  <li>
                    1&lt; P &lt; 10,000,000
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
                        <th style="height:20px">SNo.
                        </th>
                        <th style="height:20px">Input
                        </th>
                        <th style="height:20px">File content
                        </th>
                        <th style="height:20px">Output
                        </th>
                      </tr>
                      <tr>
                        <td style="width:7px;">1
                        </td>
                        <td style="width:200">file1.txt
                        </td>
                        <td style="width:200px;">
                          <br>
                          2
                          <br>19 4 337
                          <br>25 2 98
                          <br>
                          <br>
                        </td>
                        <td style="width:200px">
                          <br>
                          9
                          <br>-1
                          <br>
                        </td>							
                      </tr>
                      <tr>
                        <td style="width:7px;">2
                        </td>
                        <td style="width:200px;">file2.txt
                          <br>
                        </td>
                        <td style="width:200px;">
                          <br>1
                          <br>19 4 3
                          <br>
                        </td>
                        <td style="width:200px">
                          <br>1
                          <br>
                        </td>							
                      </tr>
                    </tbody>
                  </table>
                  <br>
                  <br>
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
