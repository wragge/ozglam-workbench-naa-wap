# OzGLAM data workbench

**Please note this is experimental and unfinished. I'm still learning about the capabilities of Jupyter. Things might change radically!**

This is a collection of [Jupyter](http://jupyter.org/) notebooks to help you explore and use data from Australian GLAM institutions. It's aimed at researchers in the humanities, but will include tutorials of more general interest -- such as an introduction to the Trove API.

<style  type="text/css" >
    #T_811841e2_50cb_11e8_a891_ac87a32cd560 th {
          font-size: 120%;
          text-align: center;
    }    #T_811841e2_50cb_11e8_a891_ac87a32cd560 .row_heading, .blank {
          display: none;
    }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row0_col0 {
            font-size:  120%;
            text-align:  left;
            font-weight:  bold;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row0_col1 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row0_col2 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row0_col3 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row0_col4 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row0_col5 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row0_col6 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row0_col7 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row0_col8 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row0_col9 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row0_col10 {
            font-size:  120%;
            background-color:  #3aa357;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row0_col11 {
            font-size:  120%;
            background-color:  #f6fcf4;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row1_col0 {
            font-size:  120%;
            text-align:  left;
            font-weight:  bold;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row1_col1 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row1_col2 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row1_col3 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row1_col4 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row1_col5 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row1_col6 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row1_col7 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row1_col8 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row1_col9 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row1_col10 {
            font-size:  120%;
            background-color:  #37a055;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row1_col11 {
            font-size:  120%;
            background-color:  #f7fcf5;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row2_col0 {
            font-size:  120%;
            text-align:  left;
            font-weight:  bold;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row2_col1 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row2_col2 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row2_col3 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row2_col4 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row2_col5 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row2_col6 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row2_col7 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row2_col8 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row2_col9 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row2_col10 {
            font-size:  120%;
            background-color:  #37a055;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row2_col11 {
            font-size:  120%;
            background-color:  #f4fbf2;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row3_col0 {
            font-size:  120%;
            text-align:  left;
            font-weight:  bold;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row3_col1 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row3_col2 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row3_col3 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row3_col4 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row3_col5 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row3_col6 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row3_col7 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row3_col8 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row3_col9 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row3_col10 {
            font-size:  120%;
            background-color:  #f7fcf5;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row3_col11 {
            font-size:  120%;
            background-color:  #f7fcf5;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row4_col0 {
            font-size:  120%;
            text-align:  left;
            font-weight:  bold;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row4_col1 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row4_col2 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row4_col3 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row4_col4 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row4_col5 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row4_col6 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row4_col7 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row4_col8 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row4_col9 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row4_col10 {
            font-size:  120%;
            background-color:  #37a055;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row4_col11 {
            font-size:  120%;
            background-color:  #f7fcf5;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row5_col0 {
            font-size:  120%;
            text-align:  left;
            font-weight:  bold;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row5_col1 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row5_col2 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row5_col3 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row5_col4 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row5_col5 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row5_col6 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row5_col7 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row5_col8 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row5_col9 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row5_col10 {
            font-size:  120%;
            background-color:  #daf0d4;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row5_col11 {
            font-size:  120%;
            background-color:  #f6fcf4;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row6_col0 {
            font-size:  120%;
            text-align:  left;
            font-weight:  bold;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row6_col1 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row6_col2 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row6_col3 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row6_col4 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row6_col5 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row6_col6 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row6_col7 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row6_col8 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row6_col9 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row6_col10 {
            font-size:  120%;
            background-color:  #38a156;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row6_col11 {
            font-size:  120%;
            background-color:  #38a156;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row7_col0 {
            font-size:  120%;
            text-align:  left;
            font-weight:  bold;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row7_col1 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row7_col2 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row7_col3 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row7_col4 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row7_col5 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row7_col6 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row7_col7 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row7_col8 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row7_col9 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row7_col10 {
            font-size:  120%;
            background-color:  #37a055;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row7_col11 {
            font-size:  120%;
            background-color:  #37a055;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row8_col0 {
            font-size:  120%;
            text-align:  left;
            font-weight:  bold;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row8_col1 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row8_col2 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row8_col3 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row8_col4 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row8_col5 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row8_col6 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row8_col7 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row8_col8 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row8_col9 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row8_col10 {
            font-size:  120%;
            background-color:  #37a055;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row8_col11 {
            font-size:  120%;
            background-color:  #37a055;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row9_col0 {
            font-size:  120%;
            text-align:  left;
            font-weight:  bold;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row9_col1 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row9_col2 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row9_col3 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row9_col4 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row9_col5 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row9_col6 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row9_col7 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row9_col8 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row9_col9 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row9_col10 {
            font-size:  120%;
            background-color:  #37a055;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row9_col11 {
            font-size:  120%;
            background-color:  #37a055;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row10_col0 {
            font-size:  120%;
            text-align:  left;
            font-weight:  bold;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row10_col1 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row10_col2 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row10_col3 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row10_col4 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row10_col5 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row10_col6 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row10_col7 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row10_col8 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row10_col9 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row10_col10 {
            font-size:  120%;
            background-color:  #37a055;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row10_col11 {
            font-size:  120%;
            background-color:  #37a055;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row11_col0 {
            font-size:  120%;
            text-align:  left;
            font-weight:  bold;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row11_col1 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row11_col2 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row11_col3 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row11_col4 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row11_col5 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row11_col6 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row11_col7 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row11_col8 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row11_col9 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row11_col10 {
            font-size:  120%;
            background-color:  #38a156;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row11_col11 {
            font-size:  120%;
            background-color:  #f4fbf1;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row12_col0 {
            font-size:  120%;
            text-align:  left;
            font-weight:  bold;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row12_col1 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row12_col2 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row12_col3 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row12_col4 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row12_col5 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row12_col6 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row12_col7 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row12_col8 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row12_col9 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row12_col10 {
            font-size:  120%;
            background-color:  #37a055;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row12_col11 {
            font-size:  120%;
            background-color:  #f7fcf5;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row13_col0 {
            font-size:  120%;
            text-align:  left;
            font-weight:  bold;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row13_col1 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row13_col2 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row13_col3 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row13_col4 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row13_col5 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row13_col6 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row13_col7 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row13_col8 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row13_col9 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row13_col10 {
            font-size:  120%;
            background-color:  #aedea7;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row13_col11 {
            font-size:  120%;
            background-color:  #f7fcf5;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row14_col0 {
            font-size:  120%;
            text-align:  left;
            font-weight:  bold;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row14_col1 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row14_col2 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row14_col3 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row14_col4 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row14_col5 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row14_col6 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row14_col7 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row14_col8 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row14_col9 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row14_col10 {
            font-size:  120%;
            background-color:  #38a156;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row14_col11 {
            font-size:  120%;
            background-color:  #f3faf0;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row15_col0 {
            font-size:  120%;
            text-align:  left;
            font-weight:  bold;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row15_col1 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row15_col2 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row15_col3 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row15_col4 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row15_col5 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row15_col6 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row15_col7 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row15_col8 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row15_col9 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row15_col10 {
            font-size:  120%;
            background-color:  #d2edcc;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row15_col11 {
            font-size:  120%;
            background-color:  #f4fbf1;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row16_col0 {
            font-size:  120%;
            text-align:  left;
            font-weight:  bold;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row16_col1 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row16_col2 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row16_col3 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row16_col4 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row16_col5 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row16_col6 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row16_col7 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row16_col8 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row16_col9 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row16_col10 {
            font-size:  120%;
            background-color:  #37a055;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row16_col11 {
            font-size:  120%;
            background-color:  #e5f5e1;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row17_col0 {
            font-size:  120%;
            text-align:  left;
            font-weight:  bold;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row17_col1 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row17_col2 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row17_col3 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row17_col4 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row17_col5 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row17_col6 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row17_col7 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row17_col8 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row17_col9 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row17_col10 {
            font-size:  120%;
            background-color:  #a8dca2;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row17_col11 {
            font-size:  120%;
            background-color:  #f7fcf5;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row18_col0 {
            font-size:  120%;
            text-align:  left;
            font-weight:  bold;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row18_col1 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row18_col2 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row18_col3 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row18_col4 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row18_col5 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row18_col6 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row18_col7 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row18_col8 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row18_col9 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row18_col10 {
            font-size:  120%;
            background-color:  #37a055;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row18_col11 {
            font-size:  120%;
            background-color:  #f7fcf5;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row19_col0 {
            font-size:  120%;
            text-align:  left;
            font-weight:  bold;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row19_col1 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row19_col2 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row19_col3 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row19_col4 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row19_col5 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row19_col6 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row19_col7 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row19_col8 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row19_col9 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row19_col10 {
            font-size:  120%;
            background-color:  #37a055;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row19_col11 {
            font-size:  120%;
            background-color:  #f7fcf5;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row20_col0 {
            font-size:  120%;
            text-align:  left;
            font-weight:  bold;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row20_col1 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row20_col2 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row20_col3 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row20_col4 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row20_col5 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row20_col6 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row20_col7 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row20_col8 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row20_col9 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row20_col10 {
            font-size:  120%;
            background-color:  #3fa85b;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row20_col11 {
            font-size:  120%;
            background-color:  #e3f4de;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row21_col0 {
            font-size:  120%;
            text-align:  left;
            font-weight:  bold;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row21_col1 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row21_col2 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row21_col3 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row21_col4 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row21_col5 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row21_col6 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row21_col7 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row21_col8 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row21_col9 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row21_col10 {
            font-size:  120%;
            background-color:  #37a055;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row21_col11 {
            font-size:  120%;
            background-color:  #f7fcf5;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row22_col0 {
            font-size:  120%;
            text-align:  left;
            font-weight:  bold;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row22_col1 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row22_col2 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row22_col3 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row22_col4 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row22_col5 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row22_col6 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row22_col7 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row22_col8 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row22_col9 {
            font-size:  120%;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row22_col10 {
            font-size:  120%;
            background-color:  #37a055;
        }    #T_811841e2_50cb_11e8_a891_ac87a32cd560row22_col11 {
            font-size:  120%;
            background-color:  #e8f6e4;
        }</style>  
<table id="T_811841e2_50cb_11e8_a891_ac87a32cd560" >
<thead>    <tr>
        <th class="blank level0" ></th>
        <th class="col_heading level0 col0" >series</th>
        <th class="col_heading level0 col1" >total_items</th>
        <th class="col_heading level0 col2" >date_from</th>
        <th class="col_heading level0 col3" >date_to</th>
        <th class="col_heading level0 col4" >Open</th>
        <th class="col_heading level0 col5" >OWE</th>
        <th class="col_heading level0 col6" >NYE</th>
        <th class="col_heading level0 col7" >Closed</th>
        <th class="col_heading level0 col8" >digitised_files</th>
        <th class="col_heading level0 col9" >digitised_pages</th>
        <th class="col_heading level0 col10" >% open</th>
        <th class="col_heading level0 col11" >% digitised</th>
    </tr></thead>
<tbody>    <tr>
        <th id="T_811841e2_50cb_11e8_a891_ac87a32cd560level0_row0" class="row_heading level0 row0" >0</th>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row0_col0" class="data row0 col0" ><a href="B13-summary.ipynb">B13</a></td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row0_col1" class="data row0 col1" >20,194</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row0_col2" class="data row0 col2" >1800</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row0_col3" class="data row0 col3" >2005</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row0_col4" class="data row0 col4" >19,786</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row0_col5" class="data row0 col5" >8</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row0_col6" class="data row0 col6" >400</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row0_col7" class="data row0 col7" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row0_col8" class="data row0 col8" >354</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row0_col9" class="data row0 col9" >5,043</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row0_col10" class="data row0 col10" >97.98%</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row0_col11" class="data row0 col11" >1.75%</td>
    </tr>    <tr>
        <th id="T_811841e2_50cb_11e8_a891_ac87a32cd560level0_row1" class="row_heading level0 row1" >1</th>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row1_col0" class="data row1 col0" ><a href="B6003-summary.ipynb">B6003</a></td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row1_col1" class="data row1 col1" >3</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row1_col2" class="data row1 col2" >1904</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row1_col3" class="data row1 col3" >1959</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row1_col4" class="data row1 col4" >3</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row1_col5" class="data row1 col5" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row1_col6" class="data row1 col6" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row1_col7" class="data row1 col7" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row1_col8" class="data row1 col8" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row1_col9" class="data row1 col9" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row1_col10" class="data row1 col10" >100.00%</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row1_col11" class="data row1 col11" >0.00%</td>
    </tr>    <tr>
        <th id="T_811841e2_50cb_11e8_a891_ac87a32cd560level0_row2" class="row_heading level0 row2" >2</th>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row2_col0" class="data row2 col0" ><a href="BP343-15-summary.ipynb">BP343/15</a></td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row2_col1" class="data row2 col1" >2,571</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row2_col2" class="data row2 col2" >1916</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row2_col3" class="data row2 col3" >1955</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row2_col4" class="data row2 col4" >2,566</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row2_col5" class="data row2 col5" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row2_col6" class="data row2 col6" >5</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row2_col7" class="data row2 col7" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row2_col8" class="data row2 col8" >85</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row2_col9" class="data row2 col9" >176</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row2_col10" class="data row2 col10" >99.81%</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row2_col11" class="data row2 col11" >3.31%</td>
    </tr>    <tr>
        <th id="T_811841e2_50cb_11e8_a891_ac87a32cd560level0_row3" class="row_heading level0 row3" >3</th>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row3_col0" class="data row3 col0" ><a href="D2860-summary.ipynb">D2860</a></td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row3_col1" class="data row3 col1" >1</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row3_col2" class="data row3 col2" >1902</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row3_col3" class="data row3 col3" >1957</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row3_col4" class="data row3 col4" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row3_col5" class="data row3 col5" >1</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row3_col6" class="data row3 col6" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row3_col7" class="data row3 col7" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row3_col8" class="data row3 col8" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row3_col9" class="data row3 col9" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row3_col10" class="data row3 col10" >0.00%</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row3_col11" class="data row3 col11" >0.00%</td>
    </tr>    <tr>
        <th id="T_811841e2_50cb_11e8_a891_ac87a32cd560level0_row4" class="row_heading level0 row4" >4</th>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row4_col0" class="data row4 col0" ><a href="D5036-summary.ipynb">D5036</a></td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row4_col1" class="data row4 col1" >1</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row4_col2" class="data row4 col2" >1906</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row4_col3" class="data row4 col3" >1935</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row4_col4" class="data row4 col4" >1</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row4_col5" class="data row4 col5" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row4_col6" class="data row4 col6" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row4_col7" class="data row4 col7" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row4_col8" class="data row4 col8" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row4_col9" class="data row4 col9" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row4_col10" class="data row4 col10" >100.00%</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row4_col11" class="data row4 col11" >0.00%</td>
    </tr>    <tr>
        <th id="T_811841e2_50cb_11e8_a891_ac87a32cd560level0_row5" class="row_heading level0 row5" >5</th>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row5_col0" class="data row5 col0" ><a href="D596-summary.ipynb">D596</a></td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row5_col1" class="data row5 col1" >11,395</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row5_col2" class="data row5 col2" >1871</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row5_col3" class="data row5 col3" >1971</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row5_col4" class="data row5 col4" >2,983</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row5_col5" class="data row5 col5" >31</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row5_col6" class="data row5 col6" >8,381</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row5_col7" class="data row5 col7" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row5_col8" class="data row5 col8" >185</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row5_col9" class="data row5 col9" >3,031</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row5_col10" class="data row5 col10" >26.18%</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row5_col11" class="data row5 col11" >1.62%</td>
    </tr>    <tr>
        <th id="T_811841e2_50cb_11e8_a891_ac87a32cd560level0_row6" class="row_heading level0 row6" >6</th>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row6_col0" class="data row6 col0" ><a href="E752-summary.ipynb">E752</a></td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row6_col1" class="data row6 col1" >722</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row6_col2" class="data row6 col2" >1905</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row6_col3" class="data row6 col3" >1941</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row6_col4" class="data row6 col4" >719</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row6_col5" class="data row6 col5" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row6_col6" class="data row6 col6" >3</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row6_col7" class="data row6 col7" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row6_col8" class="data row6 col8" >717</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row6_col9" class="data row6 col9" >9,310</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row6_col10" class="data row6 col10" >99.58%</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row6_col11" class="data row6 col11" >99.31%</td>
    </tr>    <tr>
        <th id="T_811841e2_50cb_11e8_a891_ac87a32cd560level0_row7" class="row_heading level0 row7" >7</th>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row7_col0" class="data row7 col0" ><a href="J2481-summary.ipynb">J2481</a></td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row7_col1" class="data row7 col1" >858</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row7_col2" class="data row7 col2" >1897</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row7_col3" class="data row7 col3" >1903</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row7_col4" class="data row7 col4" >858</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row7_col5" class="data row7 col5" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row7_col6" class="data row7 col6" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row7_col7" class="data row7 col7" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row7_col8" class="data row7 col8" >858</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row7_col9" class="data row7 col9" >2,031</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row7_col10" class="data row7 col10" >100.00%</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row7_col11" class="data row7 col11" >100.00%</td>
    </tr>    <tr>
        <th id="T_811841e2_50cb_11e8_a891_ac87a32cd560level0_row8" class="row_heading level0 row8" >8</th>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row8_col0" class="data row8 col0" ><a href="J2482-summary.ipynb">J2482</a></td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row8_col1" class="data row8 col1" >799</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row8_col2" class="data row8 col2" >1902</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row8_col3" class="data row8 col3" >1912</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row8_col4" class="data row8 col4" >799</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row8_col5" class="data row8 col5" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row8_col6" class="data row8 col6" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row8_col7" class="data row8 col7" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row8_col8" class="data row8 col8" >798</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row8_col9" class="data row8 col9" >3,153</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row8_col10" class="data row8 col10" >100.00%</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row8_col11" class="data row8 col11" >99.87%</td>
    </tr>    <tr>
        <th id="T_811841e2_50cb_11e8_a891_ac87a32cd560level0_row9" class="row_heading level0 row9" >9</th>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row9_col0" class="data row9 col0" ><a href="J2483-summary.ipynb">J2483</a></td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row9_col1" class="data row9 col1" >14,438</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row9_col2" class="data row9 col2" >1903</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row9_col3" class="data row9 col3" >1956</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row9_col4" class="data row9 col4" >14,436</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row9_col5" class="data row9 col5" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row9_col6" class="data row9 col6" >2</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row9_col7" class="data row9 col7" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row9_col8" class="data row9 col8" >14,436</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row9_col9" class="data row9 col9" >79,210</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row9_col10" class="data row9 col10" >99.99%</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row9_col11" class="data row9 col11" >99.99%</td>
    </tr>    <tr>
        <th id="T_811841e2_50cb_11e8_a891_ac87a32cd560level0_row10" class="row_heading level0 row10" >10</th>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row10_col0" class="data row10 col0" ><a href="J3115-summary.ipynb">J3115</a></td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row10_col1" class="data row10 col1" >161</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row10_col2" class="data row10 col2" >1899</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row10_col3" class="data row10 col3" >1928</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row10_col4" class="data row10 col4" >161</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row10_col5" class="data row10 col5" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row10_col6" class="data row10 col6" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row10_col7" class="data row10 col7" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row10_col8" class="data row10 col8" >161</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row10_col9" class="data row10 col9" >1,344</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row10_col10" class="data row10 col10" >100.00%</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row10_col11" class="data row10 col11" >100.00%</td>
    </tr>    <tr>
        <th id="T_811841e2_50cb_11e8_a891_ac87a32cd560level0_row11" class="row_heading level0 row11" >11</th>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row11_col0" class="data row11 col0" ><a href="K1145-summary.ipynb">K1145</a></td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row11_col1" class="data row11 col1" >4,816</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row11_col2" class="data row11 col2" >1900</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row11_col3" class="data row11 col3" >1955</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row11_col4" class="data row11 col4" >4,791</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row11_col5" class="data row11 col5" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row11_col6" class="data row11 col6" >25</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row11_col7" class="data row11 col7" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row11_col8" class="data row11 col8" >175</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row11_col9" class="data row11 col9" >874</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row11_col10" class="data row11 col10" >99.48%</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row11_col11" class="data row11 col11" >3.63%</td>
    </tr>    <tr>
        <th id="T_811841e2_50cb_11e8_a891_ac87a32cd560level0_row12" class="row_heading level0 row12" >12</th>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row12_col0" class="data row12 col0" ><a href="P437-summary.ipynb">P437</a></td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row12_col1" class="data row12 col1" >4,958</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row12_col2" class="data row12 col2" >1901</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row12_col3" class="data row12 col3" >1940</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row12_col4" class="data row12 col4" >4,945</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row12_col5" class="data row12 col5" >10</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row12_col6" class="data row12 col6" >2</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row12_col7" class="data row12 col7" >1</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row12_col8" class="data row12 col8" >18</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row12_col9" class="data row12 col9" >442</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row12_col10" class="data row12 col10" >99.74%</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row12_col11" class="data row12 col11" >0.36%</td>
    </tr>    <tr>
        <th id="T_811841e2_50cb_11e8_a891_ac87a32cd560level0_row13" class="row_heading level0 row13" >13</th>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row13_col0" class="data row13 col0" ><a href="P526-summary.ipynb">P526</a></td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row13_col1" class="data row13 col1" >2</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row13_col2" class="data row13 col2" >1909</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row13_col3" class="data row13 col3" >1918</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row13_col4" class="data row13 col4" >1</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row13_col5" class="data row13 col5" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row13_col6" class="data row13 col6" >1</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row13_col7" class="data row13 col7" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row13_col8" class="data row13 col8" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row13_col9" class="data row13 col9" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row13_col10" class="data row13 col10" >50.00%</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row13_col11" class="data row13 col11" >0.00%</td>
    </tr>    <tr>
        <th id="T_811841e2_50cb_11e8_a891_ac87a32cd560level0_row14" class="row_heading level0 row14" >14</th>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row14_col0" class="data row14 col0" ><a href="PP4-2-summary.ipynb">PP4/2</a></td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row14_col1" class="data row14 col1" >613</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row14_col2" class="data row14 col2" >1903</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row14_col3" class="data row14 col3" >1947</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row14_col4" class="data row14 col4" >610</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row14_col5" class="data row14 col5" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row14_col6" class="data row14 col6" >3</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row14_col7" class="data row14 col7" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row14_col8" class="data row14 col8" >28</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row14_col9" class="data row14 col9" >1,512</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row14_col10" class="data row14 col10" >99.51%</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row14_col11" class="data row14 col11" >4.57%</td>
    </tr>    <tr>
        <th id="T_811841e2_50cb_11e8_a891_ac87a32cd560level0_row15" class="row_heading level0 row15" >15</th>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row15_col0" class="data row15 col0" ><a href="PP6-1-summary.ipynb">PP6/1</a></td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row15_col1" class="data row15 col1" >6,010</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row15_col2" class="data row15 col2" >1906</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row15_col3" class="data row15 col3" >1978</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row15_col4" class="data row15 col4" >1,863</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row15_col5" class="data row15 col5" >33</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row15_col6" class="data row15 col6" >4,109</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row15_col7" class="data row15 col7" >5</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row15_col8" class="data row15 col8" >245</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row15_col9" class="data row15 col9" >6,461</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row15_col10" class="data row15 col10" >31.00%</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row15_col11" class="data row15 col11" >4.08%</td>
    </tr>    <tr>
        <th id="T_811841e2_50cb_11e8_a891_ac87a32cd560level0_row16" class="row_heading level0 row16" >16</th>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row16_col0" class="data row16 col0" ><a href="SP11-26-summary.ipynb">SP11/26</a></td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row16_col1" class="data row16 col1" >27</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row16_col2" class="data row16 col2" >1902</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row16_col3" class="data row16 col3" >1902</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row16_col4" class="data row16 col4" >27</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row16_col5" class="data row16 col5" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row16_col6" class="data row16 col6" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row16_col7" class="data row16 col7" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row16_col8" class="data row16 col8" >5</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row16_col9" class="data row16 col9" >84</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row16_col10" class="data row16 col10" >100.00%</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row16_col11" class="data row16 col11" >18.52%</td>
    </tr>    <tr>
        <th id="T_811841e2_50cb_11e8_a891_ac87a32cd560level0_row17" class="row_heading level0 row17" >17</th>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row17_col0" class="data row17 col0" ><a href="SP11-6-summary.ipynb">SP11/6</a></td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row17_col1" class="data row17 col1" >191</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row17_col2" class="data row17 col2" >1902</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row17_col3" class="data row17 col3" >1947</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row17_col4" class="data row17 col4" >101</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row17_col5" class="data row17 col5" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row17_col6" class="data row17 col6" >90</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row17_col7" class="data row17 col7" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row17_col8" class="data row17 col8" >1</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row17_col9" class="data row17 col9" >323</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row17_col10" class="data row17 col10" >52.88%</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row17_col11" class="data row17 col11" >0.52%</td>
    </tr>    <tr>
        <th id="T_811841e2_50cb_11e8_a891_ac87a32cd560level0_row18" class="row_heading level0 row18" >18</th>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row18_col0" class="data row18 col0" ><a href="SP115-1-summary.ipynb">SP115/1</a></td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row18_col1" class="data row18 col1" >1,787</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row18_col2" class="data row18 col2" >1884</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row18_col3" class="data row18 col3" >1943</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row18_col4" class="data row18 col4" >1,787</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row18_col5" class="data row18 col5" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row18_col6" class="data row18 col6" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row18_col7" class="data row18 col7" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row18_col8" class="data row18 col8" >9</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row18_col9" class="data row18 col9" >285</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row18_col10" class="data row18 col10" >100.00%</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row18_col11" class="data row18 col11" >0.50%</td>
    </tr>    <tr>
        <th id="T_811841e2_50cb_11e8_a891_ac87a32cd560level0_row19" class="row_heading level0 row19" >19</th>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row19_col0" class="data row19 col0" ><a href="SP115-10-summary.ipynb">SP115/10</a></td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row19_col1" class="data row19 col1" >6</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row19_col2" class="data row19 col2" >1884</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row19_col3" class="data row19 col3" >1888</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row19_col4" class="data row19 col4" >6</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row19_col5" class="data row19 col5" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row19_col6" class="data row19 col6" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row19_col7" class="data row19 col7" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row19_col8" class="data row19 col8" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row19_col9" class="data row19 col9" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row19_col10" class="data row19 col10" >100.00%</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row19_col11" class="data row19 col11" >0.00%</td>
    </tr>    <tr>
        <th id="T_811841e2_50cb_11e8_a891_ac87a32cd560level0_row20" class="row_heading level0 row20" >20</th>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row20_col0" class="data row20 col0" ><a href="SP42-1-summary.ipynb">SP42/1</a></td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row20_col1" class="data row20 col1" >16,256</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row20_col2" class="data row20 col2" >1881</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row20_col3" class="data row20 col3" >1960</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row20_col4" class="data row20 col4" >15,525</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row20_col5" class="data row20 col5" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row20_col6" class="data row20 col6" >731</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row20_col7" class="data row20 col7" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row20_col8" class="data row20 col8" >3,253</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row20_col9" class="data row20 col9" >45,862</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row20_col10" class="data row20 col10" >95.50%</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row20_col11" class="data row20 col11" >20.01%</td>
    </tr>    <tr>
        <th id="T_811841e2_50cb_11e8_a891_ac87a32cd560level0_row21" class="row_heading level0 row21" >21</th>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row21_col0" class="data row21 col0" ><a href="SP726-1-summary.ipynb">SP726/1</a></td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row21_col1" class="data row21 col1" >6</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row21_col2" class="data row21 col2" >1902</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row21_col3" class="data row21 col3" >1959</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row21_col4" class="data row21 col4" >6</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row21_col5" class="data row21 col5" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row21_col6" class="data row21 col6" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row21_col7" class="data row21 col7" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row21_col8" class="data row21 col8" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row21_col9" class="data row21 col9" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row21_col10" class="data row21 col10" >100.00%</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row21_col11" class="data row21 col11" >0.00%</td>
    </tr>    <tr>
        <th id="T_811841e2_50cb_11e8_a891_ac87a32cd560level0_row22" class="row_heading level0 row22" >22</th>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row22_col0" class="data row22 col0" ><a href="ST84-1-summary.ipynb">ST84/1</a></td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row22_col1" class="data row22 col1" >2,765</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row22_col2" class="data row22 col2" >1855</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row22_col3" class="data row22 col3" >1975</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row22_col4" class="data row22 col4" >2,758</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row22_col5" class="data row22 col5" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row22_col6" class="data row22 col6" >7</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row22_col7" class="data row22 col7" >0</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row22_col8" class="data row22 col8" >434</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row22_col9" class="data row22 col9" >13,979</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row22_col10" class="data row22 col10" >99.75%</td>
        <td id="T_811841e2_50cb_11e8_a891_ac87a32cd560row22_col11" class="data row22 col11" >15.70%</td>
    </tr></tbody>
</table>

## Support me

If you think this is a worthwhile endeavour, feel free to [support me on Patreon](https://www.patreon.com/timsherratt).

## Using the workbench

### View on GitHub

You can view the contents on GitHub, but note that these will be static versions so you won't be able to run any of the code.

### Run locally with Jupyter

If you have Jupyter installed, you can clone this repository, and then run Jupyter:

```
git clone https://github.com/wragge/ozglam-workbench.git
cd ozglam-workbench
jupyter notebook
```

### Run online with MyBinder

To use a live version without installing any software, try MyBinder:

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/wragge/ozglam-workbench/master)

MyBinder launches the notebooks in a custom computing environment with all the software you'll need pre-installed. But note that these environments aren't persistent, so you'll need to make sure you download any data you want to keep.

### Run locally with Docker

I've created a Docker image that includes these notebooks and all the necessary software. Assuming you have Docker installed, just open up a terminal and run:

``` shell
docker run -it --name=Workbench -v WorkbenchData:/home/jovyan/workbench -p 8888:8888 wragge/ozglam-workbench
```

This creates a persistent data volume and runs the workbench image. Once Jupyter starts up it'll display a url in the terminal that looks something like:

```
http://localhost:8888/?token=262718512d11cc3efcb1b2878f4jja9uca071924e328d554
```

Just copy and paste this into your browser to open the notebooks.

To restart the `WorkBench` container using the same data volume:

``` shell
docker start -ai Workbench
```
