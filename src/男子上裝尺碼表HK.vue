<!--
 * @Description: 男子上装尺码表 hk
 * @Author: lijiapeng
 * @Date: 2022-04-02 10:28:39
 * @LastEditTime: 2022-05-05 09:25:35
 * @LastEditors: lijiapeng
 * @Reference: 
-->

<template>

  <div class="content">
    <div class="top-title">
      <div class="sizeClose">
        <i id="closeDrawer" class="iconfont iconcross-small"></i>
      </div>
      <div class="text">男子上裝尺碼表</div>
    </div>
    <div class="type">
      <div id="left-type" class="left active">尺碼表</div>
      <div id="right-type" class="right">如何測量</div>
    </div>
    <div class="table-info">
      <div class="size-info" id="sizeInfo">
        <div class="size-content">
          <div class="size-type">
            <div class="size-title">
              <span class="text-small"></span>
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
                  <td style="width: 36%" colspan="3"><span>國際尺碼</span></td> 
                  <td><span>胸圍 (厘米)</span></td> 
                  <td><span>腰圍 (厘米)</span></td> 
                  <td><span>臀圍 (厘米)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>-</span></td> 
                  <td><span>-</span></td> 
                  <td><span>-</span></td> 
                  <td><span>58</span></td> 
                  <td><span>60</span></td> 
                  <td><span>62</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td rowspan="2"><span>XS</span></td> 
                  <td rowspan="2"><span>44</span></td> 
                  <td><span> 30/32</span></td> 
                  <td rowspan="2"><span>79 - 84</span></td> 
                  <td rowspan="2"><span>69 - 74 </span></td> 
                  <td rowspan="2"><span> 81 - 86</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span> 32/34</span></td> 
                </tr> 

                <tr class=""> 
                  <td rowspan="2"><span>S</span></td> 
                  <td><span>46</span></td> 
                  <td><span>34/36</span></td> 
                  <td rowspan="2"><span>86 - 94</span></td> 
                  <td rowspan="2"><span>76 - 81 </span></td> 
                  <td rowspan="2"><span>89 - 94</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>48</span></td> 
                  <td><span>36/38</span></td> 
                </tr> 

                <tr class="tr-color"> 
                  <td rowspan="3"><span>M</span></td> 
                  <td rowspan="2"><span>50</span></td> 
                  <td><span>38/40</span></td> 
                  <td rowspan="3"><span>94 - 102</span></td> 
                  <td rowspan="3"><span>81 - 89</span></td> 
                  <td rowspan="3"><span>94 - 102</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>40/42</span></td> 
                </tr> 

                <tr class="tr-color"> 
                  <td><span>52</span></td> 
                  <td><span>40/42</span></td> 
                </tr>

                <tr class=""> 
                  <td rowspan="2"><span>L</span></td> 
                  <td><span>54</span></td> 
                  <td><span>42/44</span></td> 
                  <td rowspan="2"><span>102 - 112</span></td> 
                  <td rowspan="2"><span>89 - 99</span></td> 
                  <td rowspan="2"><span>102 - 112</span></td> 
                </tr> 
                <tr class="r"> 
                  <td><span>56</span></td> 
                  <td><span>44/46</span></td> 
                </tr>

                <tr class="tr-color"> 
                  <td rowspan="2"><span>XL</span></td> 
                  <td><span>58</span></td> 
                  <td><span>46/48</span></td> 
                  <td rowspan="2"><span>112 - 122</span></td> 
                  <td rowspan="2"><span>99 - 109</span></td> 
                  <td rowspan="2"><span>112 - 122</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>60</span></td> 
                  <td><span>48/50</span></td> 
                </tr> 

                <tr class=""> 
                  <td rowspan="2"><span>2XL</span></td> 
                  <td><span>62</span></td> 
                  <td><span>50/52</span></td> 
                  <td rowspan="2"><span>122 - 13</span></td> 
                  <td rowspan="2"><span>109 - 119</span></td> 
                  <td rowspan="2"><span>122 - 130</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>64</span></td> 
                  <td><span>52/54</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td rowspan="2"><span> 3XL </span></td> 
                  <td><span>66</span></td> 
                  <td><span> 54/56</span></td> 
                  <td rowspan="2"><span>135 - 147</span></td> 
                  <td rowspan="2"><span>122 - 135 </span></td> 
                  <td rowspan="2"><span>130 - 142</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>68</span></td> 
                  <td><span>56/58 </span></td> 
                </tr> 
              
              </tbody> 
            </table>
          </div>
          <div class='size-chart' id="asian-code-item-one" style="display:none">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="width: 36%" colspan="2"><span>亞洲尺碼</span></td> 
                  <td><span>胸圍 (厘米)</span></td> 
                  <td><span>腰圍 (厘米)</span></td> 
                  <td><span>臀圍 (厘米)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>-</span></td> 
                  <td><span>A/2XS </span></td> 
                  <td><span>74 - 76 </span></td> 
                  <td><span>64 - 66</span></td> 
                  <td><span> 76 - 79</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>A38 </span></td> 
                  <td rowspan="2"><span>A/XS</span></td> 
                  <td rowspan="2"><span>79 - 84</span></td> 
                  <td rowspan="2"><span>69 - 74</span></td> 
                  <td rowspan="2"><span>81 - 86</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span> A40</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>A42</span></td> 
                  <td rowspan="2"><span>A/S</span></td> 
                  <td rowspan="4"><span>86 - 94</span></td> 
                  <td rowspan="4"><span>76 - 81</span></td> 
                  <td rowspan="4"><span>89 - 94 </span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>A44</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>A46</span></td> 
                  <td rowspan="2"><span>A/M</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>A48</span></td> 
                </tr> 

                <tr class="tr-color"> 
                  <td><span>A50</span></td> 
                  <td rowspan="2"><span>A/L</span></td> 
                  <td rowspan="4"><span>94 - 102</span></td> 
                  <td rowspan="4"><span>81 - 89</span></td> 
                  <td rowspan="4"><span>94 - 102</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>A52</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>A54</span></td> 
                  <td rowspan="2"><span>A/XL</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>A56</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>A58</span></td> 
                  <td rowspan="2"><span>A/2XL</span></td> 
                  <td rowspan="4"><span>102 - 112</span></td> 
                  <td rowspan="4"><span>89 - 99</span></td> 
                  <td rowspan="4"><span>102 - 112</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>A60</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>A62</span></td> 
                  <td rowspan="2"><span>A/3XL</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>A64</span></td> 
                </tr>

                <tr class="tr-color"> 
                  <td><span> -</span></td> 
                  <td><span> -</span></td> 
                  <td rowspan="2"><span>112 - 122</span></td> 
                  <td rowspan="2"><span>99 - 109</span></td> 
                  <td rowspan="2"><span>112 - 122 </span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span> -</span></td> 
                  <td><span> -</span></td> 
                </tr>  

                <tr class=""> 
                  <td><span> -</span></td> 
                  <td><span> -</span></td> 
                  <td rowspan="2"><span>122 - 132</span></td> 
                  <td rowspan="2"><span>109 - 119</span></td> 
                  <td rowspan="2"><span>122 - 130</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span> -</span></td> 
                  <td><span> -</span></td> 
                </tr> 

                <tr class="tr-color"> 
                  <td><span> -</span></td> 
                  <td><span> -</span></td> 
                  <td rowspan="2"><span>135 - 147</span></td> 
                  <td rowspan="2"><span>122 - 135</span></td> 
                  <td rowspan="2"><span>130 - 142</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span> -</span></td> 
                  <td><span> -</span></td> 
                </tr> 

              
              </tbody> 
            </table>
          </div>
          <div class="tips">
            <div class="tips-title">測量建議：</div>
            <div class="tips-content">請注意，尺碼表指的是自己的尺寸，而不是衣服本身。</div>
            <div class="tips-content">如果你的尺碼在兩個尺碼之間，穿緊一點的，請訂小一號；穿寬鬆一點的，請訂大一號。</div>
          </div>
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
                    <span class="step-title">4. 內長，</span>
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

      