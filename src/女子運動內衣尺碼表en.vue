<!--
 * @Description: 女子運動內衣尺碼表
 * @Author: lijiapeng
 * @Date: 2022-04-07 16:38:05
 * @LastEditTime: 2022-04-14 13:25:44
 * @LastEditors: lijiapeng
 * @Reference: 
-->

<template>
  <div class="content">
    <div class="top-title">
      <div class="sizeClose">
        <i id="closeDrawer" class="iconfont iconcross-small"></i>
      </div>
      <div class="text">Women's Sport Bras Size Chart</div>
    </div>
    <div class="type type-one">
      <!-- <div id="left-type" class="left active">尺碼表</div> -->
      <!-- <div id="right-type" class="right">如何測量</div> -->
      <div id="left-type" class="left active">SIZE & FIT</div>
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
                    <span class="show-content" id="show-content-one">International Size</span>
                    <img id="down-show-one" src="https://img.adidas.com.hk/resources/images/common/downArrow.png" alt="" srcset="">
                    <img id="up-show-one" style="display: none" src="https://img.adidas.com.hk/resources/images/common/upArrow.png" alt="" srcset="">
                  </span>
                  <div class="size-options" id="size-options-one" style="display: none">
                    <div class="optionsItem" id="inter-code-one">International Size</div>
                    <div class="optionsItem" id="asian-code-one">Asian Size</div>
                    <div class="optionsItem" id="eruope-code-one">European Size</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class='size-chart' id="inter-code-item-one">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="border-right: 1px solid #fff;"><span>BRA SIZE</span></td> 
                  <td style="border-bottom: 1px solid #fff;" colspan="5"><span>Cup Size</span></td> 
                </tr> 
                <tr class="tr-color tr-title"> 
                  <td style="border-right: 1px solid #fff;"><span>(CM/FRANCE/UK/ITALY)</span></td> 
                  <td><span>AA</span></td> 
                  <td><span>A</span></td> 
                  <td style="border-right: 1px solid #fff;"><span>B</span></td> 
                  <td><span>C</span></td> 
                  <td><span>D</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>65/80/30/0</span></td> 
                  <td colspan="3"><span>A/2XS AA-B</span></td> 
                  <td colspan="2"><span>A/2XS C-D</span></td> 
                </tr> 

                <tr class="tr-color"> 
                  <td><span>70/85/32/1</span></td> 
                  <td colspan="3"><span>A/XS AA-B</span></td> 
                  <td colspan="2"><span>A/XS C-D</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>70/85/32/1</span></td> 
                  <td colspan="3"><span>A/S AA-B</span></td> 
                  <td colspan="2"><span>A/S C-D</span></td> 
                </tr> 

                <tr class="tr-color"> 
                  <td><span>75/90/34/2</span></td> 
                  <td colspan="3"><span>A/M AA-B</span></td> 
                  <td colspan="2"><span>A/M C-D</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>80/95/36/3</span></td> 
                  <td colspan="3"><span>A/L AA-B</span></td> 
                  <td colspan="2"><span>A/L C-D</span></td> 
                </tr> 

                <tr class="tr-color"> 
                  <td><span>85/100/38/4</span></td> 
                  <td colspan="3"><span>A/XL AA-B</span></td> 
                  <td colspan="2"><span>A/XL C-D</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>90/105/40/5</span></td> 
                  <td colspan="3"><span>A/2SL AA-B</span></td> 
                  <td colspan="2"><span>A/2SL C-D</span></td> 
                </tr> 

              </tbody> 
            </table>
          </div>
          <div class='size-chart' id="asian-code-item-one" style="display:none">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="border-right: 1px solid #fff;"><span>Bra Size</span></td> 
                  <td style="border-bottom: 1px solid #fff;" colspan="5"><span>Cup Size</span></td> 
                </tr> 
                <tr class="tr-color tr-title"> 
                  <td style="border-right: 1px solid #fff;"><span>(Inch/cm)</span></td> 
                  <td><span>A</span></td> 
                  <td><span>B</span></td> 
                  <td style="border-right: 1px solid #fff;"><span>C</span></td> 
                  <td><span>D</span></td> 
                  <td><span>E</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>30 / 65</span></td> 
                  <td><span>A/2XS</span></td> 
                  <td><span>A/2XS</span></td> 
                  <td><span>A/S</span></td> 
                  <td><span>A/S</span></td> 
                  <td><span>A/M</span></td> 
                </tr> 

                <tr class="tr-color"> 
                  <td><span>32 / 70</span></td> 
                  <td><span>A/S</span></td> 
                  <td><span>A/S</span></td> 
                  <td><span>A/M</span></td> 
                  <td><span>A/M</span></td> 
                  <td><span>A/L</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>34 / 75</span></td> 
                  <td><span>A/M</span></td> 
                  <td><span>A/M</span></td> 
                  <td><span>A/L</span></td> 
                  <td><span>A/L</span></td> 
                  <td><span>A/XL</span></td> 
                </tr> 

                <tr class="tr-color"> 
                  <td><span>36 / 80</span></td> 
                  <td><span>A/L</span></td> 
                  <td><span>A/XL</span></td> 
                  <td><span>A/XL</span></td> 
                  <td><span>A/2XL</span></td> 
                  <td><span>A/2XL</span></td> 
                </tr>

                <tr class=""> 
                  <td><span>38 / 85</span></td> 
                  <td><span>A/2XL</span></td> 
                  <td><span>A/2XL</span></td> 
                  <td><span>N/A</span></td> 
                  <td><span>N/A</span></td> 
                  <td><span>N/A</span></td> 
                </tr> 


              </tbody> 
            </table>
          </div>
          <div class='size-chart' id="eruope-code-item-one" style="display:none">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="border-right: 1px solid #fff;"><span>Bra Size</span></td> 
                  <td style="border-bottom: 1px solid #fff;" colspan="5"><span>Cup Size</span></td> 
                </tr> 
                <tr class="tr-color tr-title"> 
                  <td style="border-right: 1px solid #fff;"><span>(Inch/cm)</span></td> 
                  <td><span>A</span></td> 
                  <td><span>B</span></td> 
                  <td style="border-right: 1px solid #fff;"><span>C</span></td> 
                  <td><span>D</span></td> 
                  <td><span>E</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>30 / 65</span></td> 
                  <td><span>2XS</span></td> 
                  <td><span>XS</span></td> 
                  <td><span>XS</span></td> 
                  <td><span>XS</span></td> 
                  <td><span>S</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>32 / 70</span></td> 
                  <td><span>XS</span></td> 
                  <td><span>XS</span></td> 
                  <td><span>S</span></td> 
                  <td><span>S</span></td> 
                  <td><span>M</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>34 / 75</span></td> 
                  <td><span>S</span></td> 
                  <td><span>S</span></td> 
                  <td><span>M</span></td> 
                  <td><span>M</span></td> 
                  <td><span>L</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>36 / 80</span></td> 
                  <td><span>M</span></td> 
                  <td><span>M</span></td> 
                  <td><span>L</span></td> 
                  <td><span>L</span></td> 
                  <td><span>XL</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>38 / 85</span></td> 
                  <td><span>L</span></td> 
                  <td><span>L</span></td> 
                  <td><span>L</span></td> 
                  <td><span>XL</span></td> 
                  <td><span>XL</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>40 / 90</span></td> 
                  <td><span>L</span></td> 
                  <td><span>XL</span></td> 
                  <td><span>XL</span></td> 
                  <td><span>XL</span></td> 
                  <td><span>2XL</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>42 / 95</span></td> 
                  <td><span>XL</span></td> 
                  <td><span>XL</span></td> 
                  <td><span>XL</span></td> 
                  <td><span>2XL</span></td> 
                  <td><span>2XL</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>44 / 100</span></td> 
                  <td><span>2XL</span></td> 
                  <td><span>2XL</span></td> 
                  <td><span>2XL</span></td> 
                  <td><span>2XL</span></td> 
                  <td><span>2XL</span></td> 
                </tr> 

              </tbody> 
            </table>
          </div>

        </div>
      </div>
      <div class="size-measure" id="measure">
      </div>
    </div>
  </div>
</template>
