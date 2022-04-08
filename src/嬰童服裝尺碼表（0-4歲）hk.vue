<!--
 * @Description: 嬰童服裝尺碼表（0-4歲）hk
 * @Author: lijiapeng
 * @Date: 2022-04-08 10:17:26
 * @LastEditTime: 2022-04-08 10:38:53
 * @LastEditors: lijiapeng
 * @Reference: 
-->

<template>
  <div class="content">
    <div class="top-title">
      <div class="sizeClose">
        <i id="closeDrawer" class="iconfont iconcross-small"></i>
      </div>
      <div class="text">嬰童服裝尺碼表（0-4歲）</div>
    </div>
    <div class="type">
      <div id="left-type" class="left active">尺碼表</div>
      <div id="right-type" class="right">如何測量</div>
      <!-- <div id="left-type" class="left active">SIZE & FIT</div> -->
      <!-- <div id="right-type" class="right">How to Measure</div> -->
    </div>
    <div class="table-info">
      <div class="size-info" id="sizeInfo">
        <div class="size-content scroll-wrap-roll">
          <div class="size-type">
            <div class="size-title">
              <span class="text-small"></span>
            </div>
          </div>
          <div class='size-chart'>
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td><span>英國碼 (UK)</span></td> 
                  <td><span>參考年齡</span></td> 
                  <td><span>高度 (厘米)</span></td> 
                  <td><span>胸圍 (厘米)</span></td> 
                  <td><span>腰圍 (厘米)</span></td> 
                  <td><span>臀圍 (厘米)</span></td> 
                  <td><span>內長 (厘米)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>56</span></td> 
                  <td><span>0 - 3 months</span></td> 
                  <td><span>56 - 62</span></td> 
                  <td><span>39 - 43</span></td> 
                  <td><span>39 - 43</span></td> 
                  <td><span>37 - 42</span></td> 
                  <td><span>19.1</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>62</span></td> 
                  <td><span>3 months</span></td> 
                  <td><span>62 - 69</span></td> 
                  <td><span>43 - 45</span></td> 
                  <td><span>43 - 45</span></td> 
                  <td><span>42 - 45</span></td> 
                  <td><span>21.8</span></td> 
                </tr> 
                  <tr class=""> 
                  <td><span>68</span></td> 
                  <td><span>3 - 6 months</span></td> 
                  <td><span>69 - 74</span></td> 
                  <td><span>45 - 47</span></td> 
                  <td><span>45 - 46</span></td> 
                  <td><span>45 - 47</span></td> 
                  <td><span>24.1</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>74</span></td> 
                  <td><span>6 - 9 months</span></td> 
                  <td><span>74 - 80</span></td> 
                  <td><span>47 - 50</span></td> 
                  <td><span>46 - 49</span></td> 
                  <td><span>47 - 50</span></td> 
                  <td><span>26.9</span></td> 
                </tr> 
                  <tr class=""> 
                  <td><span>80</span></td> 
                  <td><span>9 - 12 months</span></td> 
                  <td><span>80 - 86</span></td> 
                  <td><span>50 - 51</span></td> 
                  <td><span>49 - 50</span></td> 
                  <td><span>50 - 52</span></td> 
                  <td><span>31.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>86</span></td> 
                  <td><span>12-18 months</span></td> 
                  <td><span>86 - 91</span></td> 
                  <td><span>51 - 52</span></td> 
                  <td><span>50 - 51</span></td> 
                  <td><span>52 - 53</span></td> 
                  <td><span>34.5</span></td> 
                </tr> 
                  <tr class=""> 
                  <td><span>92</span></td> 
                  <td><span>1~2 years</span></td> 
                  <td><span>86 - 91</span></td> 
                  <td><span>52 - 53</span></td> 
                  <td><span>51 - 52</span></td> 
                  <td><span>52 - 53</span></td> 
                  <td><span>38.1</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>98</span></td> 
                  <td><span>2~3 years</span></td> 
                  <td><span>94 - 99</span></td> 
                  <td><span>53 - 55</span></td> 
                  <td><span>52 - 53</span></td> 
                  <td><span>53 - 56</span></td> 
                  <td><span>40.6</span></td> 
                </tr> 
                  <tr class=""> 
                  <td><span>104</span></td> 
                  <td><span>3~4 years</span></td> 
                  <td><span>102 - 104</span></td> 
                  <td><span>55 - 56</span></td> 
                  <td><span>53 - 55</span></td> 
                  <td><span>56 - 60</span></td> 
                  <td><span>45.7</span></td> 
                </tr> 
              </tbody> 
            </table>
          </div>
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
          如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，如何测试信息，
        </div>
      </div>
    </div>
  </div>
</template>