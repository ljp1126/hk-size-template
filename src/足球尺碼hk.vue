<!--
 * @Description: 足球尺碼
 * @Author: lijiapeng
 * @Date: 2022-04-08 12:36:06
 * @LastEditTime: 2022-04-14 14:56:11
 * @LastEditors: lijiapeng
 * @Reference: 
-->

<template>
  <div class="content">
    <div class="top-title">
      <div class="sizeClose">
        <i id="closeDrawer" class="iconfont iconcross-small"></i>
      </div>
      <div class="text">足球尺碼</div>
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
                  <td><span>圓周(英寸)</span></td> 
                  <td><span>圓周(厘米)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>1(Mini)</span></td> 
                  <td><span>13.5-16.3"</span></td> 
                  <td><span>34-41</span></td> 
                </tr> 
                  <tr class="tr-color"> 
                  <td><span>2(Midi)</span></td> 
                  <td><span>19.6-20.3"</span></td> 
                  <td><span>50-52</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>3</span></td> 
                  <td><span>23.2-23.8"</span></td> 
                  <td><span>59-60</span></td> 
                </tr> 
                  <tr class="tr-color"> 
                  <td><span>4(FIFA Inspected)</span></td> 
                  <td><span>25-26"</span></td> 
                  <td><span>64-66</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>5(FIFA Approved)</span></td> 
                  <td><span>27-27.4"</span></td> 
                  <td><span>69-70</span></td> 
                </tr> 
                  <tr class="tr-color"> 
                  <td><span>5(FIFA Inspected)</span></td> 
                  <td><span>26.8-27.6"</span></td> 
                  <td><span>68-70</span></td> 
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
