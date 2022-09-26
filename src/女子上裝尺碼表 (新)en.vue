<!--
 * @Description: 女子上装尺码表
 * @Author: lijiapeng
 * @Date: 2022-04-07 15:58:16
 * @LastEditTime: 2022-09-26 14:20:15
 * @LastEditors: lijiapeng
 * @Reference: 
-->

<template>

  <div class="content">
    <div class="top-title">
      <div class="sizeClose">
        <i id="closeDrawer" class="iconfont iconcross-small"></i>
      </div>
      <div class="text">Women's Tops Size Chart (New)</div>
    </div>
    <div class="type">
      <!-- <div id="left-type" class="left active">尺碼表</div> -->
      <!-- <div id="right-type" class="right">如何測量</div> -->
      <div id="left-type" class="left active">SIZE & FIT</div>
      <div id="right-type" class="right">HOW TO MEASURE</div>
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
                    <span class="show-content" id="show-content-one">International Size</span>
                    <img id="down-show-one" src="https://img.adidas.com.hk/resources/images/common/downArrow.png" alt="" srcset="">
                    <img id="up-show-one" style="display: none" src="https://img.adidas.com.hk/resources/images/common/upArrow.png" alt="" srcset="">
                  </span>
                  <div class="size-options" id="size-options-one" style="display: none">
                    <div class="optionsItem" id="inter-code-one">International Size</div>
                    <div class="optionsItem" id="asian-code-one">Asian Size</div>
                    <div class="optionsItem" id="japan-code-one">Japanese Size</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class='size-chart' id="inter-code-item-one">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="width: 38%" colspan="2"><span>International Size</span></td> 
                  <td><span>Chest (cm)</span></td> 
                  <td><span>Waist (cm)</span></td> 
                  <td><span>Hip (cm)</span></td> 
                </tr> 
                <tr class="">
                  <td><span>2XS</span></td>
                  <td><span>28</span></td>
                  <td><span>73.5 - 76</span></td>
                  <td><span>57.5 - 60 </span></td>
                  <td><span>82.5 - 85</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>XS</span></td>
                  <td><span>30</span></td>
                  <td><span>76.5 - 79</span></td>
                  <td><span>60.5 - 63</span></td>
                  <td><span>85.5 - 88</span></td>
                </tr>
                <tr class="">
                  <td><span>S</span></td>
                  <td><span>32</span></td>
                  <td><span>79.5 - 82</span></td>
                  <td><span>63.5 - 66</span></td>
                  <td><span>88.5 - 91</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>S-M</span></td>
                  <td><span>34</span></td>
                  <td><span>82.5 - 85</span></td>
                  <td><span>66.5 - 69</span></td>
                  <td><span>91.5 - 94</span></td>
                </tr>
                <tr class="">
                  <td><span>M</span></td>
                  <td><span>36</span></td>
                  <td><span>85.5 - 88</span></td>
                  <td><span>69.5 - 72</span></td>
                  <td><span>94.5 - 97</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>M-L</span></td>
                  <td><span>38</span></td>
                  <td><span>88.5 - 91</span></td>
                  <td><span>72.5 - 75</span></td>
                  <td><span>97.5 - 100</span></td>
                </tr>
                <tr class="">
                  <td><span>L</span></td>
                  <td><span>40</span></td>
                  <td><span>91.5 - 94</span></td>
                  <td><span>75.5 - 78</span></td>
                  <td><span>100.5 - 103</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>L-XL</span></td>
                  <td><span>42</span></td>
                  <td><span>94.5 - 97.5</span></td>
                  <td><span>78.5 - 81.5</span></td>
                  <td><span>103.5 - 106.5</span></td>
                </tr>
                <tr class="">
                  <td><span>XL</span></td>
                  <td><span>44</span></td>
                  <td><span>98 - 101</span></td>
                  <td><span>82 - 85</span></td>
                  <td><span>107 - 110 </span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>XL2X</span></td>
                  <td><span>46</span></td>
                  <td><span>101.5 - 105</span></td>
                  <td><span>85.5 - 89.5</span></td>
                  <td><span>110.5 - 113.5</span></td>
                </tr>
                <tr class="">
                  <td><span>2XL</span></td>
                  <td><span>48</span></td>
                  <td><span>48</span></td>
                  <td><span>90 - 94</span></td>
                  <td><span>114 - 117</span></td>
                </tr>
              </tbody> 
            </table>
          </div>
          <div class='size-chart' id="asian-code-item-one" style="display:none">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="width: 30%" colspan="2"><span>Asian Size</span></td> 
                  <td><span>Chest (cm)</span></td> 
                  <td><span>Waist (cm)</span></td> 
                  <td><span>Hip (cm)</span></td> 
                </tr> 
                <tr class="">
                  <td><span>A/2XS</span></td>
                  <td><span>A24</span></td>
                  <td><span>71 - 74 </span></td>
                  <td><span>59 - 61</span></td>
                  <td><span>79 - 82</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>A/XS </span></td>
                  <td><span>A28</span></td>
                  <td><span>75 - 78</span></td>
                  <td><span>62 - 64</span></td>
                  <td><span>83 - 86</span></td>
                </tr>
                <tr class="">
                  <td><span>A/S</span></td>
                  <td><span>A32</span></td>
                  <td><span>79 - 82</span></td>
                  <td><span>65 - 68</span></td>
                  <td><span>87 - 90</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>A/M</span></td>
                  <td><span>A36</span></td>
                  <td><span>83 - 86</span></td>
                  <td><span>69 - 72</span></td>
                  <td><span>91 - 94</span></td>
                </tr>
                <tr class="">
                  <td><span>A/L</span></td>
                  <td><span>A40</span></td>
                  <td><span>87 - 92</span></td>
                  <td><span>73 - 78</span></td>
                  <td><span>95 - 100</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>A/XL</span></td>
                  <td><span>A44</span></td>
                  <td><span>93 - 98</span></td>
                  <td><span>79 - 86</span></td>
                  <td><span>101 - 106</span></td>
                </tr>
                <tr class="">
                  <td><span>A/2XL</span></td>
                  <td><span>A48</span></td>
                  <td><span>99 - 104 </span></td>
                  <td><span>87 - 94</span></td>
                  <td><span>107 - 112</span></td>
                </tr>
              </tbody> 
            </table>
          </div>
          <div class='size-chart' id="japan-code-item-one" style="display:none">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="width: 34%"><span>Japanese Size (J)</span></td> 
                  <td><span>Chest (cm)</span></td> 
                  <td><span>Waist (cm)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>J/2XS</span></td> 
                  <td><span>72 - 76</span></td> 
                  <td><span>53 - 57</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>J/XS </span></td> 
                  <td><span>75 - 79 </span></td> 
                  <td><span>56 - 60 </span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>J/S</span></td> 
                  <td><span>78 - 82</span></td> 
                  <td><span>59 - 63</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>J/M</span></td> 
                  <td><span>81 - 85</span></td> 
                  <td><span>62 - 66 </span></td> 
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
                  <td><span>J/2XOT</span></td> 
                  <td><span>93 - 97</span></td> 
                  <td><span>74 - 78</span></td> 
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
              <img src="https://img.adidas.com.hk/resources/images/size/measure-women.png" alt="" srcset="">
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

</template>