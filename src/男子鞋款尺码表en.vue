<!--
 * @Description: 男子鞋款尺码表
 * @Author: lijiapeng
 * @Date: 2022-04-02 17:47:53
 * @LastEditTime: 2022-04-20 14:37:20
 * @LastEditors: lijiapeng
 * @Reference: 
-->

<template>
  <div class="content">
    <div class="top-title">
      <div class="sizeClose">
        <i id="closeDrawer" class="iconfont iconcross-small"></i>
      </div>
      <div class="text">MEN'S AND WOMEN'S SHOES SIZE CHART</div>
    </div>
    <div class="type">
      <!-- <div id="left-type" class="left active">尺碼表</div> -->
      <!-- <div id="right-type" class="right">如何測量</div> -->
      <div id="left-type" class="left active">SIZE & FIT</div>
      <div id="right-type" class="right">HOW TO MEASURE</div>
    </div>
    <div class="table-info">
      <div class="size-info" id="sizeInfo">
        <div class="size-content" id="size-content-cm">
          <div class="size-type">
            <div class="size-title">
              <span class="check-type check-active">cm</span>
              <span class="check-type" id="inches-type">Inches</span>
            </div>
            <div class="size-select">
              <div class="select-type">
                <div class="select-numb">
                  <span class="select-show">
                    <span class="show-content" id="show-content-one">EU</span>
                    <img id="down-show-one" src="https://img.adidas.com.hk/resources/images/common/downArrow.png" alt="" srcset="">
                    <img id="up-show-one" style="display: none" src="https://img.adidas.com.hk/resources/images/common/upArrow.png" alt="" srcset="">
                  </span>
                  <div class="size-options" id="size-options-one" style="display: none">
                    <div class="optionsItem" id="eu-code-one">EU</div>
                    <div class="optionsItem" id="usm-code-one">US-MEN</div>
                    <div class="optionsItem" id="usw-code-one">US-WOMEN</div>
                    <div class="optionsItem" id="cn-code-one">CN</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class='size-chart' id="eu-code-item-one">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="width: 33%"><span>UK</span></td> 
                  <td style="width: 33%"><span>EU</span></td> 
                  <td style="width: 34%"><span>Heel-toe (cm)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span> 3</span></td> 
                  <td><span> 35.5</span></td> 
                  <td><span> 21.6</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>3.5</span></td> 
                  <td><span>36</span></td> 
                  <td><span>22.1</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>4</span></td> 
                  <td><span>36.7</span></td> 
                  <td><span>22.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>4.5</span></td> 
                  <td><span>37.5</span></td> 
                  <td><span>22.9</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>5</span></td> 
                  <td><span>38</span></td> 
                  <td><span>23.3</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>5.5</span></td> 
                  <td><span>38.5</span></td> 
                  <td><span>23.5</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>6</span></td> 
                  <td><span>39.3</span></td> 
                  <td><span>24.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>6.5</span></td> 
                  <td><span>40</span></td> 
                  <td><span> 24.6</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>7</span></td> 
                  <td><span>40.7</span></td> 
                  <td><span>25.0</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>7.5</span></td> 
                  <td><span>41.3</span></td> 
                  <td><span>25.5</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>8</span></td> 
                  <td><span>42</span></td> 
                  <td><span>25.9</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>8.5</span></td> 
                  <td><span>42.7</span></td> 
                  <td><span>26.3</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>9</span></td> 
                  <td><span>43.3</span></td> 
                  <td><span>26.7</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>9.5</span></td> 
                  <td><span>44</span></td> 
                  <td><span>27.1</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>10</span></td> 
                  <td><span>44.7</span></td> 
                  <td><span> 27.6</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>10.5</span></td> 
                  <td><span>45.3</span></td> 
                  <td><span>28.0</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>11</span></td> 
                  <td><span>46</span></td> 
                  <td><span>28.4</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>11.5</span></td> 
                  <td><span>46.7</span></td> 
                  <td><span>28.8</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>12</span></td> 
                  <td><span>47.3</span></td> 
                  <td><span>29.3</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>12.5</span></td> 
                  <td><span>48</span></td> 
                  <td><span>29.7</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>13</span></td> 
                  <td><span>48.7</span></td> 
                  <td><span>30.1</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>13.5</span></td> 
                  <td><span>49.3</span></td> 
                  <td><span>30.5</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>14</span></td> 
                  <td><span>50</span></td> 
                  <td><span>31.0</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>14.5</span></td> 
                  <td><span>50.7</span></td> 
                  <td><span>31.4</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>15</span></td> 
                  <td><span>51.3</span></td> 
                  <td><span>31.8</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>16</span></td> 
                  <td><span>52.7</span></td> 
                  <td><span>32.6</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>17</span></td> 
                  <td><span>53.3</span></td> 
                  <td><span>33.5</span></td> 
                </tr> 

              </tbody> 
            </table>
          </div>
          <div class='size-chart' id="usm-code-item-one" style="display:none">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="width: 33%"><span>UK</span></td> 
                  <td style="width: 33%"><span>US-MEN</span></td> 
                  <td style="width: 34%"><span>Heel-toe (cm)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span> 3</span></td> 
                  <td><span> 3.5</span></td> 
                  <td><span> 21.6</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>3.5</span></td> 
                  <td><span>4</span></td> 
                  <td><span>22.1</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>4</span></td> 
                  <td><span>4.5</span></td> 
                  <td><span>22.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>4.5</span></td> 
                  <td><span>5</span></td> 
                  <td><span>22.9</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>5</span></td> 
                  <td><span>5.5</span></td> 
                  <td><span>23.3</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>5.5</span></td> 
                  <td><span>6</span></td> 
                  <td><span>23.5</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>6</span></td> 
                  <td><span>6.5</span></td> 
                  <td><span>24.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>6.5</span></td> 
                  <td><span>7</span></td> 
                  <td><span> 24.6</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>7</span></td> 
                  <td><span>7.5</span></td> 
                  <td><span>25.0</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>7.5</span></td> 
                  <td><span>8</span></td> 
                  <td><span>25.5</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>8</span></td> 
                  <td><span>8.5</span></td> 
                  <td><span>25.9</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>8.5</span></td> 
                  <td><span>9</span></td> 
                  <td><span>26.3</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>9</span></td> 
                  <td><span>9.5</span></td> 
                  <td><span>26.7</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>9.5</span></td> 
                  <td><span>10</span></td> 
                  <td><span>27.1</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>10</span></td> 
                  <td><span>10.5</span></td> 
                  <td><span> 27.6</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>10.5</span></td> 
                  <td><span>11</span></td> 
                  <td><span>28.0</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>11</span></td> 
                  <td><span>11.5</span></td> 
                  <td><span>28.4</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>11.5</span></td> 
                  <td><span>12</span></td> 
                  <td><span>28.8</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>12</span></td> 
                  <td><span>12.5</span></td> 
                  <td><span>29.3</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>12.5</span></td> 
                  <td><span>13</span></td> 
                  <td><span>29.7</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>13</span></td> 
                  <td><span>13.5</span></td> 
                  <td><span>30.1</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>13.5</span></td> 
                  <td><span>14</span></td> 
                  <td><span>30.5</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>14</span></td> 
                  <td><span>14.5</span></td> 
                  <td><span>31.0</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>14.5</span></td> 
                  <td><span>15</span></td> 
                  <td><span>31.4</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>15</span></td> 
                  <td><span>16</span></td> 
                  <td><span>31.8</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>16</span></td> 
                  <td><span>17</span></td> 
                  <td><span>32.6</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>17</span></td> 
                  <td><span>18</span></td> 
                  <td><span>33.5</span></td> 
                </tr> 
              </tbody> 
            </table>
          </div>
          <div class='size-chart' id="usw-code-item-one" style="display:none">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="width: 33%"><span>UK</span></td> 
                  <td style="width: 33%"><span>US-WOMEN</span></td> 
                  <td style="width: 34%"><span>Heel-toe (cm)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span> 3</span></td> 
                  <td><span> 3.5</span></td> 
                  <td><span> 21.6</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>3.5</span></td> 
                  <td><span>5</span></td> 
                  <td><span>22.1</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>4</span></td> 
                  <td><span>5.5</span></td> 
                  <td><span>22.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>4.5</span></td> 
                  <td><span>6</span></td> 
                  <td><span>22.9</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>5</span></td> 
                  <td><span>6.5</span></td> 
                  <td><span>23.3</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>5.5</span></td> 
                  <td><span>7</span></td> 
                  <td><span>23.5</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>6</span></td> 
                  <td><span>7.5</span></td> 
                  <td><span>24.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>6.5</span></td> 
                  <td><span>8</span></td> 
                  <td><span> 24.6</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>7</span></td> 
                  <td><span>8.5</span></td> 
                  <td><span>25.0</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>7.5</span></td> 
                  <td><span>9</span></td> 
                  <td><span>25.5</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>8</span></td> 
                  <td><span>9.5</span></td> 
                  <td><span>25.9</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>8.5</span></td> 
                  <td><span>10</span></td> 
                  <td><span>26.3</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>9</span></td> 
                  <td><span>10.5</span></td> 
                  <td><span>26.7</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>9.5</span></td> 
                  <td><span>11</span></td> 
                  <td><span>27.1</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>10</span></td> 
                  <td><span>11.5</span></td> 
                  <td><span> 27.6</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>10.5</span></td> 
                  <td><span>12</span></td> 
                  <td><span>28.0</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>11</span></td> 
                  <td><span>12.5</span></td> 
                  <td><span>28.4</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>11.5</span></td> 
                  <td><span>13</span></td> 
                  <td><span>28.8</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>12</span></td> 
                  <td><span>13.5</span></td> 
                  <td><span>29.3</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>12.5</span></td> 
                  <td><span>14</span></td> 
                  <td><span>29.7</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>13</span></td> 
                  <td><span>14.5</span></td> 
                  <td><span>30.1</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>13.5</span></td> 
                  <td><span>15</span></td> 
                  <td><span>30.5</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>14</span></td> 
                  <td><span>15.5</span></td> 
                  <td><span>31.0</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>14.5</span></td> 
                  <td><span> -</span></td> 
                  <td><span>31.4</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>15</span></td> 
                  <td><span> -</span></td> 
                  <td><span>31.8</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>16</span></td> 
                  <td><span> -</span></td> 
                  <td><span>32.6</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>17</span></td> 
                  <td><span> -</span></td> 
                  <td><span>33.5</span></td> 
                </tr> 
              </tbody> 
            </table>
          </div>
          <div class='size-chart' id="cn-code-item-one" style="display:none">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="width: 33%"><span>UK</span></td> 
                  <td style="width: 33%"><span>CN</span></td> 
                  <td style="width: 34%"><span>Heel-toe (cm)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span> 3</span></td> 
                  <td><span>215</span></td> 
                  <td><span> 21.6</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>3.5</span></td> 
                  <td><span>220</span></td> 
                  <td><span>22.1</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>4</span></td> 
                  <td><span>225</span></td> 
                  <td><span>22.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>4.5</span></td> 
                  <td><span>230</span></td> 
                  <td><span>22.9</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>5</span></td> 
                  <td><span>235</span></td> 
                  <td><span>23.3</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>5.5</span></td> 
                  <td><span>235</span></td> 
                  <td><span>23.5</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>6</span></td> 
                  <td><span>240</span></td> 
                  <td><span>24.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>6.5</span></td> 
                  <td><span>245</span></td> 
                  <td><span> 24.6</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>7</span></td> 
                  <td><span>250</span></td> 
                  <td><span>25.0</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>7.5</span></td> 
                  <td><span>255</span></td> 
                  <td><span>25.5</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>8</span></td> 
                  <td><span>260</span></td> 
                  <td><span>25.9</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>8.5</span></td> 
                  <td><span>265</span></td> 
                  <td><span>26.3</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>9</span></td> 
                  <td><span>265</span></td> 
                  <td><span>26.7</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>9.5</span></td> 
                  <td><span>270</span></td> 
                  <td><span>27.1</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>10</span></td> 
                  <td><span>275</span></td> 
                  <td><span> 27.6</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>10.5</span></td> 
                  <td><span>280</span></td> 
                  <td><span>28.0</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>11</span></td> 
                  <td><span>285</span></td> 
                  <td><span>28.4</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>11.5</span></td> 
                  <td><span>290</span></td> 
                  <td><span>28.8</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>12</span></td> 
                  <td><span>290</span></td> 
                  <td><span>29.3</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>12.5</span></td> 
                  <td><span>295</span></td> 
                  <td><span>29.7</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>13</span></td> 
                  <td><span>300</span></td> 
                  <td><span>30.1</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>13.5</span></td> 
                  <td><span>305</span></td> 
                  <td><span>30.5</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>14</span></td> 
                  <td><span>310</span></td> 
                  <td><span>31.0</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>14.5</span></td> 
                  <td><span>315</span></td> 
                  <td><span>31.4</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>15</span></td> 
                  <td><span>320</span></td> 
                  <td><span>31.8</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>16</span></td> 
                  <td><span>325</span></td> 
                  <td><span>32.6</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>17</span></td> 
                  <td><span>335</span></td> 
                  <td><span>33.5</span></td> 
                </tr> 
              </tbody> 
            </table>
          </div>
        </div>
        <div class="size-content" id="size-content-inches" style="display: none">
          <div class="size-type">
            <div class="size-title">
              <span class="check-type" id="cm-type">cm</span>
              <span class="check-type check-active">Inches</span>
            </div>
            <div class="size-select">
              <div class="select-type">
                <div class="select-numb">
                  <span class="select-show">
                    <span class="show-content" id="show-content-two">EU</span>
                    <img id="down-show-two" src="https://img.adidas.com.hk/resources/images/common/downArrow.png" alt="" srcset="">
                    <img id="up-show-two" style="display: none" src="https://img.adidas.com.hk/resources/images/common/upArrow.png" alt="" srcset="">
                  </span>
                  <div class="size-options" id="size-options-two" style="display: none">
                    <div class="optionsItem" id="eu-code-two">EU</div>
                    <div class="optionsItem" id="usm-code-two">US-MEN</div>
                    <div class="optionsItem" id="usw-code-two">US-WOMEN</div>
                    <div class="optionsItem" id="cn-code-two">CN</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class='size-chart' id="eu-code-item-two">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="width: 33%"><span>UK</span></td> 
                  <td style="width: 33%"><span>EU</span></td> 
                  <td style="width: 34%"><span>Heel-toe (inch)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span> 3</span></td> 
                  <td><span> 35.5</span></td> 
                  <td><span>8.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>3.5</span></td> 
                  <td><span>36</span></td> 
                  <td><span>8.7</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>4</span></td> 
                  <td><span>36.7</span></td> 
                  <td><span>8.9</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>4.5</span></td> 
                  <td><span>37.5</span></td> 
                  <td><span>9</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>5</span></td> 
                  <td><span>38</span></td> 
                  <td><span>9.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>5.5</span></td> 
                  <td><span>38.5</span></td> 
                  <td><span>9.4</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>6</span></td> 
                  <td><span>39.3</span></td> 
                  <td><span>9.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>6.5</span></td> 
                  <td><span>40</span></td> 
                  <td><span>9.7</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>7</span></td> 
                  <td><span>40.7</span></td> 
                  <td><span>9.8</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>7.5</span></td> 
                  <td><span>41.3</span></td> 
                  <td><span>10</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>8</span></td> 
                  <td><span>42</span></td> 
                  <td><span>10.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>8.5</span></td> 
                  <td><span>42.7</span></td> 
                  <td><span>10.4</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>9</span></td> 
                  <td><span>43.3</span></td> 
                  <td><span>10.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>9.5</span></td> 
                  <td><span>44</span></td> 
                  <td><span>10.7</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>10</span></td> 
                  <td><span>44.7</span></td> 
                  <td><span>10.9</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>10.5</span></td> 
                  <td><span>45.3</span></td> 
                  <td><span>11</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>11</span></td> 
                  <td><span>46</span></td> 
                  <td><span>11.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>11.5</span></td> 
                  <td><span>46.7</span></td> 
                  <td><span>11.3</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>12</span></td> 
                  <td><span>47.3</span></td> 
                  <td><span>11.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>12.5</span></td> 
                  <td><span>48</span></td> 
                  <td><span>11.7</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>13</span></td> 
                  <td><span>48.7</span></td> 
                  <td><span>11.9</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>13.5</span></td> 
                  <td><span>49.3</span></td> 
                  <td><span>12</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>14</span></td> 
                  <td><span>50</span></td> 
                  <td><span>12.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>14.5</span></td> 
                  <td><span>50.7</span></td> 
                  <td><span>12.4</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>15</span></td> 
                  <td><span>51.3</span></td> 
                  <td><span>12.7</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>16</span></td> 
                  <td><span>52.7</span></td> 
                  <td><span>13</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>17</span></td> 
                  <td><span>53.3</span></td> 
                  <td><span>13.3</span></td> 
                </tr> 

              </tbody> 
            </table>
          </div>
          <div class='size-chart' id="usm-code-item-two" style="display:none">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="width: 33%"><span>UK</span></td> 
                  <td style="width: 33%"><span>US-MEN</span></td> 
                  <td style="width: 34%"><span>Heel-toe (inch)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span> 3</span></td> 
                  <td><span> 3.5</span></td> 
                  <td><span>8.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>3.5</span></td> 
                  <td><span>4</span></td> 
                  <td><span>8.7</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>4</span></td> 
                  <td><span>4.5</span></td> 
                  <td><span>8.9</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>4.5</span></td> 
                  <td><span>5</span></td> 
                  <td><span>9</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>5</span></td> 
                  <td><span>5.5</span></td> 
                  <td><span>9.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>5.5</span></td> 
                  <td><span>6</span></td> 
                  <td><span>9.4</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>6</span></td> 
                  <td><span>6.5</span></td> 
                  <td><span>9.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>6.5</span></td> 
                  <td><span>7</span></td> 
                  <td><span>9.7</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>7</span></td> 
                  <td><span>7.5</span></td> 
                  <td><span>9.8</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>7.5</span></td> 
                  <td><span>8</span></td> 
                  <td><span>10</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>8</span></td> 
                  <td><span>8.5</span></td> 
                  <td><span>10.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>8.5</span></td> 
                  <td><span>9</span></td> 
                  <td><span>10.4</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>9</span></td> 
                  <td><span>9.5</span></td> 
                  <td><span>10.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>9.5</span></td> 
                  <td><span>10</span></td> 
                  <td><span>10.7</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>10</span></td> 
                  <td><span>10.5</span></td> 
                  <td><span>10.9</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>10.5</span></td> 
                  <td><span>11</span></td> 
                  <td><span>11</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>11</span></td> 
                  <td><span>11.5</span></td> 
                  <td><span>11.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>11.5</span></td> 
                  <td><span>12</span></td> 
                  <td><span>11.3</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>12</span></td> 
                  <td><span>12.5</span></td> 
                  <td><span>11.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>12.5</span></td> 
                  <td><span>13</span></td> 
                  <td><span>11.7</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>13</span></td> 
                  <td><span>13.5</span></td> 
                  <td><span>11.9</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>13.5</span></td> 
                  <td><span>14</span></td> 
                  <td><span>12</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>14</span></td> 
                  <td><span>14.5</span></td> 
                  <td><span>12.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>14.5</span></td> 
                  <td><span>15</span></td> 
                  <td><span>12.4</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>15</span></td> 
                  <td><span>16</span></td> 
                  <td><span>12.7</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>16</span></td> 
                  <td><span>17</span></td> 
                  <td><span>13</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>17</span></td> 
                  <td><span>18</span></td> 
                  <td><span>13.3</span></td> 
                </tr> 
              </tbody> 
            </table>
          </div>
          <div class='size-chart' id="usw-code-item-two" style="display:none">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="width: 33%"><span>UK</span></td> 
                  <td style="width: 33%"><span>US-WOMEN</span></td> 
                  <td style="width: 34%"><span>Heel-toe (inch)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span> 3</span></td> 
                  <td><span> 3.5</span></td> 
                  <td><span>8.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>3.5</span></td> 
                  <td><span>5</span></td> 
                  <td><span>8.7</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>4</span></td> 
                  <td><span>5.5</span></td> 
                  <td><span>8.9</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>4.5</span></td> 
                  <td><span>6</span></td> 
                  <td><span>9</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>5</span></td> 
                  <td><span>6.5</span></td> 
                  <td><span>9.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>5.5</span></td> 
                  <td><span>7</span></td> 
                  <td><span>9.4</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>6</span></td> 
                  <td><span>7.5</span></td> 
                  <td><span>9.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>6.5</span></td> 
                  <td><span>8</span></td> 
                  <td><span>9.7</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>7</span></td> 
                  <td><span>8.5</span></td> 
                  <td><span>9.8</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>7.5</span></td> 
                  <td><span>9</span></td> 
                  <td><span>10</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>8</span></td> 
                  <td><span>9.5</span></td> 
                  <td><span>10.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>8.5</span></td> 
                  <td><span>10</span></td> 
                  <td><span>10.4</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>9</span></td> 
                  <td><span>10.5</span></td> 
                  <td><span>10.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>9.5</span></td> 
                  <td><span>11</span></td> 
                  <td><span>10.7</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>10</span></td> 
                  <td><span>11.5</span></td> 
                  <td><span>10.9</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>10.5</span></td> 
                  <td><span>12</span></td> 
                  <td><span>11</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>11</span></td> 
                  <td><span>12.5</span></td> 
                  <td><span>11.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>11.5</span></td> 
                  <td><span>13</span></td> 
                  <td><span>11.3</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>12</span></td> 
                  <td><span>13.5</span></td> 
                  <td><span>11.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>12.5</span></td> 
                  <td><span>14</span></td> 
                  <td><span>11.7</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>13</span></td> 
                  <td><span>14.5</span></td> 
                  <td><span>11.9</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>13.5</span></td> 
                  <td><span>15</span></td> 
                  <td><span>12</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>14</span></td> 
                  <td><span>15.5</span></td> 
                  <td><span>12.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>14.5</span></td> 
                  <td><span> -</span></td> 
                  <td><span>12.4</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>15</span></td> 
                  <td><span> -</span></td> 
                  <td><span>12.7</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>16</span></td> 
                  <td><span> -</span></td> 
                  <td><span>13</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>17</span></td> 
                  <td><span> -</span></td> 
                  <td><span>13.3</span></td> 
                </tr> 
              </tbody> 
            </table>
          </div>
          <div class='size-chart' id="cn-code-item-two" style="display:none">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="width: 33%"><span>UK</span></td> 
                  <td style="width: 33%"><span>CN</span></td> 
                  <td style="width: 34%"><span>Heel-toe (inch)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span> 3</span></td> 
                  <td><span>215</span></td> 
                  <td><span>8.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>3.5</span></td> 
                  <td><span>220</span></td> 
                  <td><span>8.7</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>4</span></td> 
                  <td><span>225</span></td> 
                  <td><span>8.9</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>4.5</span></td> 
                  <td><span>230</span></td> 
                  <td><span>9</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>5</span></td> 
                  <td><span>235</span></td> 
                  <td><span>9.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>5.5</span></td> 
                  <td><span>235</span></td> 
                  <td><span>9.4</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>6</span></td> 
                  <td><span>240</span></td> 
                  <td><span>9.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>6.5</span></td> 
                  <td><span>245</span></td> 
                  <td><span>9.7</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>7</span></td> 
                  <td><span>250</span></td> 
                  <td><span>9.8</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>7.5</span></td> 
                  <td><span>255</span></td> 
                  <td><span>10</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>8</span></td> 
                  <td><span>260</span></td> 
                  <td><span>10.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>8.5</span></td> 
                  <td><span>265</span></td> 
                  <td><span>10.4</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>9</span></td> 
                  <td><span>265</span></td> 
                  <td><span>10.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>9.5</span></td> 
                  <td><span>270</span></td> 
                  <td><span>10.7</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>10</span></td> 
                  <td><span>275</span></td> 
                  <td><span>10.9</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>10.5</span></td> 
                  <td><span>280</span></td> 
                  <td><span>11</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>11</span></td> 
                  <td><span>285</span></td> 
                  <td><span>11.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>11.5</span></td> 
                  <td><span>290</span></td> 
                  <td><span>11.3</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>12</span></td> 
                  <td><span>290</span></td> 
                  <td><span>11.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>12.5</span></td> 
                  <td><span>295</span></td> 
                  <td><span>11.7</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>13</span></td> 
                  <td><span>300</span></td> 
                  <td><span>11.9</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>13.5</span></td> 
                  <td><span>305</span></td> 
                  <td><span>12</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>14</span></td> 
                  <td><span>310</span></td> 
                  <td><span>12.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>14.5</span></td> 
                  <td><span>315</span></td> 
                  <td><span>12.4</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>15</span></td> 
                  <td><span>320</span></td> 
                  <td><span>12.7</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>16</span></td> 
                  <td><span>325</span></td> 
                  <td><span>13</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>17</span></td> 
                  <td><span>335</span></td> 
                  <td><span>13.3</span></td> 
                </tr> 
              </tbody> 
            </table>
          </div>
        </div>
      </div>
      <div class="size-measure" id="measure">
        <div class="measure">
          <div class="img-info">
            <div class="instructions">
              <div class="steps-type">
                <ul class="steps">
                  <li class="step">
                    <span class="step-title">1. </span>
                    <span class="step-body">Step on а piece of paper with your heel slightly touching a wall behind.</span>
                  </li>
                  <li class="step">
                    <span class="step-title">2. </span>
                    <span class="step-body">Мark the end of your longest toe on the paper (you might need a friend to help you) and measure from the wall to the marking.</span>
                  </li>
                  <li class="step">
                    <span class="step-title">3. </span>
                    <span class="step-body">Do the same for the other foot and compare measurements with our size chart to get the right size.</span>
                  </li>
                </ul>
              </div>
            </div>
            <div class="image-container">
              <img src="https://img.adidas.com.hk/resources/images/size/measure-shoes.png" alt="" srcset="">
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
