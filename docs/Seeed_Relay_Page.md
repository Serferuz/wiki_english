![](https://github.com/SeeedDocument/Seeed_Relay_Page/raw/master/img/back.jpg)

We have released various types of relays on our website. You may find it difficult to make a choice. We feel you pain, let's talk about what's the difference between all those relays, and what's the advantage or disadvantage among them. 


For all the relay in our bazaar, please click [bazaar relay tag](https://www.seeedstudio.com/tag/relay.html) to check?


Before the start, let's check the following table, perhaps, all you need is just a table.


|Name|Thumbnail|Operate voltage|Input current|Rated load|Contact resistance|Insulation resistance|Operate time|Release time|Input interface|Type|
|----|-----|-----|------|------|------|-------|------|------|------|---|
|[Grove - Relay](https://www.seeedstudio.com/Grove-Relay-p-769.html)|<img src="https://github.com/SeeedDocument/Seeed_Relay_Page/raw/master/img/grove_relay.jpg" />|3.3V-5V|100mA|5A@250VAC<br>5A@30VDC|50mΩ<br>@6VDC 1A|100MΩ|10ms Max.|5ms Max.|Digital|Electromechanical|
|[Grove - SPDT Relay(30A)](https://www.seeedstudio.com/Grove-SPDT-Relay-30-p-1473.html)|<img src="https://github.com/SeeedDocument/Seeed_Relay_Page/raw/master/img/spdt30.jpg" />|5V|185mA|30A@250VAC<br>30A@30VDC|100mΩ Max.|100MΩ Min.@500VDC|15ms Max.|10ms Max.|Digital|Electromechanical|
|[Grove - 2-Channel SPDT Relay](https://www.seeedstudio.com/Grove-2-Channel-SPDT-Relay-p-3118.html)|<img src="https://github.com/SeeedDocument/Seeed_Relay_Page/raw/master/img/spdt2.jpg" />|5V|90mA|10A@250VAC<br> 10A@30VDC|100mΩ Max.|100MΩ Min.@500VDC|10ms Max.|5ms Max.|Digital|Electromechanical|
|[Grove - 4-Channel SPDT Relay](https://www.seeedstudio.com/Grove-4-Channel-SPDT-Relay-p-3119.html)|<img src="https://github.com/SeeedDocument/Seeed_Relay_Page/raw/master/img/spdt4.jpg" />|5V|90mA|10A@250VAC<br> 10A@30VDC|100mΩ Max.|100MΩ Min.@500VDC|10ms Max.|5ms Max.|I2C|Electromechanical|
|[Grove - Solid State Relay](https://www.seeedstudio.com/Grove-Solid-State-Relay-p-1359.html)|<img src="https://github.com/SeeedDocument/Seeed_Relay_Page/raw/master/img/ssr1.jpg" />|3V-5V|16mA Min.<br>20mA Typ.<br>50mA Max.|4A@220VAC||1000MΩ|10ms|10ms|Digital|Solid State|
|[Grove - Solid State Relay V2](https://www.seeedstudio.com/Grove-Solid-State-Relay-V2-p-3128.html)|<img src="https://github.com/SeeedDocument/Seeed_Relay_Page/raw/master/img/ssr.jpg" />|4V-6V||2A@100VAC to 240VAC||1000MΩ Min.@500VDC|1/2 of load power source cycle +1 ms max|1/2 of load power source cycle + 1 ms max|Digital|Solid State|
|[Grove - 2-Channel Solid State Relay](https://www.seeedstudio.com/Grove-2-Channel-Solid-State-Relay-p-3129.html)|<img src="https://github.com/SeeedDocument/Seeed_Relay_Page/raw/master/img/ss2.jpg" />|4V-6V||2A@100VAC to 240VAC||1000MΩ Min.@500VDC|1/2 of load power source cycle +1 ms max|1/2 of load power source cycle + 1 ms max|Digital|Solid State|
|[Grove - 4-Channel Solid State Relay](https://www.seeedstudio.com/Grove-4-Channel-Solid-State-Relay-p-3130.html)|<img src="https://github.com/SeeedDocument/Seeed_Relay_Page/raw/master/img/ssr4.jpg" />|4V-6V||2A@100VAC to 240VAC||1000MΩ Min.@500VDC|1/2 of load power source cycle +1 ms max|1/2 of load power source cycle + 1 ms max|I2C|Solid State|
|[Grove - 8-Channel Solid State Relay](https://www.seeedstudio.com/Grove-8-Channel-Solid-State-Relay-p-3131.html)|<img src="https://github.com/SeeedDocument/Seeed_Relay_Page/raw/master/img/ssr8.jpg" />|4V-6V||2A@100VAC to 240VAC||1000MΩ Min.@500VDC|1/2 of load power source cycle +1 ms max|1/2 of load power source cycle + 1 ms max|I2C|Solid State|
|[Grove - 2-Coil Latching Relay](https://www.seeedstudio.com/Grove-2-Coil-Latching-Relay-p-1446.html)|<img src="https://github.com/SeeedDocument/Seeed_Relay_Page/raw/master/img/2coil.jpg" />|5V||1A@125VAV<br>3A@30VDC|50mΩ Max.|1000MΩ@500VDC|4.5ms Max.|3.5ms Max.|Digital|Electromechanical|
|[Grove - Dry-Reed Relay](https://www.seeedstudio.com/Grove-Dry-Reed-Relay-p-1412.html)|<img src="https://github.com/SeeedDocument/Seeed_Relay_Page/raw/master/img/dry-reed.jpg" />|5V||0.1A@100VAC<br>0.5A@24VDC|150mΩ Max.|100MΩ @500VDC<br>1000MΩ @100VDC|1ms Max.|0.5ms Max.|Digital|Reed Relays|

<div align="center"><b>Table 1.</b><i>Seeed Relay Parameter</i></div>


## Glossary

A relay is an electrically operated switch, the relay opens when the two contacts are disconnected, and the relay turns on when the two contacts touch.


<div align="center">
<figure>
  <img src="https://github.com/SeeedDocument/Seeed_Relay_Page/raw/master/img/relay.jpg" alt="Relay" title="Relay" />
  <figcaption><b>Figure 1</b>. <i>Relay Contacts</i></figcaption>
</figure>
</div>


Each contact connects to an input or output terminal. The input terminal is called **Pole**, and the output terminal is called **Throw**. According to the number of terminals, the relay is divided into several types. which is **SPST**,**SPDT**,**DPDT**, and so on.

**SPST(Single Pole Single Throw):**  
SPST is the simplest relay, you can consider it as a button.  This 'button' is normally open, when the trigger signal comes, the pole contact will connect to the throw contact, we call it close.  It is great for applications that need only an on or off state. A typical representative of SPST is our [Grove - Relay](https://www.seeedstudio.com/Grove-Relay-p-769.html)

<div align="center">
<figure>
  <img src="https://github.com/SeeedDocument/Seeed_Relay_Page/raw/master/img/SPST.jpg" alt="SPST" title="SPST" />
  <figcaption><b>Figure 2</b>. <i>SPST Relay</i></figcaption>
</figure>
</div>


**SPDT(Single Pole Double Throw):**  
SPDT relay is ofen called A/B swicth, as you can see in the figure 3, there are two throws, this kind of relay is great for selecting between two options.

<div align="center">
<figure>
  <img src="https://github.com/SeeedDocument/Seeed_Relay_Page/raw/master/img/SPDT.jpg" alt="SPDT" title="SPDT" />
  <figcaption><b>Figure 3</b>. <i>SPDT Relay</i></figcaption>
</figure>
</div>

You may find that these two throws are called **NC** and **NO** respectively, and the pole is called **COM**. NC means normally connected, NO means normally open. Which means if there is no trigger signal, the NC terminal will be connected to the COM terminal, once the trigger signal comes, the NC terminal will be disconnected and the NO terminal will be connected to the COM termianl. For instance, you can refer to our [Grove - 2-Channel SPDT Relay](https://www.seeedstudio.com/Grove-2-Channel-SPDT-Relay-p-3118.html).

<div align="center">
<figure>
  <img src="https://github.com/SeeedDocument/Grove-2-Channel_SPDT_Relay/raw/master/img/pin_map.jpg" alt="Grove - 2-Channel SPDT Relay" title="Grove - 2-Channel SPDT Relay" />
  <figcaption><b>Figure 4</b>. <i>Grove - 2-Channel SPDT Relay</i></figcaption>
</figure>
</div>



We only have SPST and SPDT relays in our website now, if you want to check other types of relays please refer to the relay page by [NATIONAL INSTRUMENTS](http://www.ni.com/white-paper/3960/en/).



## Types of Relays

Although there are more than a dozen relays in our website, in general, there are only three types: **Electromechanical Relay**, **Solid State Relay** and **Reed Relay**. You can see the classification information in the last column of **Table 1.**


### Electromechanical Relay

#### Principle

Most relays in our bazaar are Electromechanical Relay. Normally a Electromechanical Relay is consisted of coils, armatures and contacts.


<div align="center">
<figure>
  <img src="https://github.com/SeeedDocument/Seeed_Relay_Page/raw/master/img/Electromechanical_Relays.JPG" alt="Electromechanical Relay" title="Electromechanical Relay" />
  <figcaption><b>Figure 5</b>. <i>Electromechanical Relay</i></figcaption>
</figure>
</div>

When the coil is energized, the induced magnetic field moves the armature, which opens or closes the contact.  


#### Advantage and Disadvantage  


**Advantage:**

- Able to withstand large inrush currents
- High mechanical structure reliability, not susceptible to external electromagnetic environment
- Cheap and cost-effective
- Relatively speaking, it can carry high voltage, high current load


**Disadvantage:**

- Electromechanical relays are slower than other types of relays, typical switch and settle in 5 to 15 ms
- Larger package sizes, not suitable for size sensitive occasions
- In general, Electromechanical relays have a shorter life than other types of relays due to mechanical wear



### Solid State Relays


#### Principle

Solid State Relays is also known as SSR, which is an electronic switching device that switches on or off when a small external voltage is applied across its control terminals. Solid state relays typically use semiconductor devices to switch the conduction and disconnection of high voltage loads. Normally a Solid State Relay is consisted of a LED driver and a photosensitive MOSFET. When the trigger signal comes the LED light up to actuate the photosensitive MOSFET, then the high voltage circuit will be turned on.


<div align="center">
<figure>
  <img src="https://github.com/SeeedDocument/Seeed_Relay_Page/raw/master/img/SSR_IN.JPG" alt="Solid State Relay" title="Solid State Relay" />
  <figcaption><b>Figure 6</b>. <i>Solid State Relay</i></figcaption>
</figure>
</div>



#### Advantage and Disadvantage  


**Advantage:**

- Fast switching speed, the switching time is dependent on the time required to power the LED on and off—approximately 1 ms and 0.5 ms. For instand the G3MC202p serial SSR we use is 1/2 of load power source cycle +1 ms.
- Totally silent operation, almost no noise
- No physical contacts means no sparking, allows it to be used in explosive environments, where it is critical that no spark is generated during switching.
- Increased lifetime, even if it is activated many times, as there are no moving parts to wear and no contacts to pit or build up carbon
- Compact, thin-profile SSR of monoblock construction with an all-in-one lead frame incorporates a PCB, terminals and heat sink, which is much smaller than mechanical relays, and can integrate more channels
- Not susceptible to physical shock




**Disadvantage:**

- Contact resistance is relatively large, usually above 100 ohms, which will generat more heat, so it need to be used with fan heat.
- High cost and low cost performance
- Only works for AC laod



!!!Tips
        Please note that some kind of solid state relays support DC load, but all the solid state relays currently sold by seeed do not support DC load.




### Reed Relays


#### Principle

Reed relays are switches that use electromagnets to control one or more reed switch. The contacts are of magnetic material and the electromagic acts directly on them without requiring an armature to move them. Sealed in a long, narrow glass tube, Fill the glass tube with inert gas so that the contacts are protected from corrosion.



<div align="center">
<figure>
  <img src="https://github.com/SeeedDocument/Seeed_Relay_Page/raw/master/img/Reed_Relay.JPG" alt="Reed Relay" title="Reed Relay" />
  <figcaption><b>Figure 7</b>. <i>Reed Relay</i></figcaption>
</figure>
</div>


As shown in Figure 7, there is no axial magnetic field generated when there is no trigger signal excitation, the reed blade will be disconnected because of the rigidity. When the signal is triggered, a transverse magnetic field will be generated and the reed will be magnetized. One contact turns N pole and the other turns S pole, they will be connected.



#### Advantage and Disadvantage  


**Advantage:**

- Low power consumption, small size
- Because it is sealed in an inert gas, very little affected by environmental factors such as temperature and humidity , high environmental adaptability
- Switching speed is fast, about 10 times higher than electromechanical relay


**Disadvantage:**

- Low load voltage and low current
- Susceptible to inductive loads

!!!Note
        If you need to use reed relay with an inductive load (such as a motor), you need to add a protection circuit between the relay and the load.



## Special Function Relays


In addition to the typical relays described above, we have several special-function relays in our website.


**1.Heelight Relay**

You can control the relay through a sound command, isn't it interesting!?

<div align="center">
<figure>
  <a href="https://www.seeedstudio.com/Heelight-Relay-p-2935.html" target="_blank"><img src="https://github.com/SeeedDocument/Seeed_Relay_Page/raw/master/img/Heelight_Relay.jpg" alt="Heelight Relay" title="Heelight Relay" />
  <figcaption><b>Figure 8</b>. <i>Heelight Relay, you can click this figure to check this magic relay</i></figcaption></a>
</figure>
</div>


**2.315MHz Codec-Adaptive Wireless Relay**

A wireless relay is a codec-adaptive RF receiver with single channel relay.


<div align="center">
<figure>
  <a href="https://www.seeedstudio.com/315MHz-Codec-Adaptive-Wireless-Relay-p-550.html" target="_blank"><img src="https://github.com/SeeedDocument/Seeed_Relay_Page/raw/master/img/315MHz%20Codec-Adaptive%20Wireless%20Relay.jpg" alt="Heelight Relay" title="Heelight Relay" />
  <figcaption><b>Figure 9</b>. <i>Wireless Relay, you can click this figure to check this magic relay</i></figcaption></a>
</figure>
</div>





## Resource

- **[PDF]** [Seeed Relay Page PDF Version](https://github.com/SeeedDocument/Seeed_Relay_Page/raw/master/Datasheet/Seeed_Relay_Page.pdf)

- **[ZIP]** [Seeed Relay Module Datasheet](https://github.com/SeeedDocument/Seeed_Relay_Page/raw/master/Datasheet/Seeed_Relay_Module_Datasheet.zip)



## Tech Support
Please do not hesitate to contact [techsupport@seeed.cc](techsupport@seeed.cc) if you have any technical issue. Or submit the issue into our [forum](http://forum.seeedstudio.com/). 