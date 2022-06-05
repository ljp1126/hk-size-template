<template>
  <div class="content">
    <div class="top-title">
      <div class="sizeClose">
        <i id="closeDrawer" class="iconfont iconcross-small"></i>
      </div>
      <div class="text">男子下裝尺碼表</div>
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
              <span class="check-type check-active">cm</span>
              <span class="check-type" id="inches-type">Inches</span>
            </div>
            <div class="size-select">
              <div class="select-type">
                <div class="select-numb">
                  <span class="select-show">
                    <span class="show-content" id="show-content-one">國際碼</span>
                    <img id="down-show-one" src="https://img.adidas.com.hk/resources/images/common/downArrow.png" alt="" srcset="">
                    <img id="up-show-one" style="display: none" src="https://img.adidas.com.hk/resources/images/common/upArrow.png" alt="" srcset="">
                  </span>
                  <div class="size-options" id="size-options-one" style="display: none">
                    <div class="optionsItem" id="inl-code-one">國際碼</div>
                    <div class="optionsItem" id="it-code-one">意大利碼</div>
                    <div class="optionsItem" id="jea-code-one">JEANS</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class='size-chart' id="inl-code-item-one">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="width: 33%"><span>國際碼</span></td> 
                  <td style="width: 33%"><span>腰圍 (CM)</span></td> 
                  <td style="width: 34%"><span>臀圍 (CM)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>XXS</span></td> 
                  <td><span>67</span></td> 
                  <td><span>87</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>XS</span></td> 
                  <td><span>71</span></td> 
                  <td><span>91</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>S</span></td> 
                  <td><span>75</span></td> 
                  <td><span>95</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>M</span></td> 
                  <td><span>79</span></td> 
                  <td><span>99</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>L</span></td> 
                  <td><span>83</span></td> 
                  <td><span>103</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>XL</span></td> 
                  <td><span>87</span></td> 
                  <td><span>107</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>XXL</span></td> 
                  <td><span>91</span></td> 
                  <td><span>111</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>XXXL</span></td> 
                  <td><span>95</span></td> 
                  <td><span>115</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span> -</span></td> 
                  <td><span>99</span></td> 
                  <td><span>119</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span> -</span></td> 
                  <td><span>103</span></td> 
                  <td><span>123</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span> -</span></td> 
                  <td><span>107</span></td> 
                  <td><span>127</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span> -</span></td> 
                  <td><span>111</span></td> 
                  <td><span>131</span></td> 
                </tr> 
              </tbody> 
            </table>
          </div>
          <div class='size-chart' id="it-code-item-one" style="display:none">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="width: 33%"><span>意大利碼</span></td> 
                  <td style="width: 33%"><span>腰圍 (CM)</span></td> 
                  <td style="width: 34%"><span>臀圍 (CM)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>42</span></td> 
                  <td><span>67</span></td> 
                  <td><span>87</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>44</span></td> 
                  <td><span>71</span></td> 
                  <td><span>91</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>46</span></td> 
                  <td><span>75</span></td> 
                  <td><span>95</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>48</span></td> 
                  <td><span>79</span></td> 
                  <td><span>99</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>50</span></td> 
                  <td><span>83</span></td> 
                  <td><span>103</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>52</span></td> 
                  <td><span>87</span></td> 
                  <td><span>107</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>54</span></td> 
                  <td><span>91</span></td> 
                  <td><span>111</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>56</span></td> 
                  <td><span>95</span></td> 
                  <td><span>115</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>58</span></td> 
                  <td><span>99</span></td> 
                  <td><span>119</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>60</span></td> 
                  <td><span>103</span></td> 
                  <td><span>123</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>62</span></td> 
                  <td><span>107</span></td> 
                  <td><span>127</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>64</span></td> 
                  <td><span>111</span></td> 
                  <td><span>131</span></td> 
                </tr> 
              </tbody> 
            </table>
          </div>
            <div class='size-chart' id="jea-code-item-one" style="display:none">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="width: 33%"><span>JEANS</span></td> 
                  <td style="width: 33%"><span>腰圍 (CM)</span></td> 
                  <td style="width: 34%"><span>臀圍 (CM)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>28-29</span></td> 
                  <td><span>67</span></td> 
                  <td><span>87</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>30-31</span></td> 
                  <td><span>71</span></td> 
                  <td><span>91</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>32-33</span></td> 
                  <td><span>75</span></td> 
                  <td><span>95</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>34-35</span></td> 
                  <td><span>79</span></td> 
                  <td><span>99</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>36-37</span></td> 
                  <td><span>83</span></td> 
                  <td><span>103</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>38-39</span></td> 
                  <td><span>87</span></td> 
                  <td><span>107</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>40-41</span></td> 
                  <td><span>91</span></td> 
                  <td><span>111</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>42-43</span></td> 
                  <td><span>95</span></td> 
                  <td><span>115</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>44-45</span></td> 
                  <td><span>99</span></td> 
                  <td><span>119</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>46</span></td> 
                  <td><span>103</span></td> 
                  <td><span>123</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span> -</span></td> 
                  <td><span>107</span></td> 
                  <td><span>127</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span> -</span></td> 
                  <td><span>111</span></td> 
                  <td><span>131</span></td> 
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
                    <span class="show-content" id="show-content-two">國際碼</span>
                    <img id="down-show-two" src="https://img.adidas.com.hk/resources/images/common/downArrow.png" alt="" srcset="">
                    <img id="up-show-two" style="display: none" src="https://img.adidas.com.hk/resources/images/common/upArrow.png" alt="" srcset="">
                  </span>
                  <div class="size-options" id="size-options-two" style="display: none">
                    <div class="optionsItem" id="inl-code-two">國際碼</div>
                    <div class="optionsItem" id="it-code-two">意大利碼</div>
                    <div class="optionsItem" id="jea-code-two">JEANS</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class='size-chart' id="inl-code-item-two">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="width: 33%"><span>國際碼</span></td> 
                  <td style="width: 33%"><span>腰圍 (IN)</span></td> 
                  <td style="width: 34%"><span>臀圍 (IN)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>XXS</span></td> 
                  <td><span>26.4</span></td> 
                  <td><span>34.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>XS</span></td> 
                  <td><span>28</span></td> 
                  <td><span>35.8</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>S</span></td> 
                  <td><span>29.5</span></td> 
                  <td><span>37.4</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>M</span></td> 
                  <td><span>31.1</span></td> 
                  <td><span>39</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>L</span></td> 
                  <td><span>32.7</span></td> 
                  <td><span>40.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>XL</span></td> 
                  <td><span>34.2</span></td> 
                  <td><span>42.1</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>XXL</span></td> 
                  <td><span>35.8</span></td> 
                  <td><span>43.7</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>XXXL</span></td> 
                  <td><span>37.4</span></td> 
                  <td><span>45.3</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span> -</span></td> 
                  <td><span>39</span></td> 
                  <td><span>46.8</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span> -</span></td> 
                  <td><span>40.5</span></td> 
                  <td><span>48.4</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span> -</span></td> 
                  <td><span>42.1</span></td> 
                  <td><span>50</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span> -</span></td> 
                  <td><span>43.7</span></td> 
                  <td><span>51.6</span></td> 
                </tr> 
              </tbody> 
            </table>
          </div>
          <div class='size-chart' id="it-code-item-two" style="display:none">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="width: 33%"><span>意大利碼</span></td> 
                  <td style="width: 33%"><span>腰圍 (IN)</span></td> 
                  <td style="width: 34%"><span>臀圍 (IN)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>42</span></td> 
                  <td><span>26.4</span></td> 
                  <td><span>34.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>44</span></td> 
                  <td><span>28</span></td> 
                  <td><span>35.8</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>46</span></td> 
                  <td><span>29.5</span></td> 
                  <td><span>37.4</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>48</span></td> 
                  <td><span>31.1</span></td> 
                  <td><span>39</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>50</span></td> 
                  <td><span>32.7</span></td> 
                  <td><span>40.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>52</span></td> 
                  <td><span>34.2</span></td> 
                  <td><span>42.1</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>54</span></td> 
                  <td><span>35.8</span></td> 
                  <td><span>43.7</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>56</span></td> 
                  <td><span>37.4</span></td> 
                  <td><span>45.3</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>58</span></td> 
                  <td><span>39</span></td> 
                  <td><span>46.8</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>60</span></td> 
                  <td><span>40.5</span></td> 
                  <td><span>48.4</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>62</span></td> 
                  <td><span>42.1</span></td> 
                  <td><span>50</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>64</span></td> 
                  <td><span>43.7</span></td> 
                  <td><span>51.6</span></td> 
                </tr> 
              </tbody> 
            </table>
          </div>
          <div class='size-chart' id="jea-code-item-two" style="display:none">
            <table> 
              <tbody> 
                <tr class="tr-color tr-title"> 
                  <td style="width: 33%"><span>JEANS</span></td> 
                  <td style="width: 33%"><span>腰圍 (IN)</span></td> 
                  <td style="width: 34%"><span>臀圍 (IN)</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>28-29</span></td> 
                  <td><span>26.4</span></td> 
                  <td><span>34.2</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>30-31</span></td> 
                  <td><span>28</span></td> 
                  <td><span>35.8</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>32-33</span></td> 
                  <td><span>29.5</span></td> 
                  <td><span>37.4</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>34-35</span></td> 
                  <td><span>31.1</span></td> 
                  <td><span>39</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>36-37</span></td> 
                  <td><span>32.7</span></td> 
                  <td><span>40.5</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>38-39</span></td> 
                  <td><span>34.2</span></td> 
                  <td><span>42.1</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>40-41</span></td> 
                  <td><span>35.8</span></td> 
                  <td><span>43.7</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>42-43</span></td> 
                  <td><span>37.4</span></td> 
                  <td><span>45.3</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span>44-45</span></td> 
                  <td><span>39</span></td> 
                  <td><span>46.8</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span>46</span></td> 
                  <td><span>40.5</span></td> 
                  <td><span>48.4</span></td> 
                </tr> 
                <tr class=""> 
                  <td><span> -</span></td> 
                  <td><span>42.1</span></td> 
                  <td><span>50</span></td> 
                </tr> 
                <tr class="tr-color"> 
                  <td><span> -</span></td> 
                  <td><span>43.7</span></td> 
                  <td><span>51.6</span></td> 
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