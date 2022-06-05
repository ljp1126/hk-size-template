<!--
 * @Description: 
 * @Author: lijiapeng
 * @Date: 2022-06-02 18:23:44
 * @LastEditTime: 2022-06-05 17:24:09
 * @LastEditors: lijiapeng
 * @Reference: 
-->
<template>
  <div class="content">
    <div class="top-title">
      <div class="sizeClose">
        <i id="closeDrawer" class="iconfont iconcross-small"></i>
      </div>
      <div class="text">男子襪子尺碼表</div>
    </div>
    <div class="type type-one">
      <div id="left-type" class="left active">尺碼表</div>
      <!-- <div id="right-type" class="right">如何測量</div> -->
      <!-- <div id="left-type" class="left active">SIZE & FIT</div> -->
      <!-- <div id="right-type" class="right">HOW TO MEASURE</div> -->
    </div>
    <div class="table-info">
      <div class="size-info" id="sizeInfo">
        <div class="size-content scroll-wrap-roll">
          <div class='size-chart'>
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td><span>鞋碼</span></td> 
                  <td><span>意大利碼</span></td> 
                  <td><span>美國碼</span></td> 
                  <td><span>英國碼</span></td> 
                  <td><span>澳大利亞碼</span></td> 
                  <td><span>日本碼</span></td> 
                  <td><span>國碼</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>S</span></td> 
                  <td><span>39 - 40</span></td> 
                  <td><span>5.5 - 6.5</span></td> 
                  <td><span>5 - 6</span></td> 
                  <td><span>5 - 6</span></td> 
                  <td><span>24 - 25</span></td> 
                  <td><span>240 - 250</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>M</span></td> 
                  <td><span>41 - 42</span></td> 
                  <td><span>7.5 - 8.5</span></td> 
                  <td><span>7 - 8</span></td> 
                  <td><span>7 - 8</span></td> 
                  <td><span>26 - 27</span></td> 
                  <td><span>260 - 270</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>L</span></td> 
                  <td><span>	43 - 44</span></td> 
                  <td><span>9.5 - 10.5</span></td> 
                  <td><span>9 - 10</span></td> 
                  <td><span>9 - 10</span></td> 
                  <td><span>27 - 28</span></td> 
                  <td><span>270 - 280</span></td> 
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