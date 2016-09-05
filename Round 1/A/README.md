<html>
  <body>
    <table>
      <tbody>
        <tr>
          <td width="auto" valign="top">
            <div class="border">
              <div class="Section1">	
                <p class="MsoNormal" align="center" style="text-align:left">
                  <b style="mso-bidi-font-weight:normal">
                    <span class="problem">Problem : Chakravyuha
                    </span>
                  </b>
                </p>
                <p class="western" align="JUSTIFY" style="line-height:140%;margin-bottom: 0in;">
                  During the battle of Mahabharat, when Arjuna was far away in the battlefield, Guru Drona made a Chakravyuha formation of the Kaurava army to capture Yudhisthir Maharaj. Abhimanyu, young son of Arjuna was the only one amongst the remaining Pandava army who knew how to crack the Chakravyuha. He took it upon himself to take the battle to the enemies.
                  <br>
                  <br>
                  Abhimanyu knew how to get power points when cracking the Chakravyuha. So great was his prowess that rest of the Pandava army could not keep pace with his advances. Worried at the rest of the army falling behind, Yudhisthir Maharaj needs your help to track of Abhimanyu's advances. Write a program that tracks how many power points Abhimanyu has collected and also uncover his trail 
                  <br>
                  <br>
                  A Chakravyuha is a wheel-like formation. Pictorially it is depicted as below
                  <br>
                  <br>
                </p>
                <div style="text-align:center">
                  <img src="files/jalebi1.png" height="200px" width="200px">
                  <br>
                  <b>Fig 1. Chakravyuha
                  </b>
                </div>
                <br>
                <br>
                A Chakravyuha has a very well-defined co-ordinate system. Each point on the co-ordinate system is manned by a certain unit of the army. The Commander-In-Chief is always located at the center of the army to better co-ordinate his forces. The only way to crack the Chakravyuha is to defeat the units in sequential order.
                <br>
                <br>
                A Sequential order of units differs structurally based on the radius of the Chakra. The radius can be thought of as length or breadth of the matrix depicted above. The structure i.e. placement of units in <i>sequential order</i> is as shown below
                <br>
                <br>
                <div style="text-align:center">
                  <img src="files/jalebi2.png" height="150px" width="150px">
                  <br>
                  <b>Fig 2. Army unit placements in Chakravyuha of size 5
                  </b>
                </div>
                <br>
                <br>
                The entry point of the Chakravyuha is always at the (0,0) co-ordinate of the matrix above. This is where the 1st army unit guards. From (0,0) i.e. 1st unit Abhimanyu has to march towards the center at (2,2) where the 25th i.e. the last of the enemy army unit guards. Remember that he has to proceed by destroying the units in sequential fashion. After destroying the first unit, Abhimanyu gets a power point. Thereafter, he gets one after destroying army units which are multiples of 11. You should also be a in a position to tell Yudhisthir Maharaj the location at which Abhimanyu collected his power points. 
                <br>
                <br>
                <p>
                </p>
                <p style="line-height:140%;">
                  <b>Input Format:
                  </b>
                  <br>
                  <br>
                  First line of input will be length as well as breadth of the army units, say N
                  <br>
                  <br>
                </p>
                <p style="line-height:140%;">
                  <b>Output Format:
                  </b>
                  <br>
                </p>
                <ul>
                  <li>Print NxN matrix depicting the placement of army units, with unit numbers delimited by (\t) Tab character
                  </li>
                  <li>Print Total power points collected
                  </li>
                  <li>Print coordinates of power points collected in sequential fashion (one per line)
                  </li>
                </ul>
                <br>
                <p>
                </p>
                <p class="western" align="JUSTIFY" style="line-height:140%;margin-bottom: 0in;">
                  <font face="Verdana, sans-serif">
                    <b>Constraints:
                    </b>
                  </font>
                  <br>
                </p>
                <p style="line-height:140%;">
                  <b>
                  </b>
                </p>
                <ol>
                  <b>
                    <li>0 &lt; N &lt;=100
                    </li>
                  </b>
                </ol>
                <b>				
                </b>
                <br>
                <p>
                </p>
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
                        <td style="width:10px;">1
                        </td>
                        <td style="width:100px;">2
                        </td>
                        <td style="width:300px">
                          <br>1	2
                          <br>4	3
                          <br>Total Power points : 1
                          <br>(0,0)
                          <br>
                        </td>						
                      </tr>
                      <tr>
                        <td style="width:10px;">2
                        </td>
                        <td style="width:100px;">5
                        </td>
                        <td style="width:300px">
                          <br>1	2	3	4	5
                          <br>16	17	18	19	6
                          <br>15	24	25	20	7
                          <br>14	23	22	21	8
                          <br>13	12	11	10	9
                          <br>Total Power points : 3
                          <br>(0,0)
                          <br>(4,2)
                          <br>(3,2)
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
                  <p class="western" align="JUSTIFY" style="margin-bottom: 0in">
                    <br>
                  </p>
                </div>
              </a>
            </div>
          </td>
        </tr>
      </tbody>
    </table>
  </body>
</html>
