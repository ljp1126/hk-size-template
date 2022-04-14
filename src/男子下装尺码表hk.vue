<!--
 * @Description: 男子下装尺码表
 * @Author: lijiapeng
 * @Date: 2022-04-02 14:56:47
 * @LastEditTime: 2022-04-14 12:16:04
 * @LastEditors: lijiapeng
 * @Reference: 
-->

<template>
  <div class="content">
    <div class="top-title">
      <div class="sizeClose">
        <i id="closeDrawer" class="iconfont iconcross-small"></i>
      </div>
      <div class="text">男子下裝尺碼表</div>
    </div>
    <div class="type">
      <div id="left-type" class="left active">尺碼表</div>
      <div id="right-type" class="right">如何測量</div>
      <!-- <div id="left-type" class="left active">SIZE & FIT</div> -->
      <!-- <div id="right-type" class="right">How to Measure</div> -->
    </div>


    <div class="table-info">
      <div class="size-info" id="sizeInfo">
        <div class="size-content">
          <div class="size-type">
            <div class="size-title">
              <span class="text-small">長褲</span>
            </div>
            <div class="size-select">
              <div class="select-type">
                <div class="select-numb">
                  <span class="select-show">
                    <span class="show-content" id="show-content-one">國際碼</span>
                    <img id="down-show-one" src="https://img.adidas.com.hk/resources/images/common/downArrow.png" alt="" srcset="">
                    <img id="up-show-one" style="display: none" src="https://img.adidas.com.hk/resources/images/common/upArrow.png" alt="" srcset="">
                  </span>
                  <div class="size-options" id="size-options-one" style="display: none">
                    <div class="optionsItem" id="inter-code-one">國際碼</div>
                    <div class="optionsItem" id="asian-code-one">亞洲碼</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class='size-chart' id="inter-code-item-one">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td colspan="3"><span>國際碼</span></td> 
                  <td><span>腰圍 (厘米)</span></td> 
                  <td><span>臀圍 (厘米)</span></td> 
                  <td><span>內長 (厘米)</span></td> 
                </tr> 
                <tr class=""> 
                  <td rowspan="2"><span> XS</span></td> 
                  <td><span> 28"</span></td> 
                  <td><span> 2832</span></td> 
                  <td rowspan="2"><span>69 - 74</span></td> 
                  <td rowspan="2"><span>81 - 86</span></td> 
                  <td rowspan="2"><span>81</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>29"</span></td> 
                  <td><span>2932</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td rowspan="3"><span>S</span></td> 
                  <td><span>30"</span></td> 
                  <td><span>3032</span></td> 
                  <td rowspan="3"><span>76 - 81</span></td> 
                  <td rowspan="3"><span>89 - 94</span></td> 
                  <td rowspan="3"><span>82</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>31"</span></td> 
                  <td><span>3132</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>32"</span></td> 
                  <td><span>3232</span></td> 
                </tr>

                <tr class=""> 
                  <td rowspan="2"><span>M</span></td> 
                  <td><span>33"</span></td> 
                  <td><span>3332</span></td> 
                  <td rowspan="2"><span>81 - 89</span></td> 
                  <td rowspan="2"><span>94 - 102</span></td> 
                  <td rowspan="2"><span>82</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>34"</span></td> 
                  <td><span>3432</span></td> 
                </tr>

                <tr class="tr-color"> 
                  <td rowspan="3"><span>L</span></td> 
                  <td><span>35"</span></td> 
                  <td><span>3532</span></td> 
                  <td rowspan="3"><span>89 - 99</span></td> 
                  <td rowspan="3"><span>102 - 112</span></td> 
                  <td rowspan="3"><span>83</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>36"</span></td> 
                  <td><span>3632</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>38"</span></td> 
                  <td><span>3832</span></td> 
                </tr> 

                <tr class=""> 
                  <td rowspan="2"><span>XL</span></td> 
                  <td><span>40"</span></td> 
                  <td><span> -</span></td> 
                  <td rowspan="2"><span>99 - 107</span></td> 
                  <td rowspan="2"><span>112 - 122</span></td> 
                  <td rowspan="2"><span>83</span></td> 
                </tr> 
                <tr class="r"> 
                  <td><span>42"</span></td> 
                  <td><span> -</span></td> 
                </tr>

                <tr class="tr-color"> 
                  <td rowspan="2"><span>2XL</span></td> 
                  <td><span>44"</span></td> 
                  <td><span> -</span></td> 
                  <td rowspan="2"><span>109 - 119</span></td> 
                  <td rowspan="2"><span>122 - 130</span></td> 
                  <td rowspan="2"><span>83</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>46"</span></td> 
                  <td><span> -</span></td> 
                </tr>
              </tbody> 
            </table>
          </div>
          <div class='size-chart' id="asian-code-item-one" style="display:none">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td><span>亞洲碼</span></td> 
                  <td><span>腰圍 (厘米)</span></td> 
                  <td><span>臀圍 (厘米)</span></td> 
                  <td><span>內長 (厘米)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>A/XS</span></td> 
                  <td><span>69 - 74</span></td> 
                  <td><span>81 - 86</span></td> 
                  <td><span>81</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>A/S</span></td> 
                  <td><span>76 - 81</span></td> 
                  <td><span>89 - 94</span></td> 
                  <td><span>82</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>A/M</span></td> 
                  <td><span>81 - 89</span></td> 
                  <td><span>94 - 102</span></td> 
                  <td><span>82</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>A/L</span></td> 
                  <td><span>89 - 99</span></td> 
                  <td><span>102 - 112</span></td> 
                  <td><span>83</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>A/XL</span></td> 
                  <td><span>99 - 107</span></td> 
                  <td><span>112 - 122</span></td> 
                  <td><span>83</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>A2XL</span></td> 
                  <td><span>109 - 119</span></td> 
                  <td><span>122 - 130</span></td> 
                  <td><span>83</span></td> 
                </tr> 
              </tbody> 
            </table>
          </div>
        </div>
        <div class="size-content">
          <div class="size-type">
            <div class="size-title">
              <span class="text-small">短褲（5''內長）</span>
            </div>
            <div class="size-select">
              <div class="select-type">
                <div class="select-numb">
                  <span class="select-show">
                    <span class="show-content" id="show-content-two">國際碼</span>
                    <img id="down-show-two" src="https://img.adidas.com.hk/resources/images/common/downArrow.png" alt="" srcset="">
                    <img id="up-show-two" style="display: none" src="https://img.adidas.com.hk/resources/images/common/upArrow.png" alt="" srcset="">
                  </span>
                  <div class="size-options" id="size-options-two" style="display: none">
                    <div class="optionsItem" id="inter-code-two">國際碼</div>
                    <div class="optionsItem" id="asian-code-two">亞洲碼</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class='size-chart' id="inter-code-item-two">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td><span>國際碼</span></td> 
                  <td><span>腰圍 (厘米)</span></td> 
                  <td><span>臀圍 (厘米)</span></td> 
                  <td><span>內長 (厘米)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span> XS</span></td> 
                  <td><span>69 - 74</span></td> 
                  <td><span>81 - 86</span></td> 
                  <td><span>12.7</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>S</span></td> 
                  <td><span>76 - 81</span></td> 
                  <td><span>89 - 94</span></td> 
                  <td><span>12.7</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span> M</span></td> 
                  <td><span>81 - 89</span></td> 
                  <td><span>94 - 102</span></td> 
                  <td><span>12.7</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>L</span></td> 
                  <td><span>89 - 99</span></td> 
                  <td><span>102 - 112</span></td> 
                  <td><span>12.7</span></td> 
                </tr>

                <tr class=""> 
                  <td><span> XL</span></td> 
                  <td><span>99 - 107</span></td> 
                  <td><span>112 - 122</span></td> 
                  <td><span>12.7</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>2XL</span></td> 
                  <td><span>109 - 119</span></td> 
                  <td><span>122 - 130</span></td> 
                  <td><span>12.7</span></td> 
                </tr>
              </tbody> 
            </table>
          </div>
          <div class='size-chart' id="asian-code-item-two" style="display:none">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td><span>亞洲碼</span></td> 
                  <td><span>腰圍 (厘米)</span></td> 
                  <td><span>臀圍 (厘米)</span></td> 
                  <td><span>內長 (厘米)</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>AXS5"</span></td> 
                  <td><span>69 - 74</span></td> 
                  <td><span>81 - 86</span></td> 
                  <td><span>12.7</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>A/S5"</span></td> 
                  <td><span>76 - 81</span></td> 
                  <td><span>89 - 94</span></td> 
                  <td><span>12.7</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>A/M5"</span></td> 
                  <td><span>81 - 89</span></td> 
                  <td><span>94 - 102</span></td> 
                  <td><span>12.7</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>A/L5"</span></td> 
                  <td><span>89 - 99</span></td> 
                  <td><span>102 - 112</span></td> 
                  <td><span>12.7</span></td> 
                </tr>

                <tr class=""> 
                  <td><span>AXL5"</span></td> 
                  <td><span>99 - 107</span></td> 
                  <td><span>112 - 122</span></td> 
                  <td><span>12.7</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>A2XL5</span></td> 
                  <td><span>109 - 119</span></td> 
                  <td><span>122 - 130</span></td> 
                  <td><span>12.7</span></td> 
                </tr> 
              </tbody> 
            </table>
          </div>
        </div>
        <div class="size-content">
          <div class="size-type">
            <div class="size-title">
              <span class="text-small">短褲（7''內長）</span>
            </div>
            <div class="size-select">
              <div class="select-type">
                <div class="select-numb">
                  <span class="select-show">
                    <span class="show-content" id="show-content-three">國際碼</span>
                    <img id="down-show-three" src="https://img.adidas.com.hk/resources/images/common/downArrow.png" alt="" srcset="">
                    <img id="up-show-three" style="display: none" src="https://img.adidas.com.hk/resources/images/common/upArrow.png" alt="" srcset="">
                  </span>
                  <div class="size-options" id="size-options-three" style="display: none">
                    <div class="optionsItem" id="inter-code-three">國際碼</div>
                    <div class="optionsItem" id="asian-code-three">亞洲碼</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class='size-chart' id="inter-code-item-three">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td><span>國際碼</span></td> 
                  <td><span>腰圍 (厘米)</span></td> 
                  <td><span>臀圍 (厘米)</span></td> 
                  <td><span>內長 (厘米)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span> XS</span></td> 
                  <td><span>69 - 74</span></td> 
                  <td><span>81 - 86</span></td> 
                  <td><span>17.8</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>S</span></td> 
                  <td><span>76 - 81</span></td> 
                  <td><span>89 - 94</span></td> 
                  <td><span>17.8</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span> M</span></td> 
                  <td><span>81 - 89</span></td> 
                  <td><span>94 - 102</span></td> 
                  <td><span>17.8</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>L</span></td> 
                  <td><span>89 - 99</span></td> 
                  <td><span>102 - 112</span></td> 
                  <td><span>17.8</span></td> 
                </tr>

                <tr class=""> 
                  <td><span> XL</span></td> 
                  <td><span>99 - 107</span></td> 
                  <td><span>112 - 122</span></td> 
                  <td><span>17.8</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>2XL</span></td> 
                  <td><span>109 - 119</span></td> 
                  <td><span>122 - 130</span></td> 
                  <td><span>17.8</span></td> 
                </tr>
              </tbody> 
            </table>
          </div>
          <div class='size-chart' id="asian-code-item-three" style="display:none">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td><span>亞洲碼(A)</span></td> 
                  <td><span>腰圍 (厘米)</span></td> 
                  <td><span>臀圍 (厘米)</span></td> 
                  <td><span>內長 (厘米)</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>AXS5"</span></td> 
                  <td><span>69 - 74</span></td> 
                  <td><span>81 - 86</span></td> 
                  <td><span>17.8</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>A/S5"</span></td> 
                  <td><span>76 - 81</span></td> 
                  <td><span>89 - 94</span></td> 
                  <td><span>17.8</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>A/M5"</span></td> 
                  <td><span>81 - 89</span></td> 
                  <td><span>94 - 102</span></td> 
                  <td><span>17.8</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>A/L5"</span></td> 
                  <td><span>89 - 99</span></td> 
                  <td><span>102 - 112</span></td> 
                  <td><span>17.8</span></td> 
                </tr>

                <tr class=""> 
                  <td><span>AXL5"</span></td> 
                  <td><span>99 - 107</span></td> 
                  <td><span>112 - 122</span></td> 
                  <td><span>17.8</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>A2XL5</span></td> 
                  <td><span>109 - 119</span></td> 
                  <td><span>122 - 130</span></td> 
                  <td><span>17.8</span></td> 
                </tr> 
              </tbody> 
            </table>
          </div>
        </div>
        <div class="tips">
          <div class="tips-title">測量建議：</div>
          <div class="tips-content">請注意，尺碼表指的是自己的尺寸，而不是衣服本身。</div>
          <div class="tips-content">如果你的尺碼在兩個尺碼之間，穿緊一點的，請訂小一號；穿寬鬆一點的，請訂大一號。</div>
        </div>
      </div>
      <div class="size-measure" id="measure">
        <div class="measure">
          <div class="img-info">
            <div class="instructions">
              <div class="steps-type">
                <p class="tipinfo">水平握住捲尺進行測量：</p>
                <ul class="steps">
                  <li class="step">
                    <span class="step-title">1. 胸部，</span>
                    <span class="step-body">圍繞最寬處</span>
                  </li>
                  <li class="step">
                    <span class="step-title">2. 腰圍，</span>
                    <span class="step-body">圍繞最窄處</span>
                  </li>
                  <li class="step">
                    <span class="step-title">3. 臀部，</span>
                    <span class="step-body">圍繞最寬處，保持雙腳併攏</span>
                  </li>
                </ul>
              </div>
              <div class="steps-type">
                <p class="tipinfo">垂直握住捲尺進行測量：</p>
                <ul class="steps">
                  <li class="step">
                    <span class="step-title">4. 內接縫，</span>
                    <span class="step-body">從胯部到地板</span>
                  </li>
                  <li class="step">
                    <span class="step-title">5. 高度，</span>
                    <span class="step-body">從頭頂到地板，保持筆直的姿勢</span>
                  </li>
                </ul>
              </div>
            </div>
            <div class="image-container">
              <img src="https://img.adidas.com.hk/resources/images/size/measure-men.png" alt="" srcset="">
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
