<!--
 * @Description: 
 * @Author: lijiapeng
 * @Date: 2022-04-08 12:56:50
 * @LastEditTime: 2022-04-20 18:09:51
 * @LastEditors: lijiapeng
 * @Reference: 
-->

<template>
  <div class="content">
    <div class="top-title">
      <div class="sizeClose">
        <i id="closeDrawer" class="iconfont iconcross-small"></i>
      </div>
      <div class="text">帽子尺碼表</div>
    </div>
    <div class="type type-one">
      <div id="left-type" class="left active">尺碼表</div>
      <!-- <div id="right-type" class="right">如何測量</div> -->
      <!-- <div id="left-type" class="left active">SIZE & FIT</div> -->
      <!-- <div id="right-type" class="right">HOW TO MEASURE</div> -->
    </div>
    <div class="table-info">
      <div class="size-info" id="sizeInfo">
        <div class="size-content">
          <div class='size-chart'>
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td><span>尺碼</span></td> 
                  <td><span>頭圍(英寸)</span></td> 
                  <td><span>頭圍(厘米)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>小童(OSFC)</span></td> 
                  <td><span>19.7" - 20.5"</span></td> 
                  <td><span>50 - 52</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>大童(OSFY)</span></td> 
                  <td><span>20.5" - 21.3"</span></td> 
                  <td><span>52 - 54</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>女子(OSFW)</span></td> 
                  <td><span>21.3" - 22.0"</span></td> 
                  <td><span>54 - 56</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>男子 (OSFM)</span></td> 
                  <td><span>22.0" - 22.8"</span></td> 
                  <td><span>56 - 58</span></td> 
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
