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
                    <span class="problem">Problem : Verify JSON Object validity
                      <o:p>
                      </o:p>
                    </span>
                  </b>
                </p>
                <p class="western" align="JUSTIFY" style="line-height:140%;margin-bottom: 0in;">
                  <br>
                  A JSON object is a key-value pair data structure that is enclosed within { }. A sample JSON object would look like
                  <br>
                  {
                  <br>
                  "key1":"value1",
                  <br>
                  "key2":"value2",
                  <br>
                  "key3": { 
                  <br>
                  "key4":"value4",
                  <br>
                  "key5":"value5"}
                  <br>
                  "key6":"value6",
                  <br>
                  "key7":[
                  <br>
                  {
                  <br>
                  "key8":"value8"
                  <br>
                  }]
                  <br>
                  }
                  <br>
                  <br>
                  Given a JSON object, ignore the literal values of the object and check whether the distinguishing characters and notation of the object are valid to determine if the JSON object is valid or not.
                  <br>
                  <br>
                  <font color="red">Note
                  </font>:
                </p>
                <ol>
                  <li>Key3 points to another JSON object (Concept of nesting of JSON objects).
                  </li>
                  <li>Key7 points to an array of JSON objects. 
                  </li>
                </ol>
                You may wish to refer 
                <a href="http://json.org/" target="_blank" style="color:#0000ff; background-color:transparent; text-decoration:none">site1
                </a> to get a more formal description of JSON grammar. 
                <a href="http://www.w3schools.com/json/" target="_blank" style="color:#0000ff; background-color:transparent; text-decoration:none">site2
                </a>, 
                <a href="http://www.tutorialspoint.com/json/json_overview.htm" target="_blank" style="color:#0000ff; background-color:transparent; text-decoration:none">site3
                </a>; are also good resources to understand JSON specifications.
                <br>
                <br>	
                <p>
                </p>
                <p style="line-height:140%;">
                  <b>Input Format:
                  </b>
                  <br>
                  <br>
                </p>
                <ol>
                  <li>First line contains a pattern of JSON without any literal
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
                  Print 1 if pattern is valid, -1 otherwise.
                  <br>
                  <br>
                </p>
                <p class="western" align="JUSTIFY" style="line-height: 140%; margin-bottom: 0in;">
                  <font face="Verdana, sans-serif">
                    <b>Constraints:
                    </b>
                  </font>
                  <br>
                </p>
                <p style="line-height: 140%;">
                  <b>
                  </b>
                </p>
                <ol>
                  <b>
                    <li>A JSON object should start with '{' and ends with a '}'.
                    </li>
                    <li>The key and value should be separated by a ':'.
                    </li>
                    <li>A ',' suggests an additional JSON property.
                    </li>
                    <li>An array only consists of JSON objects. It cannot contain a "key":"value" pair by itself.
                    </li>
                  </b>
                </ol>
                <br>
                <p>
                </p>
                <p>
                </p>
                <p style="line-height:140%;">
                  <b>Example 1:
                  </b>
                  <br>
                  <br>
                  <b>Input
                  </b>
                  <br>{:[{},{}]}
                  <br>
                  <br>
                  <b>Outputput
                  </b>
                  <br>1
                  <br>
                  <br>
                  <b>Explanation
                  </b>
                  <br>
                  {
                  <br>
                  "Key": [{
                  <br>
                  "Key": "Value"
                  <br>
                  }, {
                  <br>
                  "Key": "Value"
                  <br>
                  }]
                  <br>
                  }
                  <br>
                  Pattern is following all constrains hence prints 1
                  <br>
                  <br>
                </p>
                <p style="line-height:140%;">
                  <b>Example 2:
                  </b>
                  <br>
                  <br>
                  <b>Input
                  </b>
                  <br>{:{[]},{}}
                  <br>
                  <br>
                  <b>Outputput
                  </b>
                  <br>-1
                  <br>
                  <br>
                  <b>Explanation
                  </b>
                  <br>
                  Covert this pattern in a JSON Object
                  <br>
                  <br>
                  {
                  <br>
                  "Key": {
                  <br>
                  [
                  <br>
                  "Key": "Value"
                  <br>
                  ]
                  <br>
                  },
                  <br>
                  {
                  <br>
                  "Key": "Value"
                  <br>
                  }
                  <br>
                  }
                  <br>
                  <br>
                  Constraint 4 "An array only consists of JSON objects. It cannot contain a "key":"value" pair by itself." not followed here, so it's a invalid pattern, hence prints -1
                  <br>
                  <br>
                </p>
              </div>
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
            </div> 
            <br> 
            <br>
		</td>
        </tr>
      </tbody>
    </table>
  </body>
</html>
