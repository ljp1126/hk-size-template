<template>
  <div class="content">
    <div class="top-title">
      <div class="sizeClose">
        <i id="closeDrawer" class="iconfont iconcross-small"></i>
      </div>
      <div class="text">ADIDAS X GUCCI WOMEN'S TOPS SIZE GUIDE</div>
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
                    <div class="optionsItem" id="eu-code-one">EU</div>
                    <div class="optionsItem" id="ukau-code-one">UK/AU</div>
                    <div class="optionsItem" id="jp-code-one">JP</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class='size-chart' id="inl-code-item-one">
            <table>
              <tbody>
                <tr class="tr-color tr-title">
                  <td style="width: 33%"><span>International Size</span></td>
                  <td style="width: 33%"><span>Shouledrs (cm)</span></td>
                  <td style="width: 34%"><span>Chest (cm)</span></td>
                </tr>
                <tr class="">
                  <td><span>XXXS</span></td>
                  <td><span>37</span></td>
                  <td><span>77</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>XXS</span></td>
                  <td><span>38</span></td>
                  <td><span>80</span></td>
                </tr>
                <tr class="">
                  <td><span>XS</span></td>
                  <td><span>39</span></td>
                  <td><span>83</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>S</span></td>
                  <td><span>40</span></td>
                  <td><span>86</span></td>
                </tr>
                <tr class="">
                  <td><span>M</span></td>
                  <td><span>41</span></td>
                  <td><span>89</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>L</span></td>
                  <td><span>42.5</span></td>
                  <td><span>93</span></td>
                </tr>
                <tr class="">
                  <td><span>XL</span></td>
                  <td><span>44</span></td>
                  <td><span>97</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>XXL</span></td>
                  <td><span>45.5</span></td>
                  <td><span>101</span></td>
                </tr>
                <tr class="">
                  <td><span>XXXL</span></td>
                  <td><span>47</span></td>
                  <td><span>105</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span> -</span></td>
                  <td><span>48.5</span></td>
                  <td><span>109</span></td>
                </tr>
              </tbody>
            </table>
          </div>
          <div class='size-chart' id="it-code-item-one" style="display:none">
            <table>
              <tbody>
                <tr class="tr-color tr-title">
                  <td style="width: 33%"><span>	IT</span></td>
                  <td style="width: 33%"><span>Shouledrs (cm)</span></td>
                  <td style="width: 34%"><span>Chest (cm)</span></td>
                </tr>
                <tr class="">
                  <td><span>34</span></td>
                  <td><span>37</span></td>
                  <td><span>77</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>36</span></td>
                  <td><span>38</span></td>
                  <td><span>80</span></td>
                </tr>
                <tr class="">
                  <td><span>38</span></td>
                  <td><span>39</span></td>
                  <td><span>83</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>40</span></td>
                  <td><span>40</span></td>
                  <td><span>86</span></td>
                </tr>
                <tr class="">
                  <td><span>42</span></td>
                  <td><span>41</span></td>
                  <td><span>89</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>44</span></td>
                  <td><span>42.5</span></td>
                  <td><span>93</span></td>
                </tr>
                <tr class="">
                  <td><span>46</span></td>
                  <td><span>44</span></td>
                  <td><span>97</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>48</span></td>
                  <td><span>45.5</span></td>
                  <td><span>101</span></td>
                </tr>
                <tr class="">
                  <td><span>50</span></td>
                  <td><span>47</span></td>
                  <td><span>105</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>52</span></td>
                  <td><span>48.5</span></td>
                  <td><span>109</span></td>
                </tr>
              </tbody>
            </table>
          </div>
          <div class='size-chart' id="eu-code-item-one" style="display:none">
            <table>
              <tbody>
                <tr class="tr-color tr-title">
                  <td style="width: 33%"><span>EU</span></td>
                  <td style="width: 33%"><span>Shouledrs (cm)</span></td>
                  <td style="width: 34%"><span>Chest (cm)</span></td>
                </tr>
                <tr class="">
                  <td><span>30</span></td>
                  <td><span>37</span></td>
                  <td><span>77</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>32</span></td>
                  <td><span>38</span></td>
                  <td><span>80</span></td>
                </tr>
                <tr class="">
                  <td><span>34</span></td>
                  <td><span>39</span></td>
                  <td><span>83</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>36</span></td>
                  <td><span>40</span></td>
                  <td><span>86</span></td>
                </tr>
                <tr class="">
                  <td><span>38</span></td>
                  <td><span>41</span></td>
                  <td><span>89</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>40</span></td>
                  <td><span>42.5</span></td>
                  <td><span>93</span></td>
                </tr>
                <tr class="">
                  <td><span>42</span></td>
                  <td><span>44</span></td>
                  <td><span>97</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>44</span></td>
                  <td><span>45.5</span></td>
                  <td><span>101</span></td>
                </tr>
                <tr class="">
                  <td><span>46</span></td>
                  <td><span>47</span></td>
                  <td><span>105</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>48</span></td>
                  <td><span>48.5</span></td>
                  <td><span>109</span></td>
                </tr>
              </tbody>
            </table>
          </div>
          <div class='size-chart' id="ukau-code-item-one" style="display:none">
            <table>
              <tbody>
                <tr class="tr-color tr-title">
                  <td style="width: 33%"><span>UK/AU</span></td>
                  <td style="width: 33%"><span>Shouledrs (cm)</span></td>
                  <td style="width: 34%"><span>Chest (cm)</span></td>
                </tr>
                <tr class="">
                  <td><span>2</span></td>
                  <td><span>37</span></td>
                  <td><span>77</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>4</span></td>
                  <td><span>38</span></td>
                  <td><span>80</span></td>
                </tr>
                <tr class="">
                  <td><span>6</span></td>
                  <td><span>39</span></td>
                  <td><span>83</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>8</span></td>
                  <td><span>40</span></td>
                  <td><span>86</span></td>
                </tr>
                <tr class="">
                  <td><span>10</span></td>
                  <td><span>41</span></td>
                  <td><span>89</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>12</span></td>
                  <td><span>42.5</span></td>
                  <td><span>93</span></td>
                </tr>
                <tr class="">
                  <td><span>14</span></td>
                  <td><span>44</span></td>
                  <td><span>97</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>16</span></td>
                  <td><span>45.5</span></td>
                  <td><span>101</span></td>
                </tr>
                <tr class="">
                  <td><span>18</span></td>
                  <td><span>47</span></td>
                  <td><span>105</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>20</span></td>
                  <td><span>48.5</span></td>
                  <td><span>109</span></td>
                </tr>
              </tbody>
            </table>
          </div>
          <div class='size-chart' id="jp-code-item-one" style="display:none">
            <table>
              <tbody>
                <tr class="tr-color tr-title">
                  <td style="width: 33%"><span>JP</span></td>
                  <td style="width: 33%"><span>Shouledrs (cm)</span></td>
                  <td style="width: 34%"><span>Chest (cm)</span></td>
                </tr>
                <tr class="">
                  <td><span>3</span></td>
                  <td><span>37</span></td>
                  <td><span>77</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>5</span></td>
                  <td><span>38</span></td>
                  <td><span>80</span></td>
                </tr>
                <tr class="">
                  <td><span>7</span></td>
                  <td><span>39</span></td>
                  <td><span>83</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>9</span></td>
                  <td><span>40</span></td>
                  <td><span>86</span></td>
                </tr>
                <tr class="">
                  <td><span>11</span></td>
                  <td><span>41</span></td>
                  <td><span>89</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>13</span></td>
                  <td><span>42.5</span></td>
                  <td><span>93</span></td>
                </tr>
                <tr class="">
                  <td><span>15</span></td>
                  <td><span>44</span></td>
                  <td><span>97</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>17</span></td>
                  <td><span>45.5</span></td>
                  <td><span>101</span></td>
                </tr>
                <tr class="">
                  <td><span>19</span></td>
                  <td><span>47</span></td>
                  <td><span>105</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>21</span></td>
                  <td><span>48.5</span></td>
                  <td><span>109</span></td>
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
                    <div class="optionsItem" id="eu-code-two">EU</div>
                    <div class="optionsItem" id="ukau-code-two">UK/AU</div>
                    <div class="optionsItem" id="jp-code-two">JP</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class='size-chart' id="inl-code-item-two">
            <table>
              <tbody>
                <tr class="tr-color tr-title">
                  <td style="width: 33%"><span>International Size</span></td>
                  <td style="width: 33%"><span>Shoulders (inch)</span></td>
                  <td style="width: 34%"><span>Chest (inch)</span></td>
                </tr>
                <tr class="">
                  <td><span>XXXS</span></td>
                  <td><span>14.6</span></td>
                  <td><span>30.3</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>XXS</span></td>
                  <td><span>15</span></td>
                  <td><span>31.5</span></td>
                </tr>
                <tr class="">
                  <td><span>XS</span></td>
                  <td><span>15.4</span></td>
                  <td><span>32.7</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>S</span></td>
                  <td><span>15.7</span></td>
                  <td><span>33.8</span></td>
                </tr>
                <tr class="">
                  <td><span>M</span></td>
                  <td><span>16.1</span></td>
                  <td><span>35</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>L</span></td>
                  <td><span>16.7</span></td>
                  <td><span>36.6</span></td>
                </tr>
                <tr class="">
                  <td><span>XL</span></td>
                  <td><span>17.3</span></td>
                  <td><span>38.2</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>XXL</span></td>
                  <td><span>17.9</span></td>
                  <td><span>39.8</span></td>
                </tr>
                <tr class="">
                  <td><span>XXXL</span></td>
                  <td><span>18.5</span></td>
                  <td><span>41.3</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span> -</span></td>
                  <td><span>19</span></td>
                  <td><span>42.9</span></td>
                </tr>
              </tbody>
            </table>
          </div>
          <div class='size-chart' id="it-code-item-two" style="display:none">
            <table>
              <tbody>
                <tr class="tr-color tr-title">
                  <td style="width: 33%"><span>IT</span></td>
                  <td style="width: 33%"><span>Shoulders (inch)</span></td>
                  <td style="width: 34%"><span>Chest (inch)</span></td>
                </tr>
                <tr class="">
                  <td><span>34</span></td>
                  <td><span>14.6</span></td>
                  <td><span>30.3</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>36</span></td>
                  <td><span>15</span></td>
                  <td><span>31.5</span></td>
                </tr>
                <tr class="">
                  <td><span>38</span></td>
                  <td><span>15.4</span></td>
                  <td><span>32.7</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>40</span></td>
                  <td><span>15.7</span></td>
                  <td><span>33.8</span></td>
                </tr>
                <tr class="">
                  <td><span>42</span></td>
                  <td><span>16.1</span></td>
                  <td><span>35</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>44</span></td>
                  <td><span>16.7</span></td>
                  <td><span>36.6</span></td>
                </tr>
                <tr class="">
                  <td><span>46</span></td>
                  <td><span>17.3</span></td>
                  <td><span>38.2</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>48</span></td>
                  <td><span>17.9</span></td>
                  <td><span>39.8</span></td>
                </tr>
                <tr class="">
                  <td><span>50</span></td>
                  <td><span>18.5</span></td>
                  <td><span>41.3</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>52</span></td>
                  <td><span>19</span></td>
                  <td><span>42.9</span></td>
                </tr>
              </tbody>
            </table>
          </div>
          <div class='size-chart' id="eu-code-item-two" style="display:none">
            <table>
              <tbody>
                <tr class="tr-color tr-title">
                  <td style="width: 33%"><span>EU</span></td>
                  <td style="width: 33%"><span>Shoulders (inch)</span></td>
                  <td style="width: 34%"><span>Chest (inch)</span></td>
                </tr>
                <tr class="">
                  <td><span>30</span></td>
                  <td><span>14.6</span></td>
                  <td><span>30.3</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>32</span></td>
                  <td><span>15</span></td>
                  <td><span>31.5</span></td>
                </tr>
                <tr class="">
                  <td><span>34</span></td>
                  <td><span>15.4</span></td>
                  <td><span>32.7</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>36</span></td>
                  <td><span>15.7</span></td>
                  <td><span>33.8</span></td>
                </tr>
                <tr class="">
                  <td><span>38</span></td>
                  <td><span>16.1</span></td>
                  <td><span>35</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>40</span></td>
                  <td><span>16.7</span></td>
                  <td><span>36.6</span></td>
                </tr>
                <tr class="">
                  <td><span>42</span></td>
                  <td><span>17.3</span></td>
                  <td><span>38.2</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>44</span></td>
                  <td><span>17.9</span></td>
                  <td><span>39.8</span></td>
                </tr>
                <tr class="">
                  <td><span>46</span></td>
                  <td><span>18.5</span></td>
                  <td><span>41.3</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>48</span></td>
                  <td><span>19</span></td>
                  <td><span>42.9</span></td>
                </tr>
              </tbody>
            </table>
          </div>
          <div class='size-chart' id="ukau-code-item-two" style="display:none">
            <table>
              <tbody>
                <tr class="tr-color tr-title">
                  <td style="width: 33%"><span>UK/AU</span></td>
                  <td style="width: 33%"><span>Shoulders (inch)</span></td>
                  <td style="width: 34%"><span>Chest (inch)</span></td>
                </tr>
                <tr class="">
                  <td><span>2</span></td>
                  <td><span>14.6</span></td>
                  <td><span>30.3</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>4</span></td>
                  <td><span>15</span></td>
                  <td><span>31.5</span></td>
                </tr>
                <tr class="">
                  <td><span>6</span></td>
                  <td><span>15.4</span></td>
                  <td><span>32.7</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>8</span></td>
                  <td><span>15.7</span></td>
                  <td><span>33.8</span></td>
                </tr>
                <tr class="">
                  <td><span>10</span></td>
                  <td><span>16.1</span></td>
                  <td><span>35</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>12</span></td>
                  <td><span>16.7</span></td>
                  <td><span>36.6</span></td>
                </tr>
                <tr class="">
                  <td><span>14</span></td>
                  <td><span>17.3</span></td>
                  <td><span>38.2</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>16</span></td>
                  <td><span>17.9</span></td>
                  <td><span>39.8</span></td>
                </tr>
                <tr class="">
                  <td><span>18</span></td>
                  <td><span>18.5</span></td>
                  <td><span>41.3</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>20</span></td>
                  <td><span>19</span></td>
                  <td><span>42.9</span></td>
                </tr>
              </tbody>
            </table>
          </div>
          <div class='size-chart' id="jp-code-item-two" style="display:none">
            <table>
              <tbody>
                <tr class="tr-color tr-title">
                  <td style="width: 33%"><span>JP</span></td>
                  <td style="width: 33%"><span>Shoulders (inch)</span></td>
                  <td style="width: 34%"><span>Chest (inch)</span></td>
                </tr>
                <tr class="">
                  <td><span>3</span></td>
                  <td><span>14.6</span></td>
                  <td><span>30.3</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>5</span></td>
                  <td><span>15</span></td>
                  <td><span>31.5</span></td>
                </tr>
                <tr class="">
                  <td><span>7</span></td>
                  <td><span>15.4</span></td>
                  <td><span>32.7</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>9</span></td>
                  <td><span>15.7</span></td>
                  <td><span>33.8</span></td>
                </tr>
                <tr class="">
                  <td><span>11</span></td>
                  <td><span>16.1</span></td>
                  <td><span>35</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>13</span></td>
                  <td><span>16.7</span></td>
                  <td><span>36.6</span></td>
                </tr>
                <tr class="">
                  <td><span>15</span></td>
                  <td><span>17.3</span></td>
                  <td><span>38.2</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>17</span></td>
                  <td><span>17.9</span></td>
                  <td><span>39.8</span></td>
                </tr>
                <tr class="">
                  <td><span>19</span></td>
                  <td><span>18.5</span></td>
                  <td><span>41.3</span></td>
                </tr>
                <tr class="tr-color">
                  <td><span>21</span></td>
                  <td><span>19</span></td>
                  <td><span>42.9</span></td>
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
              <img src="https://img.adidas.com.hk/resources/images/size/measure-women.png" alt="" srcset="">
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>