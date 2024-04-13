[![](https://dcbadge.vercel.app/api/server/hw3j3RwfJf) ](https://discord.gg/hw3j3RwfJf)
 [![Donate](https://img.shields.io/badge/donate-$-brown.svg?style=for-the-badge)](http://paypal.me/mtpsilva)
<a href="https://github.com/sponsors/aeonSolutions">
   <img height="40" src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/media/become_a_github_sponsor.png">
</a>
![](https://views.whatilearened.today/views/github/aeonSolutions/PCB-Prototyping-Catalogue.svg)
**Unique Visits** <a href="https://trackgit.com"> <img src="https://us-central1-trackgit-analytics.cloudfunctions.net/token/ping/l5m5z1845s10s47cuyl5" alt="trackgit-views" /> </a>
[![GitHub Forks](https://img.shields.io/github/forks/aeonSolutions/PCB-Prototyping-Catalogue.svg?style=social&label=Fork&maxAge=2592000)](https://www.github.com/aeonSolutions/PCB-Prototyping-Catalogue/fork)
[![GitHub stars](https://img.shields.io/github/stars/aeonSolutions/PCB-Prototyping-Catalogue.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/aeonSolutions/PCB-Prototyping-Catalogue/stargazers/)
[![GitHub watchers](https://img.shields.io/github/watchers/aeonSolutions/PCB-Prototyping-Catalogue.svg?style=social&label=Watch&maxAge=2592000)](https://GitHub.com/aeonSolutions/PCB-Prototyping-Catalogue/watchers/)
[![GitHub followers](https://img.shields.io/github/followers/aeonSolutions.svg?style=social&label=Follow&maxAge=2592000)](https://github.com/aeonSolutions?tab=followers) 
</p>

<p align="right">
 <a href="https://github-com.translate.goog/aeonSolutions/PCB-Prototyping-Catalogue/tree/main?_x_tr_sl=en&_x_tr_tl=pt&_x_tr_hl=en&_x_tr_pto=wapp">Change Language</a> <br>
Last update: 12-04-2024
</p>


# 16-bit Smart DAQ Device with unique data fingerprint and a 1.69" TFT LCD 45x55 ABS
This is the repository for the 16-bit Smart DAQ Device with a unique data fingerprint able to do experimental data upload to any data repository. This specific hardware electronics utilizes the ADC IC AD5693 from Analog Devices. More information about this ADC IC [here](https://www.analog.com/en/products/ad5693.html). 

<p align="center">
<img height="300px" src="https://github.com/aeonSolutions/AeonLabs-16-bit-Smart-DAQ-Device-unique-data-fingerprint-and-a-1.69-TFT-LCD-45x55-ABS/blob/main/media/rev_03_2024_pcb_front.jpeg">
</p>p>

<br>

### rev. 10-2023
status: Fully working <br>
Known Issues: <br>
- PCB copper track optimizations
- components rearrangement for optimization of PCB track inductance 

<p align="center">
    <img height="300px" src="https://github.com/aeonSolutions/openScience-Smart-DAQ-to-Upload-Live-Experimental-Data-to-a-Data-Repository/raw/main/media/revision_10_2023_16bit.png">
</p>


### rev. 03-2024
This hardware electronics revision has major improvements in the power suppy and  also power management improving immensely battery life. It also features USB-C to serial UART communications.

status: Fully working <br>
Known Issues: <br>
- PCB copper track optimizations
- components rearrangement for optimization of PCB track inductance
- poor design of the ground plane on the power management zone of the PCB
- The ultra-deep sleep power management does not work as intended. 

<br>
<br>

<p align="center">
  <img height=300 src="https://github.com/aeonSolutions/openScienceResearch-Smart-DAQ-Device-able-to-Upload-Live-Experimental-Sensor-Data-to-a-Data-Repo/blob/main/Design/smartAsphaltSample.jpeg" >
</p>

The photo above is one of the many specimens I purposely fabricated to research the self-sensing properties of asphalt mixed with a known content of carbon fibers. This is a 10cm cylinder specimen and on the top is already setup my own design smart #DAQ (get it here on my GitHub ) with the ability to upload LIVE experimental data to a #dataverse.

In the photo above the smart DAQ is installed on an acrylic case and screwed with plastic screws to an acrylic base with the same cross-section area as the specimen to be tested. 
The acrylic base can be bought [here](https://s.click.aliexpress.com/e/_DEGsZaL). And the acrylic case [here](https://s.click.aliexpress.com/e/_Dmudkjt). 

<br>

## Dataverse API C library

This device uses my C++ library to expedite dataverse API integration on smart DAQ devices or elsewhere. Follow the link to its repository:

https://github.com/aeonSolutions/OpenScience-Dataverse-API-C-library

<p align="center">
<a href="https://github.com/aeonSolutions/OpenScience-Dataverse-API-C-library"> 
    <img height="70px" src="https://github.com/aeonSolutions/openScienceResearch-Smart-DAQ-Device-able-to-Upload-Live-Experimental-Sensor-Data-to-a-Data-Repo/blob/main/dataverse_r_project.png">
</a> 
</p>

<br>
<br>

### Smart PCB Hardware Specifications
The hardware specifications for this 16-bit pcb with dimensions of 23.5x43.5mm can be found [here](https://github.com/aeonSolutions/openScience-Smart-DAQ-to-Upload-Live-Experimental-Data-to-a-Data-Repository/wiki/16‐bit-Smart-DAQ-Hardware-revision-"10‐2023").

<br>
<br>

 **In real life this smart DAQ is able to:**
- connect to all kinds of 3V to 5V Digital sensors;
- connect to all kinds of sensors compatible with the I2C protocol. (max 118 sensors simultaneously)
- measure voltage in the range of  [0;3.3V]
- measure electrical resistance [0; 10^6] Ohm 
- do temperature and humidity compensation on all measurements 
- has a voltage reference sensor for improved accuracy on ADC measurements  
- has a motion sensor to know if anyone moved a specimen during an experiment
- ability to show live experimental data on the 1.69-inch TFT IPS LCD  

<br>
<br>

## PCB circuit Schematic 
The PCB circuit schematic is available in PDF located in the folder "PCB Schematic"
<br>

## PCB design files
The PCB KiCad files are located in the folder "KiCad" 

<br>
<br>

## Proof of Concept

To test and validate proposed smart DAQ PCB electronics and its firmware as a solution for LIVE experimental data measurements on any test specimen part of a experimental campaign, This PCB electronics is being used to measure a predefined set of variables/parameters to further study several asphalt mixtures with known carbon fiber weight content in the asphalt matrix. Below is a YouTube link to an unedited short video showing one of the experimental setups.

[![](https://github.com/aeonSolutions/openScienceResearch-Smart-DAQ-Device-able-to-Upload-Live-Experimental-Sensor-Data-to-a-Data-Repo/blob/main/Design/youtube.png)](https://youtu.be/eOA1JPgop0k)


<br />
<br />

## Author

You can get in touch with me on my LinkedIn Profile:

#### Miguel Tomas

[![LinkedIn Link](https://img.shields.io/badge/Connect-Miguel--Tomas-blue.svg?logo=linkedin&longCache=true&style=social&label=Connect)](https://www.linkedin.com/in/migueltomas/)

<a href="https://stackexchange.com/users/18907312/miguel-silva"><img src="https://stackexchange.com/users/flair/18907312.png" width="208" height="58" alt="profile for Miguel Silva on Stack Exchange, a network of free, community-driven Q&amp;A sites" title="profile for Miguel Silva on Stack Exchange, a network of free, community-driven Q&amp;A sites" /></a>

<a href="https://app.userfeel.com/t/2f6cb1e0" target="_blank"><img src="https://app.userfeel.com/tester/737648/image?.png" width="257" class="no-b-lazy"></a>

You can also follow my GitHub Profile to stay updated about my latest projects: [![GitHub Follow](https://img.shields.io/badge/Connect-Miguel--Tomas-blue.svg?logo=Github&longCache=true&style=social&label=Follow)](https://github.com/aeonSolutions)

<br>

**Hire me** <br>
See [here](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/wiki/How-to-Hire-AeonLabs) how to hire AeonLabs.

<br>

### Be supportive of my dedication and work towards technology education and buy me a cup of coffee
The PCB design Files I provide here for anyone to use are free. If you like this Smart Device or use it, please consider buying me a cup of coffee, a slice of pizza or a book to help me study, eat and think new PCB design files.

<p align="center">
    <a href="https://www.buymeacoffee.com/migueltomas">
        <img height="35" src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png">
    </a>
</p>


### Make a donation on PayPal
Make a donation on PayPal and get a TAX refund*.

<p align="center">
    <a href="http://paypal.me/mtpsilva">
        <img height="35" src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/media/paypal_small.png">
    </a>
</p>

### Support all these open hardware projects and become a GitHub sponsor  
Did you like any of my PCB KiCad Designs? Help and Support my open work to all by becoming a GitHub sponsor.

<p align="center">
    <a href="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/become_a_sponsor/aeonlabs-github-sponsorship-agreement.docx">
        <img height="50" src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/media/want_to_become_a_sponsor.png">
    </a>
    <a href="https://github.com/sponsors/aeonSolutions">
        <img height="50" src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/media/become_a_github_sponsor.png">
    </a>
</p>

# 

### License

Before proceeding to download any of AeonLabs software solutions for open-source development and/or PCB hardware electronics development make sure you are choosing the right license for your project. See [AeonLabs Solutions for Open Hardware & Source Development](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/wiki/AeonLabs-Solutions-for-Open-Hardware-&-Source-Development) for more information. 


