<!--
 * @Description: 小童服裝尺碼表-4-8歲
 * @Author: lijiapeng
 * @Date: 2022-04-08 10:01:48
 * @LastEditTime: 2022-04-14 13:06:47
 * @LastEditors: lijiapeng
 * @Reference: 
-->

<template>
  <div class="content">
    <div class="top-title">
      <div class="sizeClose">
        <i id="closeDrawer" class="iconfont iconcross-small"></i>
      </div>
      <div class="text">Children Clothing Size Chart (4-8 Years)</div>
    </div>
    <div class="type">
      <!-- <div id="left-type" class="left active">尺碼表</div> -->
      <!-- <div id="right-type" class="right">如何測量</div> -->
      <div id="left-type" class="left active">SIZE & FIT</div>
      <div id="right-type" class="right">HOW TO MEASURE</div>
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
                  <td><span>UK</span></td> 
                  <td><span>Age Reference</span></td> 
                  <td><span>Height (cm)</span></td> 
                  <td><span>Chest (cm)</span></td> 
                  <td><span>Waist (cm)</span></td> 
                  <td><span>Hip (cm)</span></td> 
                  <td><span>Inseam (cm)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>92</span></td> 
                  <td><span>1~2years</span></td> 
                  <td><span>86 - 91</span></td> 
                  <td><span>52 - 53</span></td> 
                  <td><span>51 - 52</span></td> 
                  <td><span>52 - 53</span></td> 
                  <td><span>38.1</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>98</span></td> 
                  <td><span>2~3 years</span></td> 
                  <td><span>94 - 99</span></td> 
                  <td><span>53 - 55</span></td> 
                  <td><span>52 - 53</span></td> 
                  <td><span>53 - 56</span></td> 
                  <td><span>40.6</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>104</span></td> 
                  <td><span>3~4 years</span></td> 
                  <td><span>102 - 104</span></td> 
                  <td><span>55 - 56</span></td> 
                  <td><span>53 - 55</span></td> 
                  <td><span>56 - 60</span></td> 
                  <td><span>45.7</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>110</span></td> 
                  <td><span>4~5 years</span></td> 
                  <td><span>107 - 109</span></td> 
                  <td><span>56 - 58</span></td> 
                  <td><span>55</span></td> 
                  <td><span>61 - 62</span></td> 
                  <td><span>49.5</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>116</span></td> 
                  <td><span>5~6 years</span></td> 
                  <td><span>112 - 117</span></td> 
                  <td><span>58 - 61</span></td> 
                  <td><span>56</span></td> 
                  <td><span>62 - 64</span></td> 
                  <td><span>52.1</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>122</span></td> 
                  <td><span>6~7 years</span></td> 
                  <td><span>119 - 122</span></td> 
                  <td><span>61 - 64</span></td> 
                  <td><span>57</span></td> 
                  <td><span>65 - 66</span></td> 
                  <td><span>55.9</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>128</span></td> 
                  <td><span>7~8 years</span></td> 
                  <td><span>124 - 127</span></td> 
                  <td><span>64</span></td> 
                  <td><span>57 - 58</span></td> 
                  <td><span>66 - 69</span></td> 
                  <td><span>59.7</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>134</span></td> 
                  <td><span>8~9 years</span></td> 
                  <td><span>130 - 135</span></td> 
                  <td><span>65 - 67</span></td> 
                  <td><span>60 - 61</span></td> 
                  <td><span>69 - 71</span></td> 
                  <td><span>62.2</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>140</span></td> 
                  <td><span>9~10 years</span></td> 
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
          <div class="tips-title">Fit Tips：</div>
          <div class="tips-content">Please note that the size chart refers to the measurement of oneself, but not the clothes itself.</div>
          <div class="tips-content">If you're on the borderline between two sizes, please order the smaller size for a tighter fit or the larger size for a looser fit.</div>
        </div>
      </div>
      <div class="size-measure" id="measure">
        <div class="measure">
          <div class="img-info">
            <div class="instructions">
              <div class="steps-type">
                <p class="tipinfo">Hold the tape horizontally to measure:</p>
                <ul class="steps">
                  <li class="step">
                    <span class="step-title">1. Chest, </span>
                    <span class="step-body">around the widest part</span>
                  </li>
                  <li class="step">
                    <span class="step-title">2. Waist, </span>
                    <span class="step-body">around the narrowest part</span>
                  </li>
                  <li class="step">
                    <span class="step-title">3. Hip, </span>
                    <span class="step-body">around the widest part, keeping the feet close together</span>
                  </li>
                </ul>
              </div>
              <div class="steps-type">
                <p class="tipinfo">Hold the tape vertically to measure:</p>
                <ul class="steps">
                  <li class="step">
                    <span class="step-title">4. Inseam, </span>
                    <span class="step-body">from the crotch to the floor</span>
                  </li>
                  <li class="step">
                    <span class="step-title">5. Height, </span>
                    <span class="step-body">from the top of the head to the floor, keeping a straight posture</span>
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
