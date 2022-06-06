<template>
  <div class="content">
    <div class="top-title">
      <div class="sizeClose">
        <i id="closeDrawer" class="iconfont iconcross-small"></i>
      </div>
      <div class="text">ADIDAS X GUCCI MEN’S TOPS SIZE GUIDE</div>
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
                    <span class="show-content" id="show-content-one">International</span>
                    <img id="down-show-one" src="https://img.adidas.com.hk/resources/images/common/downArrow.png" alt="" srcset="">
                    <img id="up-show-one" style="display: none" src="https://img.adidas.com.hk/resources/images/common/upArrow.png" alt="" srcset="">
                  </span>
                  <div class="size-options" id="size-options-one" style="display: none">
                    <div class="optionsItem" id="inl-code-one">International</div>
                    <div class="optionsItem" id="it-code-one">IT</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class='size-chart' id="inl-code-item-one">
            <table>
              <tbody>
                <tr class="tr-color tr-title">
                  <td style="width: 33%"><span>SIZE</span></td>
                  <td style="width: 33%"><span>SHOULDERS (CM)</span></td>
                  <td style="width: 34%"><span>CHEST (CM)</span></td>
                </tr>
                <tr class="">
                  <td><span>XXS</span></td>
                  <td><span>44</span></td>
                  <td><span>86</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>XS</span></td>
                  <td><span>45</span></td>
                  <td><span>90</span></td>
                </tr>
                <tr class="">
                  <td><span>S</span></td>
                  <td><span>46</span></td>
                  <td><span>94</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>M</span></td>
                  <td><span>47</span></td>
                  <td><span>98</span></td>
                </tr>
                <tr class="">
                  <td><span>L</span></td>
                  <td><span>48</span></td>
                  <td><span>102</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>XL</span></td>
                  <td><span>49</span></td>
                  <td><span>106</span></td>
                </tr>
                <tr class="">
                  <td><span>XXL</span></td>
                  <td><span>50</span></td>
                  <td><span>110</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>XXXL</span></td>
                  <td><span>51</span></td>
                  <td><span>114</span></td>
                </tr>
                <tr class="">
                  <td><span> -</span></td>
                  <td><span>52</span></td>
                  <td><span>118</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span> -</span></td>
                  <td><span>53</span></td>
                  <td><span>122</span></td>
                </tr>
                <tr class="">
                  <td><span> -</span></td>
                  <td><span>54</span></td>
                  <td><span>126</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span> -</span></td>
                  <td><span>55</span></td>
                  <td><span>130</span></td>
                </tr>
              </tbody>
            </table>
          </div>
          <div class='size-chart' id="it-code-item-one" style="display:none">
            <table>
              <tbody>
                <tr class="tr-color tr-title">
                  <td style="width: 33%"><span>IT</span></td>
                  <td style="width: 33%"><span>SHOULDERS (CM)</span></td>
                  <td style="width: 34%"><span>CHEST (CM)</span></td>
                </tr>
                <tr class="">
                  <td><span>42</span></td>
                  <td><span>44</span></td>
                  <td><span>86</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>44</span></td>
                  <td><span>45</span></td>
                  <td><span>90</span></td>
                </tr>
                <tr class="">
                  <td><span>46</span></td>
                  <td><span>46</span></td>
                  <td><span>94</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>48</span></td>
                  <td><span>47</span></td>
                  <td><span>98</span></td>
                </tr>
                <tr class="">
                  <td><span>50</span></td>
                  <td><span>48</span></td>
                  <td><span>102</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>52</span></td>
                  <td><span>49</span></td>
                  <td><span>106</span></td>
                </tr>
                <tr class="">
                  <td><span>54</span></td>
                  <td><span>50</span></td>
                  <td><span>110</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>56</span></td>
                  <td><span>51</span></td>
                  <td><span>114</span></td>
                </tr>
                <tr class="">
                  <td><span>58</span></td>
                  <td><span>52</span></td>
                  <td><span>118</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>60</span></td>
                  <td><span>53</span></td>
                  <td><span>122</span></td>
                </tr>
                <tr class="">
                  <td><span>62</span></td>
                  <td><span>54</span></td>
                  <td><span>126</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>64</span></td>
                  <td><span>55</span></td>
                  <td><span>130</span></td>
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
                    <span class="show-content" id="show-content-two">International</span>
                    <img id="down-show-two" src="https://img.adidas.com.hk/resources/images/common/downArrow.png" alt="" srcset="">
                    <img id="up-show-two" style="display: none" src="https://img.adidas.com.hk/resources/images/common/upArrow.png" alt="" srcset="">
                  </span>
                  <div class="size-options" id="size-options-two" style="display: none">
                    <div class="optionsItem" id="inl-code-two">International</div>
                    <div class="optionsItem" id="it-code-two">IT</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class='size-chart' id="inl-code-item-two">
            <table>
              <tbody>
                <tr class="tr-color tr-title">
                  <td style="width: 33%"><span>SIZE</span></td>
                  <td style="width: 33%"><span>SHOULDERS (IN)</span></td>
                  <td style="width: 34%"><span>CHEST (IN)</span></td>
                </tr>
                <tr class="">
                  <td><span>XXS</span></td>
                  <td><span>17.3</span></td>
                  <td><span>33.8</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>XS</span></td>
                  <td><span>17.7</span></td>
                  <td><span>35.4</span></td>
                </tr>
                <tr class="">
                  <td><span>S</span></td>
                  <td><span>18.1</span></td>
                  <td><span>37</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>M</span></td>
                  <td><span>18.5</span></td>
                  <td><span>38.6</span></td>
                </tr>
                <tr class="">
                  <td><span>L</span></td>
                  <td><span>18.9</span></td>
                  <td><span>40.2</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>XL</span></td>
                  <td><span>19.3</span></td>
                  <td><span>41.7</span></td>
                </tr>
                <tr class="">
                  <td><span>XXL</span></td>
                  <td><span>19.7</span></td>
                  <td><span>43.3</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>XXXL</span></td>
                  <td><span>20.1</span></td>
                  <td><span>44.9</span></td>
                </tr>
                <tr class="">
                  <td><span> -</span></td>
                  <td><span>20.5</span></td>
                  <td><span>46.5</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span> -</span></td>
                  <td><span>20.9</span></td>
                  <td><span>48</span></td>
                </tr>
                <tr class="">
                  <td><span> -</span></td>
                  <td><span>21.2</span></td>
                  <td><span>49.6</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span> -</span></td>
                  <td><span>21.6</span></td>
                  <td><span>51.1</span></td>
                </tr>
              </tbody>
            </table>
          </div>
          <div class='size-chart' id="it-code-item-two" style="display:none">
            <table>
              <tbody>
                <tr class="tr-color tr-title">
                  <td style="width: 33%"><span>IT</span></td>
                  <td style="width: 33%"><span>SHOULDERS (IN)</span></td>
                  <td style="width: 34%"><span>CHEST (IN)</span></td>
                </tr>
                <tr class="">
                  <td><span>42</span></td>
                  <td><span>17.3</span></td>
                  <td><span>33.8</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>44</span></td>
                  <td><span>17.7</span></td>
                  <td><span>35.4</span></td>
                </tr>
                <tr class="">
                  <td><span>46</span></td>
                  <td><span>18.1</span></td>
                  <td><span>37</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>48</span></td>
                  <td><span>18.5</span></td>
                  <td><span>38.6</span></td>
                </tr>
                <tr class="">
                  <td><span>50</span></td>
                  <td><span>18.9</span></td>
                  <td><span>40.2</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>52</span></td>
                  <td><span>19.3</span></td>
                  <td><span>41.7</span></td>
                </tr>
                <tr class="">
                  <td><span>54</span></td>
                  <td><span>19.7</span></td>
                  <td><span>43.3</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>56</span></td>
                  <td><span>20.1</span></td>
                  <td><span>44.9</span></td>
                </tr>
                <tr class="">
                  <td><span>58</span></td>
                  <td><span>20.5</span></td>
                  <td><span>46.5</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>60</span></td>
                  <td><span>20.9</span></td>
                  <td><span>48</span></td>
                </tr>
                <tr class="">
                  <td><span>62</span></td>
                  <td><span>21.2</span></td>
                  <td><span>49.6</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>64</span></td>
                  <td><span>21.6</span></td>
                  <td><span>51.1</span></td>
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
            <div class="instructions">
              <div class="steps-type">
                <p class="tipinfo">Hold the tape horizontally to measure:</p>
                <ul class="steps">
                  <li class="step">
                    <span class="step-title">1. Chest, </span>
                    <span class="step-body">around the widest part</span>
                  </li>
                  <li class="step">
                    <span class="step-title">2. Waist, </span>
                    <span class="step-body">around the narrowest part</span>
                  </li>
                  <li class="step">
                    <span class="step-title">3. Hip, </span>
                    <span class="step-body">around the widest part, keeping the feet close together</span>
                  </li>
                </ul>
              </div>
              <div class="steps-type">
                <p class="tipinfo">Hold the tape vertically to measure:</p>
                <ul class="steps">
                  <li class="step">
                    <span class="step-title">4. Inseam, </span>
                    <span class="step-body">from the crotch to the floor</span>
                  </li>
                  <li class="step">
                    <span class="step-title">5. Height, </span>
                    <span class="step-body">from the top of the head to the floor, keeping a straight posture</span>
                  </li>
                </ul>
              </div>
            </div>
            <div class="image-container">
              <img src="https://img.adidas.com.hk/resources/images/size/measure-men.png" alt="" srcset="">
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>