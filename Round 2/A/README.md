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
                    <span class="problem">Problem : Securing Financial Transactions
                    </span>
                  </b>
                </p>
                <p class="western" align="JUSTIFY" style="line-height:140%;margin-bottom: 0in;">
                  <b>Statement
                  </b>
                  <br>
                  <br>
                  ABC Corporation's finance team wants to deal with each of their supplier's invoicing details in a more secured way. Between ABC's and their suppliers' finance systems, ABC wants to build its own encryption/decryption logic.
                  <br>
                  <br>
                  ABC has a unique identifier for each of their supplier and wants to use that as part of the sensitive data that the finance systems exchange
                  <br>
                  <br>
                  You are working as part of the ABC's IT team and are tasked with implementing the functionality based on logic explained below.
                  <br>
                  <br>
                  <b>Encryption Logic:
                  </b>
                  <br>
                  <br>
                  Encryption comprises of 3 actions in sequence
                </p>
                <ol>
                  <li>Get the supplier's id and find its length and append it with Supplier id
                  </li>
                  <li>Perform the below transformations, 
                    <ol type="a">
                      <li>calculate the Hex code of every character in ASCII format, of the data to be exchanged
                      </li>
                      <li>reverse it and 
                      </li>
                      <li>append it to the String constructed in Step 1
                      </li>
                    </ol>
                  </li>
                  <li>Note that every append operation adds the '-' character
                  </li>
                </ol>
                Let's see an example
                <br>
                <br>
                Let data to be exchanged be: 
                <i>Good Morning
                </i>
                <br>
                <p>
                  <b>Step1
                  </b>
                  <br>
                </p>
                <ul>
                  <li>Supplier's Unique Identifier : 33 (provided in input)
                  </li>
                  <li>Length of the Supplier's Unique Identified : 2 (to be computed)
                  </li>
                </ul>
                <p>
                </p>
                <p>
                  <b>Step2
                  </b>
                  <br>
                </p>
                <ul>
                  <li>Calculate Corresponding Hex Code of characters in ASCII format
                    <br>
                    <b>G
                    </b>: 47, 
                    <b>o
                    </b>: 6F, 
                    <b>o
                    </b>: 6F, 
                    <b>d
                    </b>: 64, 
                    <b>SPACE
                    </b>: 20, 
                    <b>M
                    </b>: 4D, 
                    <b>o
                    </b>: 6F, 
                    <b>r
                    </b>: 72, 
                    <b>n
                    </b>: 6E, 
                    <b>i
                    </b>: 69, 
                    <b>n
                    </b>: 6E, 
                    <b>g
                    </b>: 67
                  </li>
                </ul>
                <p>
                </p>
                <p>
                  <b>Step3
                  </b>
                  <br>
                </p>
                <ul>
                  <li>Final Encrypted String: 2-33-74-F6-F6-46-02-D4-F6-27-E6-96-E6-76
                  </li>
                </ul>
                <p>
                </p>
                <br>
                <p>
                  <b>Decryption Logic: 
                  </b>
                  <br>
                  <br>
                  From encryption logic, it is easy to see how supplier id can be extracted from the encrypted string. Rest is reversing the steps done during encryption.  See example output to get a better understanding of Decryption Logic.
                  <br>
                  <br>
                </p>
                <p>
                </p>
                <p style="line-height:140%;">
                  <b>Input Format:
                  </b>
                  <br>
                  <br>
                </p>
                <p>First Line should contain 
                  <b>E
                  </b> (for Encryption) or 
                  <b>D
                  </b> (for Decryption)
                </p>
                <p>If first line character is 
                  <b>E
                  </b> then
                  <br>
                </p>
                <section style="margin-left: 2cm;">
                  Second line should contain input string to be encrypted
                  <br>Third line should contain Sender's unique identifier
                </section>
                <p>
                </p>
                <p>Else If First line character is 
                  <b>D
                  </b> then
                  <br>
                </p>
                <section style="margin-left: 2cm;">
                  Second line should contain string to be decrypted
                </section>
                <p>
                </p>
                <br>
                <br>
                <p>
                </p>
                <p style="line-height:140%;">
                  <b>Output Format:
                  </b>
                  <br>
                  <br>
                </p>
                <p>If input character is 
                  <b>E
                  </b> then print final encrypted string
                </p>
                <p>If input character is 
                  <b>D
                  </b> then
                  <br>
                </p>
                <section style="margin-left: 2cm;">
                  Print Supplier's unique identifier on first line
                  <br>Print Decrypted string on second line
                </section>
                <p>
                </p>
                <br>
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
                        <th style="height:20px">Output
                        </th>
                      </tr>
                      <tr>
                        <td style="width:10px;">
                          <br>1
                          <br>
                        </td>
                        <td style="width:300px;">
                          <br>E
                          <br>
                          Hello World
                          <br>
                          45
                          <br>
                        </td>
                        <td style="width:300px">
                          <br>2-45-84-56-C6-C6-F6-02-75-F6-27-C6-46
                          <br>
                        </td>						
                      </tr>
                      <tr>
                        <td style="width:10px;">
                          <br>2
                        </td>
                        <td style="width:300px;">
                          <br>D
                          <br>
                          2-45-84-56-C6-C6-F6-02-75-F6-27-C6-46
                          <br>
                          <br>
                        </td>
                        <td style="width:300px">
                          <br>45
                          <br>Hello World
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
