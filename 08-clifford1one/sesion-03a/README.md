# sesion-03a

<https://www.markdownguide.org/cheat-sheet/>

[Mi lindo figma les invito a mirarlo](https://www.figma.com/board/2tv4jx75qGZa6Gua2UCVer/taller.maq.electr?node-id=129-560&t=cVq1IzUTy8WWUreN-1)
![Foto de mis apuntes en figma](tme-03a-apunte.png)



## EXPERIMENTACION

<https://youtu.be/Gu-Fglth_9U>

## INVESTIGACIÓN

<https://ieeexplore.ieee.org/document/1157717/authors#authors>

Este link muestra un documento, le pedi a [Chatg GPT](https://www.figma.com/board/2tv4jx75qGZa6Gua2UCVer/taller.maq.electr?node-id=129-560&t=cVq1IzUTy8WWUreN-1) que lo trascribiera.


**SESSION VIII: Circuit Techniques and Applications**  

### **FAM 8.2. Modulated Pulse Audio and Servo Power Amplifiers**  

**H. R. Camenzind**  
P. R. Mallory and Co., Inc.  
Burlington, Mass.  

To date, audio and servo amplifiers have been used almost exclusively designed as class A or class B amplifiers. These amplifiers, although relatively simple configurations with few active components, have some disadvantages which pose serious problems if a power amplifier is to be designed in integrated circuit form. First, they have a rather limited efficiency. The theoretical maximum efficiency is 50% for class A amplifiers and 78% for class B amplifiers. In actual circuits, especially those of high performance, the efficiency is much lower. With the continuously shrinking dimensions of integrated components, it will become increasingly difficult to dissipate such appreciable amounts of waste power and still retain the advantages of reliability and small size. Secondly, there is the requirement for stable biasing currents. In circuits where coupling capacitors or transformers and selected components are available, the circuit designer can cope with this problem. But in integrated circuits no transformers or large capacitors are available, and all other components have large tolerances and temperature coefficients. The stable biasing currents required for class A and class B amplifiers are not easily or practically attainable with integrated circuits.  

If the advantages of integrated circuits are to be applied to power amplifiers, another approach which allows higher efficiency and does not require critical biasing of external components is required.  

### **The Case for the Two-State Amplifier**  

There is, in fact, a method which represents the amplifier information in the load as a square wave with a theoretical efficiency of 100%, and which, if carefully designed, eliminates biasing currents and external components. This method, called pulse-width modulation, two-state amplification or class D amplification, has been known for more than 35 years, but has never enjoyed great popularity because a large number of external components are required—compared to conventional amplifiers. In integrated circuits, where transistors are less expensive than resistors and capacitors, these objections no longer seem applicable.  

Instead of the linear representation of the signal, the two-state amplifier produces a high-frequency pulse train. Various waveforms are possible, as shown in Figure 1. The width-modulated square wave is probably the most practical approach, so we have initially concentrated on designing integrated amplifiers of this kind.  

In the two-stage amplifier under test, a wide-bandwidth limiter is used to both positive and negative transitions of the power supply at a rapid rate, approximating an infinite slew rate. At the same time, the two produce a toroidal (i.e., a high impedance of the inductive load prevents current flow). As a signal appears at the input of the amplifier, the duty cycle changes and an average low-frequency current flows into the load.  

It is a fortunate coincidence that almost all loads in this frequency range are inductive so that, with modifications, can be connected directly to the two-state amplifier through the use of an external network.  

Compared with class B amplification, pulse-width modulation promises the four advantages in integrated circuits:  

1. **Higher efficiency.** This results in lower power dissipation and smaller surface area.  
2. **Less critical components.** The crucial stages act as limiters between fully on and fully off; thus, no biasing network is required and larger component tolerances are acceptable.  
3. **Stability and higher speeds.** The speed and linearity of transistor gain does not affect gain and linearity of the amplifier. Drift problems are minimized.  
4. **Performance.** Since all stages are DC coupled, there is no lower cutoff frequency. Also, two-state amplifiers generally can be designed to work from a large spread of supply voltages and can accept different load impedances without affecting efficiency.  

### **Approaches**  

What is probably the classical approach to producing pulse-width modulation is shown in Figure 2. Here a sawtooth or triangle waveform of a high frequency is compared with the signal. The performance of this circuit is theoretically ideal in that no distortion is produced and the carrier frequency is constant except at full output power, where it increases. It is, however, difficult to hold the reference levels of sawtooth and signal constant without the use of large capacitors.  

The next figure shows a block diagram of the so-called base amplifier. This approach employs a stage with hysteresis and no RC feedback network. This circuit is very simple, but it produces some distortion and the carrier frequency varies rather drastically at large amplitudes. This causes intermodulation distortion and reduction in efficiency. Various modifications to improve these shortcomings are possible.  

Figure 4 represents a modification of the well-known astable multivibrator. The capacitors are charged with a constant current. The capacitor-source voltage at the bases of the transistors is clamped at a level determined by the output of a differential amplifier. As this level is varied, the discharge times of the two capacitors are varied.  

Stages at the output stage require special attention. A bridge configuration allows coupling balance and center-tapped power supplies. The grounded-collector connection allows more straightforward practical realization than shunt driving. In this way, the base current is derived from a fixed current. Diodes are necessary in order to maintain isolation.  

Using only transistors, diodes, large resistors and small decoupling capacitors, the two-state amplifier has been designed with efficiency approaching 85% for 15 kHz signals and distortion of less than 5%.  

---

This is the full transcription of the document shown in the image. Let me know if you need any clarifications or formatting adjustments!
