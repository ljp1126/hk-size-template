<!--
 * @Description: 
 * @Author: lijiapeng
 * @Date: 2022-08-09 14:47:34
 * @LastEditTime: 2022-08-09 14:55:37
 * @LastEditors: lijiapeng
 * @Reference: 
-->
<template>
  <div class="content">
    <div class="top-title">
      <div class="sizeClose">
        <i id="closeDrawer" class="iconfont iconcross-small"></i>
      </div>
      <div class="text"> TRAINING GLOVES SIZE CHART</div>
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
          <div class='size-chart'>
            <table>
              <tbody>
                <tr class="tr-color tr-title">
                  <td><span>Size</span></td>
                  <td><span>Length (Inch)</span></td>
                  <td><span>Length (cm)</span></td>
                </tr>
                <tr class="">
                  <td><span>S</span></td>
                  <td><span>6.5" - 7.5"</span></td>
                  <td><span>16.5 - 19</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>M</span></td>
                  <td><span>7.5" - 8.5"</span></td>
                  <td><span>19 - 22</span></td>
                </tr>
                <tr class="">
                  <td><span>L</span></td>
                  <td><span>8.5" - 9.5"</span></td>
                  <td><span>22 - 24</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>XL</span></td>
                  <td><span>9.5" - 10.5"</span></td>
                  <td><span>24 - 26.7</span></td>
                </tr>
                <tr class="">
                  <td><span>2XL</span></td>
                  <td><span>10.5" - 11.5"</span></td>
                  <td><span>26.7 - 29.2</span></td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
        <div class="tips">
          <div class="tips-title">Fit Tips：</div>
          <div class="tips-content">IN BETWEEN SIZES?</div>
          <div class="tips-content">We advise to go for the larger one. If anything is wrong, you can return your items for free. Check out our return policy for more details.</div>
        </div>
      </div>
      <div class="size-measure" id="measure">
        <div class="measure">
          <div class="img-info">
            <div class="instructions">
              <div class="steps-type">
                <ul class="steps">
                  <li class="step">
                    <span class="step-title"></span>
                    <span class="step-body">To find your ideal glove size, measure both hands from the base of the palm to the tip of your middle finger. If either hand is larger, order for this size.</span>
                  </li>
                </ul>
              </div>
            </div>
            <div class="image-container">
              <img src="https://www.adidas.co.uk/glass/react/456da4a/assets/img/size-charts/accessories/img-gloves-hand.jpg" alt="" srcset="">
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>