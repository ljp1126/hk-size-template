<!--
 * @Description: 
 * @Author: lijiapeng
 * @Date: 2022-04-08 10:41:19
 * @LastEditTime: 2022-04-20 12:11:13
 * @LastEditors: lijiapeng
 * @Reference: 
-->

<template>
  <div class="content">
    <div class="top-title">
      <div class="sizeClose">
        <i id="closeDrawer" class="iconfont iconcross-small"></i>
      </div>
      <div class="text">INFANTS & TODDLERS SHOES SIZE CHART (0-4 YEARS)</div>
    </div>
    <div class="type">
      <!-- <div id="left-type" class="left active">尺碼表</div> -->
      <!-- <div id="right-type" class="right">如何測量</div> -->
      <div id="left-type" class="left active">SIZE & FIT</div>
      <div id="right-type" class="right">HOW TO MEASURE</div>
    </div>
    <div class="table-info">
      <div class="size-info" id="sizeInfo">
        <div class="size-content" id="size-content-cm">
          <div class="size-type">
            <div class="size-title">
              <span class="check-type check-active">cm</span>
              <span class="check-type" id="inches-type">Inches</span>
            </div>
            <div class="size-select">
              <div class="select-type">
                <div class="select-numb">
                  <span class="select-show">
                    <span class="show-content" id="show-content-one">EU</span>
                    <img id="down-show-one" src="https://img.adidas.com.hk/resources/images/common/downArrow.png" alt="" srcset="">
                    <img id="up-show-one" style="display: none" src="https://img.adidas.com.hk/resources/images/common/upArrow.png" alt="" srcset="">
                  </span>
                  <div class="size-options" id="size-options-one" style="display: none">
                    <div class="optionsItem" id="eu-code-one">EU</div>
                    <div class="optionsItem" id="us-code-one">US</div>
                    <div class="optionsItem" id="cn-code-one">CN</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class='size-chart' id="eu-code-item-one">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="width: 33%"><span>UK</span></td> 
                  <td style="width: 33%"><span>EU</span></td> 
                  <td style="width: 34%"><span>Heel-toe (cm)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>0K</span></td> 
                  <td><span>16</span></td> 
                  <td><span>8.1</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>1K</span></td> 
                  <td><span>17</span></td> 
                  <td><span>8.9</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>2K</span></td> 
                  <td><span>18</span></td> 
                  <td><span>9.9</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>3K</span></td> 
                  <td><span>19</span></td> 
                  <td><span>10.7</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>4K</span></td> 
                  <td><span>20</span></td> 
                  <td><span>11.4</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>5K</span></td> 
                  <td><span>21</span></td> 
                  <td><span>12.2</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>5.5K</span></td> 
                  <td><span>22</span></td> 
                  <td><span>12.7</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>6K</span></td> 
                  <td><span>23</span></td> 
                  <td><span>13.2</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>6.5K</span></td> 
                  <td><span>23.5</span></td> 
                  <td><span>13.7</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>7K</span></td> 
                  <td><span>24</span></td> 
                  <td><span>14.0</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>7.5K</span></td> 
                  <td><span>25</span></td> 
                  <td><span>14.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>8K</span></td> 
                  <td><span>25.5</span></td> 
                  <td><span>15.0</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>8.5K</span></td> 
                  <td><span>26</span></td> 
                  <td><span>15.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>9K</span></td> 
                  <td><span>26.5</span></td> 
                  <td><span>15.7</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>9.5K</span></td> 
                  <td><span>27</span></td> 
                  <td><span>16.0</span></td> 
                </tr> 
              </tbody> 
            </table>
          </div>
          <div class='size-chart' id="us-code-item-one" style="display:none">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="width: 33%"><span>UK</span></td> 
                  <td style="width: 33%"><span>US</span></td> 
                  <td style="width: 34%"><span>Heel-toe (cm)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>0K</span></td> 
                  <td><span>1K</span></td> 
                  <td><span>8.1</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>1K</span></td> 
                  <td><span>2K</span></td> 
                  <td><span>8.9</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>2K</span></td> 
                  <td><span>3K</span></td> 
                  <td><span>9.9</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>3K</span></td> 
                  <td><span>4K</span></td> 
                  <td><span>10.7</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>4K</span></td> 
                  <td><span>5K</span></td> 
                  <td><span>11.4</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>5K</span></td> 
                  <td><span>5.5K</span></td> 
                  <td><span>12.2</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>5.5K</span></td> 
                  <td><span>6K</span></td> 
                  <td><span>12.7</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>6K</span></td> 
                  <td><span>6.5K</span></td> 
                  <td><span>13.2</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>6.5K</span></td> 
                  <td><span>7K</span></td> 
                  <td><span>13.7</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>7K</span></td> 
                  <td><span>7.5K</span></td> 
                  <td><span>14.0</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>7.5K</span></td> 
                  <td><span>8K</span></td> 
                  <td><span>14.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>8K</span></td> 
                  <td><span>8.5K</span></td> 
                  <td><span>15.0</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>8.5K</span></td> 
                  <td><span>9K</span></td> 
                  <td><span>15.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>9K</span></td> 
                  <td><span>9.5K</span></td> 
                  <td><span>15.7</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>9.5K</span></td> 
                  <td><span>10K</span></td> 
                  <td><span>16.0</span></td> 
                </tr> 
              </tbody>
            </table>
          </div>
          <div class='size-chart' id="cn-code-item-one" style="display:none">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="width: 33%"><span>UK</span></td> 
                  <td style="width: 33%"><span>CN</span></td> 
                  <td style="width: 34%"><span>Heel-toe (cm)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>0K</span></td> 
                  <td><span>80</span></td> 
                  <td><span>8.1</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>1K</span></td> 
                  <td><span>90</span></td> 
                  <td><span>8.9</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>2K</span></td> 
                  <td><span>100</span></td> 
                  <td><span>9.9</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>3K</span></td> 
                  <td><span>105</span></td> 
                  <td><span>10.7</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>4K</span></td> 
                  <td><span>115</span></td> 
                  <td><span>11.4</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>5K</span></td> 
                  <td><span>120</span></td> 
                  <td><span>12.2</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>5.5K</span></td> 
                  <td><span>125</span></td> 
                  <td><span>12.7</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>6K</span></td> 
                  <td><span>130</span></td> 
                  <td><span>13.2</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>6.5K</span></td> 
                  <td><span>135</span></td> 
                  <td><span>13.7</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>7K</span></td> 
                  <td><span>140</span></td> 
                  <td><span>14.0</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>7.5K</span></td> 
                  <td><span>145</span></td> 
                  <td><span>14.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>8K</span></td> 
                  <td><span>150</span></td> 
                  <td><span>15.0</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>8.5K</span></td> 
                  <td><span>150</span></td> 
                  <td><span>15.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>9K</span></td> 
                  <td><span>155</span></td> 
                  <td><span>15.7</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>9.5K</span></td> 
                  <td><span>160</span></td> 
                  <td><span>16.0</span></td> 
                </tr> 
              </tbody>
            </table>
          </div>
        </div>
        <div class="size-content" id="size-content-inches" style="display: none">
          <div class="size-type">
            <div class="size-title">
              <span class="check-type" id="cm-type">cm</span>
              <span class="check-type check-active">Inches</span>
            </div>
            <div class="size-select">
              <div class="select-type">
                <div class="select-numb">
                  <span class="select-show">
                    <span class="show-content" id="show-content-two">EU</span>
                    <img id="down-show-two" src="https://img.adidas.com.hk/resources/images/common/downArrow.png" alt="" srcset="">
                    <img id="up-show-two" style="display: none" src="https://img.adidas.com.hk/resources/images/common/upArrow.png" alt="" srcset="">
                  </span>
                  <div class="size-options" id="size-options-two" style="display: none">
                    <div class="optionsItem" id="eu-code-two">EU</div>
                    <div class="optionsItem" id="us-code-two">US</div>
                    <div class="optionsItem" id="cn-code-two">CN</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class='size-chart' id="eu-code-item-two">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="width: 33%"><span>UK</span></td> 
                  <td style="width: 33%"><span>EU</span></td> 
                  <td style="width: 34%"><span>Heel-toe (inch)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>0K</span></td> 
                  <td><span>16</span></td> 
                  <td><span>3.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>1K</span></td> 
                  <td><span>17</span></td> 
                  <td><span>3.5</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>2K</span></td> 
                  <td><span>18</span></td> 
                  <td><span>3.9</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>3K</span></td> 
                  <td><span>19</span></td> 
                  <td><span>4.2</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>4K</span></td> 
                  <td><span>20</span></td> 
                  <td><span>4.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>5K</span></td> 
                  <td><span>21</span></td> 
                  <td><span>4.8</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>5.5K</span></td> 
                  <td><span>22</span></td> 
                  <td><span>5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>6K</span></td> 
                  <td><span>23</span></td> 
                  <td><span>5.2</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>6.5K</span></td> 
                  <td><span>23.5</span></td> 
                  <td><span>5.4</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>7K</span></td> 
                  <td><span>24</span></td> 
                  <td><span>5.5</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>7.5K</span></td> 
                  <td><span>25</span></td> 
                  <td><span>5.7</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>8K</span></td> 
                  <td><span>25.5</span></td> 
                  <td><span>5.9</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>8.5K</span></td> 
                  <td><span>26</span></td> 
                  <td><span>6</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>9K</span></td> 
                  <td><span>26.5</span></td> 
                  <td><span>6.2</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>9.5K</span></td> 
                  <td><span>27</span></td> 
                  <td><span>6.3</span></td> 
                </tr> 
              </tbody> 
            </table>
          </div>
          <div class='size-chart' id="us-code-item-two" style="display:none">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="width: 33%"><span>UK</span></td> 
                  <td style="width: 33%"><span>US</span></td> 
                  <td style="width: 34%"><span>Heel-toe (inch)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>0K</span></td> 
                  <td><span>1K</span></td> 
                  <td><span>3.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>1K</span></td> 
                  <td><span>2K</span></td> 
                  <td><span>3.5</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>2K</span></td> 
                  <td><span>3K</span></td> 
                  <td><span>3.9</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>3K</span></td> 
                  <td><span>4K</span></td> 
                  <td><span>4.2</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>4K</span></td> 
                  <td><span>5K</span></td> 
                  <td><span>4.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>5K</span></td> 
                  <td><span>5.5K</span></td> 
                  <td><span>4.8</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>5.5K</span></td> 
                  <td><span>6K</span></td> 
                  <td><span>5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>6K</span></td> 
                  <td><span>6.5K</span></td> 
                  <td><span>5.2</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>6.5K</span></td> 
                  <td><span>7K</span></td> 
                  <td><span>5.4</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>7K</span></td> 
                  <td><span>7.5K</span></td> 
                  <td><span>5.5</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>7.5K</span></td> 
                  <td><span>8K</span></td> 
                  <td><span>5.7</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>8K</span></td> 
                  <td><span>8.5K</span></td> 
                  <td><span>5.9</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>8.5K</span></td> 
                  <td><span>9K</span></td> 
                  <td><span>6</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>9K</span></td> 
                  <td><span>9.5K</span></td> 
                  <td><span>6.2</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>9.5K</span></td> 
                  <td><span>10K</span></td> 
                  <td><span>6.3</span></td> 
                </tr> 
              </tbody>
            </table>
          </div>
          <div class='size-chart' id="cn-code-item-two" style="display:none">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="width: 33%"><span>UK</span></td> 
                  <td style="width: 33%"><span>CN</span></td> 
                  <td style="width: 34%"><span>Heel-toe (inch)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>0K</span></td> 
                  <td><span>80</span></td> 
                  <td><span>3.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>1K</span></td> 
                  <td><span>90</span></td> 
                  <td><span>3.5</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>2K</span></td> 
                  <td><span>100</span></td> 
                  <td><span>3.9</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>3K</span></td> 
                  <td><span>105</span></td> 
                  <td><span>4.2</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>4K</span></td> 
                  <td><span>115</span></td> 
                  <td><span>4.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>5K</span></td> 
                  <td><span>120</span></td> 
                  <td><span>4.8</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>5.5K</span></td> 
                  <td><span>125</span></td> 
                  <td><span>5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>6K</span></td> 
                  <td><span>130</span></td> 
                  <td><span>5.2</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>6.5K</span></td> 
                  <td><span>135</span></td> 
                  <td><span>5.4</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>7K</span></td> 
                  <td><span>140</span></td> 
                  <td><span>5.5</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>7.5K</span></td> 
                  <td><span>145</span></td> 
                  <td><span>5.7</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>8K</span></td> 
                  <td><span>150</span></td> 
                  <td><span>5.9</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>8.5K</span></td> 
                  <td><span>150</span></td> 
                  <td><span>6</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>9K</span></td> 
                  <td><span>155</span></td> 
                  <td><span>6.2</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>9.5K</span></td> 
                  <td><span>160</span></td> 
                  <td><span>6.3</span></td> 
                </tr> 
              </tbody>
            </table>
          </div>
        </div>

      </div>
      <div class="size-measure" id="measure">
        <div class="measure">
          <div class="img-info">
            <div class="instructions">
              <div class="steps-type">
                <ul class="steps">
                  <li class="step">
                    <span class="step-title">1. </span>
                    <span class="step-body">Step on а piece of paper with your heel slightly touching a wall behind.</span>
                  </li>
                  <li class="step">
                    <span class="step-title">2. </span>
                    <span class="step-body">Мark the end of your longest toe on the paper (you might need a friend to help you) and measure from the wall to the marking.</span>
                  </li>
                  <li class="step">
                    <span class="step-title">3. </span>
                    <span class="step-body">Do the same for the other foot and compare measurements with our size chart to get the right size.</span>
                  </li>
                </ul>
              </div>
            </div>
            <div class="image-container">
              <img src="https://img.adidas.com.hk/resources/images/size/measure-shoes.png" alt="" srcset="">
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>