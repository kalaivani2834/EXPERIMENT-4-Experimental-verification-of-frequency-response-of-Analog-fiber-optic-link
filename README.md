
# Exp 4 Experimental verification of frequency response of Analog fiber optic link
# Fiber Optic Link Analysis (660nm)

## AIM
To analyze the relationship between input and received signal of a 660nm fiber optic cable using analog and digital link.

---

## EQUIPMENTS REQUIRED
- Fiber optic trainer kit ST 2502  
- Power supply  
- Patch cords  
- CRO (Cathode Ray Oscilloscope)  
- 660 nm fiber cable  

---

## THEORY

Fiber optic links can be used for transmission of digital as well as analog signals. A fiber optic link typically consists of three main elements:
- **Transmitter**: Converts the electrical input signal into optical (light) energy.
- **Optical Fiber**: Serves as the transmission medium for the light signal.
- **Receiver**: Converts the received light back into an electrical signal, preserving the original signal pattern.

---

## PROCEDURE

1. Connect the power supply to the board.  
2. Ensure that all switched faults are set to ‘Off’.  
3. Make the following connections (as shown in Figure 19):  
   a. Connect the 1KHz sine wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to AC amplifier 1 input.  
4. On the board, switch emitter 1's driver to analog mode.  
5. Switch on the power.  
6. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
7. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
8. Calculate the bandwidth by determining the gain in decibels (dB).  

---

## BLOCK DIAGRAM

<img width="1189" height="704" alt="image" src="https://github.com/user-attachments/assets/2d84667c-f466-44ce-bd8f-63952ec7c296" />


---


## TABULATION  
**Transmission through Analog Link**
<img width="868" height="722" alt="image" src="https://github.com/user-attachments/assets/a93b1e0d-add5-46c7-8272-194b93501305" />

---

## MODEL GRAPH

<img width="1080" height="538" alt="image" src="https://github.com/user-attachments/assets/01f8d29c-a1d1-4441-ac5f-b26001aba6a4" />

<img width="1600" height="1270" alt="image" src="https://github.com/user-attachments/assets/428e31ba-9d75-42f8-b0a5-f69fabb74534" />

---

## RESULT
Thus, the frequency response of the analog fiber optic link was successfully studied, and the bandwidth was determined to be 95 kHz.

*(Summarize observations and conclusions here)*
