<template>
  <div class="content">
    <div class="top-title">
      <div class="sizeClose">
        <i id="closeDrawer" class="iconfont iconcross-small"></i>
      </div>
      <div class="text">ADIDAS X GUCCI 女子下裝尺碼表</div>
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
                    <div class="optionsItem" id="eu-code-one">EU</div>
                    <div class="optionsItem" id="ukau-code-one">UK/AU</div>
                    <div class="optionsItem" id="jp-code-one">日本碼</div>
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
                  <td style="width: 34%"><span>胸圍 (CM)</span></td>
                </tr>
                <tr class="">
                  <td><span>XXXS</span></td>
                  <td><span>59</span></td>
                  <td><span>85</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>XXS</span></td>
                  <td><span>62</span></td>
                  <td><span>88</span></td>
                </tr>
                <tr class="">
                  <td><span>XS</span></td>
                  <td><span>65</span></td>
                  <td><span>91</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>S</span></td>
                  <td><span>68</span></td>
                  <td><span>94</span></td>
                </tr>
                <tr class="">
                  <td><span>M</span></td>
                  <td><span>71</span></td>
                  <td><span>97</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>L</span></td>
                  <td><span>75</span></td>
                  <td><span>101</span></td>
                </tr>
                <tr class="">
                  <td><span>XL</span></td>
                  <td><span>79</span></td>
                  <td><span>105</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>XXL</span></td>
                  <td><span>83</span></td>
                  <td><span>109</span></td>
                </tr>
                <tr class="">
                  <td><span>XXXL</span></td>
                  <td><span>87</span></td>
                  <td><span>113</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span> -</span></td>
                  <td><span>91</span></td>
                  <td><span>117</span></td>
                </tr>
              </tbody>
            </table>
          </div>
          <div class='size-chart' id="it-code-item-one" style="display:none">
            <table>
              <tbody>
                <tr class="tr-color tr-title">
                  <td style="width: 33%"><span>	意大利碼</span></td>
                  <td style="width: 33%"><span>腰圍 (CM)</span></td>
                  <td style="width: 34%"><span>胸圍 (CM)</span></td>
                </tr>
                <tr class="">
                  <td><span>34</span></td>
                  <td><span>59</span></td>
                  <td><span>85</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>36</span></td>
                  <td><span>62</span></td>
                  <td><span>88</span></td>
                </tr>
                <tr class="">
                  <td><span>38</span></td>
                  <td><span>65</span></td>
                  <td><span>91</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>40</span></td>
                  <td><span>68</span></td>
                  <td><span>94</span></td>
                </tr>
                <tr class="">
                  <td><span>42</span></td>
                  <td><span>71</span></td>
                  <td><span>97</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>44</span></td>
                  <td><span>75</span></td>
                  <td><span>101</span></td>
                </tr>
                <tr class="">
                  <td><span>46</span></td>
                  <td><span>79</span></td>
                  <td><span>105</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>48</span></td>
                  <td><span>83</span></td>
                  <td><span>109</span></td>
                </tr>
                <tr class="">
                  <td><span>50</span></td>
                  <td><span>87</span></td>
                  <td><span>113</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>52</span></td>
                  <td><span>91</span></td>
                  <td><span>117</span></td>
                </tr>
              </tbody>
            </table>
          </div>
          <div class='size-chart' id="eu-code-item-one" style="display:none">
            <table>
              <tbody>
                <tr class="tr-color tr-title">
                  <td style="width: 33%"><span>EU</span></td>
                  <td style="width: 33%"><span>腰圍 (CM)</span></td>
                  <td style="width: 34%"><span>胸圍 (CM)</span></td>
                </tr>
                <tr class="">
                  <td><span>30</span></td>
                  <td><span>59</span></td>
                  <td><span>85</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>32</span></td>
                  <td><span>62</span></td>
                  <td><span>88</span></td>
                </tr>
                <tr class="">
                  <td><span>34</span></td>
                  <td><span>65</span></td>
                  <td><span>91</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>36</span></td>
                  <td><span>68</span></td>
                  <td><span>94</span></td>
                </tr>
                <tr class="">
                  <td><span>38</span></td>
                  <td><span>71</span></td>
                  <td><span>97</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>40</span></td>
                  <td><span>75</span></td>
                  <td><span>101</span></td>
                </tr>
                <tr class="">
                  <td><span>42</span></td>
                  <td><span>79</span></td>
                  <td><span>105</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>44</span></td>
                  <td><span>83</span></td>
                  <td><span>109</span></td>
                </tr>
                <tr class="">
                  <td><span>46</span></td>
                  <td><span>87</span></td>
                  <td><span>113</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>48</span></td>
                  <td><span>91</span></td>
                  <td><span>117</span></td>
                </tr>
              </tbody>
            </table>
          </div>
          <div class='size-chart' id="ukau-code-item-one" style="display:none">
            <table>
              <tbody>
                <tr class="tr-color tr-title">
                  <td style="width: 33%"><span>UK/AU</span></td>
                  <td style="width: 33%"><span>腰圍 (CM)</span></td>
                  <td style="width: 34%"><span>胸圍 (CM)</span></td>
                </tr>
                <tr class="">
                  <td><span>2</span></td>
                  <td><span>59</span></td>
                  <td><span>85</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>4</span></td>
                  <td><span>62</span></td>
                  <td><span>88</span></td>
                </tr>
                <tr class="">
                  <td><span>6</span></td>
                  <td><span>65</span></td>
                  <td><span>91</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>8</span></td>
                  <td><span>68</span></td>
                  <td><span>94</span></td>
                </tr>
                <tr class="">
                  <td><span>10</span></td>
                  <td><span>71</span></td>
                  <td><span>97</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>12</span></td>
                  <td><span>75</span></td>
                  <td><span>101</span></td>
                </tr>
                <tr class="">
                  <td><span>14</span></td>
                  <td><span>79</span></td>
                  <td><span>105</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>16</span></td>
                  <td><span>83</span></td>
                  <td><span>109</span></td>
                </tr>
                <tr class="">
                  <td><span>18</span></td>
                  <td><span>87</span></td>
                  <td><span>113</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>20</span></td>
                  <td><span>91</span></td>
                  <td><span>117</span></td>
                </tr>
              </tbody>
            </table>
          </div>
          <div class='size-chart' id="jp-code-item-one" style="display:none">
            <table>
              <tbody>
                <tr class="tr-color tr-title">
                  <td style="width: 33%"><span>日本碼</span></td>
                  <td style="width: 33%"><span>腰圍 (CM)</span></td>
                  <td style="width: 34%"><span>胸圍 (CM)</span></td>
                </tr>
                <tr class="">
                  <td><span>3</span></td>
                  <td><span>59</span></td>
                  <td><span>85</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>5</span></td>
                  <td><span>62</span></td>
                  <td><span>88</span></td>
                </tr>
                <tr class="">
                  <td><span>7</span></td>
                  <td><span>65</span></td>
                  <td><span>91</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>9</span></td>
                  <td><span>68</span></td>
                  <td><span>94</span></td>
                </tr>
                <tr class="">
                  <td><span>11</span></td>
                  <td><span>71</span></td>
                  <td><span>97</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>13</span></td>
                  <td><span>75</span></td>
                  <td><span>101</span></td>
                </tr>
                <tr class="">
                  <td><span>15</span></td>
                  <td><span>79</span></td>
                  <td><span>105</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>17</span></td>
                  <td><span>83</span></td>
                  <td><span>109</span></td>
                </tr>
                <tr class="">
                  <td><span>19</span></td>
                  <td><span>87</span></td>
                  <td><span>113</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>21</span></td>
                  <td><span>91</span></td>
                  <td><span>117</span></td>
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
                  <td style="width: 34%"><span>胸圍 (CM)</span></td>
                </tr>
                <tr class="">
                  <td><span>20</span></td>
                  <td><span>59</span></td>
                  <td><span>85</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>22</span></td>
                  <td><span>62</span></td>
                  <td><span>88</span></td>
                </tr>
                <tr class="">
                  <td><span>24</span></td>
                  <td><span>65</span></td>
                  <td><span>91</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>26</span></td>
                  <td><span>68</span></td>
                  <td><span>94</span></td>
                </tr>
                <tr class="">
                  <td><span>28</span></td>
                  <td><span>71</span></td>
                  <td><span>97</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>30</span></td>
                  <td><span>75</span></td>
                  <td><span>101</span></td>
                </tr>
                <tr class="">
                  <td><span>32</span></td>
                  <td><span>79</span></td>
                  <td><span>105</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>34</span></td>
                  <td><span>83</span></td>
                  <td><span>109</span></td>
                </tr>
                <tr class="">
                  <td><span>36</span></td>
                  <td><span>87</span></td>
                  <td><span>113</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>38</span></td>
                  <td><span>91</span></td>
                  <td><span>117</span></td>
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
                    <div class="optionsItem" id="eu-code-two">EU</div>
                    <div class="optionsItem" id="ukau-code-two">UK/AU</div>
                    <div class="optionsItem" id="jp-code-two">日本碼</div>
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
                  <td style="width: 34%"><span>胸圍 (IN)</span></td>
                </tr>
                <tr class="">
                  <td><span>XXXS</span></td>
                  <td><span>23.2</span></td>
                  <td><span>33.5</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>XXS</span></td>
                  <td><span>24.4</span></td>
                  <td><span>34.6</span></td>
                </tr>
                <tr class="">
                  <td><span>XS</span></td>
                  <td><span>25.6</span></td>
                  <td><span>35.8</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>S</span></td>
                  <td><span>26.8</span></td>
                  <td><span>37</span></td>
                </tr>
                <tr class="">
                  <td><span>M</span></td>
                  <td><span>27.9</span></td>
                  <td><span>38.2</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>L</span></td>
                  <td><span>29.5</span></td>
                  <td><span>39.8</span></td>
                </tr>
                <tr class="">
                  <td><span>XL</span></td>
                  <td><span>31.1</span></td>
                  <td><span>41.3</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>XXL</span></td>
                  <td><span>32.7</span></td>
                  <td><span>42.9</span></td>
                </tr>
                <tr class="">
                  <td><span>XXXL</span></td>
                  <td><span>34.2</span></td>
                  <td><span>44.4</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span> -</span></td>
                  <td><span>35.8</span></td>
                  <td><span>46</span></td>
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
                  <td style="width: 34%"><span>胸圍 (IN)</span></td>
                </tr>
                <tr class="">
                  <td><span>34</span></td>
                  <td><span>23.2</span></td>
                  <td><span>33.5</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>36</span></td>
                  <td><span>24.4</span></td>
                  <td><span>34.6</span></td>
                </tr>
                <tr class="">
                  <td><span>38</span></td>
                  <td><span>25.6</span></td>
                  <td><span>35.8</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>40</span></td>
                  <td><span>26.8</span></td>
                  <td><span>37</span></td>
                </tr>
                <tr class="">
                  <td><span>42</span></td>
                  <td><span>27.9</span></td>
                  <td><span>38.2</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>44</span></td>
                  <td><span>29.5</span></td>
                  <td><span>39.8</span></td>
                </tr>
                <tr class="">
                  <td><span>46</span></td>
                  <td><span>31.1</span></td>
                  <td><span>41.3</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>48</span></td>
                  <td><span>32.7</span></td>
                  <td><span>42.9</span></td>
                </tr>
                <tr class="">
                  <td><span>50</span></td>
                  <td><span>34.2</span></td>
                  <td><span>44.4</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>52</span></td>
                  <td><span>35.8</span></td>
                  <td><span>46</span></td>
                </tr>
              </tbody>
            </table>
          </div>
          <div class='size-chart' id="eu-code-item-two" style="display:none">
            <table>
              <tbody>
                <tr class="tr-color tr-title">
                  <td style="width: 33%"><span>EU</span></td>
                  <td style="width: 33%"><span>腰圍 (IN)</span></td>
                  <td style="width: 34%"><span>胸圍 (IN)</span></td>
                </tr>
                <tr class="">
                  <td><span>30</span></td>
                  <td><span>23.2</span></td>
                  <td><span>33.5</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>32</span></td>
                  <td><span>24.4</span></td>
                  <td><span>34.6</span></td>
                </tr>
                <tr class="">
                  <td><span>34</span></td>
                  <td><span>25.6</span></td>
                  <td><span>35.8</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>36</span></td>
                  <td><span>26.8</span></td>
                  <td><span>37</span></td>
                </tr>
                <tr class="">
                  <td><span>38</span></td>
                  <td><span>27.9</span></td>
                  <td><span>38.2</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>40</span></td>
                  <td><span>29.5</span></td>
                  <td><span>39.8</span></td>
                </tr>
                <tr class="">
                  <td><span>42</span></td>
                  <td><span>31.1</span></td>
                  <td><span>41.3</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>44</span></td>
                  <td><span>32.7</span></td>
                  <td><span>42.9</span></td>
                </tr>
                <tr class="">
                  <td><span>46</span></td>
                  <td><span>34.2</span></td>
                  <td><span>44.4</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>48</span></td>
                  <td><span>35.8</span></td>
                  <td><span>46</span></td>
                </tr>
              </tbody>
            </table>
          </div>
          <div class='size-chart' id="ukau-code-item-two" style="display:none">
            <table>
              <tbody>
                <tr class="tr-color tr-title">
                  <td style="width: 33%"><span>UK/AU</span></td>
                  <td style="width: 33%"><span>腰圍 (IN)</span></td>
                  <td style="width: 34%"><span>胸圍 (IN)</span></td>
                </tr>
                <tr class="">
                  <td><span>2</span></td>
                  <td><span>23.2</span></td>
                  <td><span>33.5</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>4</span></td>
                  <td><span>24.4</span></td>
                  <td><span>34.6</span></td>
                </tr>
                <tr class="">
                  <td><span>6</span></td>
                  <td><span>25.6</span></td>
                  <td><span>35.8</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>8</span></td>
                  <td><span>26.8</span></td>
                  <td><span>37</span></td>
                </tr>
                <tr class="">
                  <td><span>10</span></td>
                  <td><span>27.9</span></td>
                  <td><span>38.2</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>12</span></td>
                  <td><span>29.5</span></td>
                  <td><span>39.8</span></td>
                </tr>
                <tr class="">
                  <td><span>14</span></td>
                  <td><span>31.1</span></td>
                  <td><span>41.3</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>16</span></td>
                  <td><span>32.7</span></td>
                  <td><span>42.9</span></td>
                </tr>
                <tr class="">
                  <td><span>18</span></td>
                  <td><span>34.2</span></td>
                  <td><span>44.4</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>20</span></td>
                  <td><span>35.8</span></td>
                  <td><span>46</span></td>
                </tr>
              </tbody>
            </table>
          </div>
          <div class='size-chart' id="jp-code-item-two" style="display:none">
            <table>
              <tbody>
                <tr class="tr-color tr-title">
                  <td style="width: 33%"><span>日本碼</span></td>
                  <td style="width: 33%"><span>腰圍 (IN)</span></td>
                  <td style="width: 34%"><span>胸圍 (IN)</span></td>
                </tr>
                <tr class="">
                  <td><span>3</span></td>
                  <td><span>23.2</span></td>
                  <td><span>33.5</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>5</span></td>
                  <td><span>24.4</span></td>
                  <td><span>34.6</span></td>
                </tr>
                <tr class="">
                  <td><span>7</span></td>
                  <td><span>25.6</span></td>
                  <td><span>35.8</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>9</span></td>
                  <td><span>26.8</span></td>
                  <td><span>37</span></td>
                </tr>
                <tr class="">
                  <td><span>11</span></td>
                  <td><span>27.9</span></td>
                  <td><span>38.2</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>13</span></td>
                  <td><span>29.5</span></td>
                  <td><span>39.8</span></td>
                </tr>
                <tr class="">
                  <td><span>15</span></td>
                  <td><span>31.1</span></td>
                  <td><span>41.3</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>17</span></td>
                  <td><span>32.7</span></td>
                  <td><span>42.9</span></td>
                </tr>
                <tr class="">
                  <td><span>19</span></td>
                  <td><span>34.2</span></td>
                  <td><span>44.4</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>21</span></td>
                  <td><span>35.8</span></td>
                  <td><span>46</span></td>
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
                  <td style="width: 34%"><span>胸圍 (IN)</span></td>
                </tr>
                <tr class="">
                  <td><span>20</span></td>
                  <td><span>23.2</span></td>
                  <td><span>33.5</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>22</span></td>
                  <td><span>24.4</span></td>
                  <td><span>34.6</span></td>
                </tr>
                <tr class="">
                  <td><span>24</span></td>
                  <td><span>25.6</span></td>
                  <td><span>35.8</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>26</span></td>
                  <td><span>26.8</span></td>
                  <td><span>37</span></td>
                </tr>
                <tr class="">
                  <td><span>28</span></td>
                  <td><span>27.9</span></td>
                  <td><span>38.2</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>30</span></td>
                  <td><span>29.5</span></td>
                  <td><span>39.8</span></td>
                </tr>
                <tr class="">
                  <td><span>32</span></td>
                  <td><span>31.1</span></td>
                  <td><span>41.3</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>34</span></td>
                  <td><span>32.7</span></td>
                  <td><span>42.9</span></td>
                </tr>
                <tr class="">
                  <td><span>36</span></td>
                  <td><span>34.2</span></td>
                  <td><span>44.4</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>38</span></td>
                  <td><span>35.8</span></td>
                  <td><span>46</span></td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
        <div class="tips">
          <div class="tips-title">測量建議：</div>
          <div class="tips-content">請注意，尺碼表指的是自己的尺寸，而不是衣服本身。</div>
          <div class="tips-content">如果你的尺碼在兩個尺碼之間，穿緊一點的，請訂小一號；穿寬鬆一點的，請訂大一號。</div>
        </div>
      </div>
      <div class="size-measure" id="measure">
        <div class="measure">
          <div class="img-info">
            <div class="instructions">
              <div class="steps-type">
                <p class="tipinfo">水平握住捲尺進行測量：</p>
                <ul class="steps">
                  <li class="step">
                    <span class="step-title">1. 胸部，</span>
                    <span class="step-body">圍繞最寬處</span>
                  </li>
                  <li class="step">
                    <span class="step-title">2. 腰圍，</span>
                    <span class="step-body">圍繞最窄處</span>
                  </li>
                  <li class="step">
                    <span class="step-title">3. 臀部，</span>
                    <span class="step-body">圍繞最寬處，保持雙腳併攏</span>
                  </li>
                </ul>
              </div>
              <div class="steps-type">
                <p class="tipinfo">垂直握住捲尺進行測量：</p>
                <ul class="steps">
                  <li class="step">
                    <span class="step-title">4. 內長，</span>
                    <span class="step-body">從胯部到地板</span>
                  </li>
                  <li class="step">
                    <span class="step-title">5. 高度，</span>
                    <span class="step-body">從頭頂到地板，保持筆直的姿勢</span>
                  </li>
                </ul>
              </div>
            </div>
            <div class="image-container">
              <img src="https://img.adidas.com.hk/resources/images/size/measure-women.png" alt="" srcset="">
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>