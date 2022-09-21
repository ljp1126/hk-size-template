<!--
 * @Description: 男子下装尺码表en
 * @Author: lijiapeng
 * @Date: 2022-04-02 14:56:18
 * @LastEditTime: 2022-09-21 14:27:28
 * @LastEditors: lijiapeng
 * @Reference: 
-->

<template>

  <div class="content">
    <div class="top-title">
      <div class="sizeClose">
        <i id="closeDrawer" class="iconfont iconcross-small"></i>
      </div>
      <div class="text">MEN'S BOTTOM SIZE CHART</div>
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
              <span class="text-small">Pants</span>
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
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class='size-chart' id="inter-code-item-one">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="width: 38%" colspan="3"><span>International Size</span></td> 
                  <td><span>Waist (cm)</span></td> 
                  <td><span>Hip (cm)</span></td> 
                  <td><span>Inseam (cm)</span></td> 
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
                  <td><span>Asian Size</span></td> 
                  <td><span>Waist (cm)</span></td> 
                  <td><span>Hip (cm)</span></td> 
                  <td><span>Inseam (cm)</span></td> 
                </tr> 
                <tr class="">
                  <td><span>A/2XS</span></td>
                  <td><span>67 - 68.5</span></td>
                  <td><span>81.5</span></td>
                  <td><span>77.5</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>A/XS</span></td>
                  <td><span>69.5 - 71</span></td>
                  <td><span>82.5 - 84</span></td>
                  <td><span>77.8</span></td>
                </tr>
                <tr class="">
                  <td><span>A/S</span></td>
                  <td><span>72 - 76</span></td>
                  <td><span>85 - 89</span></td>
                  <td><span>78</span></td>
                </tr>

                <tr class="tr-color">
                  <td><span>A/M</span></td>
                  <td><span>77 - 81</span></td>
                  <td><span>90 - 94</span></td>
                  <td><span>78</span></td>
                </tr>
                <tr class="">
                  <td><span>A/L</span></td>
                  <td><span>82 - 86</span></td>
                  <td><span>95 - 99</span></td>
                  <td><span>78.5</span></td>
                </tr>

                <tr class="tr-color">
                  <td><span>A/XL</span></td>
                  <td><span>87 - 93</span></td>
                  <td><span>100 - 105</span></td>
                  <td><span>79</span></td>
                </tr>
                <tr class="">
                  <td><span>A2XL</span></td>
                  <td><span>94 - 100</span></td>
                  <td><span>106 - 111</span></td>
                  <td><span>79.5</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>A3XL</span></td>
                  <td><span>101 - 108</span></td>
                  <td><span>112 - 118</span></td>
                  <td><span>80</span></td>
                </tr>
              </tbody> 
            </table>
          </div>
        </div>
        <div class="size-content">
          <div class="size-type">
            <div class="size-title">
              <span class="text-small">Shorts (5" Inseam)</span>
            </div>
            <div class="size-select">
              <div class="select-type">
                <div class="select-numb">
                  <span class="select-show">
                    <span class="show-content" id="show-content-two">International Size</span>
                    <img id="down-show-two" src="https://img.adidas.com.hk/resources/images/common/downArrow.png" alt="" srcset="">
                    <img id="up-show-two" style="display: none" src="https://img.adidas.com.hk/resources/images/common/upArrow.png" alt="" srcset="">
                  </span>
                  <div class="size-options" id="size-options-two" style="display: none">
                    <div class="optionsItem" id="inter-code-two">International Size</div>
                    <div class="optionsItem" id="asian-code-two">Asian Size</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class='size-chart' id="inter-code-item-two">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td><span>International Size</span></td> 
                  <td><span>Waist (cm)</span></td> 
                  <td><span>Hip (cm)</span></td> 
                  <td><span>Inseam (cm)</span></td> 
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
                  <td><span>Asian Size</span></td> 
                  <td><span>Waist (cm)</span></td> 
                  <td><span>Hip (cm)</span></td> 
                  <td><span>Inseam (cm)</span></td> 
                </tr> 
                <tr class="">
                  <td><span>A/2XS5"</span></td>
                  <td><span>67 - 68.5</span></td>
                  <td><span>81.5</span></td>
                  <td><span>12.7</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>A/XS5"</span></td>
                  <td><span>69.5 - 71</span></td>
                  <td><span>82.5 - 84</span></td>
                  <td><span>12.7</span></td>
                </tr>
                <tr class="">
                  <td><span>A/S5"</span></td>
                  <td><span>72 - 76</span></td>
                  <td><span>85 - 89</span></td>
                  <td><span>12.7</span></td>
                </tr>

                <tr class="tr-color">
                  <td><span>A/M5"</span></td>
                  <td><span>77 - 81</span></td>
                  <td><span>90 - 94</span></td>
                  <td><span>12.7</span></td>
                </tr>
                <tr class="">
                  <td><span>A/L5"</span></td>
                  <td><span>82 - 86</span></td>
                  <td><span>95 - 99</span></td>
                  <td><span>12.7</span></td>
                </tr>

                <tr class="tr-color">
                  <td><span>A/XL5"</span></td>
                  <td><span>87 - 93</span></td>
                  <td><span>100 - 105</span></td>
                  <td><span>12.7</span></td>
                </tr>
                <tr class="">
                  <td><span>A/2XL5</span></td>
                  <td><span>94 - 100</span></td>
                  <td><span>106 - 111</span></td>
                  <td><span>12.7</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>A/3XL5</span></td>
                  <td><span>101 - 108</span></td>
                  <td><span>112 - 118</span></td>
                  <td><span>12.7</span></td>
                </tr>
              </tbody> 
            </table>
          </div>
        </div>
        <div class="size-content">
          <div class="size-type">
            <div class="size-title">
              <span class="text-small">Shorts (7" Inseam)</span>
            </div>
            <div class="size-select">
              <div class="select-type">
                <div class="select-numb">
                  <span class="select-show">
                    <span class="show-content" id="show-content-three">International Size</span>
                    <img id="down-show-three" src="https://img.adidas.com.hk/resources/images/common/downArrow.png" alt="" srcset="">
                    <img id="up-show-three" style="display: none" src="https://img.adidas.com.hk/resources/images/common/upArrow.png" alt="" srcset="">
                  </span>
                  <div class="size-options" id="size-options-three" style="display: none">
                    <div class="optionsItem" id="inter-code-three">International Size</div>
                    <div class="optionsItem" id="asian-code-three">Asian Size</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class='size-chart' id="inter-code-item-three">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td><span>International Size</span></td> 
                  <td><span>Waist (cm)</span></td> 
                  <td><span>Hip (cm)</span></td> 
                  <td><span>Inseam (cm)</span></td> 
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
                  <td><span>Asian Size</span></td> 
                  <td><span>Waist (cm)</span></td> 
                  <td><span>Hip (cm)</span></td> 
                  <td><span>Inseam (cm)</span></td> 
                </tr> 
                <tr class="">
                  <td><span>A/2XS7"</span></td>
                  <td><span>67 - 68.5</span></td>
                  <td><span>81.5</span></td>
                  <td><span>17.8</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>A/XS7"</span></td>
                  <td><span>69.5 - 71</span></td>
                  <td><span>82.5 - 84</span></td>
                  <td><span>17.8</span></td>
                </tr>
                <tr class="">
                  <td><span>A/S7"</span></td>
                  <td><span>72 - 76</span></td>
                  <td><span>85 - 89</span></td>
                  <td><span>17.8</span></td>
                </tr>

                <tr class="tr-color">
                  <td><span>A/M7"</span></td>
                  <td><span>77 - 81</span></td>
                  <td><span>90 - 94</span></td>
                  <td><span>17.8</span></td>
                </tr>
                <tr class="">
                  <td><span>A/L7"</span></td>
                  <td><span>82 - 86</span></td>
                  <td><span>95 - 99</span></td>
                  <td><span>17.8</span></td>
                </tr>

                <tr class="tr-color">
                  <td><span>A/XL7"</span></td>
                  <td><span>87 - 93</span></td>
                  <td><span>100 - 105</span></td>
                  <td><span>17.8</span></td>
                </tr>
                <tr class="">
                  <td><span>A/2XL7</span></td>
                  <td><span>94 - 100</span></td>
                  <td><span>106 - 111</span></td>
                  <td><span>17.8</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>A/3XL7</span></td>
                  <td><span>101 - 108</span></td>
                  <td><span>112 - 118</span></td>
                  <td><span>17.8</span></td>
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
              <img src="https://img.adidas.com.hk/resources/images/size/measure-men.png" alt="" srcset="">
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

</template>
