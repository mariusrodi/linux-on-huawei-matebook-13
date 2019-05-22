
# Table of Contents

1.  [GNU/Linux on Huawei Matebook 13 (2019)](#org33709a9)
    1.  [Background](#org1a297d3)
    2.  [Contribution](#org86ac857)
    3.  [Linux Support Matrix - Manjaro](#org3c70390)


<a id="org33709a9"></a>

# GNU/Linux on Huawei Matebook 13 (2019)

With this repository I want to track the Linux support on the Huawei
Matebook 13.

\*This repository is inspired by lidel's repository about the Huawei Matebook X
(2017). Check out
[lidel](<https://github.com/lidel/linux-on-huawei-matebook-x-2017>) on GitHub.\*


<a id="org1a297d3"></a>

## Background

The Huawei Matebook 13 is by now a fairly new device. It ships with regular
Windows 10. Information about Linux support is sparse. In this repository I want
to collect some data about things that work and things that don't work.


<a id="org86ac857"></a>

## Contribution

If you found something which is not covered in this repository or if you use
another distro or if you found a typo, please fork, write down your notes and
create a pull request.


<a id="org3c70390"></a>

## Linux Support Matrix - Manjaro

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-left" />

<col  class="org-left" />

<col  class="org-left" />

<col  class="org-left" />
</colgroup>
<thead>
<tr>
<th scope="col" class="org-left">Device</th>
<th scope="col" class="org-left">Model</th>
<th scope="col" class="org-left">Works?</th>
<th scope="col" class="org-left">Notes</th>
</tr>
</thead>

<tbody>
<tr>
<td class="org-left">Processor</td>
<td class="org-left">Intel Core i5-8254U</td>
<td class="org-left">✔️ YES</td>
<td class="org-left">8 cores (4 real ones), power states work out of the box</td>
</tr>


<tr>
<td class="org-left">Graphics</td>
<td class="org-left">Intel HD Graphics (Whiskey Lake 3x8 GT2)</td>
<td class="org-left">✔️ YES</td>
<td class="org-left">fully working</td>
</tr>


<tr>
<td class="org-left">Memory</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">✔️ YES</td>
<td class="org-left">8192 MB fully working</td>
</tr>


<tr>
<td class="org-left">Display</td>
<td class="org-left">13 inch, 3:2, 2160x1440, no touch-screen</td>
<td class="org-left">✔️ YES</td>
<td class="org-left">fully working</td>
</tr>


<tr>
<td class="org-left">Storage</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">✔️ YES</td>
<td class="org-left">256 GB fully working</td>
</tr>


<tr>
<td class="org-left">Speakers</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">✔️ YES</td>
<td class="org-left">fully working</td>
</tr>


<tr>
<td class="org-left">Headphone</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">❌ NO</td>
<td class="org-left">not working, can be partly fixed with `alsactl restore` but then headphones and speakers are playing at the same time</td>
</tr>


<tr>
<td class="org-left">Keyboard</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">➖ PARTLY</td>
<td class="org-left">every key is working except Mediacontrolkeys on keys `F7`, `F8`, `F9`, `F10`</td>
</tr>


<tr>
<td class="org-left">left USB port</td>
<td class="org-left">USB type C, Power-Input</td>
<td class="org-left">✔️ YES</td>
<td class="org-left">works for charging and data</td>
</tr>


<tr>
<td class="org-left">right USB port</td>
<td class="org-left">USB type C, Displayport-Old-Mode</td>
<td class="org-left">✔️ YES</td>
<td class="org-left">works for display and data</td>
</tr>


<tr>
<td class="org-left">Wifi</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">✔️ YES</td>
<td class="org-left">fully working</td>
</tr>


<tr>
<td class="org-left">Bluetooth</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">✔️ YES</td>
<td class="org-left">fully working</td>
</tr>


<tr>
<td class="org-left">Touchpad</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">✔️ YES</td>
<td class="org-left">fully working</td>
</tr>


<tr>
<td class="org-left">Lid</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">✔️ YES</td>
<td class="org-left">fully working</td>
</tr>


<tr>
<td class="org-left">Battery</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">✔️ YES</td>
<td class="org-left">fully working</td>
</tr>


<tr>
<td class="org-left">Port Extender</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">✔️ YES</td>
<td class="org-left">fully working</td>
</tr>
</tbody>
</table>

