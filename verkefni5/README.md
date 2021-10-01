# Verkefni 5

### 5.1

**1. Hvernig er stýrimótor (e. servo motor) ólíkur hefðbundnum DC mótor?**
    
*Sýrimótor er tegund af DC mótor með stýrikubb. Þar sem DC mótor hefur enga stýringu og snýr bara þegar það er gefið því rafmagn hefur stýrimótor stýrikubb inní sér sem gefur því miklu meiri nákvemi.*

**2. Hvernig er hægt að stjórna í hvora áttina DC mótor snýst án kóða?**

*Það er hægt að breyta áttini með því að skipta um bæði tengin (þ.e. að tengja plús við mínus og mínus við plús)*

### 5.2

**1. Settu upp og keyrðu ```sweep``` kóðann á brauðbretti Sweep leiðbeiningar**

[Video af sweeb](/verkefni5/servo.mp4)

**2. Settu upp og keyrðu ```Knob``` kóðann á brauðbretti Controlling Servo with a Potentiometer**

[Video af knob](/verkefni5/servo_potentiometer.mp4)

### 5.3

**1. Hver er munurinn á rafhlöðu og rafþétti?**

*Rafhlaða geymir hleðslu með efnahvarfi meðan rafþétta geymir hleðslu með rafmagns sviði sem leyfir því að gefa út miklu meira rafmagn í einu og hraðara en það heldur miklu minni hleðslu og geymist ekki eins lengi*

**2. Hver er munurinn á Nonpolarized (NPD) og polarized (PD) þéttum?**

*Polarized þýðir að það hefur plús og mínus tengi sem þurfa að vera tengd meðan non-polarized skiptir það ekki máli hvor megin pinnarnir eru tengdir*

**3. Afhverju er heppilegt að nota rafþéttir með mótor?**

*Þeir eru notaðir til að gefa mótorinum nægan straum þegar hann er að byrja og passar að hann eiðinlegst ekki, það kemur líka í veg fyrir noise*

### 5.4

[Mynd af stepper mótor tengdann](/verkefni5/stepper1.jpg)

[Mynd af tengingum fyrir stepper mótorinn](/verkefni5/stepper2.jpg)

### 5.5

**1. Hvað er átt við með free current í rafmótorum?**

*Það er hversu mikinn straum mótor tekur á meðan hann er ekki að gera neitt*

**2. Hvað er átt við með stall current í rafmótorum?**

*Stall current er takmark fyrir straum sem gefið er mótor sem ef farið er yfir hættir mótorinn að snúast*

### 5.6

**Upplýsingar um [mótor](https://www.robotshop.com/en/brushed-dc-motor-6v-11500rpm.html)**

* Spennusvið: *3-12V*
* Hámarkssnúningshraði (6V): *11500rpm*
* Lausagangs straumur (6V): *70mA*
* Hámarksstraumur (6V): *800mA*
* Þvermál öxuls: *2mm*

### 5.7

**Útskýrðu hugtakið snúningsvægi (torque)**

*Torque er beinn kraftur á kantinum á hring. Það er mælt sem ```Torque = Force × Distance```*

### 5.8

**Armur er 0,5m og neðan honum er 0,1kg lóð, hvaða snúningsvægi verkar á hann**

```9,8m/s² × Mass = Newtons```

```9,8m/s² × 0.1kg = 0,98N```

```Torque = Force × Distance```

```Torque = 0.98N × 0,5m```

```Torque = 0,49Nm```

### 5.9

**Hve þungu lóði lyftir [þetta](https://raw.githubusercontent.com/VESM1VS/Efni/main/Myndir/pulley.jpg) talíukerfi?**

```MA = 4```

```5kg × 4 = 20kg```

### 5.10

**Skoðið [Myndina](https://raw.githubusercontent.com/VESM1VS/Efni/main/Myndir/girar.png) vel og svarið 2 spurningum**

**1. Hvert er snúningsvægi út ef snúningsvægi mótors er 1Nm?**

```(12 ÷ 60) × (12 ÷ 60) = 25```

```1Nm × 25 = 25Nm```

**2. Hver er snúningshraði út ef snúningshraði mótors er 1000 RPM?**

```(12 ÷ 60) × (12 ÷ 60) = 25```

```1000rpm ÷ 25 = 40rpm```

### 5.11

**Útskýrðu hvað [þetta línurit](https://raw.githubusercontent.com/VESM1VS/Efni/main/Myndir/7.7.2%20Torque%20vs.%20Current%20Draw.png) sýnir okkur**

*Þetta sýnir að því meiri snúningsvægi því meiri straum þarf mótorinn*
