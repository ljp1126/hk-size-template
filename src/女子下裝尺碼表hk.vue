<!--
 * @Description: 
 * @Author: lijiapeng
 * @Date: 2022-04-07 17:07:37
 * @LastEditTime: 2022-09-21 16:05:24
 * @LastEditors: lijiapeng
 * @Reference: 
-->

<template>

  <div class="content">
    <div class="top-title">
      <div class="sizeClose">
        <i id="closeDrawer" class="iconfont iconcross-small"></i>
      </div>
      <div class="text">女子下裝尺碼表</div>
    </div>
    <div class="type">
      <div id="left-type" class="left active">尺碼表</div>
      <div id="right-type" class="right">如何測量</div>
      <!-- <div id="left-type" class="left active">SIZE & FIT</div> -->
      <!-- <div id="right-type" class="right">HOW TO MEASURE</div> -->
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
                    <div class="optionsItem" id="japan-code-one">日本碼</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class='size-chart' id="inter-code-item-one">
            <table>
              <tbody>
                <tr class="tr-color tr-title">
                  <td style="width: 38%" colspan="3"><span>國際碼</span></td>
                  <td><span>腰圍 (厘米)</span></td>
                  <td><span>臀圍 (厘米)</span></td>
                  <td><span>內長 (厘米)</span></td>
                </tr>
                <tr class="">
                  <td><span>XXS</span></td>
                  <td><span>-</span></td>
                  <td><span>30</span></td>
                  <td><span>58 - 62</span></td>
                  <td><span>83 - 86</span></td>
                  <td><span>76</span></td>
                </tr>
                <tr class="tr-color">
                  <td rowspan="2"><span>XS</span></td>
                  <td><span>0</span></td>
                  <td><span>32</span></td>
                  <td rowspan="2"><span>64 - 69</span></td>
                  <td rowspan="2"><span>88 - 93</span></td>
                  <td rowspan="2"><span>77</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>2</span></td>
                  <td><span>34</span></td>
                </tr>
                <tr class="">
                  <td rowspan="2"><span>S</span></td>
                  <td><span>4</span></td>
                  <td><span>36</span></td>
                  <td rowspan="2"><span>70 - 75</span></td>
                  <td rowspan="2"><span>94 - 99</span></td>
                  <td rowspan="2"><span>77</span></td>
                </tr>
                <tr class="">
                  <td><span>6</span></td>
                  <td><span>38</span></td>
                </tr>
                <tr class="tr-color">
                  <td rowspan="2"><span>M</span></td>
                  <td><span>8</span></td>
                  <td><span>40</span></td>
                  <td rowspan="2"><span>76 - 83</span></td>
                  <td rowspan="2"><span>100 - 105</span></td>
                  <td rowspan="2"><span>79</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>10</span></td>
                  <td><span>42</span></td>
                </tr>
                <tr class="">
                  <td rowspan="2"><span>L</span></td>
                  <td><span>12</span></td>
                  <td><span>44</span></td>
                  <td rowspan="2"><span>84 - 90</span></td>
                  <td rowspan="2"><span>107 - 113</span></td>
                  <td rowspan="2"><span>80</span></td>
                </tr>
                <tr class="">
                  <td><span>14</span></td>
                  <td><span>46</span></td>
                </tr>
                <tr class="tr-color">
                  <td rowspan="2"><span>XL</span></td>
                  <td><span>16</span></td>
                  <td><span>48</span></td>
                  <td rowspan="2"><span>91 - 98</span></td>
                  <td rowspan="2"><span>114 - 121</span></td>
                  <td rowspan="2"><span>80</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>18</span></td>
                  <td><span>50</span></td>
                </tr>
                <tr class="">
                  <td rowspan="2"><span2>XL</span2></td>
                  <td><span>20</span></td>
                  <td rowspan="2"><span>52</span></td>
                  <td rowspan="2"><span>99 - 105</span></td>
                  <td rowspan="2"><span>122 - 128</span></td>
                  <td rowspan="2"><span>81</span></td>
                </tr>
                <tr class="">
                  <td><span>22</span></td>
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
                  <td><span>A/2XS</span></td>
                  <td><span>59 - 61</span></td>
                  <td><span>79 - 82</span></td>
                  <td><span>73.5</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>A/XS</span></td>
                  <td><span>62 - 64</span></td>
                  <td><span>83 - 86</span></td>
                  <td><span>74</span></td>
                </tr>
                <tr class="">
                  <td><span>A/S</span></td>
                  <td><span>65 - 68</span></td>
                  <td><span>87 - 90</span></td>
                  <td><span>74.5</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>A/M</span></td>
                  <td><span>69 - 72</span></td>
                  <td><span>91 - 94</span></td>
                  <td><span>75</span></td>
                </tr>
                <tr class="">
                  <td><span>A/L</span></td>
                  <td><span>73 - 78</span></td>
                  <td><span>95 - 100</span></td>
                  <td><span>75.5</span></td>
                </tr>

                <tr class="tr-color">
                  <td><span>A/XL</span></td>
                  <td><span>79 - 86</span></td>
                  <td><span>101 - 106</span></td>
                  <td><span>76</span></td>
                </tr>
                <tr class="">
                  <td><span>A/2XL</span></td>
                  <td><span>87 - 94</span></td>
                  <td><span>107 - 112</span></td>
                  <td><span>76.5</span></td>
                </tr>

              </tbody>
            </table>
          </div>
          <div class='size-chart' id="japan-code-item-one" style="display:none">
            <table>
              <tbody>
                <tr class="tr-color tr-title">
                  <td><span>日本碼 (J)</span></td>
                  <td><span>腰圍 (厘米)</span></td>
                  <td><span>内長(厘米)</span></td>
                </tr>
                <tr class="">
                  <td><span>J/XS</span></td>
                  <td><span>54</span></td>
                  <td><span>65.1</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>J/S</span></td>
                  <td><span>57</span></td>
                  <td><span>66.6</span></td>
                </tr>
                <tr class="">
                  <td><span>J/M</span></td>
                  <td><span>60</span></td>
                  <td><span>68.1</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>J/L</span></td>
                  <td><span>63</span></td>
                  <td><span>69.6</span></td>
                </tr>
                <tr class="">
                  <td><span>J/OT</span></td>
                  <td><span>66</span></td>
                  <td><span>71.1</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>J/XOT</span></td>
                  <td><span>69</span></td>
                  <td><span>72.6</span></td>
                </tr>
                <tr class="">
                  <td><span>J/2XOT</span></td>
                  <td><span>72</span></td>
                  <td><span>74.1</span></td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
        <div class="size-content">
          <div class="size-type">
            <div class="size-title">
              <span class="text-small">短褲（2''內長）</span>
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
                  <td><span>XS</span></td>
                  <td><span>64 - 69</span></td>
                  <td><span>88 - 93</span></td>
                  <td><span>5.1</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>S</span></td>
                  <td><span>70 - 75</span></td>
                  <td><span>94 - 99</span></td>
                  <td><span>5.1</span></td>
                </tr>
                <tr class="">
                  <td><span>M</span></td>
                  <td><span>76 - 83</span></td>
                  <td><span>100 - 105</span></td>
                  <td><span>5.1</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>L</span></td>
                  <td><span>84 - 90</span></td>
                  <td><span>107 - 113</span></td>
                  <td><span>5.1</span></td>
                </tr>
                <tr class="">
                  <td><span>XL</span></td>
                  <td><span>91 - 98</span></td>
                  <td><span>114 - 121</span></td>
                  <td><span>5.1</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>2XL</span></td>
                  <td><span>99 - 105</span></td>
                  <td><span>122 - 128</span></td>
                  <td><span>5.1</span></td>
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
                  <td><span>A/2XS2"</span></td>
                  <td><span>59 - 61</span></td>
                  <td><span>79 - 82</span></td>
                  <td><span>5.1</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>A/XS2"</span></td>
                  <td><span>62 - 64</span></td>
                  <td><span>83 - 86</span></td>
                  <td><span>5.1</span></td>
                </tr>
                <tr class="">
                  <td><span>A/S2"</span></td>
                  <td><span>65 - 68</span></td>
                  <td><span>87 - 90</span></td>
                  <td><span>5.1</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>A/M2"</span></td>
                  <td><span>69 - 72</span></td>
                  <td><span>91 - 94</span></td>
                  <td><span>5.1</span></td>
                </tr>
                <tr class="">
                  <td><span>A/L2"</span></td>
                  <td><span>73 - 78</span></td>
                  <td><span>95 - 100</span></td>
                  <td><span>5.1</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>A/XL2"</span></td>
                  <td><span>79 - 86</span></td>
                  <td><span>101 - 106</span></td>
                  <td><span>5.1</span></td>
                </tr>
                <tr class="">
                  <td><span>A/2XL2"</span></td>
                  <td><span>87 - 94</span></td>
                  <td><span>107 - 112</span></td>
                  <td><span>5.1</span></td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
        <div class="size-content">
          <div class="size-type">
            <div class="size-title">
              <span class="text-small">短褲（4''內長）</span>
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
                  <td><span>XS</span></td>
                  <td><span>64 - 69</span></td>
                  <td><span>88 - 93</span></td>
                  <td><span>10.2</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>S</span></td>
                  <td><span>70 - 75</span></td>
                  <td><span>94 - 99</span></td>
                  <td><span>10.2</span></td>
                </tr>
                <tr class="">
                  <td><span>M</span></td>
                  <td><span>76 - 83</span></td>
                  <td><span>100 - 105</span></td>
                  <td><span>10.2</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>L</span></td>
                  <td><span>84 - 90</span></td>
                  <td><span>107 - 113</span></td>
                  <td><span>10.2</span></td>
                </tr>
                <tr class="">
                  <td><span>XL</span></td>
                  <td><span>91 - 98</span></td>
                  <td><span>114 - 121</span></td>
                  <td><span>10.2</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>2XL</span></td>
                  <td><span>99 - 105</span></td>
                  <td><span>122 - 128</span></td>
                  <td><span>10.2</span></td>
                </tr>
              </tbody>
            </table>
          </div>
          <div class='size-chart' id="asian-code-item-three" style="display:none">
            <table>
              <tbody>
                <tr class="tr-color tr-title">
                  <td><span>亞洲碼</span></td>
                  <td><span>腰圍 (厘米)</span></td>
                  <td><span>臀圍 (厘米)</span></td>
                  <td><span>內長 (厘米)</span></td>
                </tr>
                <tr class="">
                  <td><span>A/2XS4"</span></td>
                  <td><span>59 - 61</span></td>
                  <td><span>79 - 82</span></td>
                  <td><span>10.2</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>A/XS4"</span></td>
                  <td><span>62 - 64</span></td>
                  <td><span>83 - 86</span></td>
                  <td><span>10.2</span></td>
                </tr>
                <tr class="">
                  <td><span>A/S4"</span></td>
                  <td><span>65 - 68</span></td>
                  <td><span>87 - 90</span></td>
                  <td><span>10.2</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>A/M4"</span></td>
                  <td><span>69 - 72</span></td>
                  <td><span>91 - 94</span></td>
                  <td><span>10.2</span></td>
                </tr>
                <tr class="">
                  <td><span>A/L4"</span></td>
                  <td><span>73 - 78</span></td>
                  <td><span>95 - 100</span></td>
                  <td><span>10.2</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>A/XL4"</span></td>
                  <td><span>79 - 86</span></td>
                  <td><span>101 - 106</span></td>
                  <td><span>10.2</span></td>
                </tr>
                <tr class="">
                  <td><span>A/2XL4"</span></td>
                  <td><span>87 - 94</span></td>
                  <td><span>107 - 112</span></td>
                  <td><span>10.2</span></td>
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
              <img src="https://img.adidas.com.hk/resources/images/size/measure-women.png" alt="" srcset="">
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

</template>
