

# DES228 Project 2
### by Kacey Vicencio ###
#### October 23, 2024 #####
### Website found at: [kacencio.github.io/projectTwoCommunity](https://kacencio.github.io/projectTwoCommunity/) ###

## Project Overview 
The point of community is to come together as one and to put one's differences aside in order to become stronger. *Imagine* by John Lennon illustrates this concept, urging us to imagine a reality where there are no labels that create division, allowing us to unite with each other, with only our humanity defining us. With these deep meanings of community from the song, as well as myself growing
up hearing it, I decided to choose an excerpt of its lyrics in a multi-page website with accompanied keyframe and hover animations to show what community means to me: to become a society that works together, ignoring the qualities or groups we are in that divide us.

## Technical Overview 

### Font used: 
Trebuchet MS 

### Colors Used:
#### Standard Palette Colors:
##### Reds used in the background gradient:
<ul>
<li>#FF0000 - Red</li>
<li>#DA2009 - Crimson</li>
<li>#B72A10 - Brown</li>
<li>#942D15 - Chestnut</li>
<li>#732C19 - Dark Brown</li>
<li>#60271B - Burgundy</li>
<li>#4C221C - Maroon</li>
<li>#381E1B - Dark Maroon</li>
<li>#2C1818 - Very Dark Red</li>
<li>#201314 - Very Dark Maroon</li>
<li>#140B0C - Almost Black</li>

##### Other:

<li>#FF6363 - Pink (Hell)</li>
<li>#FFD138 - Yellow (Heaven)</li>
<li>#006385 - Cyan (Sky)</li>
<li>#FFFFFF - White</li>
<li>#000000 - Black</li>
</ul>

#### Rainbow Animation Colors:
<ul>
<li>#FF5252 (Red)</li>
<li>#FFA500 (Orange)</li>
<li>#FFFF00 (Yellow)</li>
<li>#2DFF2D (Green)</li>
<li>#5858FF (Blue)</li>
<li>#A62AFF (Purple)</li>
</ul>

### Animations Used: 
- **Rainbow Animation**: 
  - **Description**: Creates a rainbow color transition effect on text when Imagine is hovered.
  - **Keyframes**:
    -     0%: color: rgb(255, 82, 82);
    -     16.6%  color: orange; 
    -     33.3%  color: yellow; 
    -     50%  color: rgb(45, 255, 45); 
    -     66.6%  color: rgb(88, 88, 255); 
    -     83.3%  color: rgb(166, 42, 255);
    -     100%  color: rgb(255, 82, 82); 

- **Slide In From Left**:
  - **Description**: Elements slide in from the left with an opacity effect.
  - **Keyframes**:
    - 0%: `transform: translateX(-40px); opacity: 0;`
    - 100%: `transform: translateX(0); opacity: 1;`

- **Heaven ("heavenline") Animation**:
  - **Description**: Fades in elements with a slight opacity change.
  - **Keyframes**:
    - 0%: `opacity: 0;`
    - 100%: `opacity: 1;`

- **Hell ("hellline") Animation**:
  - **Description**: Fades in elements over time.
  - **Keyframes**:
    - 0%: `opacity: 0;`
    - 50%: `opacity: 0;`
    - 100%: `opacity: 1;`

- **Sky Animation**:
  - **Description**: Makes text appear with a sliding effect from below.
  - **Keyframes**:
    - 0%: `opacity: 0; transform: translateY(100%);`
    - 100%: `opacity: 1; transform: translateY(0);`

##### Code Editor Used: #####
[Visual Studio Code](https://code.visualstudio.com/)

## Acknowledgment
#### Sites Referenced for Inspiration: ####
<ul>
    <li>[Cayleigh IP's Project](https://cayleighip.github.io/projectTwoWordsInMotion/)</li>
    <li>[Ling CRI's Project](https://ling-cri.github.io/ProjectTwoWordsInMotion/)</li>
</ul>

#### Background Color Generator Used in CSS: ####
<ul>
    <li>[MyColor.Space](https://mycolor.space/gradient)</li>
</ul>

#### Rainbow Animation Reference: ####
<ul>
    <li>https://stackoverflow.com/questions/54702124/rainbow-text-animation-using-only-css</li>
</ul>

