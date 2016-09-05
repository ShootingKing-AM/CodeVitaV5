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
                    <span class="problem">Problem : Checking Moves 
                      <o:p>
                      </o:p>
                    </span>
                  </b>
                </p>
                <p class="western" align="JUSTIFY" style="line-height:140%;margin-bottom: 0in;">
                  <b>Background
                  </b>
                  <br>
                  <br>
                  A Chess board position is accurately captured by Forsyth-Edwards notation and is abbreviated as FEN. A FEN "record" defines a particular game position, all in one line of text and using only the ASCII character set. A FEN record consists of six fields. A complete description of the FEN format to represent Chess positions can be found 
                  <a href="https://en.wikipedia.org/wiki/Forsyth%E2%80%93Edwards_Notation" target="_blank" style="color:#0000ff; background-color:transparent; text-decoration:none">here
                  </a> 
                  <br>
                  <br>
                  For the purpose of this problem, only consider first of the six fields of FEN. Before we describe the problem, let us look at how FEN maps to a board position. The following 5 images show board positions and its corresponding FEN representation.
                  <br>
                  <br>
                </p>
                <p style="float:left;">
                  <img src="files/cv15R2_R1P2_fig1.png" height="250px" width="250px">
                  <br>
                  <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                  </span>
                  <span style="font-size:10px;">
                    <b>Figure 1.
                    </b>
                  </span>
                </p>
                <br>
                <br>
                <br>
                <br>
                <p style="float:right;">
                </p>
                <table style="float:right;" border="1" cellspacing="0" cellpadding="2" width="350">
                  <tbody>
                    <tr>
                      <td>This board position depicts initial position before any side has made a move. In FEN format this board position is represented as 
                        <br>
                        <br>
                        <br>
                        rnbqkbnr/pppppppp/8/8/8/8/PPPPPPPP/RNBQKBNR
                      </td>
                    </tr>
                  </tbody>
                </table>
                <br>
                <br>
                <p>
                </p>
                <br>
                <br>
                <br>
                <br>
                <br>
                <br>
                <br>
                <br>
                <br>
                <br>
                <br>
                <br>
                <br>
                <br>
                Let's say, White plays e4. Then the board position looks like shown below
                <br>
                <br>
                <p style="float:left;">
                  <img src="files/cv15R2_R1P2_fig2.png" height="250px" width="250px">
                  <br>
                  <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                  </span>
                  <span style="font-size:10px;">
                    <b>Figure 2.
                    </b>
                  </span>
                </p>
                <br>
                <br>
                <br>
                <br>
                <p style="float:right;">
                </p>
                <table style="float:right;" border="1" cellspacing="0" cellpadding="2" width="350">
                  <tbody>
                    <tr>
                      <td>This board position depicts the Chess board after White has played e4. In FEN format this board position is represented as 
                        <br>
                        <br>
                        <br>
                        rnbqkbnr/pppppppp/8/8/4P3/8/PPPP1PPP/RNBQKBNR
                      </td>
                    </tr>
                  </tbody>
                </table>
                <br>
                <br>
                <p>
                </p>
                <br>
                <br>
                <br>
                <br>
                <br>
                <br>
                <br>
                <br>
                <br>
                <br>
                <br>
                <br>
                <br>
                <br>					
                Similarly, 3 more half-moves are depicted in following diagrams
                <br>
                <br>
                <p>
                </p>
                <table>
                  <tbody>
                    <tr>
                      <td>
                        <div>
                          <img src="files/cv15R2_R1P2_fig3.png" height="250px" width="230px">
                          <br>
                        </div>
                      </td>
                      <td>
                        <div>
                          <img src="files/cv15R2_R1P2_fig4.png" height="250px" width="230px">
                          <br>					
                        </div>
                      </td>
                      <td>
                        <div>
                          <img src="files/cv15R2_R1P2_fig5.png" height="250px" width="230px">
                          <br>
                        </div>
                      </td>
                    </tr>
                    <tr>
                      <td align="center">
                        <span style="font-size:10px;">
                          <b>Figure 3.
                          </b>
                        </span>
                      </td>
                      <td align="center">
                        <span style="font-size:10px;">
                          <b>Figure 4.
                          </b>
                        </span>
                      </td>
                      <td align="center">
                        <span style="font-size:10px;">
                          <b>Figure 5.
                          </b>
                        </span>
                      </td>
                    </tr>
                  </tbody>
                </table>				
                <p>
                </p>
                <br>
                <br>
                The FENs corresponding to Figure 3, 4 and 5 are represented as 
                <br>
                <br>
                <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                </span>
                3.	rnbqkbnr/pppp1ppp/8/4p3/4P3/8/PPPP1PPP/RNBQKBNR
                <br>
                <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                </span>
                4.	rnbqkbnr/pppp1ppp/8/4p3/4PP2/8/PPPP2PP/RNBQKBNR
                <br>
                <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                </span>
                5.	rnbqkbnr/pppp1ppp/8/8/4Pp2/8/PPPP2PP/RNBQKBNR
                <br>
                <br>
                <b>Wikipedia describes first field of FEN format as follows
                </b>
                <br>
                <br>
                Piece placement (from white's perspective). Each rank is described, starting with rank 8 and ending with rank 1; within each rank, the contents of each square are described from file "a" through file "h". Following the 
                <a href="https://en.wikipedia.org/wiki/Algebraic_chess_notation" target="_blank" style="color:#0000ff; background-color:transparent; text-decoration:none">Standard Algebraic Notation
                </a> (SAN), each piece is identified by a single letter taken from the standard English names (pawn = "P", knight = "N", bishop = "B", rook = "R", queen = "Q" and king = "K").[1] White pieces are designated using upper-case letters ("PNBRQK") while black pieces use lowercase ("pnbrqk"). Empty squares are noted using digits 1 through 8 (the number of empty squares), and "/" separates ranks
                <br>
                <br>
                <b>Statement
                </b>
                <br>
                <br>
                Given a board position in FEN format, your task is to find out all move(s) that white can make that lead to a check to the black king.
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
                  <li>First line contains single FEN record, which corresponds to a particular board position 
                  </li>
                  <li>Second line contains -1 which indicates the end of input
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
                </p>
                <ol>
                  <li type="1">The output must be printed as follows
                    <br>
                    <ol type="a">
                      <li>A string "Checking moves " followed by "[&lt;move format&gt;]"
                      </li>
                      <li>Where &lt;move format&gt; is move represented in format "[Piece][fromSquare]-[Piece][toSquare]"
                      </li>
                      <li>If a Checking move involves a capture then represent it as "[Piece][fromSquare]-[Piece]x[toSquare]"
                      </li>
                      <li>If the Piece inflicting a check is a pawn represent it only as [fromSquare]-[toSquare]
                      </li>
                      <li>If there is more than one Checking move, then follow the rules given below
                        <br>
                        <ol type="i">
                          <li>Moves must be sorted alphabetically according to their ascii values
                          </li>
                          <li>Two moves must be separated by a comma followed by a white space characters
                          </li>
                          <li>Between the last move and terminating "]" character there should be no space or comma
                          </li>
                        </ol>
                      </li>
                    </ol>
                  </li>
                  <li>See Example section for better understanding of output format
                  </li>
                </ol>
                <br>
                <p>
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
                  <li>The board position will always be White to move.
                  </li>
                  <li>Since we focus on only first part of the FEN, we are essentially ignoring possibility of Castling being a checking move. 
                    <b>Hence our test cases don't contain FENs which give rise to such positions.
                    </b>
                  </li>
                  <li>There is no need to handle 
                    <a href="https://en.wikipedia.org/wiki/En_passant" target="_blank" style="color:#0000ff; background-color:transparent; text-decoration:none">
                      <i>En Passant
                      </i>
                    </a> positions. There are no test cases involving 
                    <i>En Passant
                    </i> moves.
                  </li>
                  <li>No need to implement 
                    <a href="https://en.wikipedia.org/wiki/Promotion_(chess)" target="_blank" style="color:#0000ff; background-color:transparent; text-decoration:none">
                      <i>pawn promotion
                      </i>
                    </a> rules. Our test cases do not contain positions which will lead to a pawn getting promoted and inflicting a check.									
                  </li>
                  <li>There are no test cases in which capture by a white pawn leads to a check.
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
                  <table width="650px" border="1" cellspacing="0" cellpadding="2" style="font-size:10.7px;">
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
                        <td style="width:7px;">1
                        </td>
                        <td style="width:300px;">
                          <br>
                          3k4/8/5p2/8/7B/R7/8/2K5
                          <br>
                          -1
                          <br>
                          <br>
                        </td>
                        <td style="width:343px">
                          <br>
                          Checking moves [Bh4-Bxf6, Ra3-Ra8, Ra3-Rd3]
                          <br>
                          <br>
                        </td>							
                      </tr>
                      <tr>
                        <td style="width:7px;">2
                        </td>
                        <td style="width:300px;">
                          <br>
                          r2k4/8/4P3/2B5/8/8/8/4K3
                          <br>
                          -1
                          <br>
                          <br>
                        </td>
                        <td style="width:343px">
                          <br>
                          Checking moves [Bc5-Bb6, Bc5-Be7, e6-e7]
                          <br>
                          <br>
                        </td>					
                      </tr>
                    </tbody>
                  </table>
                  <br>
                  <br>
                  <p style="line-height:140%;">
                    <b>Explanation:
                    </b>
                    <br>
                    <br>	
                  </p>
                  <table width="650px">
                    <tbody>
                      <tr>
                        <td>
                          <b>Board position for sample input 1: 
                          </b>
                          <br>
                          <br>
                          <span>
                            <img src="files/cv15ph2r1_R2P7_fig6.jpg" height="250px" width="250px">
                          </span>
                          <br>
                          <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                          </span>
                          <span style="font-size:10px;">
                            <b>Figure 6.
                            </b>
                          </span>	
                        </td>
                        <td>
                          <b>Board position for sample input 2: 
                          </b>
                          <br>
                          <br>
                          <span>
                            <img src="files/cv15ph2r1_R2P7_fig7.jpg" height="250px" width="250px">
                          </span>
                          <br>
                          <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                          </span>
                          <span style="font-size:10px;">
                            <b>Figure 7.
                            </b>
                          </span>	
                        </td>
                      </tr>
                    </tbody>
                  </table>
                  <br>
                  <br>
                  <p>
                  </p>
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
