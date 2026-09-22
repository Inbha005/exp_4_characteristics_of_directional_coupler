# exp_4_characteristics_of_directional_coupler

# Experiment 4 — Directional Coupler Characteristics

---

## Aim

To study the characteristics of a magic tee (hybrid junction) and to determine the isolation and the coupling coefficients between its arms.

## Apparatus Required

1 Klystron power supply. 
2 Klystron tube (2K25) with mount. 
3 Isolator. 
4 Frequency meter. 
5 Variable attenuator. 
6 Magic tee (device under test). 
7 Two matched terminations. 
8 Detector mount. 
9 VSWR meter. 
10 Waveguide stands

---

## Theory
A magic tee is a four–port waveguide junction formed by combining an E–plane tee and an H–plane tee at the same point of a main waveguide. It has two collinear arms (ports 1 and 2), an E–arm (port 3, also called the difference or sum–minus port) and an H–arm (port 4, also called the sum port). The key property of the magic tee is that the E–arm and the H–arm are isolated from each other – ideally, power fed into one of these arms does not appear at the other, provided the two collinear arms are terminated identically. If power is fed into port 1 (a collinear arm), it divides equally between ports 3 and 4, with the two output signals in phase with each other in specific pairs depending on which collinear arm is excited. If power is fed into the E–arm (port 3), it splits equally between the two collinear arms but out of phase by 180°; if fed into the H–arm (port 4), it splits equally and in phase between the two collinear arms. Because of these properties, the magic tee is used in balanced mixers, microwave bridges and duplexers. For an ideal, perfectly matched magic tee (with ports ordered 1, 2, 3(E), 4(H)), the scattering matrix has zero diagonal terms (perfect match at every port) and zero S34 / S43 terms (perfect isolation between the E– and H–arms):

<img width="520" height="247" alt="image" src="https://github.com/user-attachments/assets/f9162a45-1659-4c66-ae44-b9251b34f297" />

##CIRCUIT / PORT DIAGRAM
<img width="640" height="602" alt="image" src="https://github.com/user-attachments/assets/fbc85177-1382-4869-97bb-30ce8b317d02" />



## Experimental Setup

<img width="783" height="270" alt="image" src="https://github.com/user-attachments/assets/0b0576bb-4b6f-4e21-8a34-8f54ca04adf9" />

## Procedure
1. The bench is set up with the magic tee connected as the device under test, and the klystron output is stabilised.
2. Isolation between E and H arms: matched loads are connected to the two collinear arms (ports 1 and 2); power is fed into the E–arm (port 3) and the detector is connected to the H–arm (port 4). The leakage reading is noted and compared with the input power to obtain the isolation.
3. Coupling coefficients: with port 2 terminated in a matched load, power is fed into port 1 and the output is measured successively at port 3 and port 4 (with the other left correctly terminated), to find the power division from a collinear arm into the E– and H–arms.
4. All readings are taken on the VSWR meter (in dB) and tabulated.

---
##PROCEDURE FLOWCHART
<img width="997" height="537" alt="image" src="https://github.com/user-attachments/assets/c718a6d4-a424-4ddb-8b67-db6d4569ad17" />

TABULATION
<img width="1082" height="195" alt="image" src="https://github.com/user-attachments/assets/6b7cb8a4-308f-4f25-aab2-08fd5bd84892" />

FORMULA
1. Isolation (E – H) = Pin – Pout dB
2. Coupling coefficient (port i → port j) = Pi – Pj dB

MODEL GRAPH AND ACTUAL GRAPH
<img width="982" height="390" alt="image" src="https://github.com/user-attachments/assets/277b7b97-eb29-40c6-ae2f-efe0b3aebe97" />

CALCULATION
1. Isolation (Port 3 → Port 4) = 0.0 – (–28.0) = 28.0 dB
2. Coupling coefficient (Port 1 → Port 3) = 0.0 – (–3.6) = 3.6 dB (close to the ideal 3.0 dB equal split)
3. Coupling coefficient (Port 1 → Port 4) = 0.0 – (–3.4) = 3.4 dB

PRECAUTIONS
1. The two collinear arm ports must be terminated in identical, well–matched loads when measuring isolation, or the result will be inaccurate.
2. Waveguide flange connections must be tight and correctly aligned.
3. The klystron output should be kept stable while a set of readings is being taken.
4. Do not look directly into the open waveguide.
--

## Conclusion
The isolation between the E–arm and H–arm of the given magic tee was found to be 28.0 dB, and the coupling coefficients from a collinear arm to the E– and H–arms were found to be 3.6 dB and 3.4 dB respectively – close to the ideal 3 dB equal split predicted by theory, confirming correct operation of the junction.
