<!--
 * @Description: 大童鞋款尺碼表-8-14歲
 * @Author: lijiapeng
 * @Date: 2022-04-07 14:55:53
 * @LastEditTime: 2022-04-20 12:29:57
 * @LastEditors: lijiapeng
 * @Reference: 
-->

<template>
  <div class="content">
    <div class="top-title">
      <div class="sizeClose">
        <i id="closeDrawer" class="iconfont iconcross-small"></i>
      </div>
      <div class="text">小童(4-8歲)及大童(8-14)歲鞋款尺碼表</div>
    </div>
    <div class="type">
      <div id="left-type" class="left active">尺碼表</div>
      <div id="right-type" class="right">如何測量</div>
      <!-- <div id="left-type" class="left active">SIZE & FIT</div> -->
      <!-- <div id="right-type" class="right">HOW TO MEASURE</div> -->
    </div>
    <div class="table-info">
      <div class="size-info" id="sizeInfo">
        <div class="size-content" id="size-content-cm">
          <div class="size-type">
            <div class="size-title">
              <span class="check-type check-active">厘米</span>
              <span class="check-type" id="inches-type">英寸</span>
            </div>
            <div class="size-select">
              <div class="select-type">
                <div class="select-numb">
                  <span class="select-show">
                    <span class="show-content" id="show-content-one">歐洲碼 (EU)</span>
                    <img id="down-show-one" src="https://img.adidas.com.hk/resources/images/common/downArrow.png" alt="" srcset="">
                    <img id="up-show-one" style="display: none" src="https://img.adidas.com.hk/resources/images/common/upArrow.png" alt="" srcset="">
                  </span>
                  <div class="size-options" id="size-options-one" style="display: none">
                    <div class="optionsItem" id="eu-code-one">歐洲碼 (EU)</div>
                    <div class="optionsItem" id="us-code-one">美國碼 (US)</div>
                    <div class="optionsItem" id="cn-code-one">中國碼 (CN)</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class='size-chart' id="eu-code-item-one">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="width: 33%"><span>英國碼(UK)</span></td> 
                  <td style="width: 33%"><span>歐洲碼 (EU)</span></td> 
                  <td style="width: 34%"><span>腳掌尺寸(厘米)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>10K</span></td> 
                  <td><span>28</span></td> 
                  <td><span>16.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>10.5K</span></td> 
                  <td><span>28.5</span></td> 
                  <td><span>17.0</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>11K</span></td> 
                  <td><span>29</span></td> 
                  <td><span>17.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>11.5K</span></td> 
                  <td><span>30</span></td> 
                  <td><span>17.8</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>12K</span></td> 
                  <td><span>30.5</span></td> 
                  <td><span>18.3</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>12.5K</span></td> 
                  <td><span>31</span></td> 
                  <td><span>18.8</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>13K</span></td> 
                  <td><span>31.5</span></td> 
                  <td><span>19.1</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>13.5K</span></td> 
                  <td><span>32</span></td> 
                  <td><span>19.6</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>1</span></td> 
                  <td><span>33</span></td> 
                  <td><span>20.1</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>1.5</span></td> 
                  <td><span>33.5</span></td> 
                  <td><span>20.3</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>2</span></td> 
                  <td><span>34</span></td> 
                  <td><span>20.8</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>2.5</span></td> 
                  <td><span>35</span></td> 
                  <td><span>21.1</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>3</span></td> 
                  <td><span>35</span></td> 
                  <td><span>21.6</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>3.5</span></td> 
                  <td><span>36</span></td> 
                  <td><span>22.1</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>4</span></td> 
                  <td><span>36.7</span></td> 
                  <td><span>22.6</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>4.5</span></td> 
                  <td><span>37.3</span></td> 
                  <td><span>22.9</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>5</span></td> 
                  <td><span>38</span></td> 
                  <td><span>23.4</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>5.5</span></td> 
                  <td><span>38.7</span></td> 
                  <td><span>23.8</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>6</span></td> 
                  <td><span>39.3</span></td> 
                  <td><span>24.1</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>6.5</span></td> 
                  <td><span>40</span></td> 
                  <td><span>24.6</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>7</span></td> 
                  <td><span>40.7</span></td> 
                  <td><span>24.9</span></td> 
                </tr> 
              </tbody> 
            </table>
          </div>
          <div class='size-chart' id="us-code-item-one" style="display:none">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="width: 33%"><span>英國碼(UK)</span></td> 
                  <td style="width: 33%"><span>美國碼 (US)</span></td> 
                  <td style="width: 34%"><span>腳掌尺寸(厘米)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>10K</span></td> 
                  <td><span>10.5K</span></td> 
                  <td><span>16.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>10.5K</span></td> 
                  <td><span>11K</span></td> 
                  <td><span>17.0</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>11K</span></td> 
                  <td><span>11.5K</span></td> 
                  <td><span>17.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>11.5K</span></td> 
                  <td><span>12K</span></td> 
                  <td><span>17.8</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>12K</span></td> 
                  <td><span>12.5K</span></td> 
                  <td><span>18.3</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>12.5K</span></td> 
                  <td><span>13K</span></td> 
                  <td><span>18.8</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>13K</span></td> 
                  <td><span>13.5K</span></td> 
                  <td><span>19.1</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>13.5K</span></td> 
                  <td><span>1</span></td> 
                  <td><span>19.6</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>1</span></td> 
                  <td><span>1.5</span></td> 
                  <td><span>20.1</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>1.5</span></td> 
                  <td><span>2</span></td> 
                  <td><span>20.3</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>2</span></td> 
                  <td><span>2.5</span></td> 
                  <td><span>20.8</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>2.5</span></td> 
                  <td><span>3</span></td> 
                  <td><span>21.1</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>3</span></td> 
                  <td><span>3.5</span></td> 
                  <td><span>21.6</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>3.5</span></td> 
                  <td><span>4</span></td> 
                  <td><span>22.1</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>4</span></td> 
                  <td><span>4.5</span></td> 
                  <td><span>22.6</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>4.5</span></td> 
                  <td><span>5</span></td> 
                  <td><span>22.9</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>5</span></td> 
                  <td><span>5.5</span></td> 
                  <td><span>23.4</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>5.5</span></td> 
                  <td><span>6</span></td> 
                  <td><span>23.8</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>6</span></td> 
                  <td><span>6.5</span></td> 
                  <td><span>24.1</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>6.5</span></td> 
                  <td><span>7</span></td> 
                  <td><span>24.6</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>7</span></td> 
                  <td><span>7.5</span></td> 
                  <td><span>24.9</span></td> 
                </tr> 
              </tbody>
            </table>
          </div>
          <div class='size-chart' id="cn-code-item-one" style="display:none">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="width: 33%"><span>英國碼(UK)</span></td> 
                  <td style="width: 33%"><span>中國碼 (CN)</span></td> 
                  <td style="width: 34%"><span>腳掌尺寸(厘米)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>10K</span></td> 
                  <td><span>165</span></td> 
                  <td><span>16.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>10.5K</span></td> 
                  <td><span>170</span></td> 
                  <td><span>17.0</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>11K</span></td> 
                  <td><span>175</span></td> 
                  <td><span>17.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>11.5K</span></td> 
                  <td><span>180</span></td> 
                  <td><span>17.8</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>12K</span></td> 
                  <td><span>180</span></td> 
                  <td><span>18.3</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>12.5K</span></td> 
                  <td><span>185</span></td> 
                  <td><span>18.8</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>13K</span></td> 
                  <td><span>190</span></td> 
                  <td><span>19.1</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>13.5K</span></td> 
                  <td><span>195</span></td> 
                  <td><span>19.6</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>1</span></td> 
                  <td><span>200</span></td> 
                  <td><span>20.1</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>1.5</span></td> 
                  <td><span>205</span></td> 
                  <td><span>20.3</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>2</span></td> 
                  <td><span>210</span></td> 
                  <td><span>20.8</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>2.5</span></td> 
                  <td><span>210</span></td> 
                  <td><span>21.1</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>3</span></td> 
                  <td><span>215</span></td> 
                  <td><span>21.6</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>3.5</span></td> 
                  <td><span>220</span></td> 
                  <td><span>22.1</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>4</span></td> 
                  <td><span>225</span></td> 
                  <td><span>22.6</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>4.5</span></td> 
                  <td><span>230</span></td> 
                  <td><span>22.9</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>5</span></td> 
                  <td><span>235</span></td> 
                  <td><span>23.4</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>5.5</span></td> 
                  <td><span>235</span></td> 
                  <td><span>23.8</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>6</span></td> 
                  <td><span>240</span></td> 
                  <td><span>24.1</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>6.5</span></td> 
                  <td><span>245</span></td> 
                  <td><span>24.6</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>7</span></td> 
                  <td><span> -</span></td> 
                  <td><span>24.9</span></td> 
                </tr> 
              </tbody>
            </table>
          </div>
        </div>
        <div class="size-content" id="size-content-inches" style="display: none">
          <div class="size-type">
            <div class="size-title">
              <span class="check-type" id="cm-type">厘米</span>
              <span class="check-type check-active">英寸</span>
            </div>
            <div class="size-select">
              <div class="select-type">
                <div class="select-numb">
                  <span class="select-show">
                    <span class="show-content" id="show-content-two">歐洲碼 (EU)</span>
                    <img id="down-show-two" src="https://img.adidas.com.hk/resources/images/common/downArrow.png" alt="" srcset="">
                    <img id="up-show-two" style="display: none" src="https://img.adidas.com.hk/resources/images/common/upArrow.png" alt="" srcset="">
                  </span>
                  <div class="size-options" id="size-options-two" style="display: none">
                    <div class="optionsItem" id="eu-code-two">歐洲碼 (EU)</div>
                    <div class="optionsItem" id="us-code-two">美國碼 (US)</div>
                    <div class="optionsItem" id="cn-code-two">中國碼 (CN)</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class='size-chart' id="eu-code-item-two">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="width: 33%"><span>英國碼(UK)</span></td> 
                  <td style="width: 33%"><span>歐洲碼 (EU)</span></td> 
                  <td style="width: 34%"><span>腳掌尺寸(英寸)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>10K</span></td> 
                  <td><span>28</span></td> 
                  <td><span>6.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>10.5K</span></td> 
                  <td><span>28.5</span></td> 
                  <td><span>6.7</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>11K</span></td> 
                  <td><span>29</span></td> 
                  <td><span>6.9</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>11.5K</span></td> 
                  <td><span>30</span></td> 
                  <td><span>7</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>12K</span></td> 
                  <td><span>30.5</span></td> 
                  <td><span>7.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>12.5K</span></td> 
                  <td><span>31</span></td> 
                  <td><span>7.4</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>13K</span></td> 
                  <td><span>31.5</span></td> 
                  <td><span>7.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>13.5K</span></td> 
                  <td><span>32</span></td> 
                  <td><span>7.7</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>1</span></td> 
                  <td><span>33</span></td> 
                  <td><span>7.9</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>1.5</span></td> 
                  <td><span>33.5</span></td> 
                  <td><span>8</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>2</span></td> 
                  <td><span>34</span></td> 
                  <td><span>8.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>2.5</span></td> 
                  <td><span>35</span></td> 
                  <td><span>8.3</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>3</span></td> 
                  <td><span>35</span></td> 
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
                  <td><span>37.3</span></td> 
                  <td><span>9</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>5</span></td> 
                  <td><span>38</span></td> 
                  <td><span>9.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>5.5</span></td> 
                  <td><span>38.7</span></td> 
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
              </tbody>  
            </table>
          </div>
          <div class='size-chart' id="us-code-item-two" style="display:none">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="width: 33%"><span>英國碼(UK)</span></td> 
                  <td style="width: 33%"><span>美國碼 (US)</span></td> 
                  <td style="width: 34%"><span>腳掌尺寸(英寸)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>10K</span></td> 
                  <td><span>10.5K</span></td> 
                  <td><span>6.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>10.5K</span></td> 
                  <td><span>11K</span></td> 
                  <td><span>6.7</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>11K</span></td> 
                  <td><span>11.5K</span></td> 
                  <td><span>6.9</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>11.5K</span></td> 
                  <td><span>12K</span></td> 
                  <td><span>7</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>12K</span></td> 
                  <td><span>12.5K</span></td> 
                  <td><span>7.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>12.5K</span></td> 
                  <td><span>13K</span></td> 
                  <td><span>7.4</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>13K</span></td> 
                  <td><span>13.5K</span></td> 
                  <td><span>7.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>13.5K</span></td> 
                  <td><span>1</span></td> 
                  <td><span>7.7</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>1</span></td> 
                  <td><span>1.5</span></td> 
                  <td><span>7.9</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>1.5</span></td> 
                  <td><span>2</span></td> 
                  <td><span>8</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>2</span></td> 
                  <td><span>2.5</span></td> 
                  <td><span>8.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>2.5</span></td> 
                  <td><span>3</span></td> 
                  <td><span>8.3</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>3</span></td> 
                  <td><span>3.5</span></td> 
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
              </tbody>
            </table>
          </div>
          <div class='size-chart' id="cn-code-item-two" style="display:none">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="width: 33%"><span>英國碼(UK)</span></td> 
                  <td style="width: 33%"><span>中國碼 (CN)</span></td> 
                  <td style="width: 34%"><span>腳掌尺寸(英寸)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>10K</span></td> 
                  <td><span>165</span></td> 
                  <td><span>6.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>10.5K</span></td> 
                  <td><span>170</span></td> 
                  <td><span>6.7</span></td> 
                </tr> 

                <tr class=""> 
                  <td><span>11K</span></td> 
                  <td><span>175</span></td> 
                  <td><span>6.9</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>11.5K</span></td> 
                  <td><span>180</span></td> 
                  <td><span>7</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>12K</span></td> 
                  <td><span>180</span></td> 
                  <td><span>7.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>12.5K</span></td> 
                  <td><span>185</span></td> 
                  <td><span>7.4</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>13K</span></td> 
                  <td><span>190</span></td> 
                  <td><span>7.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>13.5K</span></td> 
                  <td><span>195</span></td> 
                  <td><span>7.7</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>1</span></td> 
                  <td><span>200</span></td> 
                  <td><span>7.9</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>1.5</span></td> 
                  <td><span>205</span></td> 
                  <td><span>8</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>2</span></td> 
                  <td><span>210</span></td> 
                  <td><span>8.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>2.5</span></td> 
                  <td><span>210</span></td> 
                  <td><span>8.3</span></td> 
                </tr>
                <tr class=""> 
                  <td><span>3</span></td> 
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
                  <td><span> -</span></td> 
                  <td><span>9.8</span></td> 
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
                    <span class="step-body">踩在一張紙上，腳後跟稍微接觸後面的牆壁。</span>
                  </li>
                  <li class="step">
                    <span class="step-title">2. </span>
                    <span class="step-body">在紙上標出最長腳趾的末端（您可能需要朋友幫助）並測量從牆壁到標記的距離。</span>
                  </li>
                  <li class="step">
                    <span class="step-title">3. </span>
                    <span class="step-body">對另一隻腳做同樣的事情，並將測量結果與我們的尺碼表進行比較以獲得合適的尺碼。</span>
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