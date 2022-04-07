<!--
 * @Description: 
 * @Author: lijiapeng
 * @Date: 2022-04-07 17:07:37
 * @LastEditTime: 2022-04-07 17:07:38
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
      <!-- <div id="right-type" class="right">How to Measure</div> -->
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
                    <span class="show-content" id="show-content-one">國際尺碼</span>
                    <img id="down-show-one" src="https://img.adidas.com.hk/resources/images/common/downArrow.png" alt="" srcset="">
                    <img id="up-show-one" style="display: none" src="https://img.adidas.com.hk/resources/images/common/upArrow.png" alt="" srcset="">
                  </span>
                  <div class="size-options" id="size-options-one" style="display: none">
                    <div class="optionsItem" id="inter-code-one">國際尺碼</div>
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
                  <td colspan="3"><span>國際碼</span></td> 
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
          <div class='size-chart' id="japan-code-item-one" style="display:none">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td><span>日本碼 (J)</span></td> 
                  <td><span>胸圍 (厘米)</span></td> 
                  <td><span>腰圍 (厘米)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>J/2XS</span></td> 
                  <td><span>72 - 76</span></td> 
                  <td><span>53 - 57</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>J/XS</span></td> 
                  <td><span>75 - 79</span></td> 
                  <td><span>56 - 60</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>J/S</span></td> 
                  <td><span>78 - 82</span></td> 
                  <td><span>59 - 63</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>J/M</span></td> 
                  <td><span>81 - 85</span></td> 
                  <td><span>62 - 66</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>J/L</span></td> 
                  <td><span>84 - 88</span></td> 
                  <td><span>65 - 69</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>J/OT</span></td> 
                  <td><span>87 - 91</span></td> 
                  <td><span>68 - 72</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>J/XOT</span></td> 
                  <td><span>90 - 94</span></td> 
                  <td><span>71 - 75</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td rowspan="2"><span>J/2XOT</span></td> 
                  <td rowspan="2"><span>93 - 97</span></td> 
                  <td><span>74 - 78</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span> </span></td> 
                </tr>

              </tbody> 
            </table>
          </div>

        </div>
      </div>
      <div class="size-measure" id="measure">
        <div class="measure">
          <div class="img-info">
            <img class="img-pc" src="https://img.adidas.com.hk/resources/images/size/men.png" alt="" srcset="">
            <img class="img-mob" src="https://img.adidas.com.hk/resources/images/size/menMeasure.jpg" alt="" srcset="">
          </div>
        </div>
        <div class="tips">
          如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，
        </div>
      </div>
    </div>
  </div>
</template>
