<!--
 * @Description: 襪子通用尺碼表
 * @Author: lijiapeng
 * @Date: 2022-04-08 13:20:35
 * @LastEditTime: 2022-04-08 13:24:59
 * @LastEditors: lijiapeng
 * @Reference: 
-->

<template>
  <div class="content">
    <div class="top-title">
      <div class="sizeClose">
        <i id="closeDrawer" class="iconfont iconcross-small"></i>
      </div>
      <div class="text">襪子通用尺碼表</div>
    </div>
    <div class="type">
      <div id="left-type" class="left active">尺碼表</div>
      <div id="right-type" class="right">如何測量</div>
      <!-- <div id="left-type" class="left active">SIZE & FIT</div> -->
      <!-- <div id="right-type" class="right">How to Measure</div> -->
    </div>
    <div class="table-info">
      <div class="size-info" id="sizeInfo">
        <div class="size-content">
          <div class='size-chart'>
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td colspan="2"><span>國際尺碼</span></td> 
                  <td><span>參考鞋碼（UK）</span></td> 
                  <td><span>參考鞋碼（EU）</span></td> 
                  <td><span>參考鞋碼（US）</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>K-XS</span></td> 
                  <td><span>1518</span></td> 
                  <td><span>0K - 2K</span></td> 
                  <td><span>16 - 18</span></td> 
                  <td><span>1K - 3K</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>K-S</span></td> 
                  <td><span>1922</span></td> 
                  <td><span>3K - 5K</span></td> 
                  <td><span>19 - 21</span></td> 
                  <td><span>4K - 5.5K</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>K-M</span></td> 
                  <td><span>2326</span></td> 
                  <td><span>5.5K - 7K</span></td> 
                  <td><span>22 - 24</span></td> 
                  <td><span>6K - 7.5K</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>K-L</span></td> 
                  <td><span>2326</span></td> 
                  <td><span>7.5K - 9.5K</span></td> 
                  <td><span>25 - 27</span></td> 
                  <td><span>8K - 10K</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>K-XL</span></td> 
                  <td><span>2730</span></td> 
                  <td><span>11K - 11.5K</span></td> 
                  <td><span>28 - 30</span></td> 
                  <td><span>10.5K - 12K</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>KXXL</span></td> 
                  <td><span>3134</span></td> 
                  <td><span>12.5K - 1</span></td> 
                  <td><span>31 - 33</span></td> 
                  <td><span>13K - 1.5</span></td> 
                </tr> 
                <tr class=""> 
                  <td rowspan="2"><span>XS</span></td> 
                  <td><span>3436</span></td> 
                  <td rowspan="2"><span>2 - 3.5</span></td> 
                  <td rowspan="2"><span>34 - 36</span></td> 
                  <td rowspan="2"><span>2.5 - 4</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>3538</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>S</span></td> 
                  <td><span>3739</span></td> 
                  <td><span>4.5 - 5.5</span></td> 
                  <td><span>37 - 39</span></td> 
                  <td><span>5 - 6</span></td> 
                </tr> 
                  <tr class=""> 
                  <td><span>M</span></td> 
                  <td><span>4042</span></td> 
                  <td><span>6.5 - 8</span></td> 
                  <td><span>40 - 42</span></td> 
                  <td><span>7 - 8.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td rowspan="2"><span>L</span></td> 
                  <td><span>4345</span></td> 
                  <td rowspan="2"><span>8.5 - 10</span></td> 
                  <td rowspan="2"><span>43 - 45</span></td> 
                  <td rowspan="2"><span>9 - 10.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>4346</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>XL</span></td> 
                  <td><span>4648</span></td> 
                  <td><span>11 - 12.5</span></td> 
                  <td><span>46 - 48</span></td> 
                  <td><span>11.5 - 13</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>XXL</span></td> 
                  <td><span>-</span></td> 
                  <td><span>13 - 14.5</span></td> 
                  <td><span>49 - 51</span></td> 
                  <td><span>13.5 - 15</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>XXXL</span></td> 
                  <td><span>-</span></td> 
                  <td><span>15 - 17</span></td> 
                  <td><span>52 - 54</span></td> 
                  <td><span>16 - 17.5</span></td> 
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
            <img class="img-pc" src="https://img.adidas.com.hk/resources/images/size/men.png" alt="" srcset="">
            <img class="img-mob" src="https://img.adidas.com.hk/resources/images/size/menMeasure.jpg" alt="" srcset="">
          </div>
        </div>
        <div class="tips">
          <div class="tips-content">
            How to measure detail how to measure detail how to measure detail How to measure detail how to measure detail how to measure detailHow to measure detail how to measure detail how to measure detail How to measure detail how to measure detail how to measure detail
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
