# Boardoza CPC1945Y Solid State Relay Breakout Board

The **Boardoza CPC1945Y Breakout Board** is built around the **CPC1945Y AC Solid State Relay (SSR)**, providing safe, silent, and reliable switching of low-power AC loads. Thanks to its optically isolated input and zero-crossing detection structure, it enables noise-free AC switching directly from microcontroller systems.

This board is ideal for applications such as **multiplexers, data acquisition systems, industrial control units, electronic meters (electricity, gas, water), medical devices, security systems, I/O subsystems**, and as a compact and long-lasting **solid-state replacement for mechanical relays**. With no mechanical contacts, it ensures long operational life and vibration-resistant performance.

## [Click here to purchase!](https://www.ozdisan.com/ureticiler/boardoza)

| Front Side | Back Side |
|:---:|:---:|
| ![CPC1945Y Front](./assets/CPC1945Y%20Front.png) | ![CPC1945Y Back](./assets/CPC1945Y%20Back.png) |

---

## Key Features

- **Solid State Relay:** Enables reliable AC switching with integrated zero-cross detection for clean transitions.  
- **Optical Isolation:** Provides safe electrical separation between low-voltage control circuits and high-voltage AC loads.  
- **Silent Operation:** No mechanical components, ensuring completely noise-free switching.  
- **Microcontroller Friendly:** Low input current requirement allows direct control from MCU GPIO pins.  
- **Low EMI/RFI:** Zero-cross switching significantly reduces electrical noise during operation.   
 

---

## Technical Specifications

**Model:** CPC1945Y  
**Manufacturer:** Boardoza  
**Manufacturer IC:** Littelfuse (IXYS Integrated Circuits Division)  
**Functions:** AC Solid State Relay (Optically Isolated)  
**Input Control Type:** DC (LED driven)  
**Typical Input Current:** 5 mA  
**Maximum Recommended Input Current:** 10 mA  
**Output Type:** AC (Zero-Cross)  
**Operating Load Voltage:** 20 – 120 Vac rms  
**Load Current:** Up to 1 A rms    
**Blocking Voltage:** 400 Vp  
**Isolation Voltage:** 3750 Vrms (Input to Output)  
**Operating Temperature:** -40°C to +85°C  
**Board Dimensions:** 20mm x 40mm  

---

## Board Pinout

### ( J1 ) Control Input Connector

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | CONTROL | DC Control Input (LED Anode) |
| 2 | GND | Ground (LED Cathode) |

---

### ( J2 ) AC Load Connector

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | AC LOAD | AC Output Terminal |
| 2 | AC LOAD | AC Output Terminal |

> The output terminals are non-polarized and internally connected to the SSR output stage.

---

## Board Dimensions

<img src="./assets/CPC1945Y Dimensions.png" alt="CPC1945Y Board Dimensions" width="450"/>

---

## Step Files

[Boardoza CPC1945Y.step](./assets/CPC1945Y%20Step.step)

---

## Datasheet

[CPC1945Y Datasheet.pdf](./assets/CPC1945Y%20Datasheet.pdf)

---

## Version History

- V1.0.0 - Initial Release  

---

## Support

- If you have any questions or need support, please contact **support@boardoza.com**

---

## **License**

### **Hardware Design**

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

All hardware design files are licensed under [Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
