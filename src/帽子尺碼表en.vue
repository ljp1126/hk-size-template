<!--
 * @Description: 
 * @Author: lijiapeng
 * @Date: 2022-04-08 12:56:55
 * @LastEditTime: 2022-04-14 14:56:05
 * @LastEditors: lijiapeng
 * @Reference: 
-->

<template>
  <div class="content">
    <div class="top-title">
      <div class="sizeClose">
        <i id="closeDrawer" class="iconfont iconcross-small"></i>
      </div>
      <div class="text">Hat & Cap Size Chart</div>
    </div>
    <div class="type type-one">
      <!-- <div id="left-type" class="left active">尺碼表</div> -->
      <!-- <div id="right-type" class="right">如何測量</div> -->
      <div id="left-type" class="left active">SIZE & FIT</div>
      <!-- <div id="right-type" class="right">How to Measure</div> -->
    </div>
    <div class="table-info">
      <div class="size-info" id="sizeInfo">
        <div class="size-content">
          <div class='size-chart'>
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td><span>Size</span></td> 
                  <td><span>Width (Inch)</span></td> 
                  <td><span>Width (cm)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>Infants</span></td> 
                  <td><span>16.5"</span></td> 
                  <td><span>42</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>Toddlers</span></td> 
                  <td><span>18.9" - 19.7"</span></td> 
                  <td><span>42 - 50</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>Children</span></td> 
                  <td><span>19.7" - 20.5"</span></td> 
                  <td><span>50 - 52</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>Youth</span></td> 
                  <td><span>20.5" - 21.3"</span></td> 
                  <td><span>52 - 54</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>Women (S/M)</span></td> 
                  <td><span>21.3" - 22.0"</span></td> 
                  <td><span>54 - 56</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>Men (M/L)</span></td> 
                  <td><span>22.0" - 22.8"</span></td> 
                  <td><span>56 - 58</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>Large (L/XL)</span></td> 
                  <td><span>22.8" - 23.6"</span></td> 
                  <td><span>58 - 60</span></td> 
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
