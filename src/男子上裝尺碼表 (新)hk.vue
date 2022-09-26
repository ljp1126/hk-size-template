<!--
 * @Description: 男子上装尺码表 hk
 * @Author: lijiapeng
 * @Date: 2022-09-26 10:28:39
 * @LastEditTime: 2022-09-26 13:44:55
 * @LastEditors: lijiapeng
 * @Reference: 
-->

<template>

  <div class="content">
    <div class="top-title">
      <div class="sizeClose">
        <i id="closeDrawer" class="iconfont iconcross-small"></i>
      </div>
      <div class="text">男子上裝尺碼表 (新)</div>
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
                  <td style="width: 36%" colspan="2"><span>國際尺碼</span></td>
                  <td><span>胸圍 (厘米)</span></td>
                  <td><span>腰圍 (厘米)</span></td>
                  <td><span>臀圍 (厘米)</span></td>
                </tr>
                <tr class="">
                  <td><span>2XS </span></td>
                  <td><span>40</span></td>
                  <td><span>81- 83</span></td>
                  <td><span>69 -71</span></td>
                  <td><span>80 - 82</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>XS</span></td>
                  <td><span>42</span></td>
                  <td><span>84 - 86</span></td>
                  <td><span>72 - 74</span></td>
                  <td><span>83 - 85</span></td>
                </tr>
                <tr class="">
                  <td><span>S</span></td>
                  <td><span>46</span></td>
                  <td><span>87 - 92</span></td>
                  <td><span>75 - 80</span></td>
                  <td><span>86 - 91</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>M</span></td>
                  <td><span>48</span></td>
                  <td><span>93 - 96</span></td>
                  <td><span>81 - 84</span></td>
                  <td><span>92 - 95</span></td>
                </tr>
                <tr class="">
                  <td><span>L</span></td>
                  <td><span>50</span></td>
                  <td><span>97 - 100</span></td>
                  <td><span>85 - 88</span></td>
                  <td><span>96 - 99</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>XL</span></td>
                  <td><span>54</span></td>
                  <td><span>101 - 108</span></td>
                  <td><span>89 - 96</span></td>
                  <td><span>100 - 107</span></td>
                </tr>
                <tr class="">
                  <td><span>2XL</span></td>
                  <td><span>56</span></td>
                  <td><span>109 - 113</span></td>
                  <td><span>97 - 101</span></td>
                  <td><span>108 - 111</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>3XL</span></td>
                  <td><span>58</span></td>
                  <td><span>114 - 118</span></td>
                  <td><span>102 - 106</span></td>
                  <td><span>112 - 116</span></td>
                </tr>
                <tr class="">
                  <td><span>4XL</span></td>
                  <td><span>60</span></td>
                  <td><span>119 - 124</span></td>
                  <td><span>107 - 112</span></td>
                  <td><span>117 - 120</span></td>
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
                  <td><span>A/2XS </span></td>
                  <td><span>A36</span></td>
                  <td><span>81 - 82.5 </span></td>
                  <td><span>67 - 68.5</span></td>
                  <td><span>81.5</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>A/XS</span></td>
                  <td><span>A38</span></td>
                  <td><span>83.5 - 85</span></td>
                  <td><span>69.5 - 71</span></td>
                  <td><span>82.5 - 84</span></td>
                </tr>
                <tr class="">
                  <td ><span>A/S</span></td>
                  <td><span>A42</span></td>
                  <td><span>86 - 90</span></td>
                  <td><span>72 - 76</span></td>
                  <td><span>85 - 89</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>A/M</span></td>
                  <td><span>A46</span></td>
                  <td><span>91 - 95</span></td>
                  <td><span>77 - 81</span></td>
                  <td><span>90 - 94</span></td>
                </tr>
                <tr class="">
                  <td><span>A/L</span></td>
                  <td><span>A50</span></td>
                  <td><span>96 - 100</span></td>
                  <td><span>82 - 86</span></td>
                  <td><span>95 - 99</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>A/XL</span></td>
                  <td><span>A54</span></td>
                  <td><span>101 - 106</span></td>
                  <td><span>87 - 93</span></td>
                  <td><span>100 - 105</span></td>
                </tr>
                <tr class="">
                  <td><span>A/2XL</span></td>
                  <td><span>A58</span></td>
                  <td><span>107 - 112</span></td>
                  <td><span>94 - 100</span></td>
                  <td><span>106 - 111</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>A/3XL</span></td>
                  <td><span>A62</span></td>
                  <td><span>113 - 119</span></td>
                  <td><span>101 - 108</span></td>
                  <td><span>112 - 118</span></td>
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

      