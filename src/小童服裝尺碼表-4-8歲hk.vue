<!--
 * @Description: 小童服裝尺碼表-4-8歲
 * @Author: lijiapeng
 * @Date: 2022-04-08 10:01:42
 * @LastEditTime: 2022-04-20 09:44:22
 * @LastEditors: lijiapeng
 * @Reference: 
-->

<template>
  <div class="content">
    <div class="top-title">
      <div class="sizeClose">
        <i id="closeDrawer" class="iconfont iconcross-small"></i>
      </div>
      <div class="text">小童服裝尺碼表 (4-8歲)</div>
    </div>
    <div class="type">
      <div id="left-type" class="left active">尺碼表</div>
      <div id="right-type" class="right">如何測量</div>
      <!-- <div id="left-type" class="left active">SIZE & FIT</div> -->
      <!-- <div id="right-type" class="right">How to Measure</div> -->
    </div>
    <div class="table-info">
      <div class="size-info" id="sizeInfo">
        <div class="size-content scroll-wrap-roll">
          <div class="size-type">
            <div class="size-title">
              <span class="text-small"></span>
            </div>
          </div>
          <div class='size-chart'>
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td><span>英國碼 (UK)</span></td> 
                  <td><span>參考年齡</span></td> 
                  <td><span>高度 (厘米)</span></td> 
                  <td><span>胸圍 (厘米)</span></td> 
                  <td><span>腰圍 (厘米)</span></td> 
                  <td><span>臀圍 (厘米)</span></td> 
                  <td><span>內長 (厘米)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>92</span></td> 
                  <td><span>1~2 歲</span></td> 
                  <td><span>86 - 91</span></td> 
                  <td><span>52 - 53</span></td> 
                  <td><span>51 - 52</span></td> 
                  <td><span>52 - 53</span></td> 
                  <td><span>38.1</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>98</span></td> 
                  <td><span>2~3 歲</span></td> 
                  <td><span>94 - 99</span></td> 
                  <td><span>53 - 55</span></td> 
                  <td><span>52 - 53</span></td> 
                  <td><span>53 - 56</span></td> 
                  <td><span>40.6</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>104</span></td> 
                  <td><span>3~4 歲</span></td> 
                  <td><span>102 - 104</span></td> 
                  <td><span>55 - 56</span></td> 
                  <td><span>53 - 55</span></td> 
                  <td><span>56 - 60</span></td> 
                  <td><span>45.7</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>110</span></td> 
                  <td><span>4~5 歲</span></td> 
                  <td><span>107 - 109</span></td> 
                  <td><span>56 - 58</span></td> 
                  <td><span>55</span></td> 
                  <td><span>61 - 62</span></td> 
                  <td><span>49.5</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>116</span></td> 
                  <td><span>5~6 歲</span></td> 
                  <td><span>112 - 117</span></td> 
                  <td><span>58 - 61</span></td> 
                  <td><span>56</span></td> 
                  <td><span>62 - 64</span></td> 
                  <td><span>52.1</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>122</span></td> 
                  <td><span>6~7 歲</span></td> 
                  <td><span>119 - 122</span></td> 
                  <td><span>61 - 64</span></td> 
                  <td><span>57</span></td> 
                  <td><span>65 - 66</span></td> 
                  <td><span>55.9</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>128</span></td> 
                  <td><span>7~8 歲</span></td> 
                  <td><span>124 - 127</span></td> 
                  <td><span>64</span></td> 
                  <td><span>57 - 58</span></td> 
                  <td><span>66 - 69</span></td> 
                  <td><span>59.7</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>134</span></td> 
                  <td><span>8~9 歲</span></td> 
                  <td><span>130 - 135</span></td> 
                  <td><span>65 - 67</span></td> 
                  <td><span>60 - 61</span></td> 
                  <td><span>69 - 71</span></td> 
                  <td><span>62.2</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>140</span></td> 
                  <td><span>9~10 歲</span></td> 
                  <td><span>137 - 140</span></td> 
                  <td><span>69 - 71</span></td> 
                  <td><span>62 - 64</span></td> 
                  <td><span>71 - 75</span></td> 
                  <td><span>65</span></td> 
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
              <img src="https://img.adidas.com.hk/resources/images/size/measure-kids.png" alt="" srcset="">
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
