<!--
 * @Description: 護腿板通用尺碼表
 * @Author: lijiapeng
 * @Date: 2022-04-08 11:55:23
 * @LastEditTime: 2022-04-20 12:46:18
 * @LastEditors: lijiapeng
 * @Reference: 
-->

<template>
  <div class="content">
    <div class="top-title">
      <div class="sizeClose">
        <i id="closeDrawer" class="iconfont iconcross-small"></i>
      </div>
      <div class="text">Shin Pads Size Chart</div>
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
          <div class='size-chart'>
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td><span>Size</span></td> 
                  <td><span>S</span></td> 
                  <td><span>M</span></td> 
                  <td><span>L</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>Height Reference (cm)</span></td> 
                  <td><span>100-120</span></td> 
                  <td><span>120-140</span></td> 
                  <td><span>140-160</span></td> 
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
